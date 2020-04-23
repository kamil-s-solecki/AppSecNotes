# Content Discovery

## Subdomains
### [assetfinder](https://github.com/tomnomnom/assetfinder)
Subdomain discovery tool written in Go. Checks i.a. crt.sh, certspotter, hackertarget, threatcrowd, **wayback machine**,  dns.bufferover.run, facebook 

### [amass](https://github.com/OWASP/Amass)
No introduction needed for this guy :)

## Brute
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

## Helpers
### [httprobe](https://github.com/tomnomnom/httprobe)
Http probing tool written in go. Can be piped with your favorite subdomain discovery tool to check which domains have running webservers (f.e. `cat subdomain_discovery_results.txt | httprobe`)

### [shodan-filters](https://github.com/JavierOlmedo/shodan-filters)
Handy list of shodan search filters
