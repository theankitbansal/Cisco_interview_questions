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

16. What is Recovery testing?

Recovery testing is a technique used in software testing, which verifies the ability of software to recover from hardware/software failures, crashes, network failures, etc. The recovery testing purpose will be determining whether the software operations can continue even after the integrity loss or disaster. It includes returning the software to the point where integrity was known and doing transaction reprocessing to the point of failure.

17. Differentiate between C and C++.


![Screenshot (956)](https://user-images.githubusercontent.com/81725794/180700733-eebab7a5-8f12-41c6-880c-023b566601d9.png)

18. What is a void pointer in C? Can a void pointer be dereferenced without being aware of its type?

A void pointer is a pointer that is useful in pointing to the memory location having an undefined data type at the time of defining a variable, which means it can be any data of any arbitrary type. You can dereference a void pointer only after explicit casting. For example:

![Screenshot (957)](https://user-images.githubusercontent.com/81725794/180700763-d97e6cc9-8e36-4338-bb57-acaa3431fe30.png)

In the above-given code, we have declared a normal variable x with the integer data type, and assigned reference of x into a void pointer y. Using printf(), we are displaying the value of y by dereferencing it.

19. How Multithreading will be achieved in Python?

Python has a Global Interpreter Lock (GIL) that makes sure only one of your ‘threads’ can be executed at a time. A thread will acquire the GIL, does a small amount of work, 
then the GIL will be passed onto the next thread.
This happens so quickly as if your threads are executing in parallel, but in reality, they are just taking turns using the same CPU core.
All this GIL passing process will add overhead to the execution. This indicates that, if you want to speed up your code run, then the usage of the threading package often is not considered to be a good idea.
![How_Multithreading_will_be_achieved_in_Python](https://user-images.githubusercontent.com/81725794/180700846-e25fbff1-beac-444a-9e15-5ebb5a8a8a0a.png)

20. What is an auto keyword in C?

The auto keyword is used for declaring a variable that has a complicated type. For example, an auto keyword can be used for variable declaration where the initialization expression consists of templates, pointers to members, or pointers to functions.
It can also be used for declaring and initializing a variable to a lambda expression. You cannot declare the variable type on your own because the type of lambda expression will be only known to the compiler.
Auto variables can be accessed only within the block or function in which they have been declared and cannot be accessed outside of them. By default, they are assigned with garbage value whenever they are declared without assigning any value.
Syntax: auto <data_type> <variable_name>;

Example:
auto int x = 1;

Here, x is a variable of storage class “auto” and with data type int.

21. Write a program to create a stack using a linked list in Java.

About Cisco
Cisco Systems is the world’s leading provider of products, systems and services around computer networking. The company was established in the year 1984 by two scientists from Stanford University finding an easier way to connect distinguished multiple computer systems. The First product of Cisco systems was sold in 1986 and is now an MNC, with thousands of employees spread across more than 115 countries. Today, Cisco offers networking solutions for numerous service providers, small-scale to medium-scale businesses and enterprise customers which includes government organisations, large corporations, utilities and educational institutions.

Cisco’s networking solutions can connect people, computer networks and computing devices, allowing the people to access or transfer data without having differences in time, place or type of computer system. Cisco provides comprehensive networking solutions that clients utilise to build a unified data infrastructure of their own or to connect to someone else’s network. Cisco offers the industry’s widest range of hardware products that operate to form information networks or give people access to those networks; Cisco IOS® software, which enables networked applications and provides network services.

Cisco caters to the customers in 3 target markets:

Enterprises - Large businesses with complex networking needs, generally spanning multiple locations & types of computer systems. 
Service Providers - Companies that give information services, including telecommunication carriers, Internet Service Providers, cable companies, and wireless communication providers. 
Small-scale/Medium-scale Businesses - Companies with a need for data networks of their own, as well as connection to the Internet and/or to business partners.
Unlike other IT companies, Cisco doesn’t take up a rigid approach that follows one technology over the rest of others and imposes it on clients as the only response. Cisco’s policy is to listen to customer queries, monitor all technological options, and provide clients with a range of alternatives from which to choose. Cisco develops its products & solutions around widely accepted industry standards.

In this article
1. Cisco Recruitment Process
2. Cisco Technical Interview Questions: Freshers and Experienced
3. Cisco Interview Preparation
4. Cisco Coding Interview Questions
5. Frequently Asked Questions
Cisco Recruitment Process
Interview Process
Every year, hundreds of candidates face the Cisco interview process. The candidates who have better knowledge of the concepts of networking, excellent analytical skills, and computer intelligence can easily clear the interview at Cisco.

Usually, the interview process at Cisco involves the following three rounds:

Online Assessment Test
Technical Interview Rounds
HR Interview
For experienced candidates also, the Cisco interview rounds will normally remain the same. But in the case of a few major roles, you may be asked to appear for two or more rounds of technical interviews preceded by an HR interview.

Interview Rounds
1. Online Assessment Test: This online assessment test consists of the following sections with no negative marking:

Aptitude Test: Questions around Probability, Permutations and Combinations, Algebra, Simple & Compound Interest, Number Series, Profit and Loss, etc.
Technical Test: Questions around Computer Networking, C, Algorithms, Data Structures as well as digital electronics, CMOS and Microprocessor, etc.
2. Technical Interview Rounds: In the technical interview rounds, the interviewer may ask questions on various Computer fundamentals like Data Structures and Algorithms, Operating Systems, Algorithms, Database Management, Networking etc. Candidates will be tested in terms of in-depth knowledge in all the aspects of domains related to Computer Science and Networking. Other technical questions are normally asked from the projects or internships mentioned in the CV. The company primarily focuses on a candidate’s approach towards a particular problem.

3. HR Interview: In this round, HR will usually question you about the job role, why do you want to join Cisco, the most challenging project that you were involved in, etc. Here the questions will be majorly asked from your CV. Overall, you are required to be prepared well before this interview round and have a fair knowledge of Cisco and the stream from which you have got graduated/experienced.

Cisco Technical Interview Questions: Freshers and Experienced
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


The benefits of subnetting are:

Improvement in network performance and speed: Subnetting will enable you to make sure about information remains in the broadcast domain or subnetted network, which permits other subnets for maximizing their speed and effectiveness. Also, subnetting will divide broadcast domains of your network which enables you to control the traffic flow in a better way, thus increasing network performance.
Reduction in network congestion: Using a router for moving the traffic between subnets will lead to no broadcast traffic and any information that does not require to be routed will be moved to other subnets. As the traffic within each subnet has been reduced, there is an increase in the speed of each subnet, which in turn will ease the network congestion.
Boosting network security: You will be able to control the flow of traffic with the help of ACLs (Access Control Lists), QoS (Quality of Service), or route maps, enabling you for identifying threats, close entry points, and target your responses more easily.
Ease administration: Using subnetting, you will be able to create networks that have more logical host limits, as opposed to the IP addressing class limitations: 8 bits (Class A), 16 bits (Class B), and 24 bits (Class C). Subnetting will enable you for selecting the number of bits in your subnetwork, thus creating more realistic host limits. Subnetting will be an effective approach for keeping eyes on the systems of your network, which will help you for determining which system needs attention when problems arise. So we can say that subnetted networks are easier to manage and troubleshoot.
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


The process will be considered to be in a deadlock when the following conditions get satisfied simultaneously:

Mutual Exclusion: When more than one process shares the same resource and all the processes are different, then each process of them has to wait for the other for utilizing the resource as at a time only one process can use the resource.
Hold and Wait: A process is already holding the resource(at least one) and waiting for resources.
No pre-emption: We cannot forcefully stop or remove a process among the waiting processes, for releasing the resource.
Circular Wait: A group of processes will be waiting in a circular manner for the resources held by each other.
14. What is Virtual memory?
Virtual Memory is a method of storage allocation where a part of secondary memory will be emulated as it is the main memory of a computer. The virtual memory will solve the insufficient memory problem by converting part of disk memory into virtual addresses, thus will create a large size of RAM for accomodating the increased memory requirement demand and will provide the illusion that we have a lot of memory. Modern microprocessors will have a built-in Memory Management Unit(MMU) which will translate the virtual addresses into physical addresses.

The size of virtual storage is limited by the computer system’s addressing scheme and the available quantity of secondary memory will not depend on an actual number of the main storage locations.
In common, Virtual memory will be implemented through demand paging or in a segmentation system. Also, demand segmentation can be used for providing virtual memory.
15. How will swapping lead to better memory management?
Swapping is a process/memory management technique used by the operating system(os) for increasing the processor utilization by moving a few blocked processes from the main memory into the secondary memory. This will lead to a queue formation that has temporarily suspended processes and the execution will be continued with the processes that are newly arrived. At the regular intervals fixed by the operating system, processes can be moved from the main memory to secondary storage, and then later they can be moved back. Swapping will allow multiple processes to run, that can fit into memory at a single time. Thus, we can say that swapping will lead to better memory management.


16. What is Recovery testing?
Recovery testing is a technique used in software testing, which verifies the ability of software to recover from hardware/software failures, crashes, network failures, etc. The recovery testing purpose will be determining whether the software operations can continue even after the integrity loss or disaster. It includes returning the software to the point where integrity was known and doing transaction reprocessing to the point of failure.

17. Differentiate between C and C++.
C	C++
It is procedural programming in which code will be in the form of a set of procedures for developing the applications.	It is a hybrid programming language as it supports both procedural and object-oriented programming concepts.
It does not support oops features like encapsulation, polymorphism, and inheritance.	It supports oops features like encapsulation, polymorphism, and inheritance.
It does not support data hiding.	It supports data hiding through encapsulation.
Operator and function overloading is not supported.	Operator and function overloading is supported.
Don’t have access specifiers.	 Does have access specifiers.
Data and functions will be kept separated and will not be encapsulated together.	Data and functions will be encapsulated together as an object.
It focuses on method or process, instead of focusing on data.	It focuses on data, instead of focusing on method or procedure.
Virtual and friend functions are not supported	Virtual and friend functions are supported.
It does not support exception handling.	It supports exception handling.
Namespace feature is not provided.	 Namespace feature is allowed to avoid name collisions.
18. What is a void pointer in C? Can a void pointer be dereferenced without being aware of its type?
A void pointer is a pointer that is useful in pointing to the memory location having an undefined data type at the time of defining a variable, which means it can be any data of any arbitrary type. You can dereference a void pointer only after explicit casting. For example:

int x = 10;
void *y = &x;
printf(“%d\n”, *((int*)y));
In the above-given code, we have declared a normal variable x with the integer data type, and assigned reference of x into a void pointer y. Using printf(), we are displaying the value of y by dereferencing it.

19. How Multithreading will be achieved in Python?
Python has a Global Interpreter Lock (GIL) that makes sure only one of your ‘threads’ can be executed at a time. A thread will acquire the GIL, does a small amount of work, then the GIL will be passed onto the next thread.
This happens so quickly as if your threads are executing in parallel, but in reality, they are just taking turns using the same CPU core.
All this GIL passing process will add overhead to the execution. This indicates that, if you want to speed up your code run, then the usage of the threading package often is not considered to be a good idea.

20. What is an auto keyword in C?
The auto keyword is used for declaring a variable that has a complicated type. For example, an auto keyword can be used for variable declaration where the initialization expression consists of templates, pointers to members, or pointers to functions.
It can also be used for declaring and initializing a variable to a lambda expression. You cannot declare the variable type on your own because the type of lambda expression will be only known to the compiler.
Auto variables can be accessed only within the block or function in which they have been declared and cannot be accessed outside of them. By default, they are assigned with garbage value whenever they are declared without assigning any value.
Syntax: auto <data_type> <variable_name>;

Example:

auto int x = 1;
Here, x is a variable of storage class “auto” and with data type int.

21. Write a program to create a stack using a linked list in Java.

We can easily implement a stack using the linked list. A stack will have a top pointer which is the “head” of the stack where the item will be pushed and popped at the head of the list. The link field of the first node will be null and the link field of the second field will have the address of the first node and so on and the address of the last node will be stored in the “top” pointer.

The major advantage of linked list usage over an array is we can implement a stack that can grow or shrink according to the need. As the array is of fixed size, it will lead to stack overflow by putting restrictions on the maximum capacity of an array. In the linked list, each new node will be allocated dynamically, so overflow will not occur.

Stack Operations are:

1. push() : This function will insert an element into the linked list which in turn will be added to the top node of Stack.
2. pop() : This function will return the top element from the Stack and the top pointer will be moved to the second node of Stack.
3. peek(): This function will return the topmost element in the stack.
4. display(): This function will print all the elements of Stack.
5. isEmpty(): It will return true if the Stack is empty otherwise it returns false.

// Java program
// Importing package
import static java.lang.System.exit;  
// Creating Stack using Linked list
class StackLinkedlist     
{
    // A node of linked list 
   private class Node    
   {
       // Integer data
       int info;    
       // Reference variable of Node type
       Node link;   
   }
   // Creating a global top reference variable 
   Node top;    
   
   // Constructor
   StackLinkedlist()    
   {
       this.top = null;
   }

   // Function for adding an element i in the stack
   public void push(int i) // Insert at the beginning
   {
       // Creating a new node t and allocate memory
       Node t = new Node(); 

       /* Checking if the stack is full, then inserting an 
       element would lead to stack overflow*/ 
       if (t == null) {
           System.out.print("\nStack Overflow");
           return;
       }
       // Initializing data into info field of t node
       t.info = i;   
       // Add top reference into link field of t node
       t.link = top; 
       // Update top reference
       top = t;   
   }
   
   // Function for checking if the stack is empty or not
   public boolean isEmpty()
   {
       return top == null;
   }

   // Function for returning topmost element of a stack
   public int peek()
   {
       // Checking for empty stack
       if (!isEmpty())   
       {
           return top.info;
       }
       else 
       {
           System.out.println("Stack is empty");
           return -1;
       }
   }

   // Function to pop the topmost element from the stack
   public void pop() 
   {
       // Checking for stack underflow
       if (top == null)    
       {
           System.out.print("\nStack Underflow");
           return;
       }
       // Updating the top pointer to point to the next node
       top = (top).link;   
   }

   public void show()
   {
        // Checking for stack underflow
       if (top == null)   
       {
           System.out.printf("\nStack Underflow");
           exit(1);
       }
       else 
       {
           Node tmp = top;
           while (tmp != null) 
           {
               // Printing node data
               System.out.printf("%d->", tmp.info); 
               // Assigning tmp link to tmp node
               tmp = tmp.link;   
           }
       }
   }
}
//Class with main() function
public class ImplementStack   
{
   public static void main(String[] args)
   {
       // Creating object for the StackLinkedList class
       StackLinkedlist ob = new StackLinkedlist();   
       
       // Inserting values for stack
       ob.push(15);
       ob.push(20);
       ob.push(25);
       ob.push(30);

       // Printing elements of Stack 
       ob.display();  
       // Printing Top element of Stack
       System.out.printf("\nTop element of Stack is %d\n", ob.peek());    

       // Deleting top element of the Stack
       ob.pop();
       ob.pop();
       
       // Printing Stack elements
       ob.show();    
       
       // Printing Top element of Stack
       System.out.printf("\nTop element of Stack is %d\n", ob.peek()); 
   }
}

Output:

30->25->20->15->
Top element of Stack is 30
20->15->
Top element of Stack is 20

22. Write a program for printing all permutations of a given string.

A permutation means re-arranging the ordered list(L) elements into a correspondence of one-to-one with the L itself. It is also known as an “order” or “arrangement number”. There will be n! permutation for a string with length n.

For finding all permutations of a given string, the recursive algorithm will make use of backtracking which finds the permutation of numbers by swapping a single element per iteration.

We are providing the “XYZ” string as an input in the below given example. It will produce 6 permutations for a given string. The permutation for a string “XYZ” are “XYZ”, “YXZ”, “ZYX”, “XZY”, “YZX”, “ZXY”.

![image](https://user-images.githubusercontent.com/81725794/180701233-ade00f61-f8d1-47be-b0e9-fb2574fe9533.png)

Program:

// C Program to print all permutations of a given string including duplicates

#include <stdio.h>
#include <string.h>
// Function for swapping values at two pointers 
void swap(char *a, char *b)  
{
   char temp;
   temp = *a;
   *a = *b;
   *b = temp;
}

/* Function for printing permutations of a string. This function takes
three parameters: String, Starting index of the string, last index of
the string. */
void permute(char *a, int beg, int end)
{
   int i;
   if (beg == end)
       printf("%s\n", a);
   else
   {
       for (i = beg; i <= end; i++)
       {
           swap((a+beg), (a+i));
           permute(a, beg+1, end);
           //backtracking method
           swap((a+beg), (a+i)); 
       }
   }
}

// Driver program for testing above defined functions 
int main()
{
   char string[] = "XYZ";
   int n = strlen(string);
   permute(string, 0, n-1);
   return 0;
}

Output:

XYZ
XZY
YXZ
YZX
ZYX
ZXY

23. Write a program for finding the greatest difference between two elements of an array that is in increasing order of elements.

A solution for this problem can be achieved with the usage of two loops. Initially, we consider the maximum difference value as the difference between the first two array elements. Later, the elements will be picked one by one in the outer loop and the difference between the picked element and every other array element will be calculated in the inner loop, then that difference will be compared with the maximum difference calculated so far.

Program:

// Java program
class MaxDiffrence
{
   /* The function will assume that there will be at least two elements 
   in an array. The function will return a negative value if the array 
   is in decreasing order of sorting. This function will return 0
   if elements are equal. */
   
   int maximumDiff(int x[], int size)
   {
       int res = x[1] - x[0];
       int i, j;
       for (i = 0; i < size; i++)
       {
           for (j = i + 1; j < size; j++)
           {
               if (x[j] - x[i] > res)
                   res = x[j] - x[i];
           }
       }
       return res;
   }

   // Driver program for testing above function 
   public static void main(String[] args)
   {
       MaxDifference md = new MaxDifference();
       int array[] = {2, 3, 90, 10, 120};
       System.out.println("Maximum difference between two elements of an array is " + md.maximumDiff(array, 5));
   }
}

Output:

Maximum difference between two elements of an array is 118

24. Write a program for finding the first and last occurrences (or positions) of a number in an array of a sorted manner.

Assign firstPos and lastPos values as -1 in the beginning, as we need to find them yet. Within for loop, you need to compare a given element with each element of an array. When an element is found for the first time, we will update the firstPos value with i. After that, whenever we find an element, we will update the lastPos value with i. Then firstpos and lastPos value will be printed.

// C++ program
#include <bits/stdc++.h>
using namespace std;

void findFirstAndLastFunc(int a[], int n, int x)
{
   int firstPos = -1, lastPos = -1;
   for (int i = 0; i < n; i++) 
   {
       if (x != a[i])
           continue;
       if (firstPos == -1)
           firstPos = i;
       lastPos = i;
   }
   if (firstPos != -1)
       cout << "First Occurrence = " << firstPos<< "\n Last Occurrence = " << lastPos;
   else
       cout << "Element not Found";
}

int main()
{
   int a[] = { 1, 2, 2, 2, 3, 3, 4, 5, 7, 7};
   int n = sizeof(a) / sizeof(int);
   int x = 7;
   findFirstAndLastFunc(a, n, x);
   return 0;
}

Output:

First Occurrence = 8
Last Occurrence = 9

25. Write a program for reversing each word in a string.

We will make use of a stack for pushing all letters until a space is found in a given string. When space is encountered, we will empty the stack and the reversed word will be printed with a space at the end. This process will be continued until the end of the string has been reached.

// C++ program
#include <bits/stdc++.h>
using namespace std;

// Reverses each word of a string
void reverseEachWords(string s)
{
   stack<char> stk;

   /* Traverses the given string and all the characters will be pushed to stack until a space is found. */
   for (int i = 0; i < s.length(); ++i) {
       if (s[i] != ' ')
           stk.push(s[i]);
       else 
       {
           // Contents of the stack will be printed when a space is found.
           while (stk.empty() == false) 
           {
               cout << stk.top();
               stk.pop();
           }
           cout << " ";
       }
   }

   // As there may not be space after last word.
   while (stk.empty() == false) 
   {
       cout << stk.top();
       stk.pop();
   }
}

int main()
{
   string s = "Welcome To InterviewBit";
   reverseWords(s);
   return 0;
}
                        
Output:
                        
emocleW oT tiBweivretnI
                        
Conclusion:
                        
The Cisco interview questions and answers provided here will guide you to prepare for your upcoming interview and face the questions confidently. In order to add more weightage to your resume, you can take up a Cisco certification or course.

Alternatively, you may go through resources on various other Networking and Hardware concepts to grow your knowledge. Preparing for the Cisco interview questions and answers in this article will definitely help you stand out as a strong potential candidate for the job.
                        
