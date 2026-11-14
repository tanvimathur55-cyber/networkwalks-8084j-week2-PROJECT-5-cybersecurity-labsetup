# Cybersecurity Lab Environment Setup project5 — Networkwalks B084J Week 2

NetworkWalks Cybersecurity Internship – Week 2

## Project Overview Using Zenmap identify and locate any active devices on the local network.
-"Identify the local network setup".

-"Use host discovery".
-Analyze results of host discovery.
-Visualize network topology.


#Tools used
Windows 11
Command Prompt
Zenmap
Nmap 7.99.3

#3.Identifying Local network
This displayed the IPv4 address, subnet mask, and default gateway.


### Network Configuration

| Parameter | Value |
| :--- | :--- |
| Network | 192.168.0.0/24 |
| Subnet Mask | 255.255.255.0 |
| Network Type | Private LAN |

<img width="621" height="207" alt="image" src="https://github.com/user-attachments/assets/0ff9a2fd-d01d-4f30-9f39-af52b77d9075" />

#4. Configuring Zenmap
   Zenmap was set up as follows:
Target: 192.168.0.0/24
Profile: Ping scan

Command used
nmap -sn 192.168.0.0/24

### Network Configuration
<img width="624" height="396" alt="image" src="https://github.com/user-attachments/assets/5f140495-b0b4-4d33-b2d7-ec95067518dd" />

###5. Performing the Network Scan
 A ping scan was performed on the local network.

 ### Scan Results

| Metric | Result |
| :--- | :--- |
| IP `addresses scanned` | `256` |
| `Active hosts` | `5` |
| `Scan duration` | `4.81 seconds` |
| `Scan type` | `Ping scan` |
| `Nmap version` | `7.99.3` |
Five hosts were reported as active during the scan.

###Screenshot – Network Topology
<img width="797" height="772" alt="image" src="https://github.com/user-attachments/assets/51f720c2-71bb-41b5-acf2-298106b83dd9" />

###6. Observations
-Zenmap provides a graphical interface for Nmap.
-The ping scan identified five responsive hosts.
-Host-discovery results represent the network state at the time of scanning.
-The Topology tab helped visualize the discovered devices.
-Host discovery alone does not confirm security vulnerabilities.



   
