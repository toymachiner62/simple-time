# simple-time [![Build Status](https://travis-ci.org/toymachiner62/simple-time.svg)](https://travis-ci.org/toymachiner62/simple-time)

> Super simple javascript time methods so you don't have to calculate milliseconds.

Ever tried to calculate how many miliseconds are in an hour? A day? 2.5 months? It sucks looking at code that calculates it like `1000 * 60 * 60 * 24...`.

This library is extremely simple and allows you to specify time in milliseconds quickly, easily, and in a readable format.

# Usage

All of these methods produce time in milliseconds.

```js
var Time = require('simple-time');

console.log(Time.MINUTE)			// A minute
console.log(5 * Time.MINUTE)	// 5 minutes

// setTimeout example that waits 30 seconds
setTimeout(function() {
	// Do something
}, 30 * Time.SECOND);

// setTimeout example that waits 2 hours
setTimeout(function() {
	// Do something
}, 2 * Time.HOUR);
```

# API

- `SECOND`
- `MINUTE`
- `HOUR`
- `DAY`
- `WEEK`
- `MONTH`
- `YEAR`
