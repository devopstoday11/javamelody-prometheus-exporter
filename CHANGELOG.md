## 1.3 / 2017-10-24
* Fix negative values comming from JavaMelody. Sometimes JavaMelody returns negative values for some metrics. We don't want them in our DB.

## 1.2 / 2017-05-17
* Added various SQL related metrics
* Added open file descriptor metric

## 1.1 / 2017-04-30
* Fixed issue #1 (Convert custom Registry to custom collector)
* When using the JavaMelody collector mode, different applications are now exposed via labeled gauges.

## 1.0 / 2017-04-14
* Initial commit