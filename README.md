# humanize #

Javascript data formatter for human readability.

Idea, name, and initial code blatently stolen from [milanvrekic/JS-humanize](http://github.com/milanvrekic/JS-humanize)

Can be loaded via AMD or in node directly.

## Installation ##

    npm install humanize

## Usage: ##
```javascript
var humanize = require('humanize');
humanize.date('Y-m-d'); // 'yyyy-mm-dd'
humanize.filesize(1234567890); // '1.15 Gb'
```

## Functions available: ##

####humanize.time####
Retrieves the current time in seconds
```javascript
humanize.time();
```
###humanize.date (a la php)###
###humanize.numberFormat###
###humanize.naturalDay###
###humanize.naturalTime###
###humanize.ordinal###
###humanize.filesize###
###humanize.linebreaks###
###humanize.nl2br###
###humanize.truncatechars###
###humanize.truncatewords###
