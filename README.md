# Implementing Tenable Nessus and Remediation through Microsoft Intune
As a Cyber Security Specialist, my primary responsibility is to manage and monitor endpoint security. I have developed a document outlining the standard technical procedure I would take for scanning an organization's network for vulnerabilities, and the subsequent steps for remediating user endpoints.

The majority of our organization's devices were managed through Microsoft 365. Given the large number of endpoints, the most efficient remediation was achieved via Microsoft Intune for mass deployment. For non-Windows devices or those not linked to Microsoft Azure Active Directory, different but similar remediation steps were used.

Although this documentation primarily details the technical steps taken with these tools, it also encompasses discussions and planning with organizations to recommend acceptable device use policies. Also note, the devices within the organizations I worked with primarily were managed by Azure Active Directories, so  other security tools (e.g., SentinelOne, ThreatLocker, DNS Filtering) to meet compliance standards.

![](images/Tenable_Nessus_Banner.png)

<h2>High Level Tenable Overview:</h2>

<b>Tenable Nessus is a vulnerability management tool designed to scan endpoints and ensure their security. The typical vulnerabilities found on these endpoints include</b>
<br />

- Unpatched/EOL Software and Applications
- Weak Passwords
- Open Ports
- Misconfigured/Unncessary Services
- Weak Encrpytion
- Misconfigured Devices



