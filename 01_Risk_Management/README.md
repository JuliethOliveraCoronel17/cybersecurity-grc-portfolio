# Cybersecurity Risk Management – R-001

## Project Overview

This project demonstrates a practical cybersecurity risk assessment for a hypothetical organization that stores customer financial information on a server.

The objective was to identify a cybersecurity risk, assess its likelihood and potential business impact, define an appropriate risk treatment, and evaluate the residual risk after implementing security controls.

> **Note:** This is a hypothetical case study created for learning and portfolio purposes. It does not represent professional experience with a real organization.

---

## Scenario

A company stores customer financial information on a server.

The server is updated and maintained; however, all employees use the same password to access the system, and Multi-Factor Authentication (MFA) is not enabled.

An attacker could obtain the shared password through a phishing attack and gain unauthorized access to the system.

---

## Risk Identification

| Risk Element | Assessment |
|---|---|
| **Asset** | Customer financial information |
| **Threat** | External attacker / phishing |
| **Vulnerability** | Shared passwords and absence of MFA |
| **Impact** | Exposure or loss of customer information, financial, reputational and compliance consequences |
| **Likelihood** | High |
| **Risk Rating** | High |

### Risk Statement

There is a **high risk** that an external attacker could obtain shared employee credentials through phishing and gain unauthorized access to customer financial information due to the use of shared passwords and the absence of MFA.

---

## Risk Treatment

**Treatment:** Mitigate

The organization should reduce the likelihood of unauthorized access by implementing appropriate security controls.

### Recommended Controls

1. Individual user accounts instead of shared credentials.
2. Multi-Factor Authentication (MFA).
3. Password security policies.
4. Security awareness and phishing training for employees.

---

## Risk Ownership

| Role | Responsibility |
|---|---|
| **Risk Owner** | IT Manager |
| **Control Owner** | IT/System Administrator |
| **Employees** | Follow security policies, protect credentials and report suspicious activity |
| **Management** | Provide resources, support and oversight for risk treatment |

---

## Residual Risk

**Residual Risk:** Medium

After implementing individual accounts, MFA and security awareness controls, the likelihood of unauthorized access is reduced.

However, the risk cannot be completely eliminated because users may still fall victim to phishing attacks, misuse credentials, or other security events may occur.

Therefore, the residual risk is assessed as **Medium**.

---

## Risk Assessment Summary

**Inherent Risk:** High

**Treatment:** Mitigate

**Key Controls:** Individual accounts, MFA and security awareness

**Residual Risk:** Medium

---

## Key Learning

This exercise helped demonstrate the relationship between:

**Asset → Threat → Vulnerability → Risk → Impact & Likelihood → Treatment → Controls → Residual Risk**

It also reinforced the distinction between a **risk owner**, a **control owner**, employees and management within a cybersecurity risk management process.
