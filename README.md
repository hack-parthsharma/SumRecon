# sumrecon

Script I built upon courtesy of @hmaverickadams

Has been tested only on kali. To be run in root directory

## DEPENDENCIES
* assetfinder - https://github.com/tomnomnom/assetfinder
* amass - https://github.com/OWASP/Amass
* certspotter - #curl -s https://certspotter.com/api/v0/certs\?domain\=$url | jq '.[].dns_names[]' | sed 's/\"//g' | sed 's/\*\.//g' | sort -u (set as alias)
* sublist3r - https://github.com/aboul3la/Sublist3r
* httprobe - https://github.com/tomnomnom/httprobe
* waybackurls - https://github.com/tomnomnom/waybackurls
* whatweb - https://github.com/urbanadventurer/WhatWeb
* nmap - https://nmap.org/download.html
* eyewitness - https://github.com/FortyNorthSecurity/EyeWitness
