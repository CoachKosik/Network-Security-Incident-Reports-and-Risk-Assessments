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
Understanding the Scenario:
1. Read the Prompt: start by carefully reading the provided prompt for each report. This gave context about the security incident, including symptoms, logs, and potentially affected systems.

Analysis and Interpretation:

2. Identify the Problem: Based on the prompt, identify the type of cyberattack that might be causing the issue. This involved analyzing symptoms (like connection timeouts) and log entries (like SYN flood or unreachable DNS server).

3. Explain Technical Concepts: explain the technical details of the identified attack or security issue. For example, in Report 1, the three-way handshake in TCP and how a SYN flood attack disrupts it.

4. Draw Conclusions: By analyzing the provided information, you are able to draw conclusions about the root cause of the incident. For instance, in Report 2, it was concluded that the unreachable DNS server could be due to a DoS attack, misconfiguration, or firewall blocking.

Documentation and Recommendations:

5. Document the Incident: Document the incident details in a clear and concise manner. This included sections like customer reports, investigative steps, network traffic analysis, and source code analysis (in Report 3).

6. Recommend Solutions:  Finally, recommend appropriate security measures to address the identified vulnerabilities. This included suggestions like password policy changes, firewall rule updates, and implementing Multi-Factor Authentication (MFA).

## Materials Provided
<a href="https://docs.google.com/document/d/1cuPXp7aDhehf9KP3VkbXoSyRjsJIHyfaUeS27iXJioc/edit?usp=sharing">Compiled Incident Reports</a><br>
<a href="https://docs.google.com/document/d/1znqlWLvP2PQP02rnBg51xvPj3sJ56RIq/edit?usp=sharing&ouid=105064495821226407439&rtpof=true&sd=true">How to read a Wireshark TCP/HTTP log</a><br>
<a href="https://docs.google.com/document/d/12MxCtwetHOm_a8FEiKKOjjBQPtae-D5K/edit?usp=sharing&ouid=105064495821226407439&rtpof=true&sd=true">How to read the tcpdump traffic log</a>
