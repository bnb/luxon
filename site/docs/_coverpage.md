![logo](_media/Luxon_icon_64x64.png)

# Luxon <small>2.x</small>

> A powerful, modern, and friendly wrapper for Javascript dates and times.

 * DateTimes, Durations, and Intervals
 * Immutable, chainable, unambiguous API.
 * Native time zone and Intl support (no locale or tz files)
 
```js
DateTime
  .now()
  .setZone('America/New_York')
  .minus({ weeks: 1 })
  .endOf('day')
  .toISO();
```

[GitHub](https://github.com/moment/luxon/)
[Get started](#Luxon)

![color](#e8dffc)