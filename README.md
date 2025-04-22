# Digicamp Network Simulation

## Project Overview
This project involved simulating a network infrastructure for Digicamp, a digital skills training provider. The goal was to implement and configure a network system across three building floors, integrating routers, switches, PCs, access points, and a server, while applying network services such as DHCP, static IP assignment, and a web server.

## Project Steps

### 1. Network Topology Design
- Created a three-floor network topology.
- Deployed core devices: routers, switches, access points, PCs, laptops, and a server.
- Assigned network addressing schemes using both DHCP and static IPs based on different sections.

![Network Topology](ss/Network_Topology.png)

### 2. Floor 1 Configuration
- Configured routers with RIP routing protocol.
- Set up DHCP pools without external servers.
- Assigned IP addresses dynamically to PCs and laptops.
- Connected and configured access points.

![Floor 1 Configuration]()

- **Testing:** Conducted pings between different rooms (e.g., SE Class to WD Class, UI/UX, Data Science, Admin Room, and Chill Room).

### 3. Floor 2 Configuration
- Configured router ports and implemented RIP routing.
- Set up PCs with static IP addressing.
- Connected and configured the access point.

![Floor 2 Configuration]()

- **Testing:** Validated connectivity through pings between floors and departments.

### 4. Floor 3 Configuration
- Configured routers and applied RIP routing.
- Configured server with a static IP.
- Enabled DHCP, DNS, and web server services.
- Connected and configured the access point.

![Floor 3 Configuration]()

- **Testing:** Verified network functionality through pings and DNS server tests.

## Tools and Environment
- **Hardware:** ASUS Vivobook
- **Operating System:** Windows 11 64-bit
- **Software:** Cisco Packet Tracer, Microsoft Word, Google Drive

## Key Outcomes
- Full network simulation for a multi-floor building.
- Implementation of DHCP and static IP addressing.
- Successful integration of web and DNS servers.
- Reliable connectivity across all floors and departments.

---

> _"Building efficient networks, one simulation at a time."_

---

# How to Add Images to GitHub Repository

1. Create a folder named `images/` in your project directory.
2. Save all screenshots (e.g., network topology, configurations) into the `images/` folder.
3. Use the following syntax to insert images:

```markdown
![Alt Text](images/your_image_filename.png)

