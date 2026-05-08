# School Platform Risk Model

## Purpose

This document helps schools, universities, and education organizations evaluate the trust risk created when too much operational dependency is concentrated inside one vendor-controlled platform.

This model is not vendor-specific.

It applies to learning management systems, student information systems, communication platforms, productivity suites, assessment tools, and other cloud-based education systems.

---

## Core risk question

> What happens if the platform that holds daily learning, identity, communication, records, and continuity becomes unavailable, compromised, or untrusted?

---

## Five dependency zones

### 1. Identity dependency

Questions:

- Does the platform function as the primary identity gate?
- Are student, staff, or parent identities verified only inside the platform?
- Can the school verify identity continuity outside the vendor system?

Risk signal:

> If the platform fails, the school may lose confidence in who is acting.

---

### 2. Communication dependency

Questions:

- Are announcements, messages, alerts, and course communications stored only in the platform?
- Can the school independently prove what was sent, received, or changed?
- Is there a trusted emergency communication path outside the vendor?

Risk signal:

> If the platform fails, the school may lose communication proof.

---

### 3. Records dependency

Questions:

- Are assignments, submissions, grades, messages, attendance records, or administrative records vendor-held?
- Is there an independent read-only archive?
- Can the school reconstruct critical records if vendor access is disrupted?

Risk signal:

> If the platform fails, the school may lose operational memory.

---

### 4. Continuity dependency

Questions:

- Can classes continue if the platform is unavailable?
- Are emergency lesson packets, rosters, assignments, and notices available outside the platform?
- Has the continuity plan been tested?

Risk signal:

> If the platform fails, instruction may stop.

---

### 5. Trust dependency

Questions:

- Does the school rely on the platform to prove what happened?
- Can the school independently verify access, changes, communication, and recovery?
- Is there a separate audit layer?

Risk signal:

> If the platform fails, the school may lose proof.

---

## Risk scoring

Use a simple 0-3 score for each dependency zone.

| Score | Meaning |
|---|---|
| 0 | No meaningful dependency or strong independent control exists |
| 1 | Limited dependency with partial independent backup |
| 2 | Significant dependency with weak independent proof |
| 3 | Critical dependency with no independent trust layer |

Total possible score: 15

| Total | Interpretation |
|---|---|
| 0-4 | Low dependency concentration |
| 5-8 | Moderate dependency concentration |
| 9-12 | High dependency concentration |
| 13-15 | Critical dependency concentration |

---

## Recommended action

If a school scores high in any zone, it should consider an independent trust layer that supports:

- identity continuity
- communication proof
- records backup
- emergency continuity
- vendor-independent audit trails

---

## Closing principle

A school may keep the platform.

But it should not let one platform become the only source of trust.
