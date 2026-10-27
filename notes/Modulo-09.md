**Unicast Transmission \_**

a device sending a message to one other device(one-to-one)

**Broadcast Transmission \_**

device sending a message to all the devices on a network(one-to-all)

IPv6 don’t have that kind of transmission

By default, routers do not forward broadcast

**Multicast Transmission \_**

device sending a single packet to a selected set of hosts subscribed in
a group

> multicast clients use services requested by a client program to
> subscribe to the multicast group.


\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

**Private IPv4 Addresses and Network Address Translation (NAT)**

NAT

used to translate between private IPv4 and public IPv4 addresses

usually done on the router that connects the internal network to the ISP
network

Identify a public IP address to a private IP address:


CIDR

169.254.0.0 /16\_\_\_\_

> /16 shows that the 16 first bits indicates the subnet mask
>
> the other 16 bits identifies the range for hosts

**Class A (0.0.0.0/8 to 127.0.0.0/8) -**

> Designed to support extremely large networks with more than 16 million
> host addresses

**Class B (128.0.0.0 /16 - 191.255.0.0 /16) -**

> Designed to support the needs of moderate to large size networks with
> up to approximately 65,000 host addresses.

**Class C (192.0.0.0 /24 - 223.255.255.0 /24) -**

> Designed to support small networks with a maximum of 254 hosts.

The solution to reduce the size of the network is to create subnets

Subnet

