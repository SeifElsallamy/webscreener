# webscreener 1.0 alpha
Webscreener is a tool for mass domain name pentesting. 
It is used to take snapshots for domains that is generated by a tool like knockpy or Sublist3r.
It cuts out most of the pentesting time by screenshooting many domains and present them in an HTML page for the pentester to check them all at once.

### Requirements
- [Python 2](https://www.python.org/downloads/)
- Tested on windows 10 

#Usage 
```
>python webscreener.py <targetlist> 
```

#TargetList content format example
domain.com
sub.domain.com
sub2.domain.com
sub.domain2.com
...
