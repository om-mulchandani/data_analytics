# What Is a Protocol?

A **protocol** is an agreed set of rules that devices or software follow to communicate and exchange information. Protocols define things such as how data is formatted, addressed, transmitted, received, and checked for errors.

There are many protocols, so it is not practical to list every protocol ever created. Below are common protocols, grouped by their main purpose.

## Common Types of Network Protocols

### 1. Internet and Transport Protocols

- **IP (Internet Protocol)** — Addresses devices and routes packets between networks. Common versions are **IPv4** and **IPv6**.
- **TCP (Transmission Control Protocol)** — Delivers data reliably and in order; commonly used for websites, email, and file transfers.
- **UDP (User Datagram Protocol)** — Sends data with low overhead but does not guarantee delivery or order; often used for live audio/video, gaming, and DNS.
- **QUIC** — A modern transport protocol built on UDP that supports secure, fast connections; used by HTTP/3.

### 2. Web and Application Protocols

- **HTTP (Hypertext Transfer Protocol)** — Transfers web pages and other resources.
- **HTTPS (HTTP Secure)** — HTTP protected with TLS encryption and authentication.
- **DNS (Domain Name System)** — Finds the IP address associated with a domain name, such as `example.com`.
- **DHCP (Dynamic Host Configuration Protocol)** — Automatically assigns network settings, such as an IP address, to devices.
- **WebSocket** — Maintains a two-way connection for real-time communication between a client and server.
- **SIP (Session Initiation Protocol)** — Sets up, manages, and ends voice or video communication sessions.
- **RTP (Real-time Transport Protocol)** — Carries real-time audio and video, often alongside session-control protocols.

### 3. File Transfer and Remote Access Protocols

- **FTP (File Transfer Protocol)** — Transfers files; standard FTP does not encrypt the connection.
- **SFTP (SSH File Transfer Protocol)** — Transfers and manages files securely over SSH.
- **TFTP (Trivial File Transfer Protocol)** — A simple file-transfer protocol with limited features, often used on local networks.
- **SSH (Secure Shell)** — Provides encrypted remote login and command access.
- **Telnet** — Provides remote command access, but sends data without encryption; generally replaced by SSH.
- **RDP (Remote Desktop Protocol)** — Provides remote access to a computer's graphical desktop.

### 4. Email Protocols

- **SMTP (Simple Mail Transfer Protocol)** — Sends email between clients and mail servers or between mail servers.
- **IMAP (Internet Message Access Protocol)** — Accesses and synchronizes email stored on a mail server.
- **POP3 (Post Office Protocol 3)** — Retrieves email from a mail server, often by downloading messages to a device.

### 5. Routing and Network Management Protocols

- **BGP (Border Gateway Protocol)** — Exchanges routing information between large networks on the internet.
- **OSPF (Open Shortest Path First)** — Finds routes within an organization's IP network.
- **RIP (Routing Information Protocol)** — A basic routing protocol for smaller networks.
- **SNMP (Simple Network Management Protocol)** — Monitors and manages network devices.
- **ICMP (Internet Control Message Protocol)** — Reports network errors and supports diagnostics, such as `ping`.
- **NTP (Network Time Protocol)** — Synchronizes clocks on computers and network devices.

### 6. Security and Tunneling Protocols

- **TLS (Transport Layer Security)** — Encrypts and authenticates communications; used by HTTPS and other secure services.
- **IPsec (Internet Protocol Security)** — Protects IP traffic and is often used to build VPNs.
- **WireGuard** — A modern VPN protocol designed to create secure network tunnels.
- **IKEv2 (Internet Key Exchange version 2)** — Negotiates and manages security associations, commonly for IPsec VPNs.
- **Kerberos** — Authenticates users and services using tickets, often within managed organization networks.

### 7. Local Network and Device Protocols

- **Ethernet (IEEE 802.3)** — Defines wired local-network communication.
- **Wi-Fi (IEEE 802.11)** — Defines wireless local-network communication.
- **Bluetooth** — Connects nearby devices wirelessly over short distances.
- **ARP (Address Resolution Protocol)** — Finds the link-layer address associated with an IPv4 address on a local network.
- **LLDP (Link Layer Discovery Protocol)** — Allows directly connected network devices to share information about themselves.

## Protocols Work Together

Communication usually uses several protocols together. For example, when opening a secure website, **DNS** can find the server, **IP** routes packets, **TCP** or **QUIC** carries the connection, **TLS** protects it, and **HTTP** requests the web content.