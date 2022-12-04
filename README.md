# Brute-force
This repository contains scripts that serve to automate DNS lookup processes, reverse-DNS and lookup for subdomains. The aim is to make life easier for pentesters.

**DNS-reverse**: To use this code, type: _./dnsreverse.txt 200.221.2._
This script will search for names on all IPs within the IP range starting at 200.221.2 and will return the entire result on the screen.

**Subdomains lookup**: To use this script, type: _./subdomains.sh_ _site.com.br_
it is useful to point out that sub-domains.txt is a wordlist file, which can be downloaded from the internet or created by you. You can use any other wordlist.

**Zone transfer**: This script will query the NS of the specified domain; after that it will force the transfer on every NS found. To run the script, type _./zone-transfer.sh _www.site.com.br__
