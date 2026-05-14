# 4.Execution_of_NetworkCommands
## AIM :Use of Network commands in Real Time environment
## Software : Command Prompt And Network Protocol Analyzer
## Procedure: To do this EXPERIMENT- follows these steps:
<BR>
In this EXPERIMENT- students have to understand basic networking commands e.g cpdump, netstat, ifconfig, nslookup ,traceroute and also Capture ping and traceroute PDUs using a network protocol analyzer 
<BR>
All commands related to Network configuration which includes how to switch to privilege mode
<BR>
and normal mode and how to configure router interface and how to save this configuration to
<BR>
flash memory or permanent memory.
<BR>
This commands includes
<BR>
• Configuring the Router commands
<BR>
• General Commands to configure network
<BR>
• Privileged Mode commands of a router 
<BR>
• Router Processes & Statistics
<BR>
• IP Commands
<BR>
• Other IP Commands e.g. show ip route etc.
<BR>

## Output
  
  Microsoft Windows [Version 10.0.26200.8246]
(c) Microsoft Corporation. All rights reserved.

C:\Users\acer>ping

Usage: ping [-t] [-a] [-n count] [-l size] [-f] [-i TTL] [-v TOS]
            [-r count] [-s count] [[-j host-list] | [-k host-list]]
            [-w timeout] [-R] [-S srcaddr] [-c compartment] [-p]
            [-4] [-6] target_name

Options:
    -t             Ping the specified host until stopped.
                   To see statistics and continue - type Control-Break;
                   To stop - type Control-C.
    -a             Resolve addresses to hostnames.
    -n count       Number of echo requests to send.
    -l size        Send buffer size.
    -f             Set Don't Fragment flag in packet (IPv4-only).
    -i TTL         Time To Live.
    -v TOS         Type Of Service (IPv4-only. This setting has been deprecated
                   and has no effect on the type of service field in the IP
                   Header).
    -r count       Record route for count hops (IPv4-only).
    -s count       Timestamp for count hops (IPv4-only).
    -j host-list   Loose source route along host-list (IPv4-only).
    -k host-list   Strict source route along host-list (IPv4-only).
    -w timeout     Timeout in milliseconds to wait for each reply.
    -R             Use routing header to test reverse route also (IPv6-only).
                   Per RFC 5095 the use of this routing header has been
                   deprecated. Some systems may drop echo requests if
                   this header is used.
    -S srcaddr     Source address to use.
    -c compartment Routing compartment identifier.
    -p             Ping a Hyper-V Network Virtualization provider address.
    -4             Force using IPv4.
    -6             Force using IPv6.


C:\Users\acer>systeminfo

Host Name:                     TMP215-75-G2
OS Name:                       Microsoft Windows 11 Home Single Language
OS Version:                    10.0.26200 N/A Build 26200
OS Manufacturer:               Microsoft Corporation
OS Configuration:              Standalone Workstation
OS Build Type:                 Multiprocessor Free
Registered Owner:              acer
Registered Organization:       N/A
Product ID:                    00342-42784-11330-AAOEM
Original Install Date:         01-09-2025, 15:21:05
System Boot Time:              14-05-2026, 08:16:47
System Manufacturer:           Acer
System Model:                  TravelMate P215-75-G2-TCO
System Type:                   x64-based PC
Processor(s):                  1 Processor(s) Installed.
                               [01]: Intel64 Family 6 Model 170 Stepping 4 GenuineIntel ~1200 Mhz
BIOS Version:                  INSYDE Corp. V1.05tt01a, 01-09-2025
Windows Directory:             C:\Windows
System Directory:              C:\Windows\system32
Boot Device:                   \Device\HarddiskVolume1
System Locale:                 en-us;English (United States)
Input Locale:                  00004009
Time Zone:                     (UTC+05:30) Chennai, Kolkata, Mumbai, New Delhi
Total Physical Memory:         15,869 MB
Available Physical Memory:     6,333 MB
Virtual Memory: Max Size:      18,301 MB
Virtual Memory: Available:     7,118 MB
Virtual Memory: In Use:        11,183 MB
Page File Location(s):         C:\pagefile.sys
Domain:                        WORKGROUP
Logon Server:                  \\TMP215-75-G2
Hotfix(s):                     6 Hotfix(s) Installed.
                               [01]: KB5082417
                               [02]: KB5087051
                               [03]: KB5054156
                               [04]: KB5089549
                               [05]: KB5088467
                               [06]: KB5092762
Network Card(s):               2 NIC(s) Installed.
                               [01]: Intel(R) Wi-Fi 6E AX211 160MHz
                                     Connection Name: Wi-Fi
                                     DHCP Enabled:    Yes
                                     DHCP Server:     10.211.32.5
                                     IP address(es)
                                     [01]: 10.211.32.128
                                     [02]: fe80::e94d:bcc3:dea5:3149
                                     [03]: 2401:4900:67cb:7c1c:d105:b4ab:674a:d483
                                     [04]: 2401:4900:67cb:7c1c:e711:eb6b:eb7b:2a26
                               [02]: Realtek PCIe GbE Family Controller
                                     Connection Name: Ethernet
                                     Status:          Media disconnected
Virtualization-based security: Status: Running
                               Required Security Properties:
                                     Base Virtualization Support
                               Available Security Properties:
                                     Base Virtualization Support
                                     Secure Boot
                                     DMA Protection
                                     UEFI Code Readonly
                                     SMM Security Mitigations 1.0
                                     Mode Based Execution Control
                                     APIC Virtualization
                               Services Configured:
                                     Hypervisor enforced Code Integrity
                               Services Running:
                                     Hypervisor enforced Code Integrity
                               App Control for Business policy: Enforced
                               App Control for Business user mode policy: Off
                               Security Features Enabled:
Hyper-V Requirements:          A hypervisor has been detected. Features required for Hyper-V will not be displayed.

C:\Users\acer>ipconfig

Windows IP Configuration


Wireless LAN adapter Local Area Connection* 1:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Local Area Connection* 2:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Wi-Fi:

   Connection-specific DNS Suffix  . :
   IPv6 Address. . . . . . . . . . . : 2401:4900:67cb:7c1c:e711:eb6b:eb7b:2a26
   Temporary IPv6 Address. . . . . . : 2401:4900:67cb:7c1c:d105:b4ab:674a:d483
   Link-local IPv6 Address . . . . . : fe80::e94d:bcc3:dea5:3149%18
   IPv4 Address. . . . . . . . . . . : 10.211.32.128
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . : fe80::4476:12ff:fe72:d6a0%18
                                       10.211.32.5

Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

C:\Users\acer>tracert www.google.com

Tracing route to www.google.com [2001:4860:482d:7700::]
over a maximum of 30 hops:

  1     2 ms     5 ms     5 ms  2401:4900:67cb:7c1c::c7
  2     *        *        *     Request timed out.
  3    59 ms    46 ms    38 ms  2401:4900:0:1537::1
  4    76 ms   177 ms    51 ms  2401:4900:0:6ff::2
  5    63 ms    34 ms    37 ms  2401:4900:0:6f9::1
  6     *        *        *     Request timed out.
  7   169 ms    70 ms    66 ms  2404:a800:3a00:1::601
  8    62 ms    25 ms    46 ms  2404:a800::92
  9    48 ms    67 ms    39 ms  2001:4860:482d:7700::

Trace complete.

C:\Users\acer>hostname
TMP215-75-G2

C:\Users\acer>getmac

Physical Address    Transport Name
=================== ==========================================================
FC-6D-77-9A-02-04   \Device\Tcpip_{FE35F4EA-51B0-4045-838B-742579F88B1D}
74-D4-DD-CF-7E-18   Media disconnected

C:\Users\acer>route print
===========================================================================
Interface List
 11...fc 6d 77 9a 02 05 ......Microsoft Wi-Fi Direct Virtual Adapter
  9...fe 6d 77 9a 02 04 ......Microsoft Wi-Fi Direct Virtual Adapter #2
 18...fc 6d 77 9a 02 04 ......Intel(R) Wi-Fi 6E AX211 160MHz
  4...74 d4 dd cf 7e 18 ......Realtek PCIe GbE Family Controller
  1...........................Software Loopback Interface 1
===========================================================================

IPv4 Route Table
===========================================================================
Active Routes:
Network Destination        Netmask          Gateway       Interface  Metric
          0.0.0.0          0.0.0.0      10.211.32.5    10.211.32.128     55
      10.211.32.0    255.255.255.0         On-link     10.211.32.128    311
    10.211.32.128  255.255.255.255         On-link     10.211.32.128    311
    10.211.32.255  255.255.255.255         On-link     10.211.32.128    311
        127.0.0.0        255.0.0.0         On-link         127.0.0.1    331
        127.0.0.1  255.255.255.255         On-link         127.0.0.1    331
  127.255.255.255  255.255.255.255         On-link         127.0.0.1    331
        224.0.0.0        240.0.0.0         On-link         127.0.0.1    331
        224.0.0.0        240.0.0.0         On-link     10.211.32.128    311
  255.255.255.255  255.255.255.255         On-link         127.0.0.1    331
  255.255.255.255  255.255.255.255         On-link     10.211.32.128    311
===========================================================================
Persistent Routes:
  None

IPv6 Route Table
===========================================================================
Active Routes:
 If Metric Network Destination      Gateway
 18     71 ::/0                     fe80::4476:12ff:fe72:d6a0
  1    331 ::1/128                  On-link
 18     71 2401:4900:67cb:7c1c::/64 On-link
 18    311 2401:4900:67cb:7c1c:d105:b4ab:674a:d483/128
                                    On-link
 18    311 2401:4900:67cb:7c1c:e711:eb6b:eb7b:2a26/128
                                    On-link
 18    311 fe80::/64                On-link
 18    311 fe80::e94d:bcc3:dea5:3149/128
                                    On-link
  1    331 ff00::/8                 On-link
 18    311 ff00::/8                 On-link
===========================================================================
Persistent Routes:
  None

C:\Users\acer>netstat

Active Connections

  Proto  Local Address          Foreign Address        State
  TCP    10.211.32.128:49375    10.211.32.5:domain     TIME_WAIT
  TCP    10.211.32.128:50130    10.211.32.5:domain     TIME_WAIT
  TCP    10.211.32.128:50313    10.211.32.5:domain     TIME_WAIT
  TCP    10.211.32.128:53465    10.211.32.5:domain     TIME_WAIT
  TCP    10.211.32.128:59756    13.69.239.72:https     ESTABLISHED
  TCP    10.211.32.128:60772    10.211.32.5:domain     TIME_WAIT
  TCP    10.211.32.128:65516    10.211.32.5:domain     TIME_WAIT
  TCP    10.211.32.128:65519    13.70.79.200:https     ESTABLISHED
  TCP    10.211.32.128:65520    52.182.143.215:https   ESTABLISHED
  TCP    127.0.0.1:5141         TMP215-75-G2:56490     ESTABLISHED
  TCP    127.0.0.1:46935        TMP215-75-G2:51010     ESTABLISHED
  TCP    127.0.0.1:46936        TMP215-75-G2:49680     ESTABLISHED
  TCP    127.0.0.1:46937        TMP215-75-G2:49683     ESTABLISHED
  TCP    127.0.0.1:49669        TMP215-75-G2:49670     ESTABLISHED
  TCP    127.0.0.1:49670        TMP215-75-G2:49669     ESTABLISHED
  TCP    127.0.0.1:49674        TMP215-75-G2:49675     ESTABLISHED
  TCP    127.0.0.1:49675        TMP215-75-G2:49674     ESTABLISHED
  TCP    127.0.0.1:49676        TMP215-75-G2:49677     ESTABLISHED
  TCP    127.0.0.1:49677        TMP215-75-G2:49676     ESTABLISHED
  TCP    127.0.0.1:49678        TMP215-75-G2:49679     ESTABLISHED
  TCP    127.0.0.1:49679        TMP215-75-G2:49678     ESTABLISHED
  TCP    127.0.0.1:49680        TMP215-75-G2:46936     ESTABLISHED
  TCP    127.0.0.1:49681        TMP215-75-G2:49682     ESTABLISHED
  TCP    127.0.0.1:49682        TMP215-75-G2:49681     ESTABLISHED
  TCP    127.0.0.1:49683        TMP215-75-G2:46937     ESTABLISHED
  TCP    127.0.0.1:49685        TMP215-75-G2:49686     ESTABLISHED
  TCP    127.0.0.1:49686        TMP215-75-G2:49685     ESTABLISHED
  TCP    127.0.0.1:49700        TMP215-75-G2:58995     ESTABLISHED
  TCP    127.0.0.1:49707        TMP215-75-G2:58995     ESTABLISHED
  TCP    127.0.0.1:51004        TMP215-75-G2:51005     ESTABLISHED
  TCP    127.0.0.1:51005        TMP215-75-G2:51004     ESTABLISHED
  TCP    127.0.0.1:51006        TMP215-75-G2:51007     ESTABLISHED
  TCP    127.0.0.1:51007        TMP215-75-G2:51006     ESTABLISHED
  TCP    127.0.0.1:51008        TMP215-75-G2:51009     ESTABLISHED
  TCP    127.0.0.1:51009        TMP215-75-G2:51008     ESTABLISHED
  TCP    127.0.0.1:51010        TMP215-75-G2:46935     ESTABLISHED
  TCP    127.0.0.1:56490        TMP215-75-G2:5141      ESTABLISHED
  TCP    127.0.0.1:58286        TMP215-75-G2:58995     ESTABLISHED
  TCP    127.0.0.1:58995        TMP215-75-G2:49700     ESTABLISHED
  TCP    127.0.0.1:58995        TMP215-75-G2:49707     ESTABLISHED
  TCP    127.0.0.1:58995        TMP215-75-G2:58286     ESTABLISHED
  TCP    [::1]:15161            TMP215-75-G2:56486     ESTABLISHED
  TCP    [::1]:15161            TMP215-75-G2:56532     ESTABLISHED
  TCP    [::1]:15161            TMP215-75-G2:56728     ESTABLISHED
  TCP    [::1]:15161            TMP215-75-G2:65518     TIME_WAIT
  TCP    [::1]:56486            TMP215-75-G2:15161     ESTABLISHED
  TCP    [::1]:56532            TMP215-75-G2:15161     ESTABLISHED
  TCP    [::1]:56727            TMP215-75-G2:15161     TIME_WAIT
  TCP    [::1]:56728            TMP215-75-G2:15161     ESTABLISHED
  TCP    [::1]:65518            TMP215-75-G2:15161     TIME_WAIT
  TCP    [2401:4900:67cb:7c1c:d105:b4ab:674a:d483]:49421  [2603:1040:a06:6::]:https  ESTABLISHED
  TCP    [2401:4900:67cb:7c1c:d105:b4ab:674a:d483]:49672  [2603:1046:c06:c76::2]:https  ESTABLISHED
  TCP    [2401:4900:67cb:7c1c:d105:b4ab:674a:d483]:53126  g2600-140f-2400-01a4-0000-0000-0000-0057:https  ESTABLISHED
  TCP    [2401:4900:67cb:7c1c:d105:b4ab:674a:d483]:54639  se-in-f188:5228        ESTABLISHED
  TCP    [2401:4900:67cb:7c1c:d105:b4ab:674a:d483]:58250  [2603:1046:c04:8a0::2]:https  FIN_WAIT_1
  TCP    [2401:4900:67cb:7c1c:d105:b4ab:674a:d483]:65475  [2603:1040:a06:6::]:https  ESTABLISHED

C:\Users\acer>curl
curl: try 'curl --help' for more information

C:\Users\acer>pathping google.com

Tracing route to google.com [2404:6800:4007:821::200e]
over a maximum of 30 hops:
  0  TMP215-75-G2 [2401:4900:67cb:7c1c:d105:b4ab:674a:d483]
  1  2401:4900:67cb:7c1c::c7
  2     *        *        *
Computing statistics for 25 seconds...
            Source to Here   This Node/Link
Hop  RTT    Lost/Sent = Pct  Lost/Sent = Pct  Address
  0                                           TMP215-75-G2 [2401:4900:67cb:7c1c:d105:b4ab:674a:d483]
                                2/ 100 =  2%   |
  1   26ms     2/ 100 =  2%     0/ 100 =  0%  2401:4900:67cb:7c1c::c7

Trace complete.

C:\Users\acer>arp -a

Interface: 10.211.32.128 --- 0x12
  Internet Address      Physical Address      Type
  10.211.32.5           46-76-12-72-d6-a0     dynamic
  10.211.32.255         ff-ff-ff-ff-ff-ff     static
  224.0.0.22            01-00-5e-00-00-16     static
  224.0.0.251           01-00-5e-00-00-fb     static
  224.0.0.252           01-00-5e-00-00-fc     static
  239.255.255.250       01-00-5e-7f-ff-fa     static
  255.255.255.255       ff-ff-ff-ff-ff-ff     static




  [text](<c:/Users/acer/Downloads/Command Prompt2.txt>)
## Result
Thus Execution of Network commands Performed 
