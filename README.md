# Capstone Project - Cybersecurity

This repository contains the final capstone project I completed during my executive post-graduation in Ethical Hacking and Cybersecurity from IIT Roorkee, delivered via Intellipaat. The project focuses on key cybersecurity domains such as cloud security, malware analysis, phishing prevention, and zero-day attack prevention, simulating real-world security challenges.

## Project Overview

As the sole information security officer for a company, I was responsible for securing all aspects of the organization, including people, processes, and tools. This project simulated real-world security scenarios where I had to implement cybersecurity measures, investigate threats, and provide security recommendations to mitigate potential risks.

## Key Challenges and Solutions

### 1. Securing Data in the Cloud
- **Challenge**: Protecting sensitive company data stored in the cloud while ensuring compliance with security standards.
- **Solution**: Implemented robust access controls, strong authentication mechanisms, and encrypted data both at rest and in transit. Techniques such as tokenization and format-preserving encryption were used to transform sensitive data for added security. Regular security audits and log monitoring were put in place to detect any unauthorized access.

### 2. Cloud Model Selection
- **Challenge**: Choosing the best cloud deployment model for the company’s needs.
- **Solution**: Opted for a **hybrid cloud model**, leveraging the scalability and flexibility of the public cloud for non-sensitive workloads, while using the private cloud for mission-critical operations that require more control and compliance adherence.

### 3. Data Classification
- **Challenge**: Classifying company data based on sensitivity and regulatory requirements.
- **Solution**: Implemented a data classification policy that categorized data into public, internal use, confidential, and restricted levels. Each category was assigned specific security controls, ensuring that sensitive data received the highest level of protection.

### 4. Digital Forensics Investigation
- **Scenario**: A user attempted to erase data, and the forensic analyst needed to store this data for investigation.
- **Solution**: Allowed the forensic analyst to store data on a secure drive under strict protocols to preserve the integrity of the evidence. The investigation focused on understanding the extent of the data erasure and recovering potential remnants of the erased data.

### 5. Malware Analysis (Base64-Encoded PowerShell Script)
- **Challenge**: Analyze a Base64-encoded PowerShell script that was detected during an investigation.
- **Solution**: Decoded the script using CyberChef, identified the URL it tried to access, and determined that it was attempting to download a malicious file ("HSTHjnhc.exe") into the Common Application Data folder. The analysis also revealed the use of the `ShellExecute` method to run the downloaded file, which further confirmed malicious intent.

## Research and Technical Challenges

### 1. Process Injection and Malware Variants
- **Research**: Studied process injection techniques used by malware like Zeus (Zbot), Mirai, TrickBot, and Emotet to inject malicious code into legitimate processes and evade detection.
- **Technical Challenge**: Identified how different malware variants use techniques like DLL injection, thread hijacking, and process hollowing to maintain persistence and avoid security controls.

### 2. Memory Injection Techniques
- **Explored Methods**: Detailed research into memory injection methods such as DLL injection, code injection, thread hijacking, and process hollowing. These techniques allow attackers to manipulate processes and execute code in stealthy ways, making detection difficult.

### 3. Sysinternals Tools for Binary File Analysis
- **Tools Used**: Process Explorer, Strings, and Autoruns were utilized for static and dynamic analysis of binary files. These tools helped in identifying suspicious processes, extracting useful strings from binaries, and analyzing programs set to auto-run during system startup.

## Scenario-Based Exercises

### 1. Incident Response - Emotet Malware Infection
- **Scenario**: Multiple systems in a company were compromised by the Emotet malware after employees opened phishing emails.
- **Solution**: Developed a structured incident notification plan to inform the customer of the breach, including detailed descriptions of the attack flow and recommended actions such as disconnecting affected systems, enhancing email filtering, and providing employee phishing awareness training.

### 2. Critical Attack Prevention and Response
- **Scenario**: In the event of a critical attack on the company’s infrastructure, I had to devise a strategy to prevent a data breach.
- **Solution**: Initiated a comprehensive risk assessment, developed a tailored incident response plan, implemented continuous network monitoring, and enforced encryption protocols for sensitive data. I also prioritized employee security training and collaboration with external cybersecurity agencies for threat intelligence sharing.

### 3. Phishing Attack Investigation
- **Scenario**: A phishing campaign was targeting employees from a specific domain.
- **Solution**: Collaborated with IT to block the malicious domain, implemented DMARC authentication to prevent email spoofing, and developed a phishing awareness campaign for employees to reduce future risks.

### 4. Red Team Engagement - Zero-Day Attack Prevention
- **Scenario**: The company was preparing to release a new product, and I was tasked with ensuring it was vulnerability-free.
- **Solution**: Performed threat modeling, penetration testing, and code reviews to identify potential vulnerabilities. Collaborated closely with the development team to mitigate any identified risks and ensure the product's security before release.

## Tools Used:
- **IDA Pro**: For reverse engineering and static analysis of malware samples.
- **Ghidra**: An open-source tool used to analyze and disassemble malware binaries.
- **Burp Suite**: To intercept and analyze web traffic during vulnerability research.
- **Metasploit Framework**: For creating and testing malware and exploit payloads.
- **CyberChef**: To decode Base64-encoded scripts and analyze malicious URLs.

## Conclusion
This capstone project provided a comprehensive understanding of real-world cybersecurity challenges. Through hands-on experience in securing cloud data, performing malware analysis, and developing incident response strategies, I gained invaluable knowledge in detecting, mitigating, and preventing cyber threats.

---

### Contact
For any inquiries or further discussion on my project, feel free to reach out via:
- **Email**: marepalli.rakesh@gmail.com
