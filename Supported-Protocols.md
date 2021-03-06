# Supported Protocols

PacketGen provides built-in packet parsers for the following protocols:

### Protocols
| Protocol 	|       Status      	|  More info  |
|:--------:	|:-----------------:	|:-----------:|
| [Dot11](http://www.rubydoc.info/gems/packetgen/PacketGen/Header/Dot11)    |     ✔     	| |
| [ETH](http://www.rubydoc.info/gems/packetgen/PacketGen/Header/Eth)   	    |     ✔     	| |
| [LLC](http://www.rubydoc.info/gems/packetgen/PacketGen/Header/LLC)   	    |     ✔     	| |
| [Dot1q](http://www.rubydoc.info/gems/packetgen/PacketGen/Header/Dot1q)    |     ✔     	| |
| [Dot1x](http://www.rubydoc.info/gems/packetgen/PacketGen/Header/Dot1x)    |     ✔     	| |
| [ARP](http://www.rubydoc.info/gems/packetgen/PacketGen/Header/ARP)   	    |     ✔     	| |
| [IP](http://www.rubydoc.info/gems/packetgen/PacketGen/Header/IP)    	    |     ✔     	| |
| [IPv6](http://www.rubydoc.info/gems/packetgen/PacketGen/Header/IPv6)      |     ✔     	| |
| [ICMP](http://www.rubydoc.info/gems/packetgen/PacketGen/Header/ICMP)   	  |     ✔     	| |
| [ICMPv6](http://www.rubydoc.info/gems/packetgen/PacketGen/Header/ICMPv6)  |     ✔     	| |
| [IGMP](http://www.rubydoc.info/gems/packetgen/PacketGen/Header/IGMP)   	  |     ✔     	| |
| [IGMPv3](http://www.rubydoc.info/gems/packetgen/PacketGen/Header/IGMPv3)  |     ✔     	| |
| [MLD](http://www.rubydoc.info/gems/packetgen/PacketGen/Header/MLD)    	  |     ✔     	| |
| [MLDv2](http://www.rubydoc.info/gems/packetgen/PacketGen/Header/MLDv2) 	  |     ✔     	| |
| [OSPFv2](http://www.rubydoc.info/gems/packetgen/PacketGen/Header/OSPFv2)  |     ✔     	| |
| [OSPFv3](http://www.rubydoc.info/gems/packetgen/PacketGen/Header/OSPFv3)  |     ✔     	| |
| [GRE](http://www.rubydoc.info/gems/packetgen/PacketGen/Header/GRE)   	    |     ✔     	| |
| [TCP](http://www.rubydoc.info/gems/packetgen/PacketGen/Header/TCP)   	    |     ✔     	| |
| [UDP](http://www.rubydoc.info/gems/packetgen/PacketGen/Header/UDP)   	    |     ✔     	| |
| [DNS](http://www.rubydoc.info/gems/packetgen/PacketGen/Header/DNS)   	    |     ✔     	| |
| [EAP](http://www.rubydoc.info/gems/packetgen/PacketGen/Header/EAP)   	    |     ✔      	| |
| [ESP](http://www.rubydoc.info/gems/packetgen-plugin-ipsec/PacketGen/Plugin/ESP)   	    |     P     	| [packetgen-plugin-ipsec](https://github.com/sdaubert/packetgen-plugin-ipsec) |
| [IKE](http://www.rubydoc.info/gems/packetgen-plugin-ipsec/PacketGen/Plugin/IKE)   	    |     P     	| [packetgen-plugin-ipsec](https://github.com/sdaubert/packetgen-plugin-ipsec) |
| [DHCP](http://www.rubydoc.info/gems/packetgen/PacketGen/Header/DHCP)      |     ✔     	| |
| [DHCPv6](http://www.rubydoc.info/gems/packetgen/PacketGen/Header/DHCPv6)  |     ✔     	| |
| [HTTP](http://www.rubydoc.info/gems/packetgen/PacketGen/Header/HTTP)      |     ✔     	| |
| [BOOTP](http://www.rubydoc.info/gems/packetgen/PacketGen/Header/BOOTP)    |     ✔     	| |
| [TFTP](http://www.rubydoc.info/gems/packetgen/PacketGen/Header/TFTP)      |     ✔             | |
| [SMB](http://www.rubydoc.info/gems/packetgen-plugin-smb/PacketGen/Plugin/SMB) |    ❗P    | [packetgen-plugin-smb](https://github.com/sdaubert/packetgen-plugin-smb) |
| [SMB2](http://www.rubydoc.info/gems/packetgen-plugin-smb/PacketGen/Plugin/SMB2) |    ❗P  | [packetgen-plugin-smb](https://github.com/sdaubert/packetgen-plugin-smb) |

##### Table Legend
| Symbol 	|    Description  	|
|:-------:|:-----------------:|
|    ✔   	|     Supported     |
|    ❗    | Under development |
|    ❌   	|   Not Supported   |
|    P          |  Plugin           |
