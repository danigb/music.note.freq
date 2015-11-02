# music.note.freq

[![Build Status](https://travis-ci.org/danigb/music.note.freq.svg?branch=master)](https://travis-ci.org/danigb/music.note.freq)
[![Test Coverage](https://codeclimate.com/github/danigb/music.note.freq/badges/coverage.svg)](https://codeclimate.com/github/danigb/music.note.freq/coverage)
[![Climate](https://codeclimate.com/github/danigb/music.note.freq/badges/gpa.svg)](https://codeclimate.com/github/danigb/music.note.freq)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)
[![npm version](https://img.shields.io/npm/v/music.note.freq.svg)](https://www.npmjs.com/package/music.note.freq)
[![license](https://img.shields.io/npm/l/music.note.freq.svg)](https://www.npmjs.com/package/music.note.freq)
[![music.kit](https://img.shields.io/badge/music-kit-yellow.svg)](https://www.npmjs.com/package/music.kit)

`music.note.freq` is a tiny function (939 bytes minified) to get the frequency of a pitch:

```js
var freq = require('music.note.freq')
freq(null, 'A4') // => 440
freq(null, 'c3') // => 130.8127826502993
freq(442, 'A3') // => 221
```

This is part of [music.kit](https://github.com/danigb/music.kit)

## Installation

Install via npm: `npm install --save music.note.freq` and require it.

## Documentation

Its only one function. The first parameter is the (optional) base tuning (440Hz by default). You can read the [generated documentation here](https://github.com/danigb/music.note.freq/blob/master/API.md)

## License

MIT License
