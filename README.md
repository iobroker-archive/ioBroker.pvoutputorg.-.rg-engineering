![Logo](admin/pvoutputorg.png)
# ioBroker.pvoutputorg

[![NPM version](http://img.shields.io/npm/v/iobroker.pvoutputorg.svg)](https://www.npmjs.com/package/iobroker.pvoutputorg)
[![Downloads](https://img.shields.io/npm/dm/iobroker.pvoutputorg.svg)](https://www.npmjs.com/package/iobroker.pvoutputorg)
![Number of Installations (latest)](http://iobroker.live/badges/pvoutputorg-installed.svg)
![Number of Installations (stable)](http://iobroker.live/badges/pvoutputorg-stable.svg)
[![Dependency Status](https://img.shields.io/david/Seqway/iobroker.pvoutputorg.svg)](https://david-dm.org/Seqway/iobroker.pvoutputorg)
[![Known Vulnerabilities](https://snyk.io/test/github/Seqway/ioBroker.pvoutputorg/badge.svg)](https://snyk.io/test/github/Seqway/ioBroker.pvoutputorg)

[![NPM](https://nodei.co/npm/iobroker.pvoutputorg.png?downloads=true)](https://nodei.co/npm/iobroker.pvoutputorg/)

**Tests:** ![Test and Release](https://github.com/Seqway/ioBroker.pvoutputorg/workflows/Test%20and%20Release/badge.svg)

## pvoutputorg adapter for ioBroker

Describe your project here

## How-To

Please provide your feedback here

## Known issues
* [ ] Source Values reset to default value at night if default value is defined in an object (bug in JS-Controller, fix needed in 2.3)
*Workaround : Ensure no default value is set for self-created states*

## To-Do
* [ ] Documentation
* [ ] Period calculation selectable but not yet implemented
* [ ] monthly cost price not yet implemented in calculation
* [ ] recalculation based on meter values (configurable by date)
* [ ] add object states for previous [x]day, [x]week, [x]month, [x]quarter, [x]year configurable in adapter settings

## Support me
If you like my work, please consider a personal donation  
(this is an personal Donate link for DutchmanNL, no relation to the ioBroker Project !)  
[![Donate](https://raw.githubusercontent.com/iobroker-community-adapters/ioBroker.sourceanalytix/master/admin/button.png)](http://paypal.me/Seqway)

## What is Sentry.io and what is reported to the servers of that company?
Sentry.io is a service for developers to get an overview about errors from their applications. And exactly this is implemented in this adapter.

When the adapter crashes or an other Code error happens, this error message that also appears in the ioBroker log is submitted to Sentry. When you allowed iobroker GmbH to collect diagnostic data then also your installation ID (this is just a unique ID **without** any additional infos about you, email, name or such) is included. This allows Sentry to group errors and show how many unique users are affected by such an error. All of this helps me to provide error free adapters that basically never crashs. 

## Changelog

### 0.0.1
* (Seqway) initial release

## License
MIT License

Copyright (c) 2020 Seqway <dirkscheck@gmx.de>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.