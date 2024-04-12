# Important Keypoints for Linux

## Linux :<br>

It is a family of powerful and open-source Unix like operating systems based on linux kernel.

## Popular Linux Distros :

<span style="color:Yellow" ><b>1. Kali Linux :</b><br></span>
Debian-based OS for cybersecurity tasks like penetration testing and digital forensics. Offers a wide range of pre-installed tools for network analysis and vulnerability assessment. Popular among professionals and students in security-related fields.

<span style="color:Yellow" ><b>2. Parrot :</b><br></span>
Lightweight Debian-based distro tailored for cybersecurity. Packed with tools for penetration testing, digital forensics, and privacy protection. User-friendly interface, ideal for security professionals and enthusiasts.

<span style="color:Yellow" ><b>3. Ubuntu :</b><br></span>
Popular Linux distribution known for its user-friendly interface and stability. Based on Debian, it offers a balance between ease of use and performance. Widely used for both personal and professional purposes, with a large community of users and developers.

<span style="color:Yellow" ><b> 4. Fedora :</b><br></span>
A Linux distribution sponsored by Red Hat, known for its cutting-edge features and commitment to open source principles. It's a leading platform for developers and enthusiasts, offering a balance between innovation and stability. With regular updates and a focus on the latest technologies, Fedora is ideal for those who want to stay at the forefront of the Linux ecosystem.

## Linux Boot Process :

It includes <b>4</b> phases.

<span style="color:Yellow" ><b>1. Bootstrap Phase :</b><br></span>

- Initial setup and preparation of essential components.
- Assessing requirements and laying down foundational plans.
- Allocating resources and initiating execution.
- Monitoring progress and adapting strategies accordingly.
- Achieving key milestones to proceed to subsequent phases.

<span style="color:Yellow" ><b>2. Bootloader Phase :</b><br></span>

- Loading the operating system into memory from storage.
- Executing the bootloader code to initiate system boot-up.
- Providing hardware initialization and configuration.
- Handing control to the kernel for further processing.
- Ensuring a smooth transition from firmware to operating system execution.

<span style="color:Yellow" ><b>3. Kernel Phase :</b><br></span>

- Core component of the operating system responsible for managing resources.
- Initializing system processes, memory management, and device drivers.
- Establishing communication between hardware and software layers.
- Handling system calls and facilitating user interaction.
- Enabling multitasking and managing system stability.

<span style="color:Yellow" ><b>4. Initialization Phase :</b><br></span>

- Initializing hardware components and system resources.
- Performing self-tests and diagnostic checks for hardware integrity.
- Setting up system configurations and parameters.
- Loading essential software components and drivers.
- Establishing a stable environment for the operating system to function effectively.

## Network Configuration using Linux :

<b>`ip` :</b><br>
A versatile command for managing networking interfaces, addresses, routes, and tunnels. It can be used to assign IP addresses, configure network interfaces, manage routing tables, and more.

- <span style="color: Grey">Command:</span> `ip addr show`<br>
  Display information about all network interfaces and their IP addresses.<br>

- <span style="color: Grey">Command:</span> `ip route show`<br>
  Show the routing table, which determines how network packets are forwarded.

<b>`dig` :</b><br>
A command-line tool for querying DNS (Domain Name System) servers. It's used to retrieve DNS-related information such as IP addresses, name servers, and DNS record types like A, AAAA, MX, etc.

- <span style="color: Grey">Command:</span> `dig example.com`<br>
  Query DNS records for the domain "example.com" and display the results.

- <span style="color: Grey">Command:</span> `dig -x 8.8.8.8`<br>
  Perform a reverse DNS lookup for the IP address "8.8.8.8" to find its associated domain name.

<b>`nslookup` :</b><br>
Another tool for querying DNS servers to obtain DNS-related information. It's used to look up IP addresses, domain names, and other DNS records.

- <span style="color: Grey">Command:</span> `nslookup example.com`<br>
  Lookup the IP address of the domain "example.com" using DNS.

- <span style="color: Grey">Command:</span> `nslookup 8.8.8.8`<br>
  Perform a reverse DNS lookup for the IP address "8.8.8.8" to find its associated domain name.

<b>`netstat` :</b><br>
A command-line tool for displaying network-related information such as active network connections, routing tables, interface statistics, and more. It's useful for monitoring network activity and troubleshooting network issues.

<b>`nmcli` :</b><br>
nmcli: Network Manager Command-Line Interface is a command-line tool for managing NetworkManager, which is a system network service in Linux. It allows users to control various aspects of network configuration such as connections, devices, IP addressing, and more.

<b>`route` :</b><br>
A command-line tool for viewing and manipulating the IP routing table. It's used to display or modify the kernel's IP routing table, including adding or deleting routes, changing metrics, and more.

Storage management:-

1. Master Boot Record(MBR)
2. ext3 file system
3. Network File System(NFS)
4. Samba/SMB
5. New Technology File System(NTFS)

Cloud and Virtualization:-

1. OVF and OVA Templates
2. Container Technology and Docker Basics
3. Types of Cloud
4. Cloud Concepts
5. Network Address Translation(NAT)

Software Management:-

1. Red Hat Package Manager(RPM)
2. Advanced Package Tool(APT)
3. tar, tgz and gz packages
4. curl and wget

User and Group management:-

1. Commands- useradd, groupadd, usermod. groupmod, userdel, groupdel, passwd, change, id, whoami, who, w, last
2. /etc/passwd, /etc/shadow, and /etc/group files

Service Management:-

1. systemd
2. systemctl and service commands

Linux Servers:-

1. Network Time protocol(NTP)
2. Secure Shell(SSH)
3. Apache and NGINX servers
4. Certificate Authority(CA)
5. Domain name System(DNS)
6. Dynamic Host Configuratiuon Protocol(DHCP)
7. Authentication Servers
8. Proxy Servers
9. Virtual Private Networks(VPN)
10. Monitoring Servers
11. Database Servers
12. Mail Servers
13. Load Balancers

Scheduling and Automation:-

1. cron
2. job control commands
3. kill command
