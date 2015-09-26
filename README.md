# Examine a host by IP address

You may add an IPv4 address in the URL query: `http://szepeviktor.github.io/ip-info/?1.2.3.4`

## IP address info providers

### Cleantalk

`https://cleantalk.org/blacklists/%s`

Adblock
```js
cleantalk.org##div.why__container
cleantalk.org##div.blacklist-content:nth-of-type(3)
```

### Project Honeypot

`http://www.projecthoneypot.org/ip_%s`

Adblock
```
projecthoneypot.org###\5f cd_iframe
```

### AbuseIPDB

Info: `http://www.abuseipdb.com/check/%s`

History: `http://www.abuseipdb.com/report-history/%s`

Adblock
```js
abuseipdb.com##DIV.banner
```

### blocklist.de

Info: `https://www.blocklist.de/en/search.html?action=search&send=start+search&ip=%s`

History: `https://www.blocklist.de/en/view.html?ip=%s`

### HE - RBL check

`http://bgp.he.net/ip/%s#_rbl`

### MX Toolbox - RBL check

`http://mxtoolbox.com/SuperTool.aspx?run=toolpage&action=blacklist%3a%s`

### OpenBL - IP list only

`https://www.openbl.org/lists/base.txt`

### Stop Forum Spam

Info: `http://www.stopforumspam.com/search?q=%s`

List: `http://www.stopforumspam.com/downloads/toxic_ip_cidr.txt`

