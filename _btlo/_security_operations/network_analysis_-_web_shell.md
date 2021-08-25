---
toc: true
toc_sticky: true
title: "Network Analysis - Web Shell"
excerpt: "The SOC received an alert in their SIEM for ‘Local to Local Port Scanning’ where an internal private IP began scanning another internal system."
permalink: /write-ups/btlo/security_operations/network_analysis_-_web_shell
layout: btlo
header:
  teaser: "/images/btlo/network_analysis_-_web_shell/challenge1_header.png"
---
![](/images/btlo/network_analysis_-_web_shell/challenge1_header.png)
## **Overview**
### <ins>Scenario</ins>
The SOC received an alert in their SIEM for ‘Local to Local Port Scanning’ where an internal private IP began scanning another internal system. Can you investigate and determine if this activity is malicious or not? You have been provided a PCAP, investigate using any tools you wish. 

### <ins>Tools</ins>
 - [Wireshark](https://www.wireshark.org/docs/man-pages/wireshark.html){:target="_blank"}
 - [TShark](https://www.wireshark.org/docs/man-pages/tshark.html){:target="_blank"}
 - [TCPDump](https://www.tcpdump.org/tcpdump_man.html){:target="_blank"}
