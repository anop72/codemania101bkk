# Code Mania 101 Bangkok, Thailand
---

Some note only session attended.

##  The Present, Past and Future of Asynchronous Programming in Python

Full deck from speaker is  [here](https://www.slideshare.net/YothinMuangsommuk/codemania101-the-present-past-and-future-of-asynchronous-programming-in-python)

I did't write python, but async look interesting. Speaker give some background about
asynchronous programming quite good with playing chess with 50 people.

http://rarehistoricalphotos.com/bobby-fisher-playing-50-opponents-simultaneously-hollywood-hotel-1964/

### Capture keywords
event loop, coroutine, async, await, concurrency

### Other resources (benchmark async libraries)

And Python [Generators.](https://wiki.python.org/moin/Generators)

https://blog.golang.org/concurrency-is-not-parallelism

https://magic.io/blog/uvloop-blazing-fast-python-networking/

https://medium.freecodecamp.com/million-requests-per-second-with-python-95c137af319

[The coroutine concurrency library](https://github.com/dabeaz/curio)

---

## Code security

Full deck from speaker is [here](https://www.slideshare.net/narudomr/coding-security-code-mania-101)

Need to care about protection these state

- When use it
- When store it
- When transmit it

OWASP Top 2013/17 top risk
https://www.owasp.org/index.php/Top_10_2017-Risk

*Security in business logic need to fix in application only, that mean not about hardware. eg, transfer money to account (on us) should check existing added account also*

### Practices

#### Input validation 1

Prevent early as possible. eg, form validate.

Will be good if validate every input bytes that send to server.

- ensure properly formed data
- prevent malformed data

*Should do both for validation, client/server*


#### Whitelist vs Blacklist
Whitelist, data type example, int, date, range

#### Output handling

#### Parameterize queries

---
