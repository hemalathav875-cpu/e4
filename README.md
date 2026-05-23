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
  
  Microsoft Windows [Version 10.0.26200.8246] (c) Microsoft Corporation. All rights reserved.

C:\Users\acer>ipconfig

Windows IP Configuration

Wireless LAN adapter Local Area Connection* 1:

Media State . . . . . . . . . . . : Media disconnected Connection-specific DNS Suffix . :

Wireless LAN adapter Local Area Connection* 2:

Media State . . . . . . . . . . . : Media disconnected Connection-specific DNS Suffix . :

Wireless LAN adapter Wi-Fi:

Connection-specific DNS Suffix . : saveetha.in IPv6 Address. . . . . . . . . . . : 2403:8600:c090:42:0:400:0:6bb1 Link-local IPv6 Address . . . . . : fe80::79b2:1df4:c41c:81b9%15 Autoconfiguration IPv4 Address. . : 169.254.39.39 Subnet Mask . . . . . . . . . . . : 255.255.0.0 Default Gateway . . . . . . . . . : fe80::eedd:24ff:fe3d:ced5%15

Ethernet adapter Ethernet:

Media State . . . . . . . . . . . : Media disconnected Connection-specific DNS Suffix . :

C:\Users\acer>ping google.com

Pinging google.com [2404:6800:4007:815::200e] with 32 bytes of data: Reply from 2404:6800:4007:815::200e: time=52ms Reply from 2404:6800:4007:815::200e: time=7ms Reply from 2404:6800:4007:815::200e: time=15ms Reply from 2404:6800:4007:815::200e: time=7ms

Ping statistics for 2404:6800:4007:815::200e: Packets: Sent = 4, Received = 4, Lost = 0 (0% loss), Approximate round trip times in milli-seconds: Minimum = 7ms, Maximum = 52ms, Average = 20ms

C:\Users\acer>nslookup microsoft.com Server: UnKnown Address: 2403:8600:c090:42:a000::200

Non-authoritative answer: Name: microsoft.com Addresses: 2603:1061:14:152::1 150.171.110.82

C:\Users\acer>tracert google.com

Tracing route to google.com [2404:6800:4007:815::200e] over a maximum of 30 hops:

1 4 ms 4 ms 5 ms 2403:8600:c090:42::1 2 * * * Request timed out. 3 * * * Request timed out. 4 14 ms 9 ms 7 ms maa05s14-in-x0e.1e100.net [2404:6800:4007:815::200e]

Trace complete.

C:\Users\acer>systeminfo

Host Name: TMP215-75-G2 OS Name: Microsoft Windows 11 Home Single Language OS Version: 10.0.26200 N/A Build 26200 OS Manufacturer: Microsoft Corporation OS Configuration: Standalone Workstation OS Build Type: Multiprocessor Free Registered Owner: acer Registered Organization: N/A Product ID: 00342-42784-11372-AAOEM Original Install Date: 01-09-2025, 15:21:05 System Boot Time: 12-05-2026, 07:55:29 System Manufacturer: Acer System Model: TravelMate P215-75-G2-TCO System Type: x64-based PC Processor(s): 1 Processor(s) Installed. [01]: Intel64 Family 6 Model 170 Stepping 4 GenuineIntel ~1200 Mhz BIOS Version: INSYDE Corp. V1.05tt01a, 01-09-2025 Windows Directory: C:\Windows System Directory: C:\Windows\system32 Boot Device: \Device\HarddiskVolume1 System Locale: en-us;English (United States) Input Locale: 00004009 Time Zone: (UTC+05:30) Chennai, Kolkata, Mumbai, New Delhi Total Physical Memory: 15,869 MB Available Physical Memory: 7,476 MB Virtual Memory: Max Size: 21,245 MB Virtual Memory: Available: 10,972 MB Virtual Memory: In Use: 10,273 MB Page File Location(s): C:\pagefile.sys Domain: WORKGROUP Logon Server: \TMP215-75-G2 Hotfix(s): 4 Hotfix(s) Installed. [01]: KB5082417 [02]: KB5054156 [03]: KB5083769 [04]: KB5088467 Network Card(s): 2 NIC(s) Installed. [01]: Intel(R) Wi-Fi 6E AX211 160MHz Connection Name: Wi-Fi DHCP Enabled: Yes DHCP Server: 255.255.255.255 IP address(es) [01]: 169.254.39.39 [02]: fe80::79b2:1df4:c41c:81b9 [03]: 2403:8600:c090:42:0:400:0:6bb1 [02]: Realtek PCIe GbE Family Controller Connection Name: Ethernet Status: Media disconnected Virtualization-based security: Status: Running Required Security Properties: Base Virtualization Support Available Security Properties: Base Virtualization Support Secure Boot DMA Protection UEFI Code Readonly SMM Security Mitigations 1.0 Mode Based Execution Control APIC Virtualization Services Configured: Hypervisor enforced Code Integrity Services Running: Hypervisor enforced Code Integrity App Control for Business policy: Enforced App Control for Business user mode policy: Enforced Security Features Enabled: Hyper-V Requirements: A hypervisor has been detected. Features required for Hyper-V will not be displayed.

C:\Users\acer>arp -a

Interface: 169.254.39.39 --- 0xf Internet Address Physical Address Type 169.254.50.66 d0-7e-28-d4-32-43 dynamic 169.254.90.209 fc-6d-77-8b-0d-62 dynamic 169.254.92.185 fc-6d-77-6c-01-1a dynamic 169.254.113.11 fc-6d-77-6b-e4-6e dynamic 169.254.118.232 fc-6d-77-6c-71-9f dynamic 169.254.119.31 fc-6d-77-6b-f2-a6 dynamic 169.254.195.221 fc-6d-77-89-b0-e3 dynamic 169.254.248.246 fc-6d-77-6f-b7-e2 dynamic 169.254.255.255 ff-ff-ff-ff-ff-ff static 224.0.0.22 01-00-5e-00-00-16 static 224.0.0.251 01-00-5e-00-00-fb static 224.0.0.252 01-00-5e-00-00-fc static 230.0.0.1 01-00-5e-00-00-01 static 239.255.255.250 01-00-5e-7f-ff-fa static 255.255.255.255 ff-ff-ff-ff-ff-ff static

C:\Users\acer>hostname TMP215-75-G2

C:\Users\acer>netstat

Active Connections

Proto Local Address Foreign Address State TCP 127.0.0.1:5141 TMP215-75-G2:50572 ESTABLISHED TCP 127.0.0.1:46935 TMP215-75-G2:52530 ESTABLISHED TCP 127.0.0.1:46936 TMP215-75-G2:49684 ESTABLISHED TCP 127.0.0.1:46937 TMP215-75-G2:49685 ESTABLISHED TCP 127.0.0.1:49669 TMP215-75-G2:49670 ESTABLISHED TCP 127.0.0.1:49670 TMP215-75-G2:49669 ESTABLISHED TCP 127.0.0.1:49673 TMP215-75-G2:49674 ESTABLISHED TCP 127.0.0.1:49674 TMP215-75-G2:49673 ESTABLISHED TCP 127.0.0.1:49676 TMP215-75-G2:49677 ESTABLISHED TCP 127.0.0.1:49677 TMP215-75-G2:49676 ESTABLISHED TCP 127.0.0.1:49678 TMP215-75-G2:49679 ESTABLISHED TCP 127.0.0.1:49679 TMP215-75-G2:49678 ESTABLISHED TCP 127.0.0.1:49680 TMP215-75-G2:49681 ESTABLISHED TCP 127.0.0.1:49681 TMP215-75-G2:49680 ESTABLISHED TCP 127.0.0.1:49682 TMP215-75-G2:49683 ESTABLISHED TCP 127.0.0.1:49683 TMP215-75-G2:49682 ESTABLISHED TCP 127.0.0.1:49684 TMP215-75-G2:46936 ESTABLISHED TCP 127.0.0.1:49685 TMP215-75-G2:46937 ESTABLISHED TCP 127.0.0.1:50572 TMP215-75-G2:5141 ESTABLISHED TCP 127.0.0.1:52391 TMP215-75-G2:58995 ESTABLISHED TCP 127.0.0.1:52524 TMP215-75-G2:52525 ESTABLISHED TCP 127.0.0.1:52525 TMP215-75-G2:52524 ESTABLISHED TCP 127.0.0.1:52526 TMP215-75-G2:52527 ESTABLISHED TCP 127.0.0.1:52527 TMP215-75-G2:52526 ESTABLISHED TCP 127.0.0.1:52528 TMP215-75-G2:52529 ESTABLISHED TCP 127.0.0.1:52529 TMP215-75-G2:52528 ESTABLISHED TCP 127.0.0.1:52530 TMP215-75-G2:46935 ESTABLISHED TCP 127.0.0.1:58995 TMP215-75-G2:52391 ESTABLISHED TCP 127.0.0.1:58995 TMP215-75-G2:59990 ESTABLISHED TCP 127.0.0.1:58995 TMP215-75-G2:64422 ESTABLISHED TCP 127.0.0.1:59990 TMP215-75-G2:58995 ESTABLISHED TCP 127.0.0.1:64422 TMP215-75-G2:58995 ESTABLISHED TCP [::1]:15161 TMP215-75-G2:50571 ESTABLISHED TCP [::1]:15161 TMP215-75-G2:50573 ESTABLISHED TCP [::1]:15161 TMP215-75-G2:56904 TIME_WAIT TCP [::1]:15161 TMP215-75-G2:61189 TIME_WAIT TCP [::1]:15161 TMP215-75-G2:61190 ESTABLISHED TCP [::1]:50571 TMP215-75-G2:15161 ESTABLISHED TCP [::1]:50573 TMP215-75-G2:15161 ESTABLISHED TCP [::1]:61190 TMP215-75-G2:15161 ESTABLISHED TCP [2403:8600:c090:42:0:400:0:6bb1]:49413 [2603:1040:a06:6::]:https ESTABLISHED TCP [2403:8600:c090:42:0:400:0:6bb1]:50575 [2603:1040:a06:6::]:https ESTABLISHED TCP [2403:8600:c090:42:0:400:0:6bb1]:52521 [2a06:98c1:3108::ac40:94eb]:https ESTABLISHED TCP [2403:8600:c090:42:0:400:0:6bb1]:52798 whatsapp-cdn6-shv-03-maa3:https TIME_WAIT TCP [2403:8600:c090:42:0:400:0:6bb1]:56901 [64:ff9b::14bd:ad05]:https TIME_WAIT TCP [2403:8600:c090:42:0:400:0:6bb1]:56902 [2600:1901:1:7c5::]:https FIN_WAIT_2 TCP [2403:8600:c090:42:0:400:0:6bb1]:58480 whatsapp-cdn6-shv-03-maa3:5222 ESTABLISHED TCP [2403:8600:c090:42:0:400:0:6bb1]:60262 [2600:1901:0:47fc::]:https ESTABLISHED TCP [2403:8600:c090:42:0:400:0:6bb1]:60334 sb-in-f188:https ESTABLISHED TCP [2403:8600:c090:42:0:400:0:6bb1]:60936 [64:ff9b::acbc:9b19]:https ESTABLISHED TCP [2403:8600:c090:42:0:400:0:6bb1]:61188 [2403:8600:80c0:4a::e62:1008]:https CLOSE_WAIT TCP [2403:8600:c090:42:0:400:0:6bb1]:61909 whatsapp-cdn6-shv-03-maa3:5222 ESTABLISHED TCP [2403:8600:c090:42:0:400:0:6bb1]:62368 whatsapp-cdn6-shv-03-maa3:https ESTABLISHED TCP [2403:8600:c090:42:0:400:0:6bb1]:64111 [2a06:98c1:3100::6812:202f]:https ESTABLISHED TCP [2403:8600:c090:42:0:400:0:6bb1]:64322 lcbomp-in-f84:https ESTABLISHED

C:\Users\acer>getmac

Physical Address Transport Name =================== ========================================================== FC-6D-77-8A-E7-A1 \Device\Tcpip_{D5D1AED3-884C-4225-B3B9-9998F6CD4806} 74-D4-DD-CF-7B-D0 Media disconnected

C:\Users\acer>pathping google.com

Tracing route to google.com [2404:6800:4007:815::200e] over a maximum of 30 hops: 0 TMP215-75-G2.saveetha.in [2403:8600:c090:42:0:400:0:6bb1] 1 2403:8600:c090:42::1 2 * * * Computing statistics for 25 seconds... Source to Here This Node/Link Hop RTT Lost/Sent = Pct Lost/Sent = Pct Address 0 TMP215-75-G2.saveetha.in [2403:8600:c090:42:0:400:0:6bb1] 0/ 100 = 0% | 1 32ms 0/ 100 = 0% 0/ 100 = 0% 2403:8600:c090:42::1

Trace complete.

[text](<c:/Users/acer/Downloads/Command Promptneq.txt>)



## Result
Thus Execution of Network commands Performed 
