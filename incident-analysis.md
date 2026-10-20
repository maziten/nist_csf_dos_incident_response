
 NIST Cybersecurity Framework: DoS Incident Report Analysis

 **Project Overview**

 This project analyzes a simulated Denial-of-Service (DoS) attack against a multimedia company that provides web design, graphic design, and social media marketing services to small businesses.

 The purpose of this project is to apply the five functions of the NIST Cybersecurity Framework (CSF) to analyze the incident and recommend improvements to the organization's network security.

**Project type:** Simulated incident-response analysis  
**Framework:** NIST Cybersecurity Framework (CSF)  
**Incident:** ICMP flood Denial-of-Service (DoS) attack

## 1. Incident Summary

The company experienced a DoS attack when a malicious actor flooded its network with Internet Control Message Protocol (ICMP) packets. 

The attack caused network services to stop responding and prevented normal internal traffic from accessing network resources for approximately two hours.

An investigation revealed that an unconfigured firewall allowed the malicious traffic to enter the network.

The incident management team blocked incoming ICMP packets, took non-critical network services offline, and restored critical services.

Following the investigation, the network security team implemented ICMP rate limiting, source IP address verification, network monitoring software, and an Intrusion Detection and Prevention System (IDS/IPS).

## 2. Identify

**Objective:** Identify security risks, vulnerabilities, and critical assets.

The primary vulnerability was an improperly configured firewall that allowed excessive incoming ICMP traffic. This weakness exposed the company's network to a DoS attack.

Recommended improvements:
- Conduct regular network security audits.
- Review firewall configurations and rules.
- Maintain an inventory of critical network devices and services.
- Identify vulnerabilities and assess their potential business impact.
- Review access privileges and security configurations regularly.

These measures can help the company discover security weaknesses before attackers exploit them.

## 3. Protect

**Objective:** Implement safeguards to reduce cybersecurity risks.

The company introduced several protective controls to reduce the likelihood and impact of similar attacks.

Recommended security measures:
- Configure firewall rules to limit excessive incoming ICMP traffic.
- Validate source IP addresses to help identify spoofed traffic.
- Deploy IDS/IPS controls to detect and filter suspicious packets.
- Apply secure configuration standards to network devices.
- Train network administrators on firewall security and incident prevention.
- Maintain secure backups of critical network configurations.

These safeguards help protect network resources and improve the organization's resistance to attacks.

## 4. Detect

**Objective:** Identify suspicious activity and potential security incidents quickly.

The ICMP flood overwhelmed network resources and disrupted normal network communication.

Recommended improvements:
- Deploy network monitoring software.
- Monitor unusual increases in ICMP traffic.
- Configure alerts for abnormal traffic volumes and network performance.
- Review firewall and network device logs.
- Use IDS/IPS alerts to identify suspicious traffic patterns.
- Regularly test detection rules to ensure they identify relevant threats.

Early detection can help the security team recognize attacks sooner and reduce service disruption.

## 5. Respond

**Objective:** Contain the incident, investigate its cause, and limit its impact.

During the incident, the response team blocked incoming ICMP packets, temporarily stopped non-critical services, and restored critical network services.

Recommended improvements:
- Establish a formal incident-response plan.
- Define responsibilities for the incident management team.
- Apply appropriate traffic-filtering and rate-limiting controls.
- Analyze firewall logs and other relevant evidence.
- Document the incident timeline, affected services, and response actions.
- Communicate incident updates to relevant stakeholders.
- Conduct a post-incident review to identify lessons learned.

These actions can improve coordination and reduce the impact of future incidents.

## 6. Recover

**Objective:** Restore affected systems and return operations to normal.

The company restored critical network services after containing the attack. A structured recovery process can help ensure that services are restored safely and reliably.

Recommended improvements:
- Verify that critical network services are functioning correctly.
- Confirm that employees can access required network resources.
- Monitor the network for continuing malicious activity.
- Restore secure configurations where necessary.
- Maintain backups of critical configurations and recovery procedures.
- Test recovery plans regularly.
- Document recovery outcomes and update security procedures.

These measures can reduce downtime and strengthen business continuity.

## 7. Lessons Learned

This incident demonstrates how a firewall misconfiguration can expose an organization to a network-level attack.

Key lessons:
- Firewall configurations should be reviewed regularly.
- Network monitoring is important for identifying abnormal traffic.
- Layered security controls can help reduce the impact of DoS attacks.
- Incident-response procedures should clearly define roles and actions.
- Recovery planning helps organizations restore services efficiently.
- Post-incident reviews help identify weaknesses and prevent recurrence.

## Conclusion

Applying the NIST Cybersecurity Framework provides a structured approach to improving network security before, during, and after a security incident.

By identifying vulnerabilities, implementing protective controls, improving detection, strengthening incident response, and preparing for recovery, the company can reduce its exposure to similar attacks and improve network resilience.

This project strengthened my understanding of how the NIST CSF can be applied to a simulated cybersecurity incident and how security controls support incident prevention, response, and recovery.

## Disclaimer

This is an educational portfolio project based on a simulated incident scenario. It does not represent an independently conducted investigation of a real-world attack.
