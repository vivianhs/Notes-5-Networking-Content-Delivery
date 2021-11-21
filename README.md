# Notes-5-Networking-Content-Delivery
CIT114 notes 5

Week 7

### WHAT IS A NETWORK?
At its core, a computer network is just two or more client machines that are connected together, using a network device, to share resources. A network can be logically partitioned to create subnets. A router or switch are used to connect the clients together and enable communications.


##### LAN vs WAN
Local Area Network >> connects home networks, corporate networks
Wide Area Network >>> The Internet/World-Wide Web

### Definitions
DNS Server – Domain Name System (or “Server”)
 ARP – Address Resolution Protocol
 RARP – Reverse Address Resolution Protocol
 The Internet – A global network of interconnected smaller networks
 The World Wide Web – a SUBSET of the internet; formatted pages
 URI – Uniform Resource Identifier (or URL)

The OSI (7-Layer Model)
7. Application 
6. Presentation
5. Session
4. Transport
3.Network
2.Datalink
1.Physical

### Introduction to IP Addresses & Binary Math
Two important components to networking are how you know where to go on a network (IP Address) and how the computer translates the number into something it can understand (Binary).
The IP Addresses and DNS are the  METHOD in which machines talk to each other, every device IP address is similar to people addresses. DNS Servers are directories of names and numbers.

### Calculating IPv4
255 maximum in each section: 255 x 255 x 255 x 255 = 4 billion
 We’re running out of IP addresses in IPv4
 Transition to IPv6: 340 UNDECILLION addresses!

#### Binary Math 
Is the language in which computers communicate, counting with 1’s and 0;s only. Works the same way as base 10 numbers, just less digits

### VPCs and Subnets
Subnets
 Is a network inside of a network, and it enables networks to work more efficiently

### Introducing Amazon VPC
Provision a section of the AWS Cloud:
Selection of IP address ranges
Creation of Subnets
Configuration of routing tables and network gateways
WE have complete control over the VPC

7.10
