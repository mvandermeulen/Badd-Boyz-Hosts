# Badd-Boyz-Hosts

<img src="https://github.com/mitchellkrogza/Badd-Boyz-Hosts/blob/master/.assets/badd-boyz-hosts-logo.jpg" alt="Badd Boyz Hosts File to Protect Your Computer and Devices Against Bad Web Sites"/><br/><img src="https://github.com/mitchellkrogza/Badd-Boyz-Hosts/blob/master/.assets/spacer.jpg"/>[![Build Status](https://travis-ci.org/mitchellkrogza/Badd-Boyz-Hosts.svg?branch=master)](https://travis-ci.org/mitchellkrogza/Badd-Boyz-Hosts)<img src="https://github.com/mitchellkrogza/Badd-Boyz-Hosts/blob/master/.assets/spacer.jpg"/>[![DUB](https://img.shields.io/dub/l/vibe-d.svg)](https://github.com/mitchellkrogza/Badd-Boyz-Hosts/blob/master/LICENSE.md)<img src="https://github.com/mitchellkrogza/Badd-Boyz-Hosts/blob/master/.assets/spacer.jpg"/>[![GitHub Stats](https://img.shields.io/badge/github-stats-ff5500.svg)](http://githubstats.com/mitchellkrogza/Badd-Boyz-Hosts)<img src="https://github.com/mitchellkrogza/Badd-Boyz-Hosts/blob/master/.assets/spacer.jpg"/><a href='https://twitter.com/ubuntu101za'><img src='https://img.shields.io/twitter/follow/ubuntu101za.svg?style=social&label=Follow' alt='Follow @ubuntu101za'></a>

A hosts file for use on any operating system to block bad domains out of your servers or devices.

* Here's the [RAW hosts file](https://raw.githubusercontent.com/mitchellkrogza/Badd-Boyz-Hosts/master/hosts)
* Here's the [DNSMASQ hosts file for DD-WRT](https://raw.githubusercontent.com/mitchellkrogza/Badd-Boyz-Hosts/master/dnsmasq)

- Copyright: https://github.com/mitchellkrogza

_______________
[![VERSION](https://img.shields.io/badge/VERSION%20-%20V1.2021.04.8557-blue.svg)](https://github.com/mitchellkrogza/Badd-Boyz-Hosts/commits/master)
#### Bad Host Count: 2
```
# Generated by PyFunceble (v3.3.9.) / https://git.io/vpZoI
# Date of generation: 2021-04-25T11:17:03.219986

Status      Percentage   Numbers     
----------- ------------ ------------
ACTIVE      66%          2           
INACTIVE    33%          1           
INVALID     0%           0           
```
____________________

- You are free to copy and distribute this file for non-commercial uses, as long the original URL and attribution is included.

## Help Support This Project 

[<img src="https://github.com/mitchellkrogza/Badd-Boyz-Hosts/blob/master/.assets/kofi5.png" alt="Buy me Coffee"/>](https://ko-fi.com/mitchellkrog)

************************************************
# DOMAIN ADDITIONS FALSE POSITIVES / DOMAIN REMOVALS / OTHER ISSUES: 

Please forward any additions, corrections or false positives by:

[![Log an Issue](https://img.shields.io/badge/LOGGING%20-%20an%20issue%20%F0%9F%9A%A6-blue.svg)](https://github.com/mitchellkrogza/Badd-Boyz-Hosts/issues) 

or send a PULL REQUEST on the domains.txt file in the PULL_REQUESTS folder. 

************************************************
## COMPILED FROM:

This list of hosts is compiled from real server logs on my own servers where I run a number of very busy web sites. 

This list originated from the list of bad referrers domain lists for:

[![NGINX ULTIMATE BAD BOT BLOCKER](https://img.shields.io/badge/NGINX%20-%20ULTIMATE%20BAD%20BOT%20BLOCKER%20%E2%9B%94-blue.svg)](https://github.com/mitchellkrogza/nginx-ultimate-bad-bot-blocker)
or [![Get the APACHE ULTIMATE BAD BOT BLOCKER](https://img.shields.io/badge/APACHE%20-%20ULTIMATE%20BAD%20BOT%20BLOCKER%20%E2%9B%94-blue.svg)](https://github.com/mitchellkrogza/apache-ultimate-bad-bot-blocker)

The list has now been separated from those projects as it contains certain domains which do not actually belong in a hosts file.

************************************************
## WHAT IS A HOSTS FILE?

A hosts file, named `hosts` (with no file extension), is a plain-text file
used by all operating systems to map hostnames to IP addresses.

In most operating systems, the `hosts` file is preferential to `DNS`.
Therefore if a domain name is resolved by the `hosts` file, the request never
leaves your computer.

Having a smart `hosts` file goes a long way towards blocking malware, adware, ransomware, porn and other nuisance web sites.

A hosts file like this causes any lookups to any of the listed domains to resolve back to your localhost so it prevents any outgoing connections to the listed domains.

************************************************
## WHERE DO I PUT THIS ON MY COMPUTER?
To modify your current `hosts` file, look for it in the following places and modify it with a text
editor.

**Linux, Mac OS X, iOS, Android**: `/etc/hosts` folder.

**Windows Systems**: `%SystemRoot%\system32\drivers\etc\hosts` folder.

************************************************
## UNDERSTANDS PUNYCODE / IDN DOMAIN NAMES
A lot of lists out there put funny domains into their hosts file. Your hosts file and DNS will not understand this. This list uses converted domains which are in the correct DNS format to be understood by any operating system.

For instance
The domain:

`lifehacĸer.com` (note the K)

actually translates to:

`xn--lifehacer-1rb.com`

You can do an nslookup on any operating system and it will resolve correctly.

`nslookup xn--lifehacer-1rb.com`

```xn--lifehacer-1rb.com
	origin = dns1.yandex.net
	mail addr = iskalko.yandex.ru
	serial = 2016120703
	refresh = 14400
	retry = 900
	expire = 1209600
	minimum = 14400
xn--lifehacer-1rb.com	mail exchanger = 10 mx.yandex.net.
Name:	xn--lifehacer-1rb.com
Address: 78.110.60.230
xn--lifehacer-1rb.com	nameserver = dns2.yandex.net.
xn--lifehacer-1rb.com	text = "v=spf1 redirect=_spf.yandex.net"
xn--lifehacer-1rb.com	nameserver = dns1.yandex.net.
```

- Look at: https://www.charset.org/punycode for more info on this.

************************************************
## Stop Bad Bot and Bad Referrers from gaining access to your web sites.

- Check Out The Amazing

[![NGINX ULTIMATE BAD BOT BLOCKER](https://img.shields.io/badge/NGINX%20-%20ULTIMATE%20BAD%20BOT%20BLOCKER%20%E2%9B%94-blue.svg)](https://github.com/mitchellkrogza/nginx-ultimate-bad-bot-blocker)
or [![Get the APACHE ULTIMATE BAD BOT BLOCKER](https://img.shields.io/badge/APACHE%20-%20ULTIMATE%20BAD%20BOT%20BLOCKER%20%E2%9B%94-blue.svg)](https://github.com/mitchellkrogza/apache-ultimate-bad-bot-blocker)

************************************************
## Contributors

- Nissar Chababy - https://github.com/funilrys/PyFunceble (Excellent script for checking ACTIVE, INACTIVE and EXPIRED Domain Names)

************************************************
## Some other awesome free projects

- https://github.com/mitchellkrogza/nginx-ultimate-bad-bot-blocker
- https://github.com/mitchellkrogza/apache-ultimate-bad-bot-blocker
- https://github.com/mitchellkrogza/Ultimate.Hosts.Blacklist
- https://github.com/mitchellkrogza/Stop.Google.Analytics.Ghost.Spam.HOWTO
- https://github.com/mitchellkrogza/fail2ban-useful-scripts
- https://github.com/mitchellkrogza/linux-server-administration-scripts
- https://github.com/mitchellkrogza/Travis-CI-Nginx-for-Testing-Nginx-Configuration
- https://github.com/mitchellkrogza/Travis-CI-for-Apache-For-Testing-Apache-and-PHP-Configurations
- https://github.com/mitchellkrogza/Fail2Ban-Blacklist-JAIL-for-Repeat-Offenders-with-Perma-Extended-Banning
- https://github.com/funilrys/funceble
- https://github.com/funilrys/PyFunceble
************************************************
## Help Support This Project 

[<img src="https://github.com/mitchellkrogza/Badd-Boyz-Hosts/blob/master/.assets/kofi5.png" alt="Buy me Coffee"/>](https://ko-fi.com/mitchellkrog)

## Help Feed My Hungry Kitty 

[<img src="https://github.com/mitchellkrogza/Badd-Boyz-Hosts/blob/master/.assets/zuko.png"/>](https://ko-fi.com/mitchellkrog)


************************************************
### Into Photography?

Come drop by and visit me at https://mitchellkrog.com
