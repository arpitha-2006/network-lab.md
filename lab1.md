(base) mtech@programming-Lab-50:~$ sudo apt install whois
[sudo] password for mtech: 
Reading package lists... Done
Building dependency tree       
Reading state information... Done
The following packages were automatically installed and are no longer required:
  libreadline5 mariadb-common
Use 'sudo apt autoremove' to remove them.
The following NEW packages will be installed:
  whois
0 upgraded, 1 newly installed, 0 to remove and 81 not upgraded.
Need to get 44.7 kB of archives.
After this operation, 279 kB of additional disk space will be used.
Get:1 http://in.archive.ubuntu.com/ubuntu focal/main amd64 whois amd64 5.5.6 [44.7 kB]
Fetched 44.7 kB in 2s (24.9 kB/s)
Selecting previously unselected package whois.
(Reading database ... 192399 files and directories currently installed.)
Preparing to unpack .../archives/whois_5.5.6_amd64.deb ...
Unpacking whois (5.5.6) ...
Setting up whois (5.5.6) ...
Processing triggers for man-db (2.9.1-1) ...
(base) mtech@programming-Lab-50:~$ whois
Usage: whois [OPTION]... OBJECT...

-h HOST, --host HOST   connect to server HOST
-p PORT, --port PORT   connect to PORT
-I                     query whois.iana.org and follow its referral
-H                     hide legal disclaimers
      --verbose        explain what is being done
      --help           display this help and exit
      --version        output version information and exit

These flags are supported by whois.ripe.net and some RIPE-like servers:
-l                     find the one level less specific match
-L                     find all levels less specific matches
-m                     find all one level more specific matches
-M                     find all levels of more specific matches
-c                     find the smallest match containing a mnt-irt attribute
-x                     exact match
-b                     return brief IP address ranges with abuse contact
-B                     turn off object filtering (show email addresses)
-G                     turn off grouping of associated objects
-d                     return DNS reverse delegation objects too
-i ATTR[,ATTR]...      do an inverse look-up for specified ATTRibutes
-T TYPE[,TYPE]...      only look for objects of TYPE
-K                     only primary keys are returned
-r                     turn off recursive look-ups for contact information
-R                     force to show local copy of the domain object even
                       if it contains referral
-a                     also search all the mirrored databases
-s SOURCE[,SOURCE]...  search the database mirrored from SOURCE
-g SOURCE:FIRST-LAST   find updates from SOURCE from serial FIRST to LAST
-t TYPE                request template for object of TYPE
-v TYPE                request verbose template for object of TYPE
-q [version|sources|types]  query specified server info
(base) mtech@programming-Lab-50:~$ whois google
% IANA WHOIS server
% for more information on IANA, visit http://www.iana.org
% This query returned 1 object

domain:       GOOGLE

organisation: Charleston Road Registry Inc.
address:      1600 Amphitheatre Parkway
address:      Mountain View CA 94043
address:      United States of America (the)

contact:      administrative
name:         TLD Admin
organisation: Google Inc.
address:      111 8th Avenue
address:      New York NY 10011
address:      United States of America (the)
phone:        +1 404 978 8419
fax-no:       +1 650 492 5631
e-mail:       iana-contact@google.com

contact:      technical
name:         TLD Engineering
organisation: Google Inc.
address:      76 Ninth Avenue, 4th Floor
address:      New York NY 10011
address:      United States of America (the)
phone:        +1 404 978 8419
fax-no:       +1 650 492 5631
e-mail:       crr-tech@google.com

nserver:      NS-TLD1.CHARLESTONROADREGISTRY.COM 2001:4860:4802:32:0:0:0:69 216.239.32.105
nserver:      NS-TLD2.CHARLESTONROADREGISTRY.COM 2001:4860:4802:34:0:0:0:69 216.239.34.105
nserver:      NS-TLD3.CHARLESTONROADREGISTRY.COM 2001:4860:4802:36:0:0:0:69 216.239.36.105
nserver:      NS-TLD4.CHARLESTONROADREGISTRY.COM 2001:4860:4802:38:0:0:0:69 216.239.38.105
nserver:      NS-TLD5.CHARLESTONROADREGISTRY.COM 2001:4860:4805:0:0:0:0:69 216.239.60.105
ds-rdata:     6125 8 2 80f8b78d23107153578bad3800e9543500474e5c30c29698b40a3db23ed9da9f

whois:        

status:       ACTIVE
remarks:      Registration information: https://www.registry.google

created:      2014-09-04
changed:      2025-04-11
source:       IANA

(base) mtech@programming-Lab-50:~$ whois 142.250.190.14

#
# ARIN WHOIS data and services are subject to the Terms of Use
# available at: https://www.arin.net/resources/registry/whois/tou/
#
# If you see inaccuracies in the results, please report at
# https://www.arin.net/resources/registry/whois/inaccuracy_reporting/
#
# Copyright 1997-2026, American Registry for Internet Numbers, Ltd.
#


NetRange:       142.250.0.0 - 142.251.255.255
CIDR:           142.250.0.0/15
NetName:        GOOGLE
NetHandle:      NET-142-250-0-0-1
Parent:         NET142 (NET-142-0-0-0-0)
NetType:        Direct Allocation
OriginAS:       
Organization:   Google LLC (GOGL)
RegDate:        2012-05-24
Updated:        2012-05-24
Ref:            https://rdap.arin.net/registry/ip/142.250.0.0



OrgName:        Google LLC
OrgId:          GOGL
Address:        1600 Amphitheatre Parkway
City:           Mountain View
StateProv:      CA
PostalCode:     94043
Country:        US
RegDate:        2000-03-30
Updated:        2019-10-31
Comment:        Please note that the recommended way to file abuse complaints are located in the following links. 
Comment:        
Comment:        To report abuse and illegal activity: https://www.google.com/contact/
Comment:        
Comment:        For legal requests: http://support.google.com/legal 
Comment:        
Comment:        Regards, 
Comment:        The Google Team
Ref:            https://rdap.arin.net/registry/entity/GOGL


OrgAbuseHandle: ABUSE5250-ARIN
OrgAbuseName:   Abuse
OrgAbusePhone:  +1-650-253-0000 
OrgAbuseEmail:  network-abuse@google.com
OrgAbuseRef:    https://rdap.arin.net/registry/entity/ABUSE5250-ARIN

OrgTechHandle: ZG39-ARIN
OrgTechName:   Google LLC
OrgTechPhone:  +1-650-253-0000 
OrgTechEmail:  arin-contact@google.com
OrgTechRef:    https://rdap.arin.net/registry/entity/ZG39-ARIN


#
# ARIN WHOIS data and services are subject to the Terms of Use
# available at: https://www.arin.net/resources/registry/whois/tou/
#
# If you see inaccuracies in the results, please report at
# https://www.arin.net/resources/registry/whois/inaccuracy_reporting/
#
# Copyright 1997-2026, American Registry for Internet Numbers, Ltd.
#

(base) mtech@programming-Lab-50:~$ man top
(base) mtech@programming-Lab-50:~$ sudo apt install nmp -y
[sudo] password for mtech: 
Reading package lists... Done
Building dependency tree       
Reading state information... Done
E: Unable to locate package nmp
(base) mtech@programming-Lab-50:~$ sudo apt install nmap -y
Reading package lists... Done
Building dependency tree       
Reading state information... Done
The following packages were automatically installed and are no longer required:
  libreadline5 mariadb-common
Use 'sudo apt autoremove' to remove them.
The following additional packages will be installed:
  libblas3 liblinear4 lua-lpeg nmap-common
Suggested packages:
  liblinear-tools liblinear-dev ncat ndiff zenmap
The following NEW packages will be installed:
  libblas3 liblinear4 lua-lpeg nmap nmap-common
0 upgraded, 5 newly installed, 0 to remove and 81 not upgraded.
Need to get 5,557 kB of archives.
After this operation, 26.3 MB of additional disk space will be used.
Get:1 http://in.archive.ubuntu.com/ubuntu focal/main amd64 libblas3 amd64 3.9.0-1build1 [142 kB]
Get:2 http://in.archive.ubuntu.com/ubuntu focal/universe amd64 liblinear4 amd64 2.3.0+dfsg-3build1 [41.7 kB]
Get:3 http://in.archive.ubuntu.com/ubuntu focal/universe amd64 lua-lpeg amd64 1.0.2-1 [31.4 kB]
Get:4 http://in.archive.ubuntu.com/ubuntu focal-updates/universe amd64 nmap-common all 7.80+dfsg1-2ubuntu0.1 [3,676 kB]
Get:5 http://in.archive.ubuntu.com/ubuntu focal-updates/universe amd64 nmap amd64 7.80+dfsg1-2ubuntu0.1 [1,666 kB]                                                     
Fetched 5,557 kB in 13s (434 kB/s)                                                                                                                                     
Selecting previously unselected package libblas3:amd64.
(Reading database ... 192408 files and directories currently installed.)
Preparing to unpack .../libblas3_3.9.0-1build1_amd64.deb ...
Unpacking libblas3:amd64 (3.9.0-1build1) ...
Selecting previously unselected package liblinear4:amd64.
Preparing to unpack .../liblinear4_2.3.0+dfsg-3build1_amd64.deb ...
Unpacking liblinear4:amd64 (2.3.0+dfsg-3build1) ...
Selecting previously unselected package lua-lpeg:amd64.
Preparing to unpack .../lua-lpeg_1.0.2-1_amd64.deb ...
Unpacking lua-lpeg:amd64 (1.0.2-1) ...
Selecting previously unselected package nmap-common.
Preparing to unpack .../nmap-common_7.80+dfsg1-2ubuntu0.1_all.deb ...
Unpacking nmap-common (7.80+dfsg1-2ubuntu0.1) ...
Selecting previously unselected package nmap.
Preparing to unpack .../nmap_7.80+dfsg1-2ubuntu0.1_amd64.deb ...
Unpacking nmap (7.80+dfsg1-2ubuntu0.1) ...
Setting up lua-lpeg:amd64 (1.0.2-1) ...
Setting up libblas3:amd64 (3.9.0-1build1) ...
update-alternatives: using /usr/lib/x86_64-linux-gnu/blas/libblas.so.3 to provide /usr/lib/x86_64-linux-gnu/libblas.so.3 (libblas.so.3-x86_64-linux-gnu) in auto mode
Setting up nmap-common (7.80+dfsg1-2ubuntu0.1) ...
Setting up liblinear4:amd64 (2.3.0+dfsg-3build1) ...
Setting up nmap (7.80+dfsg1-2ubuntu0.1) ...
Processing triggers for man-db (2.9.1-1) ...
Processing triggers for libc-bin (2.31-0ubuntu9.18) ...
(base) mtech@programming-Lab-50:~$ ip a
1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN group default qlen 1000
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
    inet 127.0.0.1/8 scope host lo
       valid_lft forever preferred_lft forever
    inet6 ::1/128 scope host 
       valid_lft forever preferred_lft forever
2: enp2s0: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc fq_codel state UP group default qlen 1000
    link/ether 88:ae:dd:28:40:02 brd ff:ff:ff:ff:ff:ff
    inet 10.10.1.91/16 brd 10.10.255.255 scope global dynamic noprefixroute enp2s0
       valid_lft 25704sec preferred_lft 25704sec
    inet6 fe80::c8bd:5875:9bbb:63ce/64 scope link noprefixroute 
       valid_lft forever preferred_lft forever
(base) mtech@programming-Lab-50:~$ map (10.10.1.95)
bash: syntax error near unexpected token `10.10.1.95'
(base) mtech@programming-Lab-50:~$ nmap 10.10.1.95
Starting Nmap 7.80 ( https://nmap.org ) at 2026-07-08 14:53 IST
Nmap scan report for 10.10.1.95
Host is up (0.000062s latency).
Not shown: 999 closed ports
PORT   STATE SERVICE
22/tcp open  ssh

Nmap done: 1 IP address (1 host up) scanned in 0.18 seconds
(base) mtech@programming-Lab-50:~$ sudo nmap -A 10.10.1.95
Starting Nmap 7.80 ( https://nmap.org ) at 2026-07-08 14:54 IST
Nmap scan report for 10.10.1.95
Host is up (0.00079s latency).
Not shown: 999 closed ports
PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 8.2p1 Ubuntu 4ubuntu0.13 (Ubuntu Linux; protocol 2.0)
MAC Address: 08:92:04:D5:B7:72 (Unknown)
No exact OS matches for host (If you know what OS is running on it, see https://nmap.org/submit/ ).
TCP/IP fingerprint:
OS:SCAN(V=7.80%E=4%D=7/8%OT=22%CT=1%CU=34360%PV=Y%DS=1%DC=D%G=Y%M=089204%TM
OS:=6A4E1741%P=x86_64-pc-linux-gnu)SEQ(SP=105%GCD=1%ISR=10D%TI=Z%CI=Z%II=I%
OS:TS=A)OPS(O1=M5B4ST11NW7%O2=M5B4ST11NW7%O3=M5B4NNT11NW7%O4=M5B4ST11NW7%O5
OS:=M5B4ST11NW7%O6=M5B4ST11)WIN(W1=FE88%W2=FE88%W3=FE88%W4=FE88%W5=FE88%W6=
OS:FE88)ECN(R=Y%DF=Y%T=40%W=FAF0%O=M5B4NNSNW7%CC=Y%Q=)T1(R=Y%DF=Y%T=40%S=O%
OS:A=S+%F=AS%RD=0%Q=)T2(R=N)T3(R=N)T4(R=Y%DF=Y%T=40%W=0%S=A%A=Z%F=R%O=%RD=0
OS:%Q=)T5(R=Y%DF=Y%T=40%W=0%S=Z%A=S+%F=AR%O=%RD=0%Q=)T6(R=Y%DF=Y%T=40%W=0%S
OS:=A%A=Z%F=R%O=%RD=0%Q=)T7(R=Y%DF=Y%T=40%W=0%S=Z%A=S+%F=AR%O=%RD=0%Q=)U1(R
OS:=Y%DF=N%T=40%IPL=164%UN=0%RIPL=G%RID=G%RIPCK=G%RUCK=G%RUD=G)IE(R=Y%DFI=N
OS:%T=40%CD=S)

Network Distance: 1 hop
Service Info: OS: Linux; CPE: cpe:/o:linux:linux_kernel

TRACEROUTE
HOP RTT     ADDRESS
1   0.79 ms 10.10.1.95

OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 11.99 seconds
(base) mtech@programming-Lab-50:~$ man nmap
(base) mtech@programming-Lab-50:~$ sudo apt install tcp
[sudo] password for mtech: 
Reading package lists... Done
Building dependency tree       
Reading state information... Done
E: Unable to locate package tcp
(base) mtech@programming-Lab-50:~$ sudo apt install tcp
Reading package lists... Done
Building dependency tree       
Reading state information... Done
E: Unable to locate package tcp
(base) mtech@programming-Lab-50:~$ sudo apt install tcpdump
Reading package lists... Done
Building dependency tree       
Reading state information... Done
The following packages were automatically installed and are no longer required:
  libreadline5 mariadb-common
Use 'sudo apt autoremove' to remove them.
The following packages will be upgraded:
  tcpdump
1 upgraded, 0 newly installed, 0 to remove and 80 not upgraded.
Need to get 370 kB of archives.
After this operation, 0 B of additional disk space will be used.
Get:1 http://in.archive.ubuntu.com/ubuntu focal-updates/main amd64 tcpdump amd64 4.9.3-4ubuntu0.3 [370 kB]
Fetched 370 kB in 6s (57.4 kB/s)                                                                                                                                       
(Reading database ... 193289 files and directories currently installed.)
Preparing to unpack .../tcpdump_4.9.3-4ubuntu0.3_amd64.deb ...
Unpacking tcpdump (4.9.3-4ubuntu0.3) over (4.9.3-4ubuntu0.2) ...
Setting up tcpdump (4.9.3-4ubuntu0.3) ...
Installing new version of config file /etc/apparmor.d/usr.sbin.tcpdump ...
Processing triggers for man-db (2.9.1-1) ...
(base) mtech@programming-Lab-50:~$ 
(base) mtech@programming-Lab-50:~$ 
