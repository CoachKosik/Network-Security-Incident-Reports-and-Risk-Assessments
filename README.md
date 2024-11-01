# Network Security Incident Reports and Risk Assessments <br> - Cybersecurity Incident Reports and Risk Assessment

## Objective

To analyze a real-world cybersecurity incident, specifically a Distributed Denial of Service (DDoS) attack, and apply the NIST Cybersecurity Framework to identify vulnerabilities, implement protective measures, and improve incident response capabilities. This project aims to enhance network security and minimize the impact of future cyber threats.

### Skills Learned

* **Incident Response:** Analyzing a security incident, identifying root causes, and implementing mitigation strategies.
* **Network Security:** Understanding network protocols, firewall configuration, and network monitoring tools.
* **Security Analysis:** Analyzing network logs and system logs to identify security threats.
* **Problem-Solving:** Identifying and resolving security issues through a systematic approach.
* **Technical Writing:** Clearly communicating technical information in written reports and documentation.
* **Critical Thinking:** Evaluating information and making informed decisions.
* **Attention to Detail:** Ensuring accuracy and thoroughness in analysis and reporting.
* **NIST Cybersecurity Framework:** Applying the NIST CSF to improve organizational security posture.

### Tools Used
**Cybersecurity Frameworks and Standards:**

* **NIST Cybersecurity Framework (CSF):** Used to guide the organization's cybersecurity efforts, including identify, protect, detect, respond, and recover functions.
* **PCI DSS:** A set of security standards for organizations that handle credit card information.
* **GDPR:** A European Union regulation on data protection and privacy.


## Steps
**Incident Analysis:**

1. **Incident Identification:** The initial step involved recognizing the symptoms of a DDoS attack, such as a sudden loss of network connectivity and increased network traffic.
2. **Data Collection:** Relevant data, such as network logs, firewall logs, and system logs, were collected to analyze the attack's nature and impact.
3. **Root Cause Analysis:** The cybersecurity team investigated the root cause, which was identified as a misconfiguration in the firewall that allowed a flood of ICMP packets to overwhelm the network.
4. **Impact Assessment:** The extent of the impact was assessed, including the duration of the outage, affected systems, and potential data loss.

**Security Improvements:**
1. **Firewall Configuration:** Implemented a new firewall rule to limit the rate of incoming ICMP packets, preventing future floods.
2. **Source IP Address Verification:** Configured the firewall to verify the source IP address of incoming packets to mitigate spoofing attacks.
3. **Network Monitoring:** Deployed network monitoring tools to detect anomalies and unusual traffic patterns, enabling early detection of future attacks.
4. **Intrusion Detection and Prevention Systems (IDS/IPS):** Implemented an IDS/IPS system to filter out malicious traffic and prevent future attacks.
5. **Incident Response Plan:** Reviewed and updated the incident response plan to address lessons learned from the attack.
6. **Employee Training:** Conducted security awareness training for employees to educate them about the risks of DDoS attacks and best practices for cybersecurity.

## Materials Provided
<a href="https://docs.google.com/document/d/1kT9r2HSVHP9oEHAQAGIQNDzLNZ__1MYEU9HwcmatYh4/edit?usp=sharing">Incident report analysis</a><br>
<a href="https://docs.google.com/document/d/1UXGnTPeBAFwRkiN7dQvqhWTEwj84_8vz/edit?usp=sharing&ouid=105064495821226407439&rtpof=true&sd=true">Applying the NIST CSF</a>
