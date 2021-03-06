[![CircleCI](https://circleci.com/gh/notmessenger/poker-analysis.svg?style=svg)](https://circleci.com/gh/notmessenger/poker-analysis)

# poker-analysis
Poker analysis code challenge program for https://gist.github.com/psbanka/1769714082e1b367f58812c3b38b011e#file-basic-challenge-md

# Installation

* `$ git clone git@github.com:notmessenger/poker-analysis.git`
* `$ cd poker-analysis`

# Usage

* `$ node index.js "4d 6h 8d Kh Ah"`
* `$ node index.js "4d 5d 8d Td Ad"`
* `$ node index.js "Ah Th Kd Qc Js"`

To achieve a Five-of-a-Kind hand a Joker (wild card) must be used, which is the text of `0r`

* `$ node index.js "Ah As Ad Ac 0r"`


# Linting

* `$ npm run lint`


# Tests

* `$ npm test`


# CI environment (linting and tests)

* `$ npm run ci`
