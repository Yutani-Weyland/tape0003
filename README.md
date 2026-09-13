
# Home Network

## Physical Topology
Optical signals travel from Valley Fibers Winkler network through underground fiber cables into my front yard, where the fiber cable connects to an Optical Network Termination (ONT) device. Through the siding and inside, the optical signal travels over a fiber optic patch cable with an LC connector, connected an OptiCore transceiver inserted into my MikroTik routers 'SFP+' slot where the optical signal is converted into an ethernet signal. Now in the living room, the MikroTik router provides local devices with connectivity via 5 GHz Wi-Fi, 2.4 GHz Wi-Fi. After that my upstairs laptop is able to connect to the routers 5 GHz channel.  
<img width="830" height="1085" alt="Home Network Physical Topology drawio" src="https://github.com/user-attachments/assets/bccc01af-4d1f-419b-94d9-13bbd0986462" />

## Logical Topology
Valley fiber Winkler sends optical signals over fiber cables to an ONT device in my network. From there, the signal is sent over fiber patch cable to my MikroTik router through an SFP+ OptiCore transceiver where the optical signal is converted to an ethernet signal. The MikroTik router provides LAN connectivity for all local devices via 5 GHz or 2.4 GHz Wi-Fi. My laptop is connected to the MikroTik router via its 5 GHz channel.  
<img width="1288" height="602" alt="Home Network Logical Topology drawio" src="https://github.com/user-attachments/assets/03ef4bc0-7250-46e4-99a8-75f303718c84" />

## IP Addressing
#### Mikrotik Router
IPv4 Address . . . . . . . . . . . . . . . . . : 192.168.100.1

#### Nitro V16 Laptop
Hostname: goerge

Wireless LAN adapter Wi-Fi:

Description. . . . . . . . . . . . . . . . . . : Killer(R) Wi-Fi 6E AX1675i 160MHz Wireless Network Adapter (211NGW)  
DHCP Enabled . . . . . . . . . . . . . . . . . : Yes  
Autoconfiguration Enabled. . . . . . . . . . . : Yes  
Link-local IPv6 Address. . . . . . . . . . . . : fe80::634b:742a:a8a6:529f%9(Preferred)  
IPv4 Address . . . . . . . . . . . . . . . . . : 192.168.100.129(Preferred)  
Subnet Mask. . . . . . . . . . . . . . . . . . : 255.255.255.0  
Default Gateway . . . . .  . . . . . . . . . . : 192.168.100.1  
DHCP Server. . . . . . . . . . . . . . . . . . : 192.168.100.1  
DNS Servers. . . . . . . . . . . . . . . . . . : 192.168.100.1  

#### Google Pixel 10
Hostname: Pixel 10  
IPv4 Address: 192.168.100.110  
IPv6 Address: fe80::8df:6fff:fe93:3bf2  

## Network Device Inventory

#### Optical Network Translation (ONT) Device
Make: N/A  
Model: N/A  

#### Micro-Tik router
Make: MikroTik  
Model: RB4011iGS+5HacQ2HnD-IN  
5 GHz Wi-Fi: 802.11 ac/n  
2.4 GHz Wi-Fi: 802.11 b/g/n  

##### Architecture  
ARM: 32bit  
CPU: AL21400  
CPU core count: 4    
CPU nominal frequency: auto (533 - 1900) MHz  
CPU Threads count: 4  
Switch chip model: RTL8367SB  
Dimensions: 228 x 120 x 30 mm  
Router OS: license: 5  
Operating System: RouterOS v7  
Size of RAM: 1 GB  
Storage size: 512 MB  
Storage type: NAND, MTBF  

##### Wireless  
Wireless 5 GHz Max data rate: 1733 Mbit/s  
Wireless 5 GHz Number of chains: 4  
Wireless 5 GHz standards: 802.11a/n/ac  
Antenna gain dBi for 5 GHz: 3  
Wireless 5 GHz chip model: QCA9984  
Wireless 5 GHz generation: Wi-Fi 5  
Wireless 2.4 GHz Max data rate: 300 Mbit/s  
Wireless 2.4 GHz Number of chains: 2  
Wireless 2.4 GHz standards: 802.11b/g/n  
Antenna gain dBi for 2.4 GHz: 3  
Wireless 2.4 GHz chip model: R11e-2HnD  
Wireless 2.4 GHz generation: Wi-Fi 4  
WiFi speed: AC2000  
Ethernet ports: 10  
SFP+ ports: 1  
MiniPCI-e slots: 1  
Serial console port: RJ45  

##### Power  
Number of DC inputs: 2 (DC jack, PoE-IN)  
DC jack input Voltage: 12-57 V  
Max power consumption: 44 W  
Max power consumption without attachments: 23 W  
PoE in: Passive PoE  
Cooling type: Passive  
PoE in input Voltage: 18-57 V  
PoE-out ports: Ether10  
PoE out: Passive PoE up to 57V  
Low voltage PoE-Out current limit: 600 mA  
High voltage PoE-Out current limit: 420 mA  
Max total out (A): 600 mA  

#### Nitro V16 Laptop
Model: AN16-73  
Operating System: Windows 11 Home  
##### CPU  
Intel(R) Core(TM) i7-14650HX  
Base speed:	2.20 GHz  
Sockets:	1  
Cores:	16  
Logical processors:	24  
Virtualization:	Enabled  
L1 cache:	1.4 MB  
L2 cache:	24.0 MB  
L3 cache:	30.0 MB  
Utilization:	4%  
Speed:	3.91 GHz  
Up time:	0:04:35:20  
Processes:	357  
Threads:	6196  
Handles:	323138  

##### Memory  
32.0 GB DDR5  
Speed:	5600 MT/s  
Slots used:	2 of 4  
Form factor:	SODIMM  
Hardware reserved:	296 MB  
Available:	17.8 GB  
Cached:	15.3 GB  
Committed:	19.6/33.7 GB  
Paged pool:	817 MB  
Non-paged pool:	1.2 GB  
In use (Compressed):	13.9 GB (1.1 GB)  

##### Disk 0 (C:)  
NVMe HFS001TEJ9X125N  
Capacity:	954 GB  
Formatted:	954 GB  
System disk:	Yes  
Page file:	Yes  
Type:	SSD  
Read speed:	0 KB/s  
Write speed:	32.7 KB/s  
Active time:	0%  
Average response time:	0.9 ms  

##### WiFi  
Killer(R) Wi-Fi 6E AX1675i 160MHz Wireless Network Adapter (211NGW)  
Adapter name:	Wi-Fi  
Connection type:	802.11ac  
IPv4 address:	192.168.100.129  
IPv6 address:	fe80::634b:742a:a8a6:529f%9  
Receive:	8.0 Kbps  
Send:	32.0 Kbps  

##### GPU 0  
NVIDIA GeForce RTX 4060 Laptop GPU  
Driver version:	32.0.16.1062  
Driver date:	2026-06-11  
DirectX version:	12 (FL 12.2)  
Physical location:	PCI bus 1, device 0, function 0  
Utilisation:	11%  
Dedicated GPU memory:	2.0/8.0 GB  
Shared GPU memory:	0.1/15.9 GB  
GPU Memory:	2.2/23.9 GB  

##### GPU 1  
Intel(R) UHD Graphics  
Driver version:	31.0.101.4502  
Driver date:	2023-06-15  
DirectX version:	12 (FL 12.1)  
Physical location:	PCI bus 0, device 2, function 0  
Utilisation:	5%  
Dedicated GPU memory:	2.1/8.0 GB  
Shared GPU memory:	0.6/15.9 GB  
GPU Memory:	0.6/15.9 GB  

#### Google Pixel 10
Model: Pixel 10  
Operating System: Android
Android Version: 16  
Build #: CP1A.260505.005  
Memory: 16 GB Ram  
Storage: 128 GB  
Processor: Google Tensor G5, Titan M2 security coprocessor  

## Network Services
MikroTik router:  
Services provided include:
* Firewall protections.
* DHCP service.
* NAT service.

## Relevant device configuration info  
##### MikroTik Router:   
ISP default configuration for standard home network.  
  
## Method to store login credentials
* WPA2-Personal (WPA2-PSK) security protocol.  
* WPA2 Personal uses the IEEE 802.11i protocol.  
* Uses a single shared password and AES encryption.  

## Revision History

| Version | Date | Time | Name |
| --- | --- | --- | --- |
| 0.1 | 2026-07-25 | 16:45 | Jonathan |
| 0.5 | 2026-07-26 | 17:02 | Jonathan |
| 1.0 | 2026-07-27 | 23:03 | Jonathan |

## References to any related materials
##### Link to router product page
https://mikrotik.com/product/rb4011igs_5hacq2hnd_in  
https://support.google.com/pixelphone/answer/7158570?hl=en#zippy=%2Cpixel  
https://store.google.com/us/product/pixel_10_specs?hl=en-US&pli=1  
