# zentyal-network-monitoring
# Zentyal Network Monitoring & Administration

## Overview

This end-of-studies project (PFE) focuses on simplifying network administration, security, and IT services for Small and Medium-sized Enterprises (SMEs) with limited resources.

The project explores **Zentyal**, an open-source Linux-based platform that provides centralized management of network infrastructure and services through a web administration interface.

The practical implementation was carried out using **VirtualBox virtual machines** to design, configure, test, and evaluate different network architectures.

## Objectives

The main objectives of this project were to:

* Simplify network administration and monitoring
* Centralize the management of network services
* Improve network reliability and security
* Configure and manage essential network protocols
* Explore different network deployment architectures
* Implement multi-network and multi-site configurations
* Test connectivity, routing, VPN, and gateway configurations

## Technologies & Tools

* **Zentyal**
* **Ubuntu Linux**
* **VirtualBox**
* **DNS**
* **DHCP**
* **NTP**
* **FTP**
* **Firewall / iptables**
* **Static routing**
* **HTTP Proxy**
* **VPN**
* **Active Directory / OpenLDAP**
* **SMTP / POP3 / IMAP4**
* **Webmail**
* **ActiveSync**

## Project Architecture

The project investigated several network deployment scenarios using virtual machines.

### Scenario 1 — Basic Network Architecture

A Zentyal server with three network interfaces:

* Bridged Internet connection using DHCP
* Host-Only network for communication with the host machine
* Internal network connecting the virtual client

### Scenario 2 — Multiple Internal Networks

The initial architecture was extended with several distinct internal virtual networks to study network segmentation and service management.

### Scenario 3 — Multi-Gateway Architecture

A multi-gateway configuration was implemented to explore:

* WAN failover
* Load balancing
* Gateway management
* Network availability

### Scenario 4 — External Client

An external client was integrated through the external network to test:

* Connectivity
* Network access
* Remote communication
* VPN functionality

### Scenario 5 — Multi-Site Architecture

The final scenario explored an architecture involving multiple Zentyal servers connected through **VPN tunnels**, representing communication between different locations.

## Network Services Studied

The project covered the configuration and administration of several essential services.

### DNS

Configuration and management of domain name resolution within the network.

### DHCP

Automatic allocation of IP addresses and network configuration to client machines.

### NTP

Time synchronization between network devices and systems.

### FTP

Configuration and testing of file transfer services.

### Firewall

Use of firewall rules and `iptables` to control and secure network traffic.

### Routing

Configuration and analysis of static routes and gateway behavior.

### Proxy

Study and configuration of HTTP proxy services, including caching.

### Directory Services

Study of centralized identity and directory management using technologies such as Active Directory and OpenLDAP.

## Virtualization Environment

The practical implementation was performed using **VirtualBox**, allowing multiple virtual machines and network interfaces to be configured in an isolated environment.

This made it possible to reproduce different network architectures without requiring physical network equipment.

## Project Documentation

The complete project documentation is available in this repository:

* [Zentyal Network Monitoring Report](Zentyal_Network_Monitoring_Report.pdf)
* [Zentyal Network Monitoring Presentation](Zentyal_Network_Monitoring_Presentation.pptx)

## Skills Demonstrated

Through this project, I developed practical experience in:

* Network administration
* Linux administration
* Network virtualization
* Network architecture design
* DNS, DHCP, NTP and FTP configuration
* Firewall and network security
* Routing and gateway management
* VPN configuration
* Network troubleshooting
* Technical documentation

## Learning Outcomes

This project provided practical experience in designing and managing network infrastructures using an open-source centralized administration platform.

It also strengthened my understanding of how network services, security mechanisms, routing, virtualization, and remote connectivity interact within an enterprise environment.

## Future Improvements

Possible extensions of the project include:

* Automated network monitoring and alerting
* Centralized log analysis
* Integration with dedicated monitoring tools
* Automated configuration and deployment
* Advanced intrusion detection
* More extensive multi-site network testing
