# Incident Report Analysis

## Summary
The company experienced a security event when all network services suddenly stopped responding. The cybersecurity team found the disruption was caused by a distributed denial of service (DDoS) attack through a flood of incoming ICMP packets. The team responded by blocking the attack and stopping all non-critical network services, so that critical network services could be restored.

## Identify
- A malicious actor or actors targeted the company with an ICMP flood attack.  
- The entire internal network was affected.  
- All critical network resources needed to be secured and restored to a functioning state.

## Protect
- The cybersecurity team implemented a new firewall rule to limit the rate of incoming ICMP packets.  
- An IDS/IPS system was implemented to filter out some ICMP traffic based on suspicious characteristics.

## Detect
- Source IP address verification was configured on the firewall to check for spoofed IP addresses on incoming ICMP packets.  
- Network monitoring software was implemented to detect abnormal traffic patterns.

## Respond
- For future security events, the cybersecurity team will:
  - Isolate affected systems to prevent further disruption to the network.  
  - Restore any critical systems and services disrupted by the event.  
  - Analyze network logs for suspicious and abnormal activity.  
  - Report all incidents to upper management and appropriate legal authorities, if applicable.

## Recover
- To recover from a DDoS attack by ICMP flooding:
  - Restore access to network services to a normal functioning state.  
  - Block external ICMP flood attacks at the firewall.  
  - Stop all non-critical network services to reduce internal network traffic.  
  - Restore critical network services first.  
  - Once the flood of ICMP packets has timed out, bring all non-critical network systems and services back online.

---

## Reflections/Notes
*(Add your reflections or additional notes here.)*