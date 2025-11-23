---
description: Test your enumeration skills on this boot-to-root machine.
---

# Publisher

{% embed url="https://tryhackme.com/room/publisher" %}

## Recon

We start with Nmap to know all running  service on the machine

```
nmap -Pn -sC -sV -oN nmap publisher.thm
```

We found two open ports. on `22` we have SSH and on port `80` we have an Apache httpd `2.4.41` web server.
