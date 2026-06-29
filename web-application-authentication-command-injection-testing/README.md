# Web Application Authentication & Command Injection Testing

## Project Overview

This project focused on testing authentication weaknesses and command injection vulnerabilities in a controlled **DVWA** security lab environment.

The goal was to understand how insecure authentication workflows and poor input validation can expose a web application to brute-force attacks, unauthorized access attempts, and operating system command execution.

This project demonstrates hands-on web application security testing, vulnerability analysis, risk identification, and remediation awareness.

## Why This Project Matters

Authentication and input validation are two major areas cybersecurity analysts must understand. Weak login controls can allow attackers to guess credentials, while command injection can allow attackers to execute system-level commands through a vulnerable web application.

This project connects directly to security analyst and SOC responsibilities because it involves:

- Identifying suspicious authentication behaviour
- Understanding brute-force attack patterns
- Testing input validation weaknesses
- Recognizing command injection risk
- Documenting security findings
- Recommending mitigation controls

## Tools & Technologies

- DVWA
- XAMPP
- Web browser
- Windows environment
- Command-line testing concepts
- Web application testing methodology
- Authentication testing
- Input validation testing

## Key Security Concepts Covered

- Brute-force attacks
- Weak authentication controls
- Account lockout
- CAPTCHA
- Token validation
- Command injection
- Input validation
- Secure coding awareness
- Web application hardening
- Vulnerability remediation

## Project Scope

The testing was performed in a local and controlled vulnerable web application environment. The purpose was to safely analyze common web application weaknesses and understand how different security levels affect attack success.

The project covered:

- Authentication brute-force testing
- Security-level comparison
- Command injection testing
- Observation of application responses
- Security control analysis
- Mitigation recommendations

## What I Worked On

- Tested brute-force login attempts against a vulnerable authentication form.
- Compared application behaviour across different DVWA security levels.
- Analyzed how weak login controls allow repeated password guessing.
- Reviewed how stronger security controls reduce brute-force attack success.
- Tested command injection payloads through vulnerable input fields.
- Documented findings, risks, and recommended defensive controls.

## Technical Summary

The project was divided into two main security testing areas:

1. Authentication security testing
2. Command injection testing

For authentication testing, I assessed how the application responded to repeated login attempts under different security levels. This helped identify how missing or weak protections can allow brute-force attacks.

For command injection testing, I submitted command-style payloads into a vulnerable web input field to understand how improper input handling can allow unauthorized commands to run on the server side.

## Brute-Force Testing

Brute-force testing was performed to understand how repeated username and password attempts can be used against weak authentication systems.

### Key Observations

- Low security allowed repeated login attempts with little to no protection.
- Medium security introduced basic validation and session handling.
- High security added stronger protections such as attempt limits or CAPTCHA.
- Impossible security significantly hardened the authentication workflow.

### Security Risk

If a real application allows unlimited login attempts, an attacker can use automated tools to guess credentials. This can lead to account compromise, unauthorized access, and further attacks inside the system.

### Recommended Mitigations

- Enforce strong password policies
- Add account lockout after repeated failed attempts
- Use CAPTCHA or rate limiting
- Monitor failed login attempts
- Alert on suspicious login activity
- Use multi-factor authentication
- Log authentication events for investigation

## Command Injection Testing

Command injection testing was performed to understand how a vulnerable application can allow user input to be interpreted as operating system commands.

### Key Observations

- The application accepted input that could be combined with system commands.
- Improper input validation created the possibility of unauthorized command execution.
- The vulnerability demonstrated how attackers can interact with the underlying operating system through a web form.

### Security Risk

Command injection is a serious vulnerability because it can allow attackers to execute commands on the server. In a real-world environment, this could lead to data exposure, system compromise, privilege escalation, or full server takeover.

### Recommended Mitigations

- Validate and sanitize all user input
- Avoid directly passing user input into system commands
- Use allowlists instead of blocklists
- Run applications with least privilege
- Disable unnecessary system command execution
- Implement secure coding practices
- Monitor logs for suspicious command patterns

## Security Analyst Relevance

This project aligns with cybersecurity analyst responsibilities because it demonstrates the ability to:

- Identify authentication weaknesses
- Understand brute-force attack behaviour
- Analyze web application vulnerabilities
- Recognize suspicious input patterns
- Document security findings clearly
- Recommend practical remediation steps
- Support vulnerability assessment and incident investigation workflows

## Job-Relevant Skills Demonstrated

- Web application security testing
- Vulnerability assessment
- Authentication security analysis
- Brute-force attack analysis
- Command injection testing
- Input validation review
- Risk analysis
- Technical documentation
- Security control recommendation
- Incident investigation support

## Example Resume Bullet Points

- Conducted web application security testing in a controlled DVWA environment to assess authentication weaknesses, brute-force exposure, and the effectiveness of security controls across different protection levels.

- Analyzed brute-force attack behaviour and documented mitigation controls including strong password enforcement, account lockout, CAPTCHA, token validation, and hardened authentication workflows.

- Tested command injection scenarios by validating how improper input handling can allow unauthorized operating system command execution, supporting secure coding, vulnerability identification, and remediation awareness.

## What I Learned

This project helped me understand how authentication controls and input validation directly affect application security. It also strengthened my ability to analyze vulnerabilities from both an attacker and defender perspective, which is important for security monitoring, vulnerability assessment, and incident response.

## Disclaimer

This project was completed in a controlled DVWA lab environment for educational and defensive cybersecurity learning only. No unauthorized systems were accessed, tested, or targeted.
