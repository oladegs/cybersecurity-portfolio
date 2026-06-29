# Web Application XSS, CSRF & File Inclusion Testing

## Project Overview

This project focused on testing common web application vulnerabilities in a controlled **DVWA** environment, including:

- Stored Cross-Site Scripting
- Cross-Site Request Forgery
- File Inclusion

The goal was to understand how insecure input handling, weak request validation, and unsafe file access can expose web applications to client-side attacks, unauthorized actions, and sensitive file exposure.

This project demonstrates practical web application security testing, vulnerability analysis, and remediation awareness.

## Why This Project Matters

Many real-world security incidents start with web application weaknesses. Vulnerabilities such as XSS, CSRF, and file inclusion can allow attackers to steal session data, perform unauthorized actions, manipulate users, or access files that should not be exposed.

This project connects directly to cybersecurity analyst responsibilities because it involves:

- Identifying application-layer vulnerabilities
- Understanding attack behaviour
- Analyzing risk and business impact
- Documenting findings
- Recommending mitigation controls
- Supporting secure application practices

## Tools & Technologies

- DVWA
- XAMPP
- Web browser
- Local security lab environment
- HTTP request analysis concepts
- Web application testing methodology
- Input validation testing

## Key Security Concepts Covered

- Stored Cross-Site Scripting
- JavaScript injection
- Session cookie exposure
- Cross-Site Request Forgery
- Unauthorized password change risk
- File inclusion
- URL parameter manipulation
- Input validation
- Output encoding
- Secure request validation
- Web application hardening

## Project Scope

The project focused on testing application behaviour in a controlled vulnerable environment. The goal was not only to trigger vulnerabilities, but also to understand the risk behind each issue and how it can be prevented.

The project covered:

- Stored XSS testing
- CSRF request behaviour analysis
- File inclusion testing
- Application response observation
- Vulnerability risk analysis
- Recommended remediation steps

## What I Worked On

- Tested Stored XSS by submitting script-based payloads through a vulnerable guestbook form.
- Observed how untrusted user input can execute in a browser when output is not properly encoded.
- Tested CSRF behaviour by analyzing password-change request parameters.
- Evaluated how authenticated users can be forced into unintended actions without proper request protection.
- Tested file inclusion by modifying URL parameters to load unintended files.
- Documented security risks and recommended defensive controls.

## Stored Cross-Site Scripting Testing

Stored XSS occurs when malicious input is saved by an application and later displayed to users without proper encoding or sanitization.

### Testing Focus

The test focused on submitting script payloads through an input field and observing whether the application stored and executed the script when the page was viewed.

### Security Risk

Stored XSS can be dangerous because the payload remains inside the application. Any user who views the affected page may unknowingly execute the attacker’s script in their browser.

Possible impact includes:

- Session theft
- Credential exposure
- User impersonation
- Browser-based attacks
- Malicious redirects
- Defacement
- Sensitive data exposure

### Recommended Mitigations

- Validate user input
- Encode output before rendering it in the browser
- Use Content Security Policy
- Sanitize HTML where user-generated content is allowed
- Avoid directly rendering untrusted input
- Use secure frameworks that automatically escape output
- Monitor application logs for suspicious script input

## Cross-Site Request Forgery Testing

CSRF occurs when an attacker tricks an authenticated user into submitting an unwanted request to a web application where the user is already logged in.

### Testing Focus

The test analyzed how a password-change request could be triggered through URL parameters without strong request validation.

### Security Risk

If a web application does not properly validate sensitive requests, attackers may force authenticated users to perform actions they did not intend to perform.

Possible impact includes:

- Unauthorized password changes
- Account setting changes
- Transaction manipulation
- User account compromise
- Unauthorized administrative actions

### Recommended Mitigations

- Use anti-CSRF tokens
- Validate request origin and referrer headers
- Require re-authentication for sensitive actions
- Use SameSite cookie protections
- Avoid state-changing actions through GET requests
- Implement proper session management
- Log and monitor unusual account change activity

## File Inclusion Testing

File inclusion vulnerabilities occur when an application allows user-controlled input to determine which file is loaded or displayed.

### Testing Focus

The test involved modifying URL parameters to request different files and observe how the application handled the request.

### Security Risk

Improper file inclusion controls can allow attackers to access sensitive files, execute unauthorized scripts, or gather information about the application and server environment.

Possible impact includes:

- Sensitive file disclosure
- Source code exposure
- Server configuration exposure
- Remote code execution in severe cases
- Reconnaissance for further attacks

### Recommended Mitigations

- Avoid passing raw user input into file paths
- Use allowlisted file names
- Restrict file access to approved directories
- Disable remote file inclusion where not required
- Apply least privilege to web server accounts
- Validate and normalize file paths
- Monitor logs for suspicious file access patterns

## Security Analyst Relevance

This project aligns with cybersecurity analyst responsibilities because it demonstrates the ability to:

- Analyze application-layer vulnerabilities
- Understand client-side and server-side attack behaviour
- Identify insecure request handling
- Explain security risk clearly
- Recommend remediation steps
- Support vulnerability assessment and incident response
- Document technical findings professionally

## Job-Relevant Skills Demonstrated

- Web application security testing
- Vulnerability assessment
- XSS analysis
- CSRF analysis
- File inclusion testing
- HTTP request analysis
- Input validation review
- Secure coding awareness
- Risk identification
- Technical reporting
- Security remediation planning

## Example Resume Bullet Points

- Performed vulnerability testing for Stored Cross-Site Scripting by injecting script-based payloads and validating how untrusted input can execute in a user browser.

- Assessed Cross-Site Request Forgery risk by analyzing password-change request behaviour and identifying how authenticated sessions can be abused without proper request validation.

- Tested file inclusion vulnerabilities by manipulating URL parameters to evaluate insecure file handling, unauthorized resource access, and potential exposure of sensitive application files.

## What I Learned

This project strengthened my understanding of how web application vulnerabilities occur when applications fail to validate input, encode output, protect sessions, or restrict file access. It also improved my ability to explain technical vulnerabilities in a way that connects to real business and security risk.

## Disclaimer

This project was completed in a controlled DVWA lab environment for educational and defensive cybersecurity learning only. No unauthorized systems were accessed, tested, or targeted.
