# IP info

[![Build Status](https://travis-ci.org/szepeviktor/ip-info.svg?branch=gh-pages)](https://travis-ci.org/szepeviktor/ip-info)

Examine a host by IP address.

You may add an IPv4 address in the URL query: `http://szepeviktor.github.io/ip-info/?1.2.3.4`

Have ip-info prompt you for an IP address: `http://szepeviktor.github.io/ip-info/?prompt`

## Adblock Plus rules

See: https://github.com/szepeviktor/lean-filter/blob/master/build/0200-ip_info.txt

## IP address info providers

### Cleantalk

`https://cleantalk.org/blacklists/%s`

### Project Honeypot

`http://www.projecthoneypot.org/ip_%s`

### AbuseIPDB

Info: `http://www.abuseipdb.com/check/%s`

History: `http://www.abuseipdb.com/report-history/%s`

### blocklist.de (opened in new window)

Info: `https://www.blocklist.de/en/search.html?action=search&send=start+search&ip=%s`

History: `https://www.blocklist.de/en/view.html?ip=%s`

### Stop Forum Spam (opened in new window)

Info: `http://www.stopforumspam.com/search?q=%s`

List: `http://www.stopforumspam.com/downloads/toxic_ip_cidr.txt`

### HE - RBL check, whois, Origin AS, PTR record etc.

`http://bgp.he.net/ip/%s#_rbl`

### MX Toolbox - RBL check

`http://mxtoolbox.com/SuperTool.aspx?run=toolpage&action=blacklist%3a%s`

### OpenBL - IP list only

`https://www.openbl.org/lists/base.txt`

### CINS Score - IP list only

`http://cinsscore.com/list/ci-badguys.txt`

### Labs

`https://otx.alienvault.com/browse`

## Used services

- cdnjs by CloudFlare
- ipify by Randall Degges
- alloworigin.com by Terry
- and of course the [above listed services](https://github.com/szepeviktor/ip-info/blob/gh-pages/index.html#L54)

## HTML5 validity

https://validator.w3.org/nu/?doc=http%3A%2F%2Fszepeviktor.github.io%2Fip-info%2F
