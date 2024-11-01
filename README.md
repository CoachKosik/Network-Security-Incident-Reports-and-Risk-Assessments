# Network Security Incident Reports and Risk Assessments <br> - Cybersecurity Incident Reports and Risk Assessment

## Objective

These incident report labs are designed to simulate real-world cybersecurity incidents, allowing the practice of critical thinking, problem-solving, and incident response skills.

### Skills Learned

1. **Network Traffic Analysis:**
   * Interpret network traffic logs, identifying protocols like TCP, UDP, HTTP, and ICMP.
   * Recognize patterns in network traffic data, such as SYN floods or unreachable ports, to identify potential security incidents.
   * Utilize tools like tcpdump to capture and analyze network traffic for investigation purposes.

2. **Incident Response Procedures:**
   * Understand the importance of identifying the type of cyberattack impacting a system.
   * Explain the technical details of specific attacks, such as SYN floods and DNS server issues.
   * Differentiate between different network protocols and their roles in security breaches.

3. **Security Best Practices:**
   * Identify security vulnerabilities, such as weak password policies or misconfigured firewalls.
   * Recommend appropriate remediation strategies for identified vulnerabilities.
   * Understand the importance of strong password policies, including password complexity, regular updates, and account lockout mechanisms.

4. **Technical Communication:**
   * Document technical information in a clear and concise manner for both technical and non-technical audiences.
   * Explain complex cybersecurity concepts in an understandable way.
   * Effectively structure incident reports, including sections for problem identification, analysis, and remediation.

5. **Digital Forensics:**
   * Familiar with collecting and preserving digital evidence for security investigations.
   * Analyze network traffic logs and other digital artifacts to identify the root cause of an incident.

### Tools Used
* **Log Analysis:** Examining logs from various sources like web servers, firewalls, and DNS servers can provide valuable insights into network activity and potential security incidents.
* **Source Code Analysis:** Examining the source code of websites and applications can help identify vulnerabilities or malicious code injected by attackers.


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
