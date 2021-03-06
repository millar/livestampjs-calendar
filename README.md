[Livestamp.js](http://mattbradley.github.com/livestampjs)
=====================================================

A simple, unobtrusive jQuery plugin that provides auto-updating timeago/calendar/date text to
your timestamped HTML elements using [Moment.js](http://momentjs.com).

#### Changes by [millar](https://github.com/millar)
This library will make different calls to Moment.js based on the difference of the timestamp from the current time.

- In less than 6.7 days: `calendar()`
- Within 26 days: `fromNow()`
- Same year: `format('lll')`
- Otherwise: `format('ll')`

This package will also localize dates but in doing so requires that the values be passed in UTC.

Usage
-----

See the [livestamp documentation](http://mattbradley.github.com/livestampjs).

Dependencies
------------

* [jQuery](http://jquery.com): you already know what this is
* [Moment.js](http://momentjs.com): a great JavaScript library for parsing
  and displaying dates and times

License
-------

Copyright (c) 2015 Matt Bradley

This software is freely distributable under the terms of the
[MIT License](http://www.opensource.org/licenses/MIT).
