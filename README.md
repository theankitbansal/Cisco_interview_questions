# Cisco_interview_questions
Interview questions asked in cisco


About Cisco


Cisco Systems is the world’s leading provider of products, systems and services around computer networking. The company was established in the year 1984 by two scientists from Stanford University finding an easier way to connect distinguished multiple computer systems. The First product of Cisco systems was sold in 1986 and is now an MNC, with thousands of employees spread across more than 115 countries. Today, Cisco offers networking solutions for numerous service providers, small-scale to medium-scale businesses and enterprise customers which includes government organisations, large corporations, utilities and educational institutions.

Cisco’s networking solutions can connect people, computer networks and computing devices, allowing the people to access or transfer data without having differences in time, place or type of computer system. Cisco provides comprehensive networking solutions that clients utilise to build a unified data infrastructure of their own or to connect to someone else’s network. Cisco offers the industry’s widest range of hardware products that operate to form information networks or give people access to those networks; Cisco IOS® software, which enables networked applications and provides network services.

Cisco caters to the customers in 3 target markets:

Enterprises - Large businesses with complex networking needs, generally spanning multiple locations & types of computer systems. 
Service Providers - Companies that give information services, including telecommunication carriers, Internet Service Providers, cable companies, and wireless communication providers. 
Small-scale/Medium-scale Businesses - Companies with a need for data networks of their own, as well as connection to the Internet and/or to business partners.
Unlike other IT companies, Cisco doesn’t take up a rigid approach that follows one technology over the rest of others and imposes it on clients as the only response. Cisco’s policy is to listen to customer queries, monitor all technological options, and provide clients with a range of alternatives from which to choose. Cisco develops its products & solutions around widely accepted industry standards.



1. What is a diskless workstation?

Diskless workstations refer to the client computers that are in connection with a networked server. These computers will need only a minimum amount of hardware for interacting with the system by the user. They do not have a hard disk. Data and programs will be retrieved from the network. The server will do all the “hard work”, including data storage, booting, and performing calculations.

Diskless workstations are helpful in reducing the overall LAN cost as a single disk drive with large-capacity will be less expensive than multiple low-capacity drives. Along with this, it also simplifies the security and backups because all files are in a single place, i.e., on the file server. Also, data access from a larger remote file server is usually faster than data access from a smaller local storage device. The major disadvantage of these diskless workstations is that they become useless on network failure.

2. Which protocol will be used for booting diskless workstations?

BootP or Bootstrap Protocol will be used for booting the diskless workstations across the Internet by themselves. Similar to DHCP (Dynamic Host Configuration Protocol), BootP will allow a computer to obtain the server’s IP address as well as their own IP address.

3. Explain in detail about Bridges in Networking and mention its usage.

A bridge is a networking device that will connect numerous LANs (Local Area Networks) for forming a larger LAN. Also, it can connect LAN segments to form newer LAN segments. It operates in the OSI model’s Data-Link layer. Bridges are helpful in increasing the network capacity of a single LAN by joining multiple LANs.

Working of Bridge:

The bridge will connect two or more different LANs that are having similar protocols and help to communicate between the devices (nodes) in them. It will accept all the data packets and all of them will be amplified to the other side. The bridges are considered to be intelligent devices as they will permit the passing of only selective packets from them.

A bridge will pass only those packets which are addressed from the node of one network to the node of the other network. That means the bridge will consult a database on receiving the data frame for deciding whether to pass, transmit or discard the frame.

If the frame consists of a destination MAC (Media Access Control) address within the same network, then the bridge will pass the frame to that node and discard it later.
If the frame consists of a destination MAC address within the connected network, then the bridge will forward the frame towards it.

![image](https://user-images.githubusercontent.com/81725794/180632499-7e999c32-448b-49ad-b9fa-6cc2b811efab.png)

Uses of Bridge:

The capacity of the network will be increased and multiplied as multiple smaller networks are combined to form a single network using the bridge.
The database in the bridge will help for deciding whether a data frame should be transmitted or discarded on receiving the data frame.
A single faulty node will be prevented from bringing down the whole network, by deciding on whether to forward or discard the data frame.
It helps for frame broadcasting to each node even if the MAC or destination address is not available.
With the help of a wireless bridge, we can connect the wireless networks with wireless segments.

4. What is an IP access list?

An IP access list is a rule set for traffic control in the network and for reducing the possibilities of network attacks. This list will be useful in filtering the traffic based on rules that are defined for incoming as well as outgoing networks. The standard IP access list features are:

Provide bandwidth control: IP Access lists on a slower link are helpful in preventing excess traffic on a network.
Trigger dial-on-demand: Access lists do have the right to enforce the criteria for dial and disconnect.
Provide NAT control: Access lists are helpful in controlling which addresses are translated by NAT (Network Address Translation).
Control access to Virtual teletype (vty): Access lists on an inbound vty are capable of controlling which person can access the lines to a device. Access lists on an outbound vty are capable of controlling the destinations to which can be reached by the lines from a device.
Authenticate remote shell (rsh) and Rate Control Protocol (RCP): Using access lists, it is possible to simplify the remote hosts, remote users, and local users identification in an authentication database that is configured for controlling the device access. For receiving incoming rsh as well as rcp protocol requests, the authentication database will enable the Cisco software.
Block unwanted traffic: These access lists are capable of filtering incoming/outgoing packets on an interface, thus helpful in controlling the network access depending on the source address, destination address, or user authentication. It is also useful in determining the traffic type that is forwarded or blocked at the device interface.
Limit debug command output: We can limit the debug output using access lists, depending on an IP address or a protocol.

5. Give the reasons why a Layered model is used by the Networking industry.

It provides systematic troubleshooting in the network.
It clarifies what task has to be done by general function rather than how to do those tasks.
Modifications made to one layer doesn't affect the other layers in the layered model.

6. What are TACACS (Terminal Access Controller Access Control System) and RADIUS (Remote Authentication Dial In User Service) in networking?

TACACS: It is a group of remote authentication protocols useful in controlling remote authentication and other related services for the networked access control via a centralized server. TACACS will help for determining whether the user is having access to the network or not as it will permit the remote access server to communicate with an authentication server.
RADIUS: It is an AAA (Authentication, Authorization, and Accounting) protocol to control access to network resources. RADIUS is used by ISPs (Internet Service Providers) and corporations to manage access into the Internet or internal networks across a group of access technologies that include wireless, DSL, modem, and VPNs.

7. What are the Benefits of Subnetting?

Subnetting refers to the process of dividing a larger network into smaller networks. In the below-given image, the network has been divided into two broadcast networks, which will reduce the network load and will provide greater network security to the users.

![image](https://user-images.githubusercontent.com/81725794/180632542-9840fcce-42b5-4b7f-b1dc-5e19c308865f.png)

The benefits of subnetting are:

1. Improvement in network performance and speed: Subnetting will enable you to make sure about information remains in the broadcast domain or subnetted network, which permits other subnets for maximizing their speed and effectiveness. Also, subnetting will divide broadcast domains of your network which enables you to control the traffic flow in a better way, thus increasing network performance.
2. Reduction in network congestion: Using a router for moving the traffic between subnets will lead to no broadcast traffic and any information that does not require to be routed will be moved to other subnets. As the traffic within each subnet has been reduced, there is an increase in the speed of each subnet, which in turn will ease the network congestion.
3. Boosting network security: You will be able to control the flow of traffic with the help of ACLs (Access Control Lists), QoS (Quality of Service), or route maps, enabling you for identifying threats, close entry points, and target your responses more easily.
4. Ease administration: Using subnetting, you will be able to create networks that have more logical host limits, as opposed to the IP addressing class limitations: 8 bits (Class A), 16 bits (Class B), and 24 bits (Class C). Subnetting will enable you for selecting the number of bits in your subnetwork, thus creating more realistic host limits. Subnetting will be an effective approach for keeping eyes on the systems of your network, which will help you for determining which system needs attention when problems arise. So we can say that subnetted networks are easier to manage and troubleshoot.

8. How is a TCP connection made?

A TCP(Transmission Control Protocol) connection will be done as given below:

Step 1: At first, the receiver (host) will send a packet to the sender (server) with an SYN (SYNchronize) flag. It is considered as an attempt made to open a connection. Then, the server will respond with an SYN flag and ACK (ACKnowledge) flag for acknowledging(approving) the connection. Now, the receiver will send an ACK flag for confirming the handshake. The operating systems at both ends will be kept informed about the connection establishment.

Step 2: Now the sender will begin data transmission. It will also gain acknowledgements from the receiver. A timer will begin when the sender initiates the sending of data.

Step 3: The data will be retransmitted by the sender if it hasn’t received any acknowledgements even after the timer limit has been exceeded.

Step 4: When the receiver buffer is full (in the case of windowing), the receiver will send a stop signal to the sender. The sender will stop the data transmission.

Step 5: Then after all the data processing is done, the receiver will be sending a go signal into the sender. Now, the sender will again begin transmitting the data.

9. What is the CISCO default TCP session timeout?

The default timeout in the TCP session for CISCO will be one minute. Here, connection slots will get freed on an average of sixty seconds later, when the sequence of normal connection close has been completed. It can be configured into other settings as per the requirements.

For the connection and translation slots of different protocols, a global idle timeout duration can be set manually. The resources will be returned so that pools can be freed, in case slots are not used for the specified idle time.

10. What is a transparent firewall?

A transparent firewall or bridge firewall will behave like a line of the layer among 2 devices and can be easily installed into an existing network without any modification into the Internet Protocol (IP) address. The transparent firewall will allow for entering into the traffic of layer 3 from the level of higher security to lower security levels without the help of access lists. It will act similar to a bridge as it inspects and moves network frames between interfaces.

A transparent firewall is considered a “stealth firewall” that supports outside as well as inside interfaces. Using this, security equipment can be connected with the same network on external and internal ports, with a separate VLAN(Virtual Local Area Network) for each interface.
