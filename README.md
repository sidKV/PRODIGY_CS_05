# PRODIGY_CS_05

# Task-05
Develop a packet sniffer tool that captures and analyzes network packets. Display relevant information such as source and destination IP addresses, protocols, and payload data. Ensure the ethical use of the tool for educational purposes.

# Network Packet Analyzer
A Network Packet Analyzer (also known as a network protocol analyzer, packet sniffer, or network analyzer) is a tool or software application used to capture, inspect, and analyze network packets transmitted over a network. These packets are the fundamental units of data communication in a network, and analyzing them helps in understanding and diagnosing network behavior, performance, and security. A packet sniffer is a tool used to capture and analyze network traffic. Developing such a tool involves capturing packets from the network and then analyzing the contents to extract information like source and destination IP addresses, protocols, and payload data. This can be used for network troubleshooting, monitoring, or educational purposes.
Install Required Library: Ensure you have the 'scapy' library installed.

# How It Works:
Packet Capture with Scapy: The sniff() function from scapy is used to capture packets. It takes prn=packet_callback as a parameter, which means that for every captured packet, the packet_callback function will be called.
IP Layer Analysis: The tool checks if the packet contains an IP layer, and if so, extracts and prints the source and destination IP addresses and the protocol number.
TCP/UDP/ICMP Protocol Analysis: Depending on the protocol (TCP, UDP, ICMP), it further extracts and prints information such as port numbers for TCP and UDP, or the type and code for ICMP.
Payload Display: The tool also prints the raw payload data in the packet, which can be useful for further analysis.

# Repository Contents
PRODIGY_CS_05.py : The main Python script containing the implementation of the Network Packet Analyzer.
README.md : This file, providing an overview of the task and the project.
