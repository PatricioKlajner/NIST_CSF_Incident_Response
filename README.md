<h1>Using the NIST Cybersecurity Framework to Respond to a Security Incident</h1>

<h2>Description</h2>
This project involves creating an incident report to analyze a network incident. I will analyze the situation using the National Institute of Standards and Technology's Cybersecurity Framework (NIST CSF). It will demonstrate a proactive approach to security, improve communication and transparency with stakeholders, and improve security practices within the organization.
<br />
<br />
As a cybersecurity analyst, I am tasked with using this security event to create a plan to improve my company’s network security, following the NIST CSF. I will use the CSF to help me navigate through the different steps of analyzing this cybersecurity event and integrate my analysis into a general security strategy.

<h2>Scenario</h2>
I am a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. My organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.
<br />
<br />
During the attack, my organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 
<br />
<br />
The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 
<br />
<br />
To address this security event, the network security team implemented: 
<br />
- A new firewall rule to limit the rate of incoming ICMP packets.
<br />
- Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets.
<br />
- Network monitoring software to detect abnormal traffic patterns.
<br />
- An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics.
<br />

<h2>Incident Report Analysis</h2>

<h3>Summary:</h3>
The company experienced a security event when all network services suddenly stopped responding, disrupting regular business operations. The cybersecurity team found the disruption was caused by a distributed denial of services (DDoS) attack through a flood of incoming ICMP packets, which compromised the internal network for two hours. The incident management team responded by blocking incoming ICMP packets and stopping all non-critical network services so that critical network services could be restored.

<h3>Identify:</h3>
A malicious actor or actors targeted the company with an ICMP flood attack, affecting the entire internal network and business operations. The attackers accomplished this by sending the ICMP flood into the company's network through an unconfigured firewall, which allowed the attackers to overwhelm the company's network through a DDoS attack. All critical network resources needed to be secured and restored to a functioning state. 

<h3>Protect:</h3>
To address this security event, the cybersecurity team implemented a new firewall rule to limit the rate of incoming ICMP packets and an IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics. These changes will help protect the company against future attacks.

<h3>Detect:</h3>
To detect possible attacks in the future, the cybersecurity team configured source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets and implemented network monitoring software to detect abnormal traffic patterns. This was implemented to be able to continuously monitor network traffic on network devices to check for suspicious activity, such as incoming external ICMP packets from non-trusted IP addresses attempting to pass through the organization’s network firewall. 

<h3>Respond:</h3>
To be able to respond to future security events, the cybersecurity team will implement network segmentation by isolating affected systems to prevent further disruption to the network. They will attempt to restore any critical systems and services that were disrupted by the event. Then, the team will analyze network logs to check for suspicious and abnormal activity. The team will also develop a playbook for this situation and report all incidents to upper management and appropriate legal authorities, if applicable. 

<h3>Recover:</h3>
To recover from a DDoS attack by ICMP flooding, access to network services needs to be restored to a normal functioning state. In the future, external ICMP flood attacks can be blocked at the firewall. Then, all non-critical network services should be stopped to reduce internal network traffic. Next, critical network services should be restored first. Finally, once the flood of ICMP packets has timed out, all non-critical network systems and services can be brought back online.



