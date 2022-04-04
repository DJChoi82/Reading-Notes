Class 1

Windows Server looks very similar to windows but it is used to manage computers, files, and services. It uses the same kernel and can run the same software. Windows server supports SMB direct. Windows server supports more ram than windows 10 (2tb vs 24tb). Windows server supports more physical CPUs. Windows server is more expensive and can cost up to $6,200.

This topic is important as most larger businesses will probably use a server as a domain to control the other computers.

Class 2 Windows domain remotely controls a large number of computers in a same local network or VPN. User accounts, passwords, and group policy settings are on the domain controller. Only Windows pro or enterprise can join a domain. Most home computers are not part of a domain but part of a workgroup. Computers on a workgroup doesn't have control over other computers. You can't leave a domain without local admin access or reinstalling windows.

This topic is important as network admins will be controlling the domains.

Class 3

Active directory is microsofts management service for windows domain. It manages users, resources, applications, digital certificates, access, and rights. It supports users, groups, contact, computer, folders, printer, and OU. It uses protocols like LDAP, DNS, version of Kerberos. It uses a structure with domain, tree, and forest.

This topic is important as businesses can manage many computers from a central server.

Class 4

Group policy has a lot of advanced settings. When used correctly can increase security of computers and help with attacks. GPO should be used to ensure the IT infrastructure is set up securely. GPO can have password policy, systems management, health check. GPOs are not immune to cyberattacks.

This topic is important as GPOs need to be setup to secure the computers.

Class 5

Path Tuesday is when Microsoft releases large updates on second Tuesday of each month. Patches include security vulnerabilities patches. Critical security updates can happen anytime.

This is an important topic as IT professionals need to know when big updates come out.

Class 6

The OSI model is the 7 layers that computers use to communicate. The seven layers are physical, data link, network, transport, session, presentation, and application.

Wireshark is a tool to capture network packets. This tool lets you check your network traffic under a microscope. Wireshark can be used to troubleshoot networks with performance issues. Cybersecurity professionals can use to trace connections.

Class 7

NGINX is a software for web hosting, load balancing, media streaming, caching, reverse proxying. It can function as a mail server. NGINX goal was to create the fastest web server. NGINX is an open source software.

Class 8

VirtualBox network can be connected to different networks and provides multiple network modes. Each VM can use up to 8 virtual network adapters. The different modes are not attached, NAT, NAT Network, bridged adapter, internal network, and host only adapter. Not attached is when it is used as if there is no network cable attached. NAT only gives access to the internet and the VM is not accessible from another machine. All VMs using NAT will get the same IP in its own isolated network. NAT network is similar to NAT except the machines on the NAT network can communicate with each other. Machines outside of the NAT network cannot communicate with the machines on the NAT network. Bridged adapter connects the machine to the network on the physical adapter. Other computers on the physical network can access the VM. Internal network is a network isolated from other networks, only the machines connected within the internal network can communicate with each other. Host-only adapter can only communicate with other VMs connected to the host only network.

Class 9

CIDR notation is a way of representing a CIDR block/range of IP addresses.

Network segmentation is when different parts of the network come together by bridges, switches or routers. You can create different zones and limit access to each other zones. Segmentation is better for security.

Class 10

Site to site VPN is a connection between multiple networks. It is a private and protected traffic. Remote access VPN is a temporary connection between two or more users and used for remote workers. Intranet-based site to site connects one or more lans to create a wan. Extranet based site to site used by two or more companies to share certain resources.

Class 11

Nat allows multiple private IP addresses access to the the internet with one public ip address. NAT masks source port numbers. Nat provides privacy and eliminate address renumbering. Nat complicates tunneling protocols such as IPsec.

class 12

RADIUS authenticates from requests from a client. Client is 100% responsible for the request. Client send request to server and the server look in the authorize section to see if it recognize something. If it doesn't recognize it will do nothing.

class 13

Port mirroring (SPAN) & TAP (Terminal Access Point) can be used to capture network traffic. SPAN forwards a copy of incoming and outgoing packets to another port. It is inexpensive and flexible but consumes a lot cpu resources. Network tap is a hardware device and passively captures traffic. It is expensive but captures all packets and no risk of dropped packets.

Class 14

Port scanners check for open, closed, or filtered ports. Port scanners are useful to diagnose network issues. Attacker can also use it to infiltrate a network.

Class 15

OAuth is a protocol that allow authenticated access with a initial single logon. Released in 2010 and v2 released in 2912. With OAuth a user logon once and can access other websites with the first logon. OAuth works by having multiple sites work together for authorization. OpenID is also for signoe sign on and uses authentication.

Authentication is for logon and authorization is what a user can do. Authorization code flow is when an authorization code is exchanged for a token. Authorization for PKCE is when is requires more security. Implicit flow with form post is for public clients that can't store client secrets. Client credentials flow is when the system authenticates/authorizes the app. Device authorization flow is when a link is used to authorize the device. Resource owner password flow is when credentials are needed.
