---
siteroot: ..
layout: master
menu-download: selected
title: Multigraph - Release Notes for version 4.1
---
Release Notes
=============

Version 4.1 (2013-03-21)
---------------------------

* removes serializer from release
* adds a custom lightbox plugin for mobile devices
* adds support for `adapter` plugins for `values` and `csv` data sources
* adds `repeat` tag to support periodic data
* `boolean` attributes in the MUGL can all be `yes` or `no` OR `true` or `false`
* graphs with bound axes will automatically be redrawn when one is interacted with
* improves raphael's performance
* improves canvas's performance in IE 10
* error reporting now includes full stack trace
* cursor does not change to text mode on mouse down
* corrects test for instances of DataValue
* abstracts graph generation
* simplifies touch handlers
* removes references to logger renderer in release
* bugfixes with the legend
* bugfixes in defaults handler
* fixes whitespace issues

Version 4.0 (2013-01-03)
---------------------------

* first official release!

Version 4.0rc7 (2012-12-20)
---------------------------

* bugfix for `throttle` MUGL tag

Version 4.0rc6 (2012-12-20)
---------------------------

* adds `throttle` mugl tag for throttling ajax requests
* a few very minor tweaks to MUGL spec and processing

Version 4.0rc5 (2012-12-12)
---------------------------

* interpret relative URLs mentioned in MUGL files relative to the MUGL file URL itself
* minor bugfixes

Version 4.0rc4 (2012-12-11)
---------------------------

* adds MIT license

Version 4.0rc3 (2012-12-10)
---------------------------

* minor enhancements to jQuery plugin
* adds "busy spinner" in upper left corner to show when ajax request is outstanding

Version 4.0rc2 (2012-12-06)
---------------------------

* Another test release, includes new jQuery plugin

Version 4.0rc1 (2012-12-06)
---------------------------

* Another test release, mostly just checking to make sure that release system
  works correctly with version tags containing a string suffix.
