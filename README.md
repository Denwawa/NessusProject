# Implementing Tenable Nessus and Remediation through Microsoft Intune
As a Cyber Security Specialist, my primary responsibility is to manage and monitor endpoint security. I have developed a document outlining the standard technical procedure I would take for scanning an organization's network for vulnerabilities, and the subsequent steps for remediating user endpoints.

The majority of our organization's devices were managed through Microsoft 365. Because of this, the most efficient remediation was achieved via Microsoft 365 Services. For non-Windows devices or those not linked to Microsoft Azure Active Directory, different but similar remediation steps were used.

Although this documentation primarily details the technical steps taken with these tools, the project planning/implementation process also encompassed discussions and planning with organizations to recommend acceptable device use policies. Also note, other tools were also implemented (e.g., SentinelOne, ThreatLocker, DNS Filtering, LastPass) to remediate these vulnerabilites and meet compliance standards.

![](images/Tenable_Nessus_Banner.png)

<h2>Vulnerability Assessment </h2>

<b>Tenable Nessus is a vulnerability management tool designed to scan endpoints and ensure their security. The typical vulnerabilities found on these endpoints include</b>
<br />

- Unpatched/EOL Software and Applications
- Weak Passwords
- Open Ports
- Misconfigured/Unncessary Services
- Weak Encrpytion
- Misconfigured Devices

A scan identifies the severity of issues and suggests remediation steps. After remediation, another scan ensures the vulnerabilities are resolved. If similar issues persist, the process is repeated until all issues are addressed.

Once the project is completed, automated scans are conducted at the organization's discretion (e.g., yearly, bi-yearly, monthly). Scan reports are also generated automatically according to the organization's specifications.

# Deploying Nessus Agent
- Obtaining powershell script via Tenable Portal
  - Explain Sensors and how linking to cloud sensors worked
  - Brief note of how a sensors can be deployed on premise as well and the agent can be deployed from on premise server
- modifying script to include elevated permissions
- Pushing the script through Intune
- Performing Credentialed Scan and Exporting results. Scan would be performed after remedation as well
- Configuring Yearly reports and automatic scans

# Investigating Vulnerabilities

## Unpatched/EOL Software and Applications
## Weak Passwords
## Open Ports
## Misconfigured/Unncessary Services
## Weak Encrpytion
## Misconfigured Devices

<h2>High Level Microsoft Intune Overview </h2>




