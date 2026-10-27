physical address \_ Mac Address (communication on the same network)

logical address \_ IP Address (communication on the same network or not)

**Example to send a packet**

layer 2 \_

Destination MAC address

Source MAC address

layer 3 \_

Source IPv4 address

Destination IPv4 address

When the destination is in another network:

the mac address destination will be the default gateway

> after pass through de gateway, it will change de Dest and Sour MAC
> address to a new router

Address Resolution Protocol

used to determine the MAC address of a known destination device IPv4
address

Neighbor Discover

used to determine the MAC address of a known destination device IPv6
address

Router are used to divide the network into multiple broadcast domains

ARP

host send a ARP Request (broadcast / FFFF.FFFF.FFFF)

the “target” will send a ARP Reply with his MAC address

host stores the MAC address reply in a ARP table
