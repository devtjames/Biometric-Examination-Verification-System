# Technical Decisions

This document explains the key technical and design decisions made during the development of the Biometric Examination Verification System.

The focus was on practicality, reliability, and suitability for an academic environment.

---

## Desktop Application Approach

**Decision:** Build a desktop-based application rather than a web system.

**Reasoning:**
- Examination halls may not have reliable internet access  
- Biometric hardware integrates more easily with desktop applications  
- Reduced external dependencies  

This ensured the system could run reliably in controlled environments.

---

## Fingerprint-Based Verification

**Decision:** Use fingerprint biometrics instead of ID cards or facial recognition.

**Reasoning:**
- Fingerprints provide unique and stable identification  
- Reduces impersonation risk significantly  
- Less sensitive to lighting or camera quality  

Fingerprint verification was the most practical option for the target environment.

---

## GrFinger SDK Selection

**Decision:** Use GrFinger SDK for biometric processing.

**Reasoning:**
- Provides reliable fingerprint capture and matching  
- Well-documented for VB.NET integration  
- Suitable for academic and prototype deployments  

SDK limitations were acknowledged and managed during development.

---

## Microsoft Access as Database

**Decision:** Use Microsoft Access for data storage.

**Reasoning:**
- Simple setup and deployment  
- No need for a dedicated database server  
- Suitable for department-level usage  

This choice reduced setup complexity while supporting required data volume.

---

## Parallel Implementation Strategy

**Decision:** Design the system to support parallel use with existing manual methods.

**Reasoning:**
- Reduces risk during adoption  
- Allows fallback in case of technical issues  
- Eases transition for staff and supervisors  

Parallel operation was safer for real-world testing.

---

## Staff-Controlled Verification

**Decision:** Restrict verification access to assigned supervisors only.

**Reasoning:**
- Prevents system misuse  
- Reduces manipulation risks  
- Establishes accountability during examinations  

Access control was a core part of system trust.

---

## Academic Scope Limitation

**Decision:** Limit the system to departmental-level deployment.

**Reasoning:**
- Hardware and licensing constraints  
- Academic project scope  
- Focus on correctness rather than scale  

The system was intentionally scoped for reliability over expansion.

---

## Summary

Key priorities guiding decisions:
- Accuracy over complexity  
- Controlled access over convenience  
- Practical deployment over large-scale architecture  

These decisions ensured the system met its core goal: preventing examination impersonation reliably.
