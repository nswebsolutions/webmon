NSWeb Solutions Visual Change tracker - LibreNMS Plugin
=======================================================

##License
NSWeb Solutions Visual Change tracker - program to monitor web pages for change and detect the change with email alerts
Copyleft (C) NSWeb Solutions - 2016

Based on the great work of Prabhas Gupte (Webmon)

NSWeb Solutions Visual Change tracker is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

NSWeb Solutions Visual Change tracker is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with NSWeb Solutions Visual Change tracker.  If not, see <http://www.gnu.org/licenses/gpl.txt>

##About NSWeb Solutions Visual Change tracker
NSWeb Solutions Visual Change tracker collection of scripts to monitor web pages.

It have following objectives:

1) Detect whether listed webpage have any change in contents.

2) If change is detected, show an error in LibreNMS Services

##Dependencies
Bash and PHP and working LibreNMS with nagios-plugins package

##Tested on
PHP 5.6 / 7.0 with Debian 8

##Installation
<code>mkdir /opt/nsw-vct/librenms-plugin && cd /opt/nsw-vct/librenms-plugin && wget https://raw.githubusercontent.com/nswebsolutions/NSWeb-Solutions-Visual-Change-tracker/master/librenms-plugin/check_nsw-vct --no-check-certificate && wget https://raw.githubusercontent.com/nswebsolutions/NSWeb-Solutions-Visual-Change-tracker/master/librenms-plugin/webmon.php --no-check-certificate && chmod +x /opt/nsw-vct/librenms-plugin/webmon.php && chmod +x /opt/nsw-vct/librenms-plugin/check_nsw-vct && mv check_nsw-vct /usr/lib/nagios/plugins/</code>
