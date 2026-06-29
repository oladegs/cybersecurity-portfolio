# Security Assessment, Fingerprinting & Nmap Scanning

## Project Overview

This project focused on performing discovery and fingerprinting activities as part of a partial security assessment. The goal was to identify web server details, open ports, service versions, and system indicators that can support vulnerability assessment, security triage, and incident investigation.

The project used both manual and automated techniques, including Telnet, Nmap, and Zenmap.

This project demonstrates foundational security assessment skills used by cybersecurity analysts, SOC teams, vulnerability analysts, and incident response teams.

## Why This Project Matters

Before defenders can protect systems, they need to understand what is exposed. Discovery and fingerprinting help identify visible services, server technologies, open ports, and possible attack surfaces.

Cybersecurity analysts use this type of information to:

- Investigate suspicious activity
- Validate exposed services
- Support vulnerability management
- Prioritize security risks
- Assist with incident response
- Document technical findings
- Understand network and application exposure

## Tools & Technologies

- Telnet
- Nmap
- Zenmap
- Windows environment
- HTTP header analysis
- Port scanning
- Service version detection
- Operating system detection
- Web server fingerprinting

## Key Security Concepts Covered

- Discovery
- Fingerprinting
- HTTP header analysis
- Port scanning
- Service enumeration
- Operating system detection
- Version detection
- Vulnerability scanning fundamentals
- Attack surface identification
- Security assessment reporting

## Project Scope

The project focused on the discovery phase of a security assessment. It included manual fingerprinting using Telnet and automated scanning using Nmap/Zenmap.

The project covered:

- Environment setup
- Telnet client enablement
- Manual HTTP header inspection
- Nmap scanning
- Zenmap scan review
- Service and version detection
- Technical documentation of findings

## What I Worked On

- Enabled and configured Telnet Client on Windows for manual testing.
- Installed and used Nmap with the Zenmap GUI.
- Performed manual fingerprinting by connecting to a web server over port 80.
- Sent HTTP requests to observe response headers and server behaviour.
- Used Nmap/Zenmap to scan a target host for open ports and service details.
- Reviewed scan output to identify service versions and host information.
- Documented results in a structured security assessment format.

## Manual Fingerprinting

Manual fingerprinting was performed using Telnet to connect to a web server over HTTP.

### Testing Focus

The goal was to obtain HTTP response information and observe how the server responds to direct requests.

### Security Value

HTTP response headers can reveal useful information such as:

- Web server type
- Server version
- Framework or platform details
- Technology stack indicators
- Misconfiguration clues

This information can help analysts understand the environment and determine whether known vulnerabilities may apply.

### Security Risk

Overly detailed server headers can expose information that helps attackers perform reconnaissance. If server banners reveal outdated software versions, attackers can search for known vulnerabilities against those versions.

### Recommended Mitigations

- Limit unnecessary server header information
- Remove or reduce version disclosure
- Keep web server software updated
- Review exposed services regularly
- Monitor unexpected connection attempts
- Harden server configuration
- Use vulnerability scanning as part of regular security operations

## Nmap & Zenmap Scanning

Nmap and Zenmap were used to perform active scanning and identify open ports, service versions, and host details.

### Testing Focus

The scan focused on discovering exposed services and gathering technical details useful for security analysis.

### Security Value

Nmap scanning helps analysts identify:

- Open ports
- Running services
- Service versions
- Operating system indicators
- Potential exposure points
- Misconfigured or unnecessary services

### Security Risk

Open ports and exposed services increase the attack surface. If outdated or vulnerable services are exposed, attackers may attempt exploitation, brute-force attacks, or reconnaissance.

### Recommended Mitigations

- Close unnecessary ports
- Restrict access using firewall rules
- Patch exposed services regularly
- Disable unused services
- Monitor network traffic for scanning activity
- Review external attack surface continuously
- Maintain accurate asset inventory

## Security Analyst Relevance

This project aligns strongly with cybersecurity analyst responsibilities because it demonstrates the ability to:

- Perform discovery and fingerprinting
- Analyze HTTP service responses
- Use scanning tools to identify exposed services
- Interpret port and service scan results
- Support vulnerability assessment workflows
- Document findings clearly
- Assist with threat investigation and incident triage

## Job-Relevant Skills Demonstrated

- Security assessment
- Network discovery
- Fingerprinting
- Nmap scanning
- Zenmap analysis
- Port scanning
- Service enumeration
- HTTP header analysis
- Vulnerability assessment support
- Incident investigation support
- Technical reporting
- Risk identification

## Example Resume Bullet Points

- Conducted partial security assessment activities covering discovery, fingerprinting, port scanning, service identification, vulnerability analysis, and technical reporting.

- Used Telnet to manually fingerprint web servers by connecting to HTTP services, collecting response headers, and identifying server details useful for security triage and investigation.

- Used Nmap and Zenmap to perform active scanning, identify open ports, detect service versions, and collect operating system indicators to support incident investigation and threat analysis.

## What I Learned

This project improved my understanding of how discovery and fingerprinting support cybersecurity operations. It helped me understand how analysts identify exposed services, gather technical evidence, and connect scan results to risk, vulnerability management, and incident response.

## Disclaimer

This project was completed for educational and defensive security learning only. Testing was performed in a controlled and authorized environment. No unauthorized systems were accessed, exploited, or targeted.
