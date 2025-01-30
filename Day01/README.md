# Understanding IP Addresses:
In any network setup, devices communicate with each other using IP addresses. There are two types of IP addresses:
1.IPv4: Shorter addresses, like phone numbers for devices.
2.IPv6: Longer addresses, similar to phone numbers but with more digits.

# IP Address Ranges:
IPv4 addresses range from 0.0.0.0 to 255.255.255.255. They are divided into five classes: A, B, C, D, and E.
Class A: 1.0.0.0 to 126.255.255.255
Class B: 128.0.0.0 to 191.255.255.255
Class C: 192.0.0.0 to 223.255.255.255
Class D: 224.0.0.0 to 239.255.255.255
Class E: 240.0.0.0 to 255.255.255.255

# Loopback Address
127.0.0.1 is reserved for loopback address for device pings itself.

# Public and Private IPs
As IP addresses are limited, there's a concept of public and private IPs.

Public IPs: Used for communication over external networks.
Private IPs: Used internally within closed infrastructures or office environments.

# Private IP Ranges
Private IPs are reserved within specific ranges:

10.0.0.0 to 10.255.255.255 (10/8 prefix)
172.16.0.0 to 172.31.255.255 (172.16/12 prefix)
192.168.0.0 to 192.168.255.255 (192.168/16 prefix)
These addresses are for internal use only and should not be accessible from outside the network.


To demonstrate, you can open CMD and type ipconfig to view your IPv4 private address. Then, by searching "my public IP" on Google, you can find your public IP address.
