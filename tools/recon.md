# recon

## Subdomains
### [assetfinder](https://github.com/tomnomnom/assetfinder)
Subdomain discovery tool written in Go. Checks i.a. crt.sh, certspotter, hackertarget, threatcrowd, **wayback machine**,  dns.bufferover.run, facebook 

### [amass](https://github.com/OWASP/Amass)
No introduction needed for this guy :)

### [DNSdumpster](https://dnsdumpster.com/)
DNSdumpster.com is a FREE domain research tool that can discover hosts related to a domain.

### [dnscan](https://github.com/rbsec/dnscan)
dnscan is a python wordlist-based DNS subdomain scanner (also looks for MX and TX records!)

### [subfinder](https://github.com/projectdiscovery/subfinder)
A passive subdomain discorvery tool.

### [viewdns.info](https://viewdns.info/)
Online service for reverse dns/whois lookups and more (chineese firewall test? port **scanner** and more :O )

## Reverse DNS lookup
### [hackertarget's reverse ip lookup](https://hackertarget.com/reverse-ip-lookup/)
Pretty good onlie reverse ip lookup.

## Brute
### [gau](https://github.com/lc/gau)
Fetch known URLs from AlienVault's Open Threat Exchange, the Wayback Machine, and Common Crawl.
(written in GO!)

### [gobuster](https://github.com/OJ/gobuster)
More performant dirbuster alternative.<br>
Gobuster is a tool used to brute-force:

* URIs (directories and files) in web sites.
* DNS subdomains (with wildcard support).
* Virtual Host names on target web servers.

### [dirsearch](https://github.com/maurosoria/dirsearch)
Web path scanner. Written in python, but multithreaded.

### [parameth](https://github.com/mak-/parameth)
This tool can be used to brute discover GET and POST parameters

### [ffuf](https://github.com/ffuf/ffuf)
Fast web fuzzer written in GO. Directory and vhosts discovery. GET/POST parameters fuzzing.

## Google Dorks
### [Google Hacking Database](https://www.exploit-db.com/google-hacking-database)
Google dorks database

## Helpers
### [httprobe](https://github.com/tomnomnom/httprobe)
Http probing tool written in go. Can be piped with your favorite subdomain discovery tool to check which domains have running webservers (f.e. `cat subdomain_discovery_results.txt | httprobe`)

### [shodan-filters](https://github.com/JavierOlmedo/shodan-filters)
Handy list of shodan search filters

### [publicsuffixlist](https://publicsuffix.org/list/public_suffix_list.dat)
Used by browsers to check if domain is tld. Useful to verify what 'site' means for specific domain to verify csp policies etc.

## Comprehensive
### [spiderfoot](https://www.spiderfoot.net)
SpiderFoot is a reconnaissance tool that automatically queries over 100 public data sources (OSINT) to gather intelligence on IP addresses, domain names, e-mail addresses, names and more.

### [recon-ng](https://github.com/lanmaster53/recon-ng)
Open source, full-featured reconnaissance framework designed with the goal of providing a powerful environment to conduct open source web-based reconnaissance quickly and thoroughly.

## Other
### [FOCA](https://github.com/ElevenPaths/FOCA)
Tool to find metadata and hidden information in the documents. 
