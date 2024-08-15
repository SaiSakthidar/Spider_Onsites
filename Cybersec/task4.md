# Vulerability test spider.nitt.edu

Name:   spider.nitt.edu
Address: 10.0.0.137


sublist3r used
Subdomains
spider.nitt.edu	14.139.162.136
api.lynxid.spider.nitt.edu	14.139.162.136
api.lynx.spider.nitt.edu	203.129.195.136
lynx.spider.nitt.edu	203.129.195.136
inductions.spider.nitt.edu	203.129.195.136
api.spider.nitt.edu	203.129.195.136
restapis.lcas.spider.nitt.edu	203.129.195.136
ctf.spider.nitt.edu	203.129.195.136


nmap
Scanning api.spider.nitt.edu (10.0.0.137) [65535 ports]
Discovered open port 80/tcp on 10.0.0.137
Discovered open port 443/tcp on 10.0.0.137
Discovered open port 22/tcp on 10.0.0.137


# No input field :(
 No way to sqlinject, crossside script etc

 Not shown: 65501 filtered ports
PORT      STATE  SERVICE           VERSION
22/tcp    open   ssh               OpenSSH 8.7 (protocol 2.0)
80/tcp    open   http?
443/tcp   open   ssl/http          nginx 1.22.1
3000/tcp  open   http              Node.js Express framework
3001/tcp  open   nessus?
3002/tcp  open   exlm-agent?
3025/tcp  open   http              Node.js Express framework
3040/tcp  open   http              Node.js Express framework
3050/tcp  open   http              Node.js Express framework
3060/tcp  open   http              Node.js Express framework
3075/tcp  open   http              Node.js Express framework
3090/tcp  open   http              Node.js Express framework
3095/tcp  open   http              Node.js Express framework
3308/tcp  open   tns-server?
4000/tcp  open   http              Node.js Express framework
4001/tcp  open   newoak?
4002/tcp  open   http              Node.js (Express middleware)
4003/tcp  open   pxc-splr-ft?
5000/tcp  open   upnp?
7000/tcp  open   http              Node.js (Express middleware)
7050/tcp  open   http              Node.js (Express middleware)
