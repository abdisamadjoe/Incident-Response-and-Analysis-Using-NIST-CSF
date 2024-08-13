# NIST Cybersecurity Framework: Incident Response Project

## Project Description

In this project, you will analyze a Distributed Denial of Service (DDoS) attack using the National Institute of Standards and Technology's Cybersecurity Framework (NIST CSF). The goal is to create an incident report and improvement plan to enhance your company's network security and incident response strategies. This project demonstrates a proactive approach to cybersecurity, improves communication with stakeholders, and strengthens overall security practices.

## Scenario

**Organization**: Multimedia Company

**Incident**: DDoS Attack

**Impact**: Network services stopped responding due to a flood of ICMP packets.

**Response Actions**:
- Blocked incoming ICMP packets.
- Stopped non-critical network services.
- Restored critical network services.

**Investigation Findings**:
- Attack exploited an unconfigured firewall.
- Network overwhelmed with ICMP pings.

## Incident Report Analysis Using NIST Cybersecurity Framework

### Summary

The company experienced a DDoS attack caused by a flood of ICMP packets, disrupting all network services. The cybersecurity team responded by blocking the attack, stopping non-critical network services, and restoring critical network services.

### Analysis

| **NIST CSF Function** | **Summary** |
|-----------------------|-------------|
| **Identify**          | A malicious actor targeted the company with an ICMP flood attack, affecting the entire internal network. All critical network resources needed to be secured and restored. |
| **Protect**           | A new firewall rule was implemented to limit ICMP packet rates, and an IDS/IPS system was added to filter suspicious ICMP traffic. |
| **Detect**            | Source IP address verification was configured on the firewall, and network monitoring software was installed to detect abnormal traffic patterns. |
| **Respond**           | For future incidents, affected systems will be isolated, critical systems and services restored, network logs analyzed for suspicious activity, and incidents reported to management and legal authorities. |
| **Recover**           | Recovery involves restoring network services, blocking ICMP flood attacks at the firewall, stopping non-critical services to reduce traffic, and reactivating non-critical systems once the attack subsides. |

## Conclusion

Applying the NIST Cybersecurity Framework ensures a structured approach to managing and responding to security incidents. This method enhances cybersecurity practices and resilience against future threats.
