# -IT250423_26-06-2025_HARLEEN
5 Individual learning points in this file
1.How to run command line in a specific directory from desktop.
2.Change Notepads settings to start from new session. 
3.learnt commands as ipconfig 
4.how to see the text inside document by command type notepad A221-PC007.txt
5.system information command

Microsoft Windows [Version 10.0.26100.4351]
(c) Microsoft Corporation. All rights reserved.

C:\Work>dir
 Volume in drive C is Windows
 Volume Serial Number is 5015-428E

 Directory of C:\Work

06/26/2025  08:58 AM    <DIR>          .
06/26/2025  08:57 AM                 0 A221-PC007.txt
               1 File(s)              0 bytes
               1 Dir(s)  833,548,972,032 bytes free

C:\Work>notepad A221-PC007.txt

C:\Work>type A221-PC007.txt
This will contain information about this computer.

second line

C:\Work>systeminfo

Host Name:                     A221-PC007
OS Name:                       Microsoft Windows 11 Pro
OS Version:                    10.0.26100 N/A Build 26100
OS Manufacturer:               Microsoft Corporation
OS Configuration:              Member Workstation
OS Build Type:                 Multiprocessor Free
Registered Owner:              Windows user
Registered Organization:       PEC
Product ID:                    00331-10000-00001-AA801
Original Install Date:         3/25/2025, 3:43:55 PM
System Boot Time:              6/13/2025, 9:02:44 AM
System Manufacturer:           Dell Inc.
System Model:                  OptiPlex SFF Plus 7010
System Type:                   x64-based PC
Processor(s):                  1 Processor(s) Installed.
                               [01]: Intel64 Family 6 Model 183 Stepping 1 GenuineIntel ~2100 Mhz
BIOS Version:                  Dell Inc. 1.17.0, 8/9/2024
Windows Directory:             C:\Windows
System Directory:              C:\Windows\system32
Boot Device:                   \Device\HarddiskVolume1
System Locale:                 en-us;English (United States)
Input Locale:                  en-us;English (United States)
Time Zone:                     (UTC-05:00) Eastern Time (US & Canada)
Total Physical Memory:         32,457 MB
Available Physical Memory:     18,033 MB
Virtual Memory: Max Size:      34,505 MB
Virtual Memory: Available:     14,578 MB
Virtual Memory: In Use:        19,927 MB
Page File Location(s):         C:\pagefile.sys
Domain:                        networksupport.local
Logon Server:                  \\SRV01
Hotfix(s):                     5 Hotfix(s) Installed.
                               [01]: KB5056579
                               [02]: KB5048779
                               [03]: KB5050575
                               [04]: KB5063060
                               [05]: KB5059502
Network Card(s):               2 NIC(s) Installed.
                               [01]: VirtualBox Host-Only Ethernet Adapter
                                     Connection Name: Ethernet 2
                                     DHCP Enabled:    No
                                     IP address(es)
                                     [01]: 192.168.56.1
                                     [02]: fe80::ce8f:db13:b41f:942a
                               [02]: Intel(R) Ethernet Connection (17) I219-LM
                                     Connection Name: Ethernet
                                     DHCP Enabled:    Yes
                                     DHCP Server:     192.168.221.1
                                     IP address(es)
                                     [01]: 192.168.221.126
                                     [02]: fe80::9b94:b115:f252:1245
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
                                     Hypervisor-Enforced Paging Translation
                               App Control for Business policy: Enforced
                               App Control for Business user mode policy: Off
                               Security Features Enabled:
Hyper-V Requirements:          A hypervisor has been detected. Features required for Hyper-V will not be displayed.

C:\Work>ipconfig/all

Windows IP Configuration

   Host Name . . . . . . . . . . . . : A221-PC007
   Primary Dns Suffix  . . . . . . . : networksupport.local
   Node Type . . . . . . . . . . . . : Hybrid
   IP Routing Enabled. . . . . . . . : No
   WINS Proxy Enabled. . . . . . . . : No
   DNS Suffix Search List. . . . . . : networksupport.local

Ethernet adapter Ethernet:

   Connection-specific DNS Suffix  . : networksupport.local
   Description . . . . . . . . . . . : Intel(R) Ethernet Connection (17) I219-LM
   Physical Address. . . . . . . . . : CC-96-E5-36-9A-ED
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes
   Link-local IPv6 Address . . . . . : fe80::9b94:b115:f252:1245%17(Preferred)
   IPv4 Address. . . . . . . . . . . : 192.168.221.126(Preferred)
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Lease Obtained. . . . . . . . . . : Friday, June 13, 2025 9:02:58 AM
   Lease Expires . . . . . . . . . . : Friday, June 27, 2025 9:06:13 AM
   Default Gateway . . . . . . . . . : 192.168.221.1
   DHCP Server . . . . . . . . . . . : 192.168.221.1
   DHCPv6 IAID . . . . . . . . . . . : 399283941
   DHCPv6 Client DUID. . . . . . . . : 00-01-00-01-2F-74-E9-B6-CC-96-E5-36-9A-ED
   DNS Servers . . . . . . . . . . . : 192.168.2.203
                                       192.168.2.205
                                       192.168.2.155
   Primary WINS Server . . . . . . . : 192.168.2.205
   Secondary WINS Server . . . . . . : 192.168.2.203
   NetBIOS over Tcpip. . . . . . . . : Enabled

Ethernet adapter Ethernet 2:

   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : VirtualBox Host-Only Ethernet Adapter
   Physical Address. . . . . . . . . : 0A-00-27-00-00-05
   DHCP Enabled. . . . . . . . . . . : No
   Autoconfiguration Enabled . . . . : Yes
   Link-local IPv6 Address . . . . . : fe80::ce8f:db13:b41f:942a%5(Preferred)
   IPv4 Address. . . . . . . . . . . : 192.168.56.1(Preferred)
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . :
   DHCPv6 IAID . . . . . . . . . . . : 168427559
   DHCPv6 Client DUID. . . . . . . . : 00-01-00-01-2F-74-E9-B6-CC-96-E5-36-9A-ED
   NetBIOS over Tcpip. . . . . . . . : Enabled

Ethernet adapter vEthernet (Default Switch):

   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Hyper-V Virtual Ethernet Adapter
   Physical Address. . . . . . . . . : 00-15-5D-B6-AB-0B
   DHCP Enabled. . . . . . . . . . . : No
   Autoconfiguration Enabled . . . . : Yes
   Link-local IPv6 Address . . . . . : fe80::e630:f075:4db8:4a19%19(Preferred)
   IPv4 Address. . . . . . . . . . . : 172.28.96.1(Preferred)
   Subnet Mask . . . . . . . . . . . : 255.255.240.0
   Default Gateway . . . . . . . . . :
   DHCPv6 IAID . . . . . . . . . . . : 318772573
   DHCPv6 Client DUID. . . . . . . . : 00-01-00-01-2F-74-E9-B6-CC-96-E5-36-9A-ED
   NetBIOS over Tcpip. . . . . . . . : Enabled

C:\Work>

 
