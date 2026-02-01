# System Architecture

## Overview

The Biometric Examination Verification System is a desktop-based application designed to enforce identity verification and attendance control during examinations using fingerprint biometrics.

The architecture prioritizes accuracy, controlled access, and simplicity, suitable for departmental or institution-level deployment.

---

## High-Level Architecture

The system is organized into four main layers:

1. User Interface Layer  
2. Biometric Processing Layer  
3. Application Logic Layer  
4. Data Storage Layer  

Each layer has a clear responsibility and communicates only with the layers directly above or below it.

---

## User Interface Layer

This layer handles all user interactions.

Key interfaces include:
- Staff login screen  
- Student registration form  
- Course and venue registration screens  
- Examination attendance and verification screen  

The UI is designed to:
- Guide users through required workflows  
- Prevent unauthorized actions  
- Reduce human error during examination verification  

---

## Biometric Processing Layer

This layer manages fingerprint capture and verification.

Responsibilities:
- Capturing fingerprint data during student registration  
- Generating fingerprint templates using the GrFinger SDK  
- Matching live fingerprints against stored templates  

Fingerprint verification is mandatory before examination attendance is recorded.

---

## Application Logic Layer

This layer controls system rules and workflows.

Key responsibilities:
- Validating staff authentication and permissions  
- Ensuring students are registered before verification  
- Linking fingerprint verification to attendance records  
- Preventing duplicate or invalid attendance entries  

All decisions are made by system logic, not manual overrides.

---

## Data Storage Layer

The database layer stores all persistent records.

Data includes:
- Student personal records  
- Fingerprint templates  
- Course and venue data  
- Examination attendance logs  

Microsoft Access was used to support structured storage while keeping deployment simple.

---

## Security Considerations

- Only authenticated staff can access verification features  
- Biometric data is stored in structured form and never manually edited  
- Attendance records are generated only after successful fingerprint validation  

---

## Deployment Model

- Desktop-based Windows application  
- Intended for controlled environments such as examination halls  
- Designed for parallel use alongside existing manual systems during adoption  

---

## Summary

The architecture emphasizes:
- Clear separation of concerns  
- Reliable biometric verification  
- Minimal human intervention during examinations  

This design ensures the system remains dependable, easy to operate, and suitable for real academic environments.
