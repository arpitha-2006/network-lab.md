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
(base) mtech@programming-Lab-50:~$ sudo tcpdump -A tcp
[sudo] password for mtech: 
tcpdump: verbose output suppressed, use -v or -vv for full protocol decode
listening on enp2s0, link-type EN10MB (Ethernet), capture size 262144 bytes
15:35:29.529121 IP lb-140-82-114-25-iad.github.com.https > programming-Lab-50.51526: Flags [P.], seq 1614392287:1614392313, ack 3621576184, win 1540, options [nop,nop,TS val 1803720 ecr 1282782604], length 26
E..N.u@.@.Ud.Rr.

.[...F`9...........o.....
....Lu........o..3nr#H....B.......
15:35:29.529400 IP programming-Lab-50.51526 > lb-140-82-114-25-iad.github.com.https: Flags [P.], seq 1:31, ack 26, win 501, options [nop,nop,TS val 1282842646 ecr 1803720], length 30
E..R..@.@.4.

.[.Rr..F......`9......
......
Lv.............{...zD.f.npP..n.....W..
15:35:29.529540 IP lb-140-82-114-25-iad.github.com.https > programming-Lab-50.51526: Flags [.], ack 31, win 1540, options [nop,nop,TS val 1803721 ecr 1282842646], length 0
E..4.v@.@.U}.Rr.

.[...F`9..........gO.....
....Lv..
15:35:48.257608 IP 93.243.107.34.bc.googleusercontent.com.https > programming-Lab-50.46908: Flags [P.], seq 2962390269:2962390293, ack 1375947688, win 1540, options [nop,nop,TS val 1809339 ecr 1721350841], length 24
E..L..@.@..."k.]

.[...<..|.R.K......j.....
....f..........k{.MPD..>r...E...
15:35:48.257832 IP programming-Lab-50.46908 > 93.243.107.34.bc.googleusercontent.com.https: Flags [P.], seq 1:29, ack 24, win 501, options [nop,nop,TS val 1721651112 ecr 1809339], length 28
E..P..@.@.kn

.["k.].<..R.K...}.....!p.....
f.O..........",.......4.g........2.Q
15:35:48.258070 IP 93.243.107.34.bc.googleusercontent.com.https > programming-Lab-50.46908: Flags [.], ack 29, win 1540, options [nop,nop,TS val 1809339 ecr 1721651112], length 0
E..4..@.@..."k.]

.[...<..}.R.K.....y......
....f.O.
15:36:29.487251 IP lb-140-82-114-25-iad.github.com.https > programming-Lab-50.51526: Flags [P.], seq 26:52, ack 31, win 1540, options [nop,nop,TS val 1821708 ecr 1282842646], length 26
E..N.w@.@.Ub.Rr.

.[...F`9.........../.....
....Lv........7..V"P...[ +.i..*.X>
15:36:29.487475 IP programming-Lab-50.51526 > lb-140-82-114-25-iad.github.com.https: Flags [P.], seq 31:61, ack 52, win 501, options [nop,nop,TS val 1282902604 ecr 1821708], length 30
E..R..@.@.4.

.[.Rr..F......`9......
......
Lw.L..........<._.zv.......K.....BqrT.
15:36:29.487635 IP lb-140-82-114-25-iad.github.com.https > programming-Lab-50.51526: Flags [.], ack 61, win 1540, options [nop,nop,TS val 1821708 ecr 1282902604], length 0
E..4.x@.@.U{.Rr.

.[...F`9.....4....6......
....Lw.L
15:36:31.303781 IP programming-Lab-50.46814 > connectivity-check-ubuntu-com-0.ps5.canonical.com.http: Flags [S], seq 2670944598, win 64240, options [mss 1460,sackOK,TS val 1828613086 ecr 0,nop,wscale 7], length 0
E..<..@.@...

.[.}.c...P.3aV.........t.........
l.k.........
15:36:31.304384 IP connectivity-check-ubuntu-com-0.ps5.canonical.com.http > programming-Lab-50.46814: Flags [S.], seq 1804729533, ack 2670944599, win 32768, options [mss 1400,sackOK,TS val 1822253 ecr 1828613086,nop,wscale 5], length 0
E..<..@.@..v.}.c

.[.P..k....3aW....}......x...
...-l.k.....
15:36:31.304420 IP programming-Lab-50.46814 > connectivity-check-ubuntu-com-0.ps5.canonical.com.http: Flags [.], ack 1, win 502, options [nop,nop,TS val 1828613086 ecr 1822253], length 0
E..4..@.@...

.[.}.c...P.3aWk........l.....
l.k....-
15:36:31.304583 IP programming-Lab-50.46814 > connectivity-check-ubuntu-com-0.ps5.canonical.com.http: Flags [P.], seq 1:88, ack 1, win 502, options [nop,nop,TS val 1828613086 ecr 1822253], length 87: HTTP: GET / HTTP/1.1
E.....@.@..V

.[.}.c...P.3aWk..............
l.k....-GET / HTTP/1.1
Host: connectivity-check.ubuntu.com
Accept: */*
Connection: close


15:36:31.305113 IP connectivity-check-ubuntu-com-0.ps5.canonical.com.http > programming-Lab-50.46814: Flags [.], ack 88, win 1024, options [nop,nop,TS val 1822253 ecr 1828613086], length 0
E..42.@.@....}.c

.[.P..k....3a.....'......
...-l.k.
15:36:31.618553 IP connectivity-check-ubuntu-com-0.ps5.canonical.com.http > programming-Lab-50.46814: Flags [P.], seq 1:115, ack 88, win 1024, options [nop,nop,TS val 1822347 ecr 1828613086], length 114: HTTP: HTTP/1.1 204 No Content
E...2.@.@..x.}.c

.[.P..k....3a.....+/.....
....l.k.HTTP/1.1 204 No Content
server: nginx/1.18.0 (Ubuntu)
date: Wed, 08 Jul 2026 10:06:31 GMT
connection: close


15:36:31.618561 IP connectivity-check-ubuntu-com-0.ps5.canonical.com.http > programming-Lab-50.46814: Flags [F.], seq 115, ack 88, win 1024, options [nop,nop,TS val 1822347 ecr 1828613086], length 0
E..42.@.@....}.c

.[.P..k..0.3a.....' .....
....l.k.
15:36:31.618600 IP programming-Lab-50.46814 > connectivity-check-ubuntu-com-0.ps5.canonical.com.http: Flags [.], ack 115, win 502, options [nop,nop,TS val 1828613400 ecr 1822347], length 0
E..4..@.@...

.[.}.c...P.3a.k..0.....l.....
l.m.....
15:36:31.618818 IP programming-Lab-50.46814 > connectivity-check-ubuntu-com-0.ps5.canonical.com.http: Flags [F.], seq 88, ack 116, win 502, options [nop,nop,TS val 1828613401 ecr 1822347], length 0
E..4..@.@...

.[.}.c...P.3a.k..1.....l.....
l.m.....
15:36:31.619057 IP connectivity-check-ubuntu-com-0.ps5.canonical.com.http > programming-Lab-50.46814: Flags [.], ack 89, win 1024, options [nop,nop,TS val 1822347 ecr 1828613401], length 0
E..42.@.@....}.c

.[.P..k..1.3a.....%......
....l.m.
15:37:29.488442 IP lb-140-82-114-25-iad.github.com.https > programming-Lab-50.51526: Flags [P.], seq 52:93, ack 61, win 1540, options [nop,nop,TS val 1839707 ecr 1282902604], length 41
E..].y@.@.UQ.Rr.

.[...F`9.....4.....C.....
...[Lw.L....$#..{.M.Cc.......1oy.......,^.2	...>'
15:37:29.489883 IP programming-Lab-50.51526 > lb-140-82-114-25-iad.github.com.https: Flags [P.], seq 61:106, ack 93, win 501, options [nop,nop,TS val 1282962607 ecr 1839707], length 45
E..a..@.@.4.

.[.Rr..F.....4`9.<....
$.....
Lxt....[....(:f.E.5>........D....*r..)N.P88Wh2v..	<Gg
15:37:29.490069 IP lb-140-82-114-25-iad.github.com.https > programming-Lab-50.51526: Flags [.], ack 106, win 1540, options [nop,nop,TS val 1839708 ecr 1282962607], length 0
E..4.z@.@.Uy.Rr.

.[...F`9.<...a...........
...\Lxt.
15:37:29.782761 IP programming-Lab-50.36710 > lb-140-82-112-26-iad.github.com.https: Flags [S], seq 3387123168, win 64240, options [mss 1460,sackOK,TS val 243549742 ecr 0,nop,wscale 7], length 0
E..<<.@.@...

.[.Rp..f....e....................
..F.........
15:37:29.783137 IP lb-140-82-112-26-iad.github.com.https > programming-Lab-50.36710: Flags [S.], seq 1438457666, ack 3387123169, win 32768, options [mss 1400,sackOK,TS val 1839796 ecr 243549742,nop,wscale 5], length 0
E..<..@.@.2..Rp.

.[...fU..B..e....."......x...
......F.....
15:37:29.783176 IP programming-Lab-50.36710 > lb-140-82-112-26-iad.github.com.https: Flags [.], ack 1, win 502, options [nop,nop,TS val 243549742 ecr 1839796], length 0
E..4<.@.@...

.[.Rp..f....e.U..C...........
..F.....
15:37:29.784660 IP programming-Lab-50.36710 > lb-140-82-112-26-iad.github.com.https: Flags [.], seq 1:1389, ack 1, win 502, options [nop,nop,TS val 243549744 ecr 1839796], length 1388
E...<.@.@...

.[.Rp..f....e.U..C.....d.....
..F0................t1r....S.~.....1...]...;....	jn .S....I.bw...............l&...7..".......+./.....,.0.
.	........./.5.............alive.github.com..........
...............................h2.http/1.1..........".
...............3./.-..........N.OD.q.....	G.`.I_
Stx...%L.0C.....y/..`.......m?..".J.r.3R..c..a.....3.. I&&(..V...].Z...k.4
...0....=....[V..v5.L..a..1s....u.)...q.>P..	.5...0..^+..lhd.0...O.&...b....w..(]..T.c...Ch.o.0.Wl.H..B...e..9X.'...4.S7!...v.Z...|...cG613q.Q.!.D.....h...".......L.6f..p..k.....C.#.-. ....WN.i.+XN...q.I~.7q.FC.9PdeS.=..R.......lL...*.=..<...W.A..\1..H.z..."....3s:......tDu...A.."X.,.3...^8..
.A.....	."..:^........kP....h......P.^......f6..8b..0....."..+RL\)H..#..dR'..p..D.v,z..0.
..}.>..-B0.../	6]od...M:G....<0;u...Ps.8....wL....=SC.`?.8KUrT_.g.$1..A.
	..d.......;x..f.*.Fk......5..F...X..x(O..E43S.5....z....H..)D..V....."AZ..P..K0.....H
& 3a.....AK...H...
r..z..S.FYJg.)LP+....
H...*."7.g..L...lf.(0p8@.C|a..	V..[..H..f?a. ...|).....-.2.
JK..U:.{...o.I... ,a.KQ...gI5...)<1*....V...".5.i	I..y.L../..!.
p.zJ9....i-xV..'|9YqUT.,...a=\.i..r,.)....E].F...l.84..WL8..P.5..h..6...Zs......"P.h..ho.Q..$q.V....`..].Z{d^Ta._+B:...k.mc.q.N1.....v'.AqdmH[.....N^k?t..J..z....L...e.>..Y.688....X...a<...:...]y..cX=:R.......W..
...T.,&...:.7.5@w..:...Z.\cts.V%..P..!F_0q..E..(?..a2.[...a..Jp..Sm9T.
....
.8G...........-.....`..C......h0..fyM1...!..}.E...f..a.....
15:37:29.784664 IP programming-Lab-50.36710 > lb-140-82-112-26-iad.github.com.https: Flags [P.], seq 1389:2073, ack 1, win 502, options [nop,nop,TS val 243549744 ecr 1839796], length 684
E...<.@.@..j

.[.Rp..f....kMU..C....
......
..F0......_.....2..0b...zM......c.X...lvQ....r.6"C..}......a..l.<!.... ...lvQ....r.6"C..}......a..l.<!....A..`.n........u.$.#...1X`.b.=...V..&.[y^..K6...~..IrgWR.{..<.<.....+....................................-........@...............y.....A. R2o.Bi..
r#.5Z7.....t..?...x\.Ic.OYjk.s...>[|s..U..V@y..x.ox.N...9.T.<..h....f .&...9.J.%...... "m../S..^.k.QJ"..i.l...C......".............l....da....\....da..J......pK.y&..K....b8.b...c+..ef...R..V
1.v.4m....p...~..F..R..$.O9....l.0.....h.M..~.S..r....._......1..|.w.F.{..i'....x..E..JTTE........q.h.l..>....a..	j.~ftL.P..mT.e9.p.k..c.[Sb..'.=..0..kI....2*.}.....g!h|.).K.&. .:..Q..j.......O.....@........3	.-.1.! ..hGA.J..p..d..j.[.}.......$..'\
15:37:29.784958 IP lb-140-82-112-26-iad.github.com.https > programming-Lab-50.36710: Flags [.], ack 1389, win 1540, options [nop,nop,TS val 1839796 ecr 243549744], length 0
E..4..@.@.$..Rp.

.[...fU..C..kM...........
......F0
15:37:29.784960 IP lb-140-82-112-26-iad.github.com.https > programming-Lab-50.36710: Flags [.], ack 2073, win 1540, options [nop,nop,TS val 1839796 ecr 243549744], length 0
E..4..@.@.$..Rp.

.[...fU..C..m......d.....
......F0
15:37:30.351344 IP lb-140-82-112-26-iad.github.com.https > programming-Lab-50.36710: Flags [P.], seq 1:3103, ack 2073, win 1540, options [nop,nop,TS val 1839966 ecr 243549744], length 3102
E..R..@.@....Rp.

.[...fU..C..m............
...^..F0....z...v......m....8.....a.~#...q.{.sR*... .S....I.bw...............l&...7.......+.....3.$... .M...."......;2r......M.(.."Pa.K..........*.7/..x..B.....(...Z./...\..].%.wa.M.!=`......
..w...
..f.kO.....g.....CN..;.....R......~N....R.W.;..+...?....z....^..%....
.:..s.,..q....n~gb]].d.z.;..a?...(,}Y+e..k7....J.....2W..>..A...........+`w6.f	..	LU.a.fV;NA&A.oa...+3o..Vp...>..l....
o.j...q..s.P.^[.........P..qF..~J.!...u.....N...;p......+........s.k;.c.#........0.R...>*P....&......=.#.\.vy\...Ci...!.]....[5><2......eH."_4@$........Yg..a.......d..Y ..z.v.`.....d....
.....%y....02...p&..Um5#..|.+.c.....c-....M7...R..>...m..vP6....A....8!m8.^8Q..Zm(J......'O..j`.w. ..i..x....,..%o.......[..Y..p..-..J......a.e...4...)..............sU.x.L..*+.0}WKv..J....O..!z..s1..ms.(..^.tr.j?...%".o....4....X....Su.e.....-.....:.....=.{$........o,@.
.#J1..!..b.....W.I]...V.......Z.P...Nz....M)...........Zu.9?..6..qn..y..O	P...-%.P.Nf%..o4$....... .....&(.}]b.q...|....,.<..	rC.-xme.-.!.H=a.-....h....00.%....|4...........Bk....0.qd.X....B...G..X...f...l.x.j..Mb#......`.<4~.WI.<N.<....~.o=....d...V`..e.kOp^u.=..m.R-...#....c....	. X.....#.v..z.!.@=;....6..].
.......!.....|}.r.f2.......|-....."....a|(.m.4...V.....@....5.....T..`...Y>.j..*D.H......"h.W.....f4.CA....@...*tVO....N...]X./.....O^&.|..#....7...k(."..f...eo._..!..\...&.Q.<.........-b.v..0U..j...?i.7...[K.....1.....g.L........"b.p..z.Nwy...
e`....LcS.....C..
..x.....q..9.....W.g.[)B.d-.\H.9..f..i.^.p...'io...Q...
....O<J..<......'....L."l..LV.O.......'..."=0.E...`.O..o[........
..I..jH.ao.O.'.f|Oy......b.S....2.*4...ClX.[Dn......{.....}=.V....Z.9..O(..A
C..j...+.......zj.h.oo...z........}......"..v ..R.U..... .......9..F..~.....UBWqP.@..6.H.|...0.....OlL..-........O.....9.~...".).y`.x..XCd...n....aBcy...L..5..{......$J....F
...i	.....s..>BM..*!....hF.Y;5IC.?..8 w.%.....w.1u....k.~....../.. ..n+/..4.|..[.	.`...V.@..CR8...8N..2..7.:_.........v.u....5..O	...&B${ ...;.`...L?.y...8..	.........N3.....zy..c...mg...nS<g..Z...!...c.......q...i..,....2G.....*.....A7E.P.&p~...d........	... m..........L..c-Yc..........z..dpO...%a..`...	.....6.M.A.\.f.uT.Gvhi.XwW3R.p...x.f...k.....7......\T..uZ..:......!.:..g#h0.A....Z_....w-..M........t...7|...W.u.s.p#_X./..s....>1.EIS.CK{=..J.3....gS.b....;t4.pe...L..4..|.xpg.dp...j...ZkI.&..9.|.._kw.....P.......o\..8.x+...'...ED....r..1.......Z..~#m....P..=.(..J_?.B..g..2v.~...[Uw."6U........H5.E...U..g=B.F.......\C..s._.A!.PhT.n...EF..yI..1...8...q.::X	........U.E.J.....Dd.x&Lv...%Q1..%...I...KC....P...o..,_.w.J&Zv~41~,$MU.{..5....k...3._w";..5-..;I.}..	|
.....x.....yV>c....YB..n\ZKM.0sK6s...5...2.89u.{..=.(....h..F.pOJ.....4Z...T...M....8pz..0....)../.........
m.I.........ts/.a..a...y.........cr..;..n.|A....}..]..N..m..o......	l......0.F.1.<_6.M.......g.h^.......z......#H'.a..F.p..W..A..SA.c.!Kd......9.x.L....|.)........eg.~...ED+.....$.2.q....Oh.....x.c.R*..)...g.\..!/....c.B....p<.v.....Q.....,...........:....hKu%.f......yO...t~3......`...O.....|b.U...vU..f.w.O.Q..y...LW.J................<.....V'2..q.c.._..EZ....^J.#
..A...k...u......5l..i.uV..6.....XGXzM.J...X.XDk)............7..]...g..
15:37:30.351384 IP programming-Lab-50.36710 > lb-140-82-112-26-iad.github.com.https: Flags [.], ack 3103, win 492, options [nop,nop,TS val 243550310 ecr 1839966], length 0
E..4<.@.@...

.[.Rp..f....m.U.+a...........
..Hf...^
15:37:30.353685 IP programming-Lab-50.36710 > lb-140-82-112-26-iad.github.com.https: Flags [P.], seq 2073:2137, ack 3103, win 501, options [nop,nop,TS val 243550313 ecr 1839966], length 64
E..t<.@.@...

.[.Rp..f....m.U.+a.....8.....
..Hi...^..........5+_.W..:..y#....Z...
...E.*Z.(H.i.lB	........L...o{4..
15:37:30.353848 IP lb-140-82-112-26-iad.github.com.https > programming-Lab-50.36710: Flags [.], ack 2137, win 1540, options [nop,nop,TS val 1839967 ecr 243550313], length 0
E..4..@.@.$..Rp.

.[...fU.+a..n9.....".....
..._..Hi
15:37:30.353982 IP programming-Lab-50.36710 > lb-140-82-112-26-iad.github.com.https: Flags [P.], seq 2137:3291, ack 3103, win 501, options [nop,nop,TS val 243550313 ecr 1839967], length 1154
E...<.@.@...

.[.Rp..f....n9U.+a.....z.....
..Hi..._....}...ySc}C.z..Mxj..t...|-5.x....... z.}..I]..4.#N.er....=r.lm...V{.j..=..v...QK`d#.s...........8....\....5.=P.....D .$.:....P..D..b..\F....MymiA..>...H.5./0k../T.......oJ.jh.x..y......I......KG<m....4..u...u..z.x.CG.U..}..2
.RE...	..'.f.....jWP5.0>U..E...l.;7T.~..?7..."...f..n..O_.p......D.*.>...rR..9=.Wy .....v:.N!..YJG........B(o........j.B...........~.W.A...7.......`~....hD....U......+0....5.J|Lcq3....}.PV...[..2..O.o..Lgx...d....r>]..{,.....S...Z..WR8q......@..*N.hl....=.S...;........~.Z.j.e.r..3.....OZ...... .....E.....i-T.....X.!........x8..U....D...Mv.\...))U4.1N.e./	i...;..j.:.!C.....Ag.s..o......!.....j}.,...7...;. .;...N.)l.....I..
....4YH....L^`'...."9..6.C_........W..B@3....E..l.....d}.vr......@.H...1\$.+..BD~.gW...yy.@~..:8.....' ..Ut.+..E.f..|=....i.y.p..N...B]?...m.i..._s1n.q.9.1.DH.>...'.[+Sg..F.\dw...T......?R8e.
.....K..2..&.D	.....1.$.......%...#....
.......mT.......5.......g......./..M..!J...j.4.+...B..h...p.p.......X0.a.3\$...1+..NdS....._.Y.G.../.G.2.l.z......V.>..@N...[.$@*3..C..f9..Tt.1.!jf..{n/fW~..0...x..Q.t..........AG...tG.u(.....W....A.BC..]..":4j#.......j.........$hB.J.....Z.6...+._g......Q0.my.~.....^.*
15:37:30.354195 IP lb-140-82-112-26-iad.github.com.https > programming-Lab-50.36710: Flags [.], ack 3291, win 1540, options [nop,nop,TS val 1839967 ecr 243550313], length 0
E..4..@.@.$..Rp.

.[...fU.+a..r............
..._..Hi
15:37:30.490427 IP programming-Lab-50.51526 > lb-140-82-114-25-iad.github.com.https: Flags [P.], seq 106:130, ack 93, win 501, options [nop,nop,TS val 1282963607 ecr 1839708], length 24
E..L..@.@.4.

.[.Rr..F.....a`9.<....
......
Lxx....\.....=..cmd....Wkx...@..
15:37:30.490454 IP programming-Lab-50.51526 > lb-140-82-114-25-iad.github.com.https: Flags [F.], seq 130, ack 93, win 501, options [nop,nop,TS val 1282963607 ecr 1839708], length 0
E..4..@.@.4.

.[.Rr..F.....y`9.<....	......
Lxx....\
15:37:30.490653 IP lb-140-82-114-25-iad.github.com.https > programming-Lab-50.51526: Flags [.], ack 130, win 1540, options [nop,nop,TS val 1840008 ecr 1282963607], length 0
E..4.{@.@.Ux.Rr.

.[...F`9.<...y.....g.....
....Lxx.
15:37:30.528421 IP lb-140-82-114-25-iad.github.com.https > programming-Lab-50.51526: Flags [.], ack 131, win 1540, options [nop,nop,TS val 1840020 ecr 1282963607], length 0
E..4.|@.@.Uw.Rr.

.[...F`9.<...z.....Z.....
....Lxx.
15:37:30.637910 IP lb-140-82-112-26-iad.github.com.https > programming-Lab-50.36710: Flags [P.], seq 3103:3182, ack 3291, win 1540, options [nop,nop,TS val 1840052 ecr 243550313], length 79
E.....@.@.$..Rp.

.[...fU.+a..r......G.....
......Hi....J...O...|T.....O...;k.z..}..){..v./.o.......T.................>!.z.=..N....
15:37:30.678658 IP programming-Lab-50.36710 > lb-140-82-112-26-iad.github.com.https: Flags [.], ack 3182, win 501, options [nop,nop,TS val 243550638 ecr 1840052], length 0
E..4<.@.@...

.[.Rp..f....r.U.+............
..I.....
15:37:30.678837 IP lb-140-82-112-26-iad.github.com.https > programming-Lab-50.36710: Flags [P.], seq 3182:3261, ack 3291, win 1540, options [nop,nop,TS val 1840065 ecr 243550638], length 79
E.....@.@.$..Rp.

.[...fU.+...r............
......I.....J.?$...d.%.v.D<....}.R....Z&.h.6.!.M0.....uWr.,.<9.A..A.a.Q..p..A..+.3..n.5
15:37:30.678858 IP programming-Lab-50.36710 > lb-140-82-112-26-iad.github.com.https: Flags [.], ack 3261, win 501, options [nop,nop,TS val 243550638 ecr 1840065], length 0
E..4<.@.@...

.[.Rp..f....r.U.+............
..I.....
15:37:30.759083 IP lb-140-82-114-25-iad.github.com.https > programming-Lab-50.51526: Flags [P.], seq 93:117, ack 131, win 1540, options [nop,nop,TS val 1840089 ecr 1282963607], length 24
E..L.}@.@.U^.Rr.

.[...F`9.<...z...........
....Lxx..............@..?.......
15:37:30.759115 IP programming-Lab-50.51526 > lb-140-82-114-25-iad.github.com.https: Flags [R], seq 3621576314, win 0, length 0
E..(..@.@.1.

.[.Rr..F.....z....P...$...
15:37:30.936118 IP lb-140-82-112-26-iad.github.com.https > programming-Lab-50.36710: Flags [P.], seq 3261:3823, ack 3291, win 1540, options [nop,nop,TS val 1840142 ecr 243550638], length 562
E..f..@.@."..Rp.

.[...fU.+...r.....O......
......I.....-'..i....)(.t.....w..(....l|G..7.TJl{.)....9.X.Ww.=....4}ug..<N.P.....(.=.X.md.t..o..r.o.......9.n.5.#..S./.d./....LPuK.V..._q.......n..2).F7.a..{..>M.@.By.@...q)!....k...Y.k....xx.....I'..Ax..cV.._.d......5.]1.T...."]6t../a.../bDi..b"Lt.^........s|..i.1(.(.O]........u+V.60Mc.qz{(...}..J.....W..TzmA..Hfxu......Y..?@q...;[qm..9...l..KR.'.:...w..c..4E..T4........Ms.,.\...n,).%.8[1:.F..'..sP4X.....ncdc..$XB.;.9.^-T(....z.....6`.y8..... }.O...eX&.C...p..2@Z?.7Kii........e...k.s~..Jtild.}3.c.Z..o.yj.../@..u[*X...8.n7....v.........86. ......I...E..
..	..Tm@O
15:37:30.936150 IP programming-Lab-50.36710 > lb-140-82-112-26-iad.github.com.https: Flags [.], ack 3823, win 501, options [nop,nop,TS val 243550895 ecr 1840142], length 0
E..4<.@.@...

.[.Rp..f....r.U..1...........
..J.....
15:37:30.938994 IP programming-Lab-50.36710 > lb-140-82-112-26-iad.github.com.https: Flags [P.], seq 3291:3666, ack 3823, win 501, options [nop,nop,TS val 243550898 ecr 1840142], length 375
E...<.@.@...

.[.Rp..f....r.U..1....	o.....
..J.........rKqK../..R.\....&..c...%.t.PFh.Ee.
b[e.e.x.M....HU...G..Z....rC>.b.o......n9...b..P.M.y...u..:..:......92.....H...0....	.x...b.....&}.q.z..(<...]......I.(."..7-=.4&`..D..O.|4. 8..A.bJ?jee!v(..+a.-tq_k..,v.....a..{.e..t'6......XY.6 .N[*@x=VO.........z..W.......nhc..F.Y......96.AR...>.....T.K/.K...".H/..8.S..).......#..]4a...!...+..OUdu.S.o.o......r52.2...+..}4p[.......?
15:37:30.939184 IP lb-140-82-112-26-iad.github.com.https > programming-Lab-50.36710: Flags [.], ack 3666, win 1540, options [nop,nop,TS val 1840143 ecr 243550898], length 0
E..4..@.@.$..Rp.

.[...fU..1..t2.....`.....
......J.
15:37:31.224985 IP lb-140-82-112-26-iad.github.com.https > programming-Lab-50.36710: Flags [P.], seq 3823:3896, ack 3666, win 1540, options [nop,nop,TS val 1840228 ecr 243550898], length 73
E..}..@.@.$..Rp.

.[...fU..1..t2.....#.....
...d..J.....D..4.6b.`.....ej.^W........J.*...r..H......<.....9.....@>l...[s.r....
15:37:31.266718 IP programming-Lab-50.36710 > lb-140-82-112-26-iad.github.com.https: Flags [.], ack 3896, win 501, options [nop,nop,TS val 243551226 ecr 1840228], length 0
E..4<.@.@...

.[.Rp..f....t2U..z...........
..K....d
15:37:49.074029 IP programming-Lab-50.37750 > pu-in-f95.1e100.net.https: Flags [S], seq 2071349080, win 64240, options [mss 1460,sackOK,TS val 3974606529 ecr 0,nop,wscale 7], length 0
E..<..@.@.B.

.[..._.v..{vGX........,..........
............
15:37:49.074939 IP pu-in-f95.1e100.net.https > programming-Lab-50.37750: Flags [S.], seq 4187827731, ack 2071349081, win 32768, options [mss 1400,sackOK,TS val 1845583 ecr 3974606529,nop,wscale 5], length 0
E..<..@.@......_

.[...v....{vGY....V......x...
..)O........
15:37:49.074976 IP programming-Lab-50.37750 > pu-in-f95.1e100.net.https: Flags [.], ack 1, win 502, options [nop,nop,TS val 3974606530 ecr 1845583], length 0
E..4..@.@.B.

.[..._.v..{vGY........,......
......)O
15:37:49.075757 IP programming-Lab-50.37750 > pu-in-f95.1e100.net.https: Flags [.], seq 1:1389, ack 1, win 502, options [nop,nop,TS val 3974606531 ecr 1845583], length 1388
E.....@.@.<.

.[..._.v..{vGY........2Q.....
......)O...	...	... ".|.G...z...'..:
u~F.N.M.m.[c.3 z../1x.._.XC.......	O.iT.=...X.J.".......+./.....,.0.
.	........./.5..	.... .....safebrowsing.googleapis.com..........
...............................h2.http/1.1..........".
...............3./.-.....(f..~.'\u..Z....p]K.,J?;g?.9...rL4.w)1............8Bf.,.h.,s.@.2G..D....a.B!..c.#..`.c].s%.r	R..6:.pR.l<..n.yI.i "0p,.-....8.)...U......'.i........:G!.I....4...U,..5V.-.\.I9.Vf<.)x.x(x...x..c>...[..{...h.RO0V.+.t............*Y.bB..v~0.)..`..J}Ln....U....r....^..&f:
..x.h.L.&.vV..C..d.G..!<.....u.7.=.h..#.Qt.'ft....(.._...n..
.R.....G....&.%*3...f..I..	U..W<R...V.p..[....k.h....Y)E....8.f..#......'.T<.....y....Z...B..*..5..#.;...a.gY?.c
....|?.0.&.>A..2.%T`:.$w#s.l..a..++..`%d.m...l.F..;y..(<.G&...Bt'.......N.P..".jhq.. e.h. ....e#W,"......^.....7."....3..t.'s...g.9.....0i.r.f..5..?.......i......$......)8gf8G....Y..k..g.....u.gb....g_viq;X2.a.."Aj%...k.*.
.M)........|.....	.0.."o{..R.T.....BgK.QDM&x.y .SBp....P...
9(.r..U..%c....Tg.....3...p6.^....1.hg+,,..j..$.9......~.`t..A.......CF.5....Cir*.Q0..@Wi.e....2...;7.6).g..7dc&.t..	.(.....2:...P.-K...S.(...k...>*..'......-.*5.... ..Q..../.yL.X..4.qIrb.....A..A...7.I.1...'...Q<.F..o..s.._h.....9....Y....6#{.4...?...S.R"..j..H.z......
...g t..FHL1.!'bK.wH.T.A...........k.y.F..c...n[h}.D]#j.U9~...koy..........V.4\.PS{.k....C.6.......],.#F.L..J-......@.a5........s.o;...).f.SU./eRE..C..
15:37:49.075758 IP programming-Lab-50.37750 > pu-in-f95.1e100.net.https: Flags [P.], seq 1389:2549, ack 1, win 502, options [nop,nop,TS val 3974606531 ecr 1845583], length 1160
E.....@.@.=~

.[..._.v..{vL.........1m.....
......)Oe.9..DZ}......~......r.y....
......;|
.n.eyJ.}p. n.a..k.R.G.cD....S#..... .n.eyJ.}p. n.a..k.R.G.cD....S#.....A....:...W..@O.U.@!U.$.|..E.f..'U.q.
i}..h.>...@......E...(.\e>y...*...+....................................-........@...............Y.....). .M........?....R.5.B..n.......>[./.RH0=..0M....c.
..#........2!.w	.s.o'c.a....7....b....../T..N.P...UU.Q
......Q...#...S...c...*...."M...g..]>tC.u.(.]i..fe^.H/..|R.9.....s.{./...~.WQ*..,5N.p}..Z.D.B,....ly]...........'.4..=.2...............).N..UM.....).$+#.Fo....Q..a..B	:.|..|.OT.3"J.....3.E.....`...h...:....1*i~!.ch..s.5...........TX.;.*.S1........%..........#.%..a..#..iu..@^5.....R.J....9
.Lh.,.r...R..F....].97 .i...6......[.....}.g.b.).G<...H...p..\...y0..P|.....y....c...7N...$o.....L.......W!j...>I.7EB..U'./.G...r.zAm..1.......b...P.9.-.['.L..ct.]q.	%.k.1.u`.p&A..2.(.....?......Y...).8......O.q.b..c..RiOLy>br..Sg..].4!.W....R.s...t`'.9ph...w...#:.........."..V@`J0.$W.]..UBW..Q.5.....:.NJ.d.Y..?{_[.A..nr.:.>.......%z~....*..c..a....BIB@	...]......n....\.gl...U..O*.u..;...... ...m...=...r.?....W1Mk.b.=a+.Z...{../..T....U....`.JwBOM'.Y.......e>.10.a........L.Fx.W...W8...(.[.}.....Z&qN.-A.._J.>.
15:37:49.075986 IP programming-Lab-50.37750 > pu-in-f95.1e100.net.https: Flags [P.], seq 2549:2555, ack 1, win 502, options [nop,nop,TS val 3974606531 ecr 1845583], length 6
E..:..@.@.A.

.[..._.v..{vQM........,......
......)O......
15:37:49.075995 IP programming-Lab-50.37750 > pu-in-f95.1e100.net.https: Flags [P.], seq 2555:3258, ack 1, win 502, options [nop,nop,TS val 3974606531 ecr 1845583], length 703
E.....@.@.?E

.[..._.v..{vQS......../......
......)O.....pg..
..#.2.b;..j....A...vh.....=.......^..+..W]PX...0.%9..... l?nj.......b........B..d....b.....h.s.....n.Q.,zoG...Y..}6/R..fS..}3..,..l.....C.vH.......#f...D.B...m0.v..Q......5.S.v...4.W..i\.....aF....~..U\@330..p....|oz...]..{._.!i.....k.*..yt6.V..../.'.v..N.r..nN..%a.+.u...G.<.cU.S.O....Y.2/~..a?.......0...Y....!.Jz.Tb.8.vm.p.D!:..*....))...R.wy.&.i...... .......i.p.."!....d..)7./..(..A..u#.5=.r.MI..7....]..,D..W..w...}RO9...\ka..Z>szUK..B....&...s
.hd.%...G.v_..Y...,.l.'.....@...q.....4.Wh)}i|......v.Y....z._.C..2.....c......+h4.......]...L.....{.4v.g.%..R......)..hv.Q.x.4......T|.E}...3/Ps.|SL^	o.\Uf........@.q..a.cbN.A`W.>=..6.....].Yl.m#....zC......[,...]......&...;@........K.%^T...
15:37:49.076049 IP pu-in-f95.1e100.net.https > programming-Lab-50.37750: Flags [.], ack 2549, win 1540, options [nop,nop,TS val 1845584 ecr 3974606531], length 0
E..4.[@.@......_

.[...v....{vQM.....;.....
..)P....
15:37:49.076165 IP pu-in-f95.1e100.net.https > programming-Lab-50.37750: Flags [.], ack 2555, win 1540, options [nop,nop,TS val 1845584 ecr 3974606531], length 0
E..4.\@.@......_

.[...v....{vQS.....5.....
..)P....
15:37:49.076165 IP pu-in-f95.1e100.net.https > programming-Lab-50.37750: Flags [.], ack 3258, win 1540, options [nop,nop,TS val 1845584 ecr 3974606531], length 0
E..4.]@.@......_

.[...v....{vT......v.....
..)P....
15:37:49.153045 IP pu-in-f95.1e100.net.https > programming-Lab-50.37750: Flags [P.], seq 1:1971, ack 3258, win 1540, options [nop,nop,TS val 1845607 ecr 3974606531], length 1970
E....^@.@......_

.[...v....{vT.....4......
..)g..................+.cb.m.8.`".$....)..K...R...k z../1x.._.XC.......	O.iT.=...X.J....t.).....3.d...`...`z.....5.2N..D..&..	~uLn..{.`n.....p...P.....g........../.i+:.X2>=...
]....guM.........:.U.q..!...c;H,.x.X.[...<...g!+........h^.E...z....2.z......,KM....... ..HhkC{*..t.}m(Kf.P........I..&.0.....o..,.W!.....s.~..j1r!.4..-D...U..w...|.w....).l8..~S+_.3..x..D........Y......O2..*N...T....Ne.?h..q.^.Oo/..R...?...]..U..r.|.B..i1.R&z.........V.D...zaWi.hl.X+.5x...149.5..f&d...
..4.~p ...&.$.K.q..VD.......9.l K..........H..7a..z.v..!hbn.<.2.X!p.....Z.=..t........<.G.T....]YdDl1K.zki..!.	....E..D......(..k.....[9) /kN.....|.O.^.u.R..Q..0._...'..e.s.#...rw..?<....
$..a.U...Ku...;MemiP.+ j&\&:X&F/DO'B.......p.:...o.|...O.ngP....t......;.I....4..}w.....".fU.x...W..........7.....,{.}....0.~...{.....F..6.z.......`..}..'..|...=.......?.(...Rvu..U........G....Iqk....`....r%c..[.kx.BZ.C.....F.1.oA5.....0.Aq...u.....y.......Hf..t
..1tTC8(..\......+!.H......@,CnV.*.J7v..8m..	....Z....k..._5..:.E....8.o..?.......z.?i....Qeh...T...U..'..
I....t...~.;K..... .T....Qn..Z.......Pf8..V.......=5.&.d....k<.....b.hbxhh&.d....[5...8..V5.r.. .........o.i..p..W..}.....C.;Q!..:m.M..9`-..=~..}3.. ..F..k...f..Z_R....s]u....@..]....U.+..............X;5W.Z.oX~.6O.W^h.....R.%./.........z.x...n.lwXH.....(...@S6...y.....@./...H.9O.0...N...$....Ge..L...=.vqI..8.I../....o...|......*..r.a9.......Q..A.....U.^)m.....E.....h..{...WZF.....&........e...xSc....si.\	n..T.>H.f.....>.GS...;.c....XhJ.....e...x.H&.......!......'W1=..O\+].:.._..j^X..C^....H._....\f..WJ1k.'A..Qi.(..{&.....$k....~2..O>.....hh.a..:.I%..;.4....MF.N.f3.oI._.L...U.ne....aQ..A..D....))...f.#3..M.`inZK.j&..<?.....4.|0-..Q..vf.!..w	9zF.y..s2...DW.v.X...g3......P.~Ec.C..J...aA.|..N..
..a....^.b.t.4dR\_....k...:..2^...o....Q....3.I.A\....'-..U......V....D.8.4/p......'p<8t.n..^..g...:N...a.M...y...J.}=.......-.e......l9..|P:S.K....9...G2.9...!..T....VE.}.>..	.....9I?.d....SUZ.o.... =..o..3.:.bQ..M.o.......D>.lN.....s.N..
15:37:49.153072 IP programming-Lab-50.37750 > pu-in-f95.1e100.net.https: Flags [.], ack 1971, win 500, options [nop,nop,TS val 3974606608 ecr 1845607], length 0
E..4..@.@.B.

.[..._.v..{vT...5.....,......
......)g
15:37:49.153263 IP pu-in-f95.1e100.net.https > programming-Lab-50.37750: Flags [P.], seq 1971:2002, ack 3258, win 1540, options [nop,nop,TS val 1845607 ecr 3974606608], length 31
E..S.`@.@......_

.[...v..5.{vT............
..)g............Ra.s......l|....)....
.
15:37:49.153280 IP programming-Lab-50.37750 > pu-in-f95.1e100.net.https: Flags [.], ack 2002, win 500, options [nop,nop,TS val 3974606608 ecr 1845607], length 0
E..4..@.@.B.

.[..._.v..{vT...5.....,......
......)g
15:37:49.153572 IP pu-in-f95.1e100.net.https > programming-Lab-50.37750: Flags [P.], seq 2002:2241, ack 3258, win 1540, options [nop,nop,TS val 1845607 ecr 3974606608], length 239
E..#.a@.@......_

.[...v..5.{vT............
..)g............Z$.^.TL...2#FB.C*6;.!.....eh]Y..n..:p...~U..B....!.%{/......<...?+......v4.......V.....:.../.G,...Kb.K!j....=....d.K&......(..vp..x...*<U.{O.	."..c...\
..Tv\.+y.rS"...e.'.F.(............[.SG.A]..n44X.a....B....(....N:..d....P:..it.
15:37:49.153588 IP programming-Lab-50.37750 > pu-in-f95.1e100.net.https: Flags [.], ack 2241, win 499, options [nop,nop,TS val 3974606608 ecr 1845607], length 0
E..4..@.@.B.

.[..._.v..{vT...6.....,......
......)g
15:37:49.153628 IP pu-in-f95.1e100.net.https > programming-Lab-50.37750: Flags [.], seq 2241:3629, ack 3258, win 1540, options [nop,nop,TS val 1845607 ecr 3974606608], length 1388
E....b@.@..8..._

.[...v..6.{vT............
..)g........g....$..t.1..(E..On!.N.~...W......:j..........O....*.	L..}P....._..m........:.......UU."......B.X....p9...2<...".-9.jH.m#..#,....):.F.csS...7...g.f.. .......I...{V.......3..R.J&2IL.m.......aoQO...#.._..D."..iU.q..d:.....d9.....n.F..T..p.....$..."..C...U.hz...Y....N..o0.-.a5..-
...-..-.Js.*/_....(1m....q..D.sl.....b .v...wH....1.h.6..9.9...N....*$L....Q..6I....5h^.Y...s....;...f..f./..5{..g...X.u<.n[lL.Fg,...4...K.......Q.k ....K.q..}..4O5.zP....;X...DJ..L....<W..:7....)....X...ir.pSD..".b....y.Q........@.X.IL....w....h.J......y.*..x	X.H...D..I8.tw..0d..6..-...[Z.t...O..a"....z...D..B.... vJX....p....-.W....cU...
[.,..P9;...8.D.t%....@.*gbOn.Bh.m.N5,.QRe.P.)O..pv!....).H&e........#zc.f....a.BF#AY
.j..b.|w^.}X...Y#.j......]3........#.._....sU.....a	..X.?t...........gq...fC.3.C..."..i.@...^.......X... H.h.....n3....&.............	..?H.i..a..e..E.............8.....~.[N.u......f*1..\......g6./.p5....~.a.._....M...P......$.|.Z.....H/...(..6v..|r.'..........hx@9.#mF5f..u.=4.Mq.Hz..=.j.>...W..K..R....|..]...=.[r....%>:.....VNb-EB....+=...........tl.=.xj@..V..'=..G......>.[.Ur..cA.../...........|.........#o.=........0.B].Y....97....../....G.#...S.....f.T~......MA..m..<..3H..y.p....B.E....8..J>......'....@!.-...............kTP.$.............`.....)V.3....S~..8..z*....dR.Q.&..F_.f....`..@..i............^...s.u...i......!.!...9C..........IerM'.6..q.
..\... ../.G...N..Q.. ..
15:37:49.153633 IP programming-Lab-50.37750 > pu-in-f95.1e100.net.https: Flags [.], ack 3629, win 489, options [nop,nop,TS val 3974606609 ecr 1845607], length 0
E..4..@.@.B.

.[..._.v..{vT...<@....,......
......)g
15:37:49.153851 IP pu-in-f95.1e100.net.https > programming-Lab-50.37750: Flags [P.], seq 3629:4833, ack 3258, win 1540, options [nop,nop,TS val 1845607 ecr 3974606608], length 1204
E....c@.@......_

.[...v..<@{vT......M.....
..)g.........8/..\I.e.'..<..:.Z.......Z..W+f|.....zF.Q...R.jP..B..PN..
.
pK.u...$.I..-|i..<.A..;...i.....}.........L..W..q.m...z.1b[[[..S...P....P<.].V...jn..K	.....ykF.!.+....k.......D.;.r.Y.=@.qA.v.b...T\....}E...Y.f=....9..,(..]{&..T...W..rP~^x...!.Z{s..r.. o^........7..P...S...{3Z..xq...k^B*..aj.Z_s...s....q...FJ..X..mTl.QI7x.mx
=j-THB....!...+.3.h.)..wA1.5.9...1.. .....2I@!........d.&..-lgG....==.SE......M.y......./...u{.....\......$vq..P..$...Ue..%+...$..}.ZB....b.........3d...e#.s!..o.0.....]....I.L..=....4.&#.}bAb..H8dTA.,..B\....j^.......+~...3(...pWgH	.....C!.]...Q.u....c..~H...8Q.v.W.ca.HI.....:....4...;..........}#..V........7}tj...Z.&..\...)..y.b...4-.._..K..1*.g.H3..H....f.Fyp.N.V1>~+z. ...]q)....E{...2`>.ET...f`tx.PO..)..o.....=...*..&'.X..2.W....L.~.q..G....`./....$CG..?Ob..Y>U.L.%..q.-.....G...0%..E	....X.1n.M.v.B)...F&....o.C	\.=.8....."i...=SSIJ.?.?!`#....y....(T....b.M.O....%1~.0..X[....E`..]..Zy....dS..I...Y...n.rL.}\.2...).'.#.V..C%oNF.....`0o....|...,..9".x...;l..(pL..[..W.EI.2D_...3..F....J.u8.F..EC.[...{q..W...71>^o....m..Xi..]01T..\.....P.........cjn.......s.m.p......?..D.h.9...L(kN.f.#.0.=......}>.>..x7G.	P.......%...t	..`......#.....j.@..f.2..v..X2....`..\..SWt..3V.
15:37:49.153871 IP programming-Lab-50.37750 > pu-in-f95.1e100.net.https: Flags [.], ack 4833, win 480, options [nop,nop,TS val 3974606609 ecr 1845607], length 0
E..4..@.@.A.

.[..._.v..{vT...@.....,......
......)g
15:37:49.154057 IP pu-in-f95.1e100.net.https > programming-Lab-50.37750: Flags [P.], seq 4833:4872, ack 3258, win 1540, options [nop,nop,TS val 1845607 ecr 3974606609], length 39
E..[.d@.@..{..._

.[...v..@.{vT............
..)g........"..N...A..n.......6...8.;..Q.%Y...j
15:37:49.154073 IP programming-Lab-50.37750 > pu-in-f95.1e100.net.https: Flags [.], ack 4872, win 480, options [nop,nop,TS val 3974606609 ecr 1845607], length 0
E..4..@.@.A.

.[..._.v..{vT...A.....,......
......)g
15:37:49.154199 IP programming-Lab-50.37750 > pu-in-f95.1e100.net.https: Flags [P.], seq 3258:3358, ack 4872, win 480, options [nop,nop,TS val 3974606609 ecr 1845607], length 100
E.....@.@.A.

.[..._.v..{vT...A.....-I.....
......)g......y.c..}.o./.....VC.e]....Ee......l..T....Rj....~[X=..?.3.0d..a.........L,..Y..z4/......j1.v5...
15:37:49.154355 IP pu-in-f95.1e100.net.https > programming-Lab-50.37750: Flags [.], ack 3358, win 1540, options [nop,nop,TS val 1845607 ecr 3974606609], length 0
E..4.e@.@......_

.[...v..A.{vTv...........
..)g....
15:37:49.155024 IP programming-Lab-50.37750 > pu-in-f95.1e100.net.https: Flags [P.], seq 3358:3389, ack 4872, win 488, options [nop,nop,TS val 3974606610 ecr 1845607], length 31
E..S.	@.@.A.

.[..._.v..{vTv..A.....-......
......)g.....)1.HX.{8+C.......J...a}_..
15:37:49.155208 IP pu-in-f95.1e100.net.https > programming-Lab-50.37750: Flags [.], ack 3389, win 1540, options [nop,nop,TS val 1845607 ecr 3974606610], length 0
E..4.f@.@......_

.[...v..A.{vT............
..)g....
15:37:49.155290 IP programming-Lab-50.37750 > pu-in-f95.1e100.net.https: Flags [P.], seq 3389:3428, ack 4872, win 501, options [nop,nop,TS val 3974606610 ecr 1845607], length 39
E..[.
@.@.A.

.[..._.v..{vT...A.....-......
......)g....".........s.t7.NP.0..k....K........
15:37:49.155477 IP pu-in-f95.1e100.net.https > programming-Lab-50.37750: Flags [.], ack 3428, win 1540, options [nop,nop,TS val 1845608 ecr 3974606610], length 0
E..4.g@.@......_

.[...v..A.{vT......^.....
..)h....
15:37:49.157059 IP programming-Lab-50.37750 > pu-in-f95.1e100.net.https: Flags [P.], seq 3428:3452, ack 4872, win 501, options [nop,nop,TS val 3974606612 ecr 1845608], length 24
E..L..@.@.A.

.[..._.v..{vT...A.....,......
......)h.........U...$+.E.<.....
15:37:49.157076 IP programming-Lab-50.37750 > pu-in-f95.1e100.net.https: Flags [F.], seq 3452, ack 4872, win 501, options [nop,nop,TS val 3974606612 ecr 1845608], length 0
E..4..@.@.A.

.[..._.v..{vT...A.....,......
......)h
15:37:49.157189 IP pu-in-f95.1e100.net.https > programming-Lab-50.37750: Flags [.], ack 3452, win 1540, options [nop,nop,TS val 1845608 ecr 3974606612], length 0
E..4.h@.@......_

.[...v..A.{vT......D.....
..)h....
15:37:49.195148 IP pu-in-f95.1e100.net.https > programming-Lab-50.37750: Flags [F.], seq 4872, ack 3453, win 1540, options [nop,nop,TS val 1845619 ecr 3974606612], length 0
E..4.i@.@......_

.[...v..A.{vT......7.....
..)s....
15:38:30.937262 IP lb-140-82-112-26-iad.github.com.https > programming-Lab-50.36710: Flags [P.], seq 3896:3921, ack 3666, win 1540, options [nop,nop,TS val 1858142 ecr 243551226], length 25
E..M..@.@.$..Rp.

.[...fU..z..t2....\......
..Z^..K......6JC..v>....x.b......
15:38:30.937303 IP programming-Lab-50.36710 > lb-140-82-112-26-iad.github.com.https: Flags [.], ack 3921, win 501, options [nop,nop,TS val 243610896 ecr 1858142], length 0
E..4<.@.@..

.[.Rp..f....t2U..............
..5...Z^
15:38:30.937555 IP programming-Lab-50.36710 > lb-140-82-112-26-iad.github.com.https: Flags [P.], seq 3666:3695, ack 3921, win 501, options [nop,nop,TS val 243610896 ecr 1858142], length 29
E..Q<.@.@...

.[.Rp..f....t2U..............
..5...Z^........K....b....W...(G....q
15:38:30.937695 IP lb-140-82-112-26-iad.github.com.https > programming-Lab-50.36710: Flags [.], ack 3695, win 1540, options [nop,nop,TS val 1858142 ecr 243610896], length 0
E..4..@.@.$..Rp.

.[...fU.....tO....w3.....
..Z^..5.
^C
87 packets captured
89 packets received by filter
1 packet dropped by kernel
(base) mtech@programming-Lab-50:~$ 
