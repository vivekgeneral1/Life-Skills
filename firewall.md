# Firewall

A firewall is a technology that filters incoming and outgoing network traffic passing through a network. A firewall can be software or hardware. A software firewall is installed on a computer, whereas a hardware firewall is a hardware devices that interface between your local network and the internet. A software firewall can only be installed on a single device, whereas a hardware firewall can protect all the devices on your local network.

## Types of Firewalls

### Packet filtering firewall

A packet filtering firewall is the earliest and most basic type of firewall. It can only perform very basic operations like:
+ Packet header examination
+ IP Address verification
+ Port verification

It acts as a simple bidirectional filter. It is very fast and can perform operations independently, without user intervention. Although it lacks advanced filtering, it provides a good level of security since it is placed strategically at the choke point. It is also the cheapest.


### Circuit Proxy Firewall

A circuit proxy firewall is similar to a packet filtering firewall, but it pretends to be the sender of the request to the server. The server sees the request coming from the firewall, and our IP address is hidden.

### Application Proxy Firewall

An Application Proxy firewall is more complicated than a packet filtering firewall or a Circuit Proxy firewall. It understands the Application Protocol and the data, based on which it decides whether to authenticate the user or reject the request. It is commonly referred to as a proxy server. 

### Packet Inspection Firewall

All the firewalls previously mentioned only check the headers of the data packet, but a packet inspection firewall inspects the payload as well.

### Firewall Limitations

It is a common misconception that all the problems in internal network security can be solved by installing a firewall. 
+ A firewall protects our computer or network from external infiltration, but it can't help with securing an already infected computer. 
+ It does not provide any real defence against viruses, Trojans, malware, etc. 
+ Configuring a firewall is a very complicated process, especially on a large local network interfacing multiple zones.
+ A misconfigured firewall may leave a loophole for hackers to abuse.

## Conclusions

A firewall is the first line of defense in network security, but we should not be dependent upon only the firewall for securing computers in our network.

## References

https://en.wikipedia.org/wiki/Firewall_(computing)

https://www.researchgate.net/publication/367103503_Research_on_firewall_technology_and_its_application_in_computer_network_security_strategy

https://www.fortinet.com/resources/cyberglossary/firewall
 
https://www.youtube.com/watch?v=eO6QKDL3p1I&list=PLBbU9-SUUCwV7Dpk7GI8QDLu3w54TNAA6"

