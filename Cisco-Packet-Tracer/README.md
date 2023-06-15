<h1>How to build a Network solution on Cisco Packet Tracer</h1>

<h2>Description</h2>
<p>The following networking diagram is a simple network architecture I developed for a small business as part of my Network Security paper. It includes a number of security measures and features, such as:

VLAN tagging: Each department has been assigned a VLAN tag. This allows each department to only ping devices within their own network, and not other departments. For example, a marketing employee would not be able to ping a finance employee's device.

DMZ: The external IT contractor has access only to the DMZ web server. This prevents them from accessing any internal resources.

SSH: IT administrators have access to all internal networks and can use SSH to connect to devices.

NAT: The ASA stateful firewall server translates internal network IP addresses to public IP addresses. This prevents external parties from knowing the private IP addresses of the actual devices.

DHCP: The ASA stateful firewall server also acts as a DHCP server, which assigns IP addresses to internal hosts.

In addition to other vital network security measures. This network architecture demonstrates some of the fundamental elements of network security for a small organisation. </p>
<br>
===========================================<br>
<br>
Links to my Packet Trace & Cisco Commands: <br>
https://lnkd.in/g9RQcBkG

https://lnkd.in/gsT--36T


<br>
Resources for Learning Packet Tracer <br>
===========================================<br>
<br>
I put in a lot of time understanding packet tracer and Cisco switch commands. If you are a networking student seeking for a decent resource to study packet tracer, worth checking the following.

Getting Started with Cisco Packet Tracer - Cisco Packet Tracer: A Free and Fun Course for Beginners
https://lnkd.in/g6pEuCWV

The Complete Networking Fundamentals Course. Your CCNA start by David Bombal (Highly Recommend)
https://lnkd.in/ghukJDja

Saleh Al-Moghrabi - YouTube
https://lnkd.in/g66dTaZn

Greg South - YouTube
https://lnkd.in/gTaZ9UG9
<br />


<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Cisco Packet Tracer <br/>
<img src="https://i.imgur.com/bxgc907.png" height="80%" width="80%" alt="Cisco Packet Tracer "/>
<br />
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

README.md
