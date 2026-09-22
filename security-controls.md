# Security Controls and Control Mapping

## Purpose

This document maps identified security risks to practical security controls.

The objective is to show how Mwangaza Research can reduce information security, data protection, and AI-related risks through preventive, detective, and corrective controls.

---

## Control Mapping

| Control ID | Security Risk                                               | Control                          | Control Type           | Purpose                                                        |
| ---------- | ----------------------------------------------------------- | -------------------------------- | ---------------------- | -------------------------------------------------------------- |
| C001       | Sensitive information submitted to unapproved AI tools      | AI Acceptable Use Policy         | Preventive             | Define what employees can and cannot submit to AI tools        |
| C002       | Sensitive information submitted to unapproved AI tools      | Approved AI Tool List            | Preventive             | Identify AI tools approved for organizational use              |
| C003       | Employee account compromised through phishing               | Multi-Factor Authentication      | Preventive             | Reduce the risk of unauthorized account access                 |
| C004       | Employee account compromised through phishing               | Security Awareness Training      | Preventive             | Help employees identify and report security threats            |
| C005       | Former employee retains access                              | Joiner, Mover and Leaver Process | Preventive             | Remove or change access when employment status changes         |
| C006       | Excessive permissions expose sensitive information          | Access Reviews                   | Detective / Preventive | Identify and remove unnecessary access                         |
| C007       | Sensitive data exposed or accessed improperly               | Data Classification              | Preventive             | Identify information requiring additional protection           |
| C008       | Third-party vendor mishandles information                   | Vendor Security Assessment       | Preventive             | Assess security and data protection risks before using vendors |
| C009       | Security incident is not detected or escalated quickly      | Incident Response Procedure      | Corrective             | Provide a consistent process for responding to incidents       |
| C010       | Source code exposed through compromised developer account   | Repository Access Controls       | Preventive             | Limit access to source code and development resources          |
| C011       | Sensitive information stored without appropriate protection | Encryption                       | Preventive             | Protect information from unauthorized access                   |
| C012       | Security events are not identified                          | Security Monitoring and Logging  | Detective              | Support detection and investigation of suspicious activity     |

---

## Priority Controls

Based on the risk assessment, the following controls receive particular attention:

### 1. AI Acceptable Use

Employees need clear guidance about what information can and cannot be submitted to AI tools.

### 2. Data Classification

Employees should understand whether information is public, internal, confidential, or sensitive before sharing it with external services.

### 3. Access Control

Users should only have the access required to perform their responsibilities.

### 4. Multi-Factor Authentication

MFA provides an additional layer of protection if an employee password is compromised.

### 5. Security Awareness

Employees need practical guidance on phishing, data protection, AI risks, and incident reporting.

### 6. Incident Response

The organization needs a defined process for detecting, assessing, containing, investigating, and recovering from security incidents.

---

## Preventive, Detective and Corrective Controls

### Preventive Controls

Designed to reduce the likelihood of an incident.

Examples:

* MFA
* Access controls
* AI acceptable-use policy
* Data classification
* Security awareness
* Vendor assessments

### Detective Controls

Designed to identify suspicious activity or security incidents.

Examples:

* Security monitoring
* Logging
* Access reviews
* Incident reporting

### Corrective Controls

Designed to respond to and recover from incidents.

Examples:

* Incident response procedures
* Remediation
* Recovery activities
* Lessons learned

---

## Control Approach

The control strategy follows a risk-based approach.

Higher-risk situations should receive stronger controls and greater monitoring.

For example, allowing an employee to use an approved AI tool for general writing presents a different risk from allowing the same employee to upload research participant information to an external AI service.

The control should therefore consider both:

**The technology being used + the sensitivity of the information being processed.**

---

## Expected Outcome

By connecting risks to specific controls, Mwangaza Research can move from simply identifying security problems to managing and reducing those risks.

This also provides a foundation for future security reviews, internal audits, employee awareness activities, and continuous improvement.