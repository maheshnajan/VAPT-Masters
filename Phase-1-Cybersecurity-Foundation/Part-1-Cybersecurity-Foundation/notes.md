# Phase 1 - Cybersecurity Fundamentals & VAPT Introduction

---

# What is Cybersecurity?

## Definition

Cybersecurity is the practice of protecting **computer systems, networks, applications, cloud environments, data, and users** from unauthorized access, cyber attacks, misuse, theft, and damage.

**Simple Definition**

> Cybersecurity is the practice of protecting digital assets from cyber threats.

---

## Cybersecurity Components

```text
                Cybersecurity

        Computer Systems
               ↓
            Networks
               ↓
          Applications
               ↓
             Cloud
               ↓
              Data
               ↓
             Users
```

---

## Protects Against

- Unauthorized Access
- Cyber Attacks
- Malware
- Data Theft
- Misuse
- Damage

---

## Goals of Cybersecurity (CIA Triad)

### 1. Confidentiality (C)

Only authorized users can access information.

### 2. Integrity (I)

Ensure data remains accurate and cannot be modified without authorization.

### 3. Availability (A)

Ensure systems and data are available whenever required.

---

## Interview Definition

> Cybersecurity is the practice of protecting computer systems, networks, applications, cloud infrastructure, data, and users from unauthorized access, cyber attacks, misuse, theft, and damage.

---

# Threat

## Definition

A Threat is anything that has the potential to exploit a vulnerability and cause harm.

**Simple Definition**

> A threat is anything that can harm your system.

---

## Examples

- Malware
- Hackers
- Insider Threats
- Fire
- Flood
- Phishing
- Power Failure

---

## Flow

```text
Threat
   ↓
Exploits
   ↓
Vulnerability
   ↓
Causes
   ↓
Damage
```

---

## Interview Definition

> A threat is any person, event, or circumstance capable of causing harm to an organization's assets.

---

# Vulnerability

## Definition

A Vulnerability is a weakness or flaw that can be exploited by a threat.

**Simple Definition**

> A vulnerability is a weakness in a system.

---

## Examples

- Weak Password
- Outdated Software
- SQL Injection
- Open Ports
- Misconfiguration
- Excessive Permissions

---

## Flow

```text
Vulnerability
      ↓
Weakness
      ↓
Exploited By
      ↓
Threat
```

---

## Interview Definition

> A vulnerability is a weakness in a system, network, application, or process that can be exploited by a threat.

---

# Risk

## Definition

Risk is the possibility that a threat will exploit a vulnerability and cause damage.

**Simple Definition**

> Risk is the chance of loss or damage.

---

## Formula

```text
Threat
   +
Vulnerability
   =
Risk
```

---

## Example

```text
Weak Password
      +
Attacker
      =
Account Compromise
```

---

## Interview Definition

> Risk is the likelihood that a threat will exploit a vulnerability and cause harm.

---

# Asset

## Definition

An Asset is anything valuable that needs protection.

**Simple Definition**

> Anything valuable.

---

## Examples

- Server
- Database
- Laptop
- Website
- Employees
- Cloud
- Data
- Email System

---

## Interview Definition

> An asset is any valuable resource that must be protected.

---

# Exploit

## Definition

An Exploit is code or a technique used to take advantage of a vulnerability.

**Simple Definition**

> An exploit is the method used to exploit a vulnerability.

---

## Examples

- SQL Injection Exploit
- XSS Exploit
- RCE Exploit
- Buffer Overflow Exploit
- Directory Traversal Exploit

---

## Interview Definition

> An exploit is code or a technique that leverages a vulnerability to compromise a system.

---

# Payload

## Definition

A Payload is the malicious code executed after successful exploitation.

**Simple Definition**

> The actual malicious code executed after exploitation.

---

## Examples

- Reverse Shell
- Ransomware
- Keylogger
- Data Stealer
- RAT

---

## Interview Definition

> A payload is the malicious code delivered after an exploit successfully compromises a target.

---

# Security Controls

## Definition

Security Controls are safeguards implemented to protect assets and reduce security risks.

---

# Types of Security Controls

## 1. Administrative Controls

Examples

- Policies
- Procedures
- Awareness
- Security Training
- Password Policy
- Incident Response Plan

---

## 2. Physical Controls

Examples

- Locks
- CCTV
- Biometrics
- Security Guards
- ID Cards

---

## 3. Technical Controls

Examples

- Firewall
- IDS
- IPS
- Antivirus
- MFA
- Encryption
- VPN
- WAF
- SIEM

---

## Security Controls Diagram

```text
Security Controls

├── Administrative
│     ├── Policies
│     ├── Procedures
│     ├── Training
│     └── Awareness
│
├── Physical
│     ├── Locks
│     ├── CCTV
│     ├── Biometrics
│     └── Security Guards
│
└── Technical
      ├── Firewall
      ├── IDS
      ├── IPS
      ├── Antivirus
      ├── MFA
      ├── Encryption
      ├── VPN
      ├── WAF
      └── SIEM
```

---

# Types of Hackers

## White Hat

- Authorized
- Ethical
- Improves security
- Performs Penetration Testing

---

## Gray Hat

- Unauthorized
- Usually not malicious
- Reports vulnerabilities after discovery

---

## Black Hat

- Unauthorized
- Malicious
- Data Theft
- Financial Gain
- Ransomware

---

## Script Kiddie

- Uses existing tools
- Limited knowledge
- Relies on public exploits

---

## Hacktivist

- Political or Social Motivation
- Website Defacement
- Data Leaks

---

## Nation-State

- Government Sponsored
- Cyber Espionage
- Cyber Warfare
- Intelligence Gathering

---

## Insider

- Employee or Trusted User
- Intentional or Accidental Threat

---

## Hacker Comparison

| Type | Permission | Intent |
|-------|------------|--------|
| White Hat | Authorized | Ethical |
| Gray Hat | Unauthorized | Usually Non-Malicious |
| Black Hat | Unauthorized | Malicious |
| Script Kiddie | Unauthorized | Limited Knowledge |
| Hacktivist | Unauthorized | Political/Social |
| Nation-State | Government Sponsored | Cyber Warfare |
| Insider | Legitimate Access | Malicious or Accidental |

---

# What is VAPT?

## Definition

VAPT (Vulnerability Assessment and Penetration Testing) is the process of identifying, validating, and helping remediate security vulnerabilities.

**Simple Definition**

> Find vulnerabilities and verify whether they can be exploited.

---

## Objectives

- Identify vulnerabilities
- Assess severity
- Validate exploitability
- Reduce risk
- Recommend remediation

---

## Interview Definition

> VAPT is a security assessment process that combines Vulnerability Assessment and Penetration Testing to identify, validate, and remediate security weaknesses.

---

# Vulnerability Assessment vs Penetration Testing

| Vulnerability Assessment | Penetration Testing |
|---------------------------|---------------------|
| Finds vulnerabilities | Exploits vulnerabilities |
| Mostly Automated | Manual + Automated |
| No Exploitation | Exploitation Performed |
| Produces Vulnerability List | Demonstrates Business Impact |

---

# VAPT Lifecycle

```text
Planning & Scope
        ↓
Reconnaissance
        ↓
Scanning & Enumeration
        ↓
Vulnerability Assessment
        ↓
Exploitation
        ↓
Post Exploitation
        ↓
Reporting
        ↓
Remediation
        ↓
Re-Testing
```

---

## Lifecycle Phases

1. Planning & Scope
2. Information Gathering
3. Scanning
4. Vulnerability Assessment
5. Exploitation
6. Post Exploitation
7. Reporting
8. Remediation
9. Re-Testing

---

# Types of Penetration Testing

## Black Box

- No prior knowledge
- Simulates external attacker

---

## White Box

- Complete knowledge
- Source Code
- Credentials
- Network Architecture

---

## Gray Box

- Partial knowledge
- Simulates authenticated user

---

## Comparison

| Type | Knowledge |
|------|-----------|
| Black Box | None |
| White Box | Complete |
| Gray Box | Partial |

---

# VAPT Methodologies

## OWASP WSTG

Used for Web Application Security Testing.

---

## PTES

Penetration Testing Execution Standard.

Phases

- Pre-Engagement
- Intelligence Gathering
- Threat Modeling
- Vulnerability Analysis
- Exploitation
- Post Exploitation
- Reporting

---

## NIST SP 800-115

Technical Guide for Security Testing.

---

## OSSTMM

Open Source Security Testing Methodology Manual.

Focus

- Network
- Wireless
- Physical
- Human Security

---

## MITRE ATT&CK

Knowledge base of attacker tactics and techniques used for:

- Threat Hunting
- Detection Engineering
- Purple Teaming
- Incident Response

---

# Complete Security Flow

```text
Asset
   ↓
Threat
   ↓
Vulnerability
   ↓
Risk
   ↓
Vulnerability Assessment
   ↓
Penetration Testing
   ↓
Report
   ↓
Remediation
   ↓
Secure System
```

---

# Quick Revision

```text
Cybersecurity = Protect Digital Assets

Threat = Potential Danger

Vulnerability = Weakness

Risk = Threat + Vulnerability

Asset = Anything Valuable

Exploit = Method to Exploit a Vulnerability

Payload = Malicious Code Executed After Exploitation

Security Controls = Administrative + Physical + Technical

Hackers =
White Hat
Gray Hat
Black Hat
Script Kiddie
Hacktivist
Nation-State
Insider

VAPT = Vulnerability Assessment + Penetration Testing

VA = Find Vulnerabilities

PT = Exploit Vulnerabilities

VAPT Lifecycle

Planning
Recon
Scanning
VA
PT
Post Exploitation
Reporting
Remediation
Re-Testing

Methodologies

OWASP WSTG
PTES
NIST SP 800-115
OSSTMM
MITRE ATT&CK
```
