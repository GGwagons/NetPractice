# Net Practice - System Administration Networking Exercise

**Version**: 3.1

## Project Overview

Welcome to **Net Practice**, a system administration project aimed at helping you understand networking through a series of practical exercises. The project consists of configuring small-scale networks using a training interface available in your web browser.

## Theory: What You Need to Know to Complete the Project

### 1. Understanding TCP/IP Networking

To complete this project, it’s essential to have a basic understanding of networking concepts, particularly the **TCP/IP (Transmission Control Protocol/Internet Protocol)** model, which forms the foundation of modern networking. TCP/IP is divided into four main layers:

- **Application Layer**: Protocols like HTTP, FTP, DNS, and SMTP work here. This layer interacts with user-facing software.
- **Transport Layer**: Manages communication between hosts. TCP ensures reliable transmission, while UDP provides faster, connectionless communication.
- **Internet Layer**: Handles IP addressing, routing, and packet forwarding using IP (Internet Protocol). Devices must be correctly addressed in this layer.
- **Link Layer**: Deals with the physical transmission of data between network devices, including hardware like routers and switches.

### 2. IP Addressing and Subnetting

You will work with **IP addresses**, which are used to identify devices on a network. Every device in a network must have a unique IP address.

- **IPv4**: The traditional addressing system, composed of four octets (e.g., `192.168.1.1`).
- **Subnetting**: Allows you to divide a network into smaller, more efficient segments. You’ll need to understand how to define subnets and correctly assign IPs within these subnets.

A grasp of **subnet masks** (e.g., `255.255.255.0`) and **CIDR notation** (e.g., `/24`) will be crucial for configuring networks.

### 3. Router Configuration

Routers are used to direct network traffic between different subnets and external networks. For this project, you will need to:

- Understand **routing tables**, which define the routes that data takes between devices.
- Configure **static routes** so that data can be passed correctly from one network to another.

### 4. Network Devices and Their Roles

In this project, you’ll simulate working with various network devices, including:

- **Routers**: Devices that direct data between different networks.
- **Switches**: Manage data traffic within the same network.
- **Hosts/Clients**: End devices (e.g., computers, servers) that participate in the network.

Each device plays a different role in making a network functional, and misconfiguring even one of these devices can break the network.

### 5. Troubleshooting and Debugging

When setting up networks, problems will inevitably arise. To solve them, you need to:

- Analyze **logs**: The training interface provides logs that can indicate what went wrong during the configuration.
- Use **ping tests**: These help verify if devices in the network can communicate.
- Debug common issues like **IP conflicts**, **misconfigured routing tables**, or **subnetting errors**.

---
