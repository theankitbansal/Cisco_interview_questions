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

11. Explain how Cut-through LAN switching works.

Cut-through LAN switching is useful in packet-switching systems. In the packet-switching technique, the message will be divided into many smaller units known as packets and it will be individually routed from source to the destination. It does not require the establishment of a dedicated circuit for communication, as it is a connection-less network switching technique.

![image](https://user-images.githubusercontent.com/81725794/180632615-5b870f7f-8375-4507-9f50-06cac8ecf0f4.png)

In cut−through switching, when a packet or data frame begins arriving at a switch or bridge, the transmission of data can be started immediately after the destination address field has arrived. The switch will do a look–up at the address table stored in it and check for the validity of the destination address. If it is a valid address and the outgoing link is available, the data frame transmission into the destination port will be immediately started by a switching device, even before the arrival of the remaining frame.

Here, the switching device will act as a forwarder of data frames. The error checks cannot be performed when it starts forwarding, as the total frame is still not available. For error handling, it depends upon the destination devices.

12. What are the different types of memories used in the CISCO router?

Different types of memories are being used in a CISCO router. They are:

Random Access Memory (RAM): RAM used in a router is the same as the RAM that is installed in our Mobile Phones, Laptops, and PCs. The RAM will be divided into two areas:
Main Processor Memory: It stores the information that belongs to the routing table, running router configuration, and ARP (Address Resolution Protocol) cache.
Shared I/ry: It is a temporary storage memory where the queued data packets will be stored.
When the router gets restarted or rebooted, all the information stored within the RAM will be deleted(that is why it is considered as Volatile memory). We can store the data permanently using NVRAM.
Non-Volatile Random Access Memory (NVRAM): NVRAM is useful in storing the start-up configuration file which are copies of the CISCO Router Configuration file and will be retained even after rebooting or restarting of router occurs. In this, the data will not be lost and can be easily recovered by rebooting or switching off the router. If you want to permanently save the running configuration files, these files should be moved from RAM to NVRAM.
Read-Only Memory (ROM): The boot procedure of a CISCO router will begin from the ROM memory section. ROM will have programming instructions such as Bootstrap program and POST (Power-On-Self-Test). POST test is useful in verifying whether hardware components like RAM, CPU, and interfaces are properly working or not. If they are not functioning properly, an error message will be sent by POST. After this, for setting up the CPU and boot functions of the router, the bootstrap application is used. The bootstrap program will be in charge of finding and loading the operating system (IOS) of the router. All this information will be saved or stored inside the ROM and the data will be retained even after switching off or rebooting the router.
Flash Memory: It is an EPROM (Erasable Programmable Read-only Memory) chip that is more cost-effective for enterprise environments. The router operating system i.e., IOS (Internetwork Operating System) will be available in flash memory. It can be easily upgradable and does not need any hardware changes. Also, the content in flash memory will be retained when the router is switched off or rebooted.

13. What is a deadlock in Operating Systems? What are the situations for the deadlock to happen?

Deadlock refers to the situation that happens in the operating system where each process will enter into the waiting state for obtaining the resource which has been assigned to some other process.

Consider a real-time example of traffic that is going only in a single direction. Here, we can consider the bridge as a resource. If one car backs up, the deadlock situation will be resolved easily. Multiple cars may have to be backed up on deadlock occurrence. So it might lead to starvation.

![image](https://user-images.githubusercontent.com/81725794/180632648-dc720a0b-fc94-431a-9891-93e86d587d1a.png)

The process will be considered to be in a deadlock when the following conditions get satisfied simultaneously:

Mutual Exclusion: When more than one process shares the same resource and all the processes are different, then each process of them has to wait for the other for utilizing the resource as at a time only one process can use the resource.
Hold and Wait: A process is already holding the resource(at least one) and waiting for resources.
No pre-emption: We cannot forcefully stop or remove a process among the waiting processes, for releasing the resource.
Circular Wait: A group of processes will be waiting in a circular manner for the resources held by each other.

14. What is Virtual memory?

Virtual Memory is a method of storage allocation where a part of secondary memory will be emulated as it is the main memory of a computer. The virtual memory will solve the insufficient memory problem by converting part of disk memory into virtual addresses, thus will create a large size of RAM for accomodating the increased memory requirement demand and will provide the illusion that we have a lot of memory. Modern microprocessors will have a built-in Memory Management Unit(MMU) which will translate the virtual addresses into physical addresses.

![image](https://user-images.githubusercontent.com/81725794/180632664-4dc20409-5a43-4b23-b7b6-bbcae7e129ef.png)

The size of virtual storage is limited by the computer system’s addressing scheme and the available quantity of secondary memory will not depend on an actual number of the main storage locations.
In common, Virtual memory will be implemented through demand paging or in a segmentation system. Also, demand segmentation can be used for providing virtual memory.

15. How will swapping lead to better memory management?

Swapping is a process/memory management technique used by the operating system(os) for increasing the processor utilization by moving a few blocked processes from the main memory into the secondary memory. This will lead to a queue formation that has temporarily suspended processes and the execution will be continued with the processes that are newly arrived. At the regular intervals fixed by the operating system, processes can be moved from the main memory to secondary storage, and then later they can be moved back. Swapping will allow multiple processes to run, that can fit into memory at a single time. Thus, we can say that swapping will lead to better memory management.

![image](https://user-images.githubusercontent.com/81725794/180632677-52b94d78-ec27-46f4-9482-89f4d12d0cd6.png)
