# Vendor Dependency Audit

## Purpose

This document is a lightweight framework for identifying where operational trust has become concentrated inside external platforms.

The goal is not platform removal.

The goal is visibility.

---

## Platform inventory

| Platform | Function | Criticality | Independent Backup Exists? |
|---|---|---|---|
| Canvas | Learning management | High | No |
| Google Workspace | Productivity and communication | High | Partial |
| PowerSchool | Student information | Critical | No |

---

## Dependency review

For each platform, answer:

1. Does this platform hold identity information?
2. Does this platform hold communication records?
3. Does this platform hold operational continuity?
4. Does this platform function as a proof source?
5. Does this platform control recovery?
6. Can operations continue if the platform fails?
7. Can records be independently verified?
8. Can trust be independently verified?

---

## Concentration warning signs

Warning indicators include:

- one platform controls too many functions
- no offline continuity exists
- no independent audit trail exists
- communication proof is vendor-held
- recovery depends entirely on vendor cooperation
- administrators cannot independently reconstruct events

---

## Goal state

Organizations should aim for:

- platform flexibility
- independent continuity
- independent proof
- vendor-aware governance
- recoverable operations
- reduced trust concentration

---

## Closing principle

A valuable platform can still become a dangerous custody point if too much trust depends on it.
