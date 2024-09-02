[![Networking Basics](https://i.postimg.cc/T2Sd0s5C/2022-02-Blockchain-1p1.jpg)](https://postimg.cc/QVQZx0bT)

# Holberton School Networking Repository

## Overview

The `holbertonschool-network` repository is designed to help students grasp fundamental networking concepts through hands-on exercises. This repository is divided into subfolders that each cover specific networking topics and related tasks. By working through these tasks, students will build a solid foundation in understanding how networks operate, how IP addressing works, and how to interact with network interfaces in a Linux environment.

## Key Networking Concepts

### Localhost and 127.0.0.1
- **Localhost**: Refers to the computer you are currently using. The IP address `127.0.0.1` is commonly associated with `localhost`, allowing you to test networking configurations without needing an external network.

### IP Addressing and 0.0.0.0
- **IP Addressing**: Every device on a network is identified by an IP address, which allows for communication between devices.
- **0.0.0.0**: This address is a non-routable meta-address used to designate an invalid, unknown, or non-applicable target. It can also refer to all IP addresses on the local machine.

### `/etc/hosts` File
- **/etc/hosts**: A file used in Unix-like operating systems to map hostnames to IP addresses. It can override DNS queries, making it a quick way to locally resolve domain names.

### Network Interfaces
- **Network Interfaces**: These are software abstractions that represent network connections. Tools like `ifconfig` or `ip` are used to display and configure network interfaces.

## Subfolders Overview

### `basics_0`
This directory covers the very basics of networking, including understanding localhost, IP addresses, and basic commands to interact with network interfaces. The tasks here are designed to introduce you to these concepts in a practical, hands-on manner.

| Task No | Task Name                 | Description                                                                                      | File Name                 | Points |
|---------|---------------------------|--------------------------------------------------------------------------------------------------|---------------------------|--------|
| 0       | Localhost                  | Write a Bash script that returns the IP address of `localhost`.                                  | `0-localhost`             | 1      |
| 1       | What's my IP               | Write a Bash script that displays your machine's public IP address.                               | `1-whats_my_ip`           | 1      |
| 2       | Display active interfaces  | Write a Bash script that displays all active network interfaces.                                  | `2-display_active_ifaces` | 1      |

### `basics_1`
This directory builds on the fundamentals, diving deeper into how to manipulate network configurations, such as modifying the `/etc/hosts` file and setting up port listening on localhost. The tasks are intended to solidify your understanding of network configuration in a Unix environment.

| Task No | Task Name                  | Description                                                                                      | File Name                          | Points |
|---------|----------------------------|--------------------------------------------------------------------------------------------------|------------------------------------|--------|
| 0       | Change your home IP         | Modify the `/etc/hosts` file so that `localhost` resolves to `127.0.0.2` and `facebook.com` resolves to `8.8.8.8`. | `0-change_your_home_IP`            | 2      |
| 1       | Show attached IPs           | Display all active IPv4 IPs on the machine.                                                      | `1-show_attached_IPs`              | 1      |
| 2       | Port listening on localhost | Write a Bash script that listens on port 98 on `localhost`.                                      | `2-port_listening_on_localhost`    | 1      |


___

### **Author**: Clément DEFER