# IP-Spoofing
Ethical Hacking

IP Spoofing is essentially a technique used by a hackers to gain unauthorized access to Computers. Concepts of IP Spoofing was initially discussed in academic circles as early as 1980. IP Spoofing types of attacks, had been known to Security expert on the theoretical level. It was primarily theoretical until Robert Morris discovered a security weakness in the TCP protocol known as sequence prediction. Occasionally IP spoofing is done to mask the origins of a Dos attack. In fact Dos attacks often mask actual IP address from where attack has originated from. 

Process : 

With IP spoofing, intruder sends message to a computer system with an IP address indicating message is coming from a different IP address than its actually coming from. If intent is to gain unauthorized access, then Spoof IP address will be that of a system the target considers a trusted host. To Successfully perpetrate an IP Spoofing attack, hacker must find IP address of a machine that the target System Considers a trusted source. Hackers might employ a variety of techniques to find an IP address of a trusted host. After they have obtained trusted IP address they can then modify packet headers of their transmission so its appears that the packet coming from the host. 

Different ways to address IP Spoofing include :

Do not reveal any information regarding your internal IP addresses.This helps prevent those addresses from being “spoofed”.
Monitor incoming IP packets for signs of IP spoofing using network monitoring software. One popular product is “Netlog”, is along side similar products, seeks incoming packets to the external interface that have the both source and destination IP addresses in your local domain. This essentially means an incoming packet that claims to be from inside network is actually coming from outside your network. Finding one means that an attack is underway.
Danger that IP spoofing contains is that some firewalls do not examine packets that appear to come from an internal IP address.Routing packets through filtering router is possible, if they are not configured to filter incoming packets whose source address is in local domain. 

The risks associated with IP Spoofing include:

Denial-of-service attacks: An attacker can use IP Spoofing to flood a network or system with a large number of requests, making it unavailable to legitimate users.
Unauthorized access: An attacker can use IP Spoofing to bypass access controls and gain unauthorized access to a system or network.

Data interception: An attacker can use IP Spoofing to intercept sensitive data, such as login credentials, financial information, or personal information.

Reputation damage: IP Spoofing can damage the reputation of legitimate businesses and organizations, as the attack can appear to be coming from their IP address.

Examples of router configurations that are potentially vulnerable include :

Routers to external networks that support multiple internal interfaces.
Proxy firewalls where the proxy applications use source IP address for authentication.
Router with two interfaces support sub-netting on the internal network.
Routers that do not filter packets whose source address is in the local domain.
Conclusion :

IP spoofing attacks are becoming less frequent.
Primarily because the Venues they use have become more Secure and in some case no longer used.
Spoofing can still be used and all security administrators should address it.
