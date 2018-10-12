# Linux Cloud Engineer

- Boot process of Linux

- How to install package (Red hat, Debian, Ubuntu)

- Difference between soft link and hard link

- SSH not working in general for linux. how will you troubleshoot.
- Permissions - chown, chgrp, chmod
- sticky bit
- sgid
SGID (Set Group ID up on execution) is a special type of file permissions given to a file/folder. 
Normally in Linux/Unix when a program runs, it inherits access permissions from the logged in user.

- suid
SUID (Set owner User ID up on execution) is a special type of file permissions given to a file. 
Normally in Linux/Unix when a program runs, it inherits access permissions from the logged in user.


- Linux File Structure
https://www.geeksforgeeks.org/linux-file-hierarchy-structure/

- what is Shell - UI
In computing, a shell is a user interface for access to an operating system's services. In general, operating system shells use either a command-line interface (CLI) or graphical user interface (GUI), depending on a computer's role and particular operation.

- Primary, Extended, Logical Partition

- Different run levels
- single user mode and its use
- file of runlevels - /etc/init
- What is GRUB
- /etc/resolve.conf --> where DNS server names are stored
- How to mount file system
- chkconfig command -> to make changes persistent
- How to check CPU and memory
- ifconfig
- ip addr show
- TOP 100 Linux commands
- How to mount a file system
- lsblk -> command to check which is not mounted
- How to do permanent mount?
- What is \etc\fstab
- What is mounting in Linux
- Difference between ext2, ext3, ext4
- RAID0, RAID1 difference
- What are SSD?
- What are IP tables?
- How to create an Empty file
- how to apply ACL on a file -> setfacl command
- LVM - How to create logical Volume
- What is SEL (secure enhanced linux)
- How to create user/usergroup?
- Linux is overloaded, How to troubleshoot

# Network Support Engineer

VPN

- What are VPN basic messages (9 messages) using preshared key.
http://book.soundonair.ru/cisco/ch13lev1sec4.html
 
Troubleshooting 

- phase 1 Phase2 not coming up
- Traffic not passing
- Packet loss in VPN


TCP/IP and Protocols

- TCP handshake   ---> Microsoft kb
- SSL Handshake   ---> Microsoft kb

(Above TCP and SSL handshake is very very important)

- In NATTING, what is NAT, SNAT, DNAT, PAT eg. VIP
- What is loadbalancing and how is it done on application layer?
- What are the different types of DNS loadbalancing?
- BGP states/Attributes
- Switching states
- Study the TCP header, IP header (all fields)
- What is IP fragmentation? 
- What is DNS Recursive, Iterative (Microsoft documents)
- Windows machine ---> The flow of resolving the domain name to ip address > browser cache, host file, normal DNS
- what is Path MTU?
- Layer 2 and Layer 3 broadcast in DHCP (DORA)
- What is DORA process in DHCP?
- DNS records (Micrsoft site), alias/cname, SPF record, DNS TTL
- What is Cloud Computing?
- Subnetting. how is it done? Read basic examples

HTTP

- HTTP 1.0, 1.1 difference
- HTTP 1.1 - Persistent connection, HTTP Tunneling, host header, 100 continue
- Top 10 HTTP response codes

Proxy

- what is  web proxy
- what is X forwarder, Y forwarder

Tools 

- Traceroute (Windows and Linux)
- MTR (Traceroute + Ping) (Windows and Linux)
- ICMP codes
- Iperf, netstat, ipconfig, tools on networking

Scripting (Basic knowledge not in depth)

- Shell scripting
- SQL queries
