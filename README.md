# Roundcube Libcalendaring

Library providing common functions for calendar-based plugins. Fork of [Texas Edition](https://github.com/texxasrulez/caldav_calendar_te), which in turn is a fork of the original [Kolab calendar](https://git.kolab.org/diffusion/RPK/browse/master/plugins/libcalendaring).

Provides utility functions for calendar-related modules such as

* alarms display and dismissal
* attachment handling
* iCal parsing and exporting
* iTip invitations handling

## Requirements

iCal parsing and exporting is done with the help of the [Sabre VObject library](http://sabre.io/vobject/). It needs to be installed with Roundcube using composer:

```bash
$ composer require "sabre/vobject" "~3.5.3"
```

## Changelog

**0.7**
* Assume default method when not provided
* Fix composer.json typo
* Remove the event organizer
