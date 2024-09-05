# Network Basics

This read me provides information about the `ifconfig`, `telnet`, `nc`, and `cut` commands, along with some learning objectives related to networking.

## Commands

### ifconfig
The `ifconfig` command is used to configure and display information about network interfaces on a system. It allows you to view and modify network interface settings such as IP address, netmask, and more.

### telnet
The `telnet` command is a network protocol used to establish a remote connection to a device over a TCP/IP network. It allows you to communicate with remote servers or devices using the Telnet protocol.

### nc
The `nc` (netcat) command is a versatile networking utility that can be used for various purposes, such as port scanning, file transfer, and network troubleshooting. It provides a simple way to establish TCP and UDP connections.

### cut
The `cut` command is used to extract specific sections or fields from lines of text. It is often used in conjunction with other commands or in shell scripts to manipulate and process text data.

## Learning Objectives

- **localhost/127.0.0.1**: The term "localhost" refers to the loopback network interface, which is used to access the network services running on the same machine. The IP address 127.0.0.1 is the loopback address that points to the local machine itself.

- **0.0.0.0**: The IP address 0.0.0.0 is a special address used to represent all IP addresses on the local machine or network. It is often used as a placeholder or wildcard address.

- **/etc/hosts**: The `/etc/hosts` file is a local text file that maps hostnames to IP addresses. It is used by the operating system to resolve domain names before querying DNS servers. It can be used to override DNS settings or define custom hostnames.

- **Displaying Active Network Interfaces**: To display the active network interfaces on your machine, you can use the `ifconfig` command or the `ip` command (iproute2 package). These commands provide detailed information about the network interfaces, including IP addresses, netmasks, MAC addresses, and more.