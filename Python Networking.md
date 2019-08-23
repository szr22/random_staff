###Chapter 1,</br>
Review of TCP/IP Protocol Suite and Python, reviews the fundamental technologies that make up internet communication today, 
from the OSI and client-server model to TCP, UDP, and IP protocol suites. 
The chapter will review the basics of Python languages such as types, operators, loops, functions, and packages.
</br>
TCP state machine to accomplish their daily tasks (I know I don't), but they would be familiar with the basics of the OSI model, the TCP and UDP operations, different IP headers fields, and other fundamental concepts.
</br>
*An overview of the internet
  **Local Area Network (LAN)
  **Internet Service Provider (ISP)
  **Hosts, Internet of Things (IoT), Client; servers; network components as roads
  **Main Distribution Frame (MDF), central location; Intermediate Distribution Frame (IDF), closer to user
  **cloud data center CLOS network; edge data center
  **Open System Interconnection (OSI): application, presentation, session, transport, network, data link, physical; tcp/ip model
  **Client-server model
  **[tcp/ip guide](http://www.tcpipguide.com/)
  
*The OSI and client-server model
*TCP, UDP, and IP protocol suites
*Python syntax, types, operators, and loops
*Extending Python with functions, classes, and packages
</br>


###Chapter 2,</br>
Low-Level Network Device Interactions, uses practical examples to illustrate how to use Python to execute commands on a network device. 
It will also discuss the challenges of having a CLI-only interface in automation. 
The chapter will use the Pexpect and Paramiko libraries for the examples. 
*Pexpect and Paramiko, Netmiko</br>
*[Data center networking changes](https://www.bigswitch.com/sites/default/files/presentations/murraydouglasstartuphotseatpanel.pdf)

###Chapter 3,</br>
APIs and Intent-Driven Networking, discusses the newer network devices that support Application Programming Interfaces (APIs) and other high-level interaction methods. 
It also illustrates tools that allow abstraction of low-level tasks while focusing on the intent of the network engineers. 
A discussion about and examples of Cisco NX-API, Juniper PyEZ, and Arista Pyeapi will be used in the chapter. 

###Chapter 4,</br>
The Python Automation Framework – Ansible Basics, discusses the basics of Ansible, an open source, Python-based automation framework. 
Ansible moves one step further from APIs and focuses on declarative task intent. 
In this chapter, we will cover the advantages of using Ansible, its high-level architecture, 
and see some practical examples of Ansible with Cisco, Juniper, and Arista devices. 

###Chapter 5,</br>
The Python Automation Framework – Beyond Basics, builds on the knowledge in the previous chapter and covers the more advanced Ansible topics. 
We will cover conditionals, loops, templates, variables, Ansible Vault, and roles. 
It will also cover the basics of writing custom modules. 

###Chapter 6,</br> 
Network Security with Python, introduces several Python tools to help you secure your network. 
It will discuss using Scapy for security testing, using Ansible to quickly implement access lists, 
and using Python for network forensic analysis. 

###Chapter 7,</br>
Network Monitoring with Python – Part 1, covers monitoring the network using various tools. 
The chapter contains some examples using SNMP and PySNMP for queries to obtain device information. 
Matplotlib and Pygal examples will be shown for graphing the results. 
The chapter will end with a Cacti example using a Python script as an input source. 

###Chapter 8,</br>
Network Monitoring with Python – Part 2, covers more network monitoring tools. 
The chapter will start with using Graphviz to graph the network from LLDP information. 
We will move to use examples with push-based network monitoring using Netflow and other technologies. 
We will use Python to decode flow packets and ntop to visualize the results. 
An overview of Elasticsearch and how it can be used for network monitoring will also be covered. 

###Chapter 9,</br> 
Building Network Web Services with Python, shows you how to use the Python Flask web framework to create our own API for network automation. 
The network API offers benefits such as abstracting the requester from network details, consolidating and customizing operations, 
and providing better security by limiting the exposure of available operations. 

###Chapter 10,</br>
AWS Cloud Networking, shows how we can use AWS to build a virtual network that is functional and resilient.
We will cover virtual private cloud technologies such as CloudFormation, VPC routing table, access-list, Elastic IP, NAT Gateway, 
Direct Connect, and other related topics. 

###Chapter 11,</br> 
Working with Git, we will illustrate how we can leverage Git for collaboration and code version control. 
Practical examples of using Git for network operations will be used in this chapter. 

###Chapter 12,</br> 
ontinuous Integration with Jenkins, uses Jenkins to automatically create operations pipelines that can save us time and increase reliability. 

###Chapter 13,</br>
Test-Driven Development for Networks, explains how to use Python's unittest and PyTest to create simple tests to verify our code. 
We will also see examples of writing tests for our network to verify reachability, network latency, security, and network transactions. 
We will also see how we can integrate the tests into continuous integration tools, such as Jenkins. 

[mastering python networking github](https://github.com/PacktPublishing/Mastering-Python-Networking-Second-Edition)
