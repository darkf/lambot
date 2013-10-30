Lambot is a simple IRC bot written in the [Lamb](https://github.com/darkf/lamb) programming language.

Currently it supports:

* Factoids (`$defact foo bar`, `$foo` says `bar`)
* Ping (`$ping`)
* Simple admin commands (`$savefacts`, `$join`, `$quit`)

**Running**

1. Install [Lamb](https://github.com/darkf/lamb)
2. Configure the options in the beginning of `irc.lamb`
3. Run `lamb irc.lamb`