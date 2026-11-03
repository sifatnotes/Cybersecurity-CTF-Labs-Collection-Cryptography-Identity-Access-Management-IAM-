# Cybersecurity-CTF-Labs-Collection-Cryptography-Identity-Access-Management-IAM-
A curated, searchable index of hands-on CTF labs covering classical/modern cryptography, XOR ciphers, hashing, OAuth flows, session hardening, MFA implementation, broken authentication, and access control from Learn SecByte.
# Cryptography, Identity & Access Management (IAM) CTF Labs Collection

A structured, searchable index of hands-on cybersecurity labs focusing on Applied Cryptography & Encoding (XOR encryption, cryptographic hashing primitives, classical ciphers, data encoding formats) and Identity & Access Management (IAM lifecycle management, session hardening, broken authentication triage, access control vulnerabilities, MFA resistance, OAuth token/redirect security, and bash session handling) hosted on Learn SecByte.

This collection is designed for application security engineers, web developers, IAM architects, security analysts, and penetration testers seeking practical experience in data protection, identity workflows, and authentication security.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
  - [Applied Cryptography, Encoding & Primitives](#applied-cryptography-encoding--primitives)
  - [Identity Lifecycle & Access Control Engineering](#identity-lifecycle--access-control-engineering)
  - [Authentication, Session Hardening & OAuth Flows](#authentication-session-hardening--oauth-flows)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Flawless application security depends on strong cryptographic primitives and robust identity management. Cryptographic weaknesses—such as key reuse in XOR ciphers, weak hashing algorithms, or encoding confusion—expose data to unauthorized interception and tampering. Simultaneously, flaws in identity management, session handling, access control, and OAuth flows remain leading vectors for account takeovers and privilege escalation.

This repository organizes hands-on cryptography and IAM labs from Learn SecByte into structured learning paths covering data encryption, session integrity, and identity governance.

---

## Lab Collection & Index

| Lab Title | Domain Focus | Primary Category | Access Link |
| :--- | :--- | :--- | :--- |
| **XOR Under Pressure** | Cryptography | XOR Mechanics, Key Reuse & Analysis | [Access Lab](https://learn.secbyte.org/ctf/xor-under-pressure) |
| **Hashing Fundamentals** | Cryptography | Digests, Salting & Defensive Hashing | [Access Lab](https://learn.secbyte.org/ctf/hashing-fundamentals-from-digests-to-defenses) |
| **Modern Cryptography** | Cryptography | Primitives, Symmetric/Asymmetric Protocols | [Access Lab](https://learn.secbyte.org/ctf/modern-cryptography-from-primitives-to-protocols) |
| **Classical Cryptography** | Cryptography | Ciphers, Historical Codes & Deception | [Access Lab](https://learn.secbyte.org/ctf/classical-cryptography-ciphers-codes-and-deception) |
| **Encoding Fundamentals** | Data Security | Encoding Formats & Cipherdesk Incident | [Access Lab](https://learn.secbyte.org/ctf/encoding-fundamentals-the-cipherdesk-incident) |
| **Identity Management (JML)** | IAM / Governance | Joiner, Mover, Leaver Lifecycles | [Access Lab](https://learn.secbyte.org/ctf/identity-management-joiner-mover-leaver) |
| **Cookie Security** | Web / Session | Session Integrity & Cookie Hardening | [Access Lab](https://learn.secbyte.org/ctf/cookie-security-session-integrity-hardening) |
| **Broken Authentication** | AppSec / Identity | Token Triage, Hijacking & Session Abuse | [Access Lab](https://learn.secbyte.org/ctf/broken-authentication-token-triage-session-abuse) |
| **Broken Gates** | AppSec / AuthZ | Access Control Bypass & IDOR Lab | [Access Lab](https://learn.secbyte.org/ctf/broken-gates-access-control-lab) |
| **Multi-Factor Authentication** | IAM / Auth | Basics to Bypass-Resistant MFA | [Access Lab](https://learn.secbyte.org/ctf/multi-factor-authentication-from-basics-to-bypass-resistant-) |
| **OAuth Basics** | IAM / API | Tokens, Redirects & Consent Flows | [Access Lab](https://learn.secbyte.org/ctf/oauth-basics-tokens-redirects-consent-flows) |
| **Session Management Bash** | CLI / Linux | Terminal Session Management & Hardening | [Access Lab](https://learn.secbyte.org/ctf/session-management-bash) |

---

## Categories

### Applied Cryptography, Encoding & Primitives
Hands-on CTF labs detailing data representation, bitwise operations, cryptographic hash functions, symmetric/asymmetric ciphers, and cryptanalysis:

* **Encoding Fundamentals:** Distinguishing between encoding (Base64, Hex, URL), encryption, and hashing to resolve data leakage incidents.
  * Lab Link: https://learn.secbyte.org/ctf/encoding-fundamentals-the-cipherdesk-incident
* **Classical Cryptography:** Analyzing historical substitution/transposition ciphers, frequency analysis, and codebreaking concepts.
  * Lab Link: https://learn.secbyte.org/ctf/classical-cryptography-ciphers-codes-and-deception
* **XOR Under Pressure:** Exploiting single-byte XOR key reuse, multi-byte key analysis, and bitwise manipulation.
  * Lab Link: https://learn.secbyte.org/ctf/xor-under-pressure
* **Hashing Fundamentals:** Implementing SHA-256/SHA-3 digests, password salting (`bcrypt`, `Argon2`), and defending against length extension attacks.
  * Lab Link: https://learn.secbyte.org/ctf/hashing-fundamentals-from-digests-to-defenses
* **Modern Cryptography:** Combining symmetric ciphers (AES-GCM), asymmetric key exchange (RSA, Diffie-Hellman), and TLS protocol primitives.
  * Lab Link: https://learn.secbyte.org/ctf/modern-cryptography-from-primitives-to-protocols

### Identity Lifecycle & Access Control Engineering
Practical security labs focused on enterprise identity governance, provisioning workflows, role access boundaries, and authorization bugs:

* **Identity Management (Joiner, Mover, Leaver):** Securing identity lifecycle events, enforcing least privilege during internal role transitions, and preventing orphaned accounts during offboarding.
  * Lab Link: https://learn.secbyte.org/ctf/identity-management-joiner-mover-leaver
* **Broken Gates (Access Control Lab):** Identifying and remediating Insecure Direct Object References (IDOR), path traversal authorization bypasses, and privilege escalation vectors.
  * Lab Link: https://learn.secbyte.org/ctf/broken-gates-access-control-lab

### Authentication, Session Hardening & OAuth Flows
Security engineering labs detailing web session security, OAuth 2.0 / OpenID Connect vulnerabilities, MFA enforcement, and shell session management:

* **Cookie Security & Session Hardening:** Enforcing `HttpOnly`, `Secure`, `SameSite` flags, token signing, and session fixation defenses.
  * Lab Link: https://learn.secbyte.org/ctf/cookie-security-session-integrity-hardening
* **Broken Authentication & Session Abuse:** Triaging JWT vulnerabilities (none-alg, weak keys), session hijacking, brute-force attacks, and credential stuffing vectors.
  * Lab Link: https://learn.secbyte.org/ctf/broken-authentication-token-triage-session-abuse
* **Multi-Factor Authentication (MFA):** Implementing TOTP/FIDO2 webauthn protocols and hardening MFA against push fatigue, SIM swapping, and proxy bypasses.
  * Lab Link: https://learn.secbyte.org/ctf/multi-factor-authentication-from-basics-to-bypass-resistant-
* **OAuth Basics (Tokens, Redirects, Consent):** Auditing authorization code flows, implicit grants, state parameter validation, and open redirect exploitation in OAuth implementations.
  * Lab Link: https://learn.secbyte.org/ctf/oauth-basics-tokens-redirects-consent-flows
* **Session Management Bash:** Hardening CLI environments, managing environment variables, preventing session leaks, and auditing TTY shell access.
  * Lab Link: https://learn.secbyte.org/ctf/session-management-bash

---

## Learning Path

Follow this structured roadmap to master applied cryptography and identity access management:

1. **Encoding, Hashing & Cryptographic Primitives**
   - Differentiate data formats in Encoding Fundamentals.
   - Master XOR mechanics and implement secure hashing with Hashing Fundamentals and Modern Cryptography.
2. **Identity Lifecycle & Access Control**
   - Configure enterprise JML workflows with Identity Management (Joiner, Mover, Leaver).
   - Audit web applications for authorization flaws in Broken Gates (Access Control).
3. **Session Management & Cookie Hardening**
   - Secure web tokens and browser storage using Cookie Security and Session Management Bash.
   - Investigate session abuse and token tampering in Broken Authentication.
4. **OAuth 2.0 & Bypass-Resistant MFA**
   - Secure external identity providers using OAuth Basics (Tokens & Redirects).
   - Implement FIDO2/WebAuthn standards via Multi-Factor Authentication.

---

## How to Use the Labs

1. Select a practice scenario from the index table or category breakdown above.
2. Launch the target lab environment directly on Learn SecByte using the provided access link.
3. Complete hands-on tasks using security tools (CyberChef, Burp Suite, Postman, Python cryptography modules, JWT debuggers, and IAM administrative consoles).
4. Review post-lab code remediations, OAuth configuration standards, and identity hardening frameworks to secure enterprise infrastructure.

---

## Disclaimer

This repository is strictly intended for educational research, authorized identity auditing, and defensive security engineering. All concepts, tools, and lab environments are provided to help cybersecurity practitioners build practical expertise and defend enterprise application stacks. Unsanctioned testing, unauthorized access attempts, or attacks against external identity infrastructure are strictly illegal.
