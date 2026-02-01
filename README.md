# Biometric Examination Verification System

## Overview

This project is a fingerprint-based examination verification system designed to prevent impersonation and examination malpractice in academic environments.

The system replaces manual examination clearance methods with biometric verification, ensuring that only registered and eligible students are allowed to sit for examinations. It was developed as an academic final year project and deployed at department level for evaluation.

The focus of the system is accurate identity verification, controlled access during examinations, and reliable attendance recording.

---

## Problem Statement

Manual examination verification relies heavily on ID cards and visual confirmation, which are prone to impersonation, human error, and manipulation.

With large student populations, invigilators often find it difficult to confirm identities accurately, leading to unauthorized candidates gaining access to examination halls.

This project addresses these issues by using fingerprint-based verification tied directly to student records.

---

## Core Features

- Student biometric registration using fingerprint capture  
- Fingerprint-based verification before examination entry  
- Examination attendance recording linked to biometric validation  
- Course and venue registration for examination sessions  
- Staff authentication and supervision control  
- Examination card generation with student and course details  
- Reporting for attendance and verification records  

---

## Screenshots

> Screenshots below show the actual working application.

### Login Screen
<img width="816" height="519" alt="image" src="https://github.com/user-attachments/assets/f82d430f-f04c-4607-a122-463419c430b3" />


### Student Registration Form with Biometric
<img width="816" height="467" alt="image" src="https://github.com/user-attachments/assets/3d3bd602-c10d-49ea-bc07-8ffb2894acc2" />


### Staff Registration Page
<img width="547" height="472" alt="image" src="https://github.com/user-attachments/assets/6eb90446-da61-4560-8206-c91b2f070429" />


### Admin Registration Page
<img width="383" height="452" alt="image" src="https://github.com/user-attachments/assets/a6b99d71-1d6b-457d-9121-5808409eca69" />


### Staff Admin Page
<img width="881" height="464" alt="image" src="https://github.com/user-attachments/assets/c87d267f-e4d8-497f-9545-60a823969fd7" />


### Course Registration
<img width="420" height="378" alt="image" src="https://github.com/user-attachments/assets/a0c95d23-a219-4a35-a1ae-9a7166461692" />
<img width="824" height="511" alt="image" src="https://github.com/user-attachments/assets/8c6a16ab-288f-4717-a190-2393c40c2259" />


### Report Card Generation
<img width="975" height="248" alt="image" src="https://github.com/user-attachments/assets/01cfaa5d-0671-4cd5-8e15-d840def59a2b" />


### Exam Card
<img width="438" height="475" alt="image" src="https://github.com/user-attachments/assets/8796163f-343c-4c1e-8e64-aa023c264d12" />


### Student Biometric Capture
<img width="856" height="483" alt="image" src="https://github.com/user-attachments/assets/1e1eea89-290a-466c-a579-850c48df7cee" />


### Attendance Checking Page
<img width="433" height="397" alt="image" src="https://github.com/user-attachments/assets/ee347f7c-c3a3-4168-97e5-8cd957bb1fe0" />


### Booklet Submission Page
<img width="425" height="334" alt="image" src="https://github.com/user-attachments/assets/47cfbcb7-340c-4156-8c99-3d3545831108" />


### Attendance Report
<img width="645" height="414" alt="image" src="https://github.com/user-attachments/assets/d195927c-59fb-4575-9f99-8fd071906eee" />




---

## Tech Stack

- **Application Type:** Desktop Application  
- **Programming Language:** VB.NET  
- **Biometric SDK:** GrFinger SDK  
- **Database:** Microsoft Access  
- **Development Environment:** Visual Studio  
- **Platform:** Windows  

---

## My Role

I handled the full development of the project, including:

- System analysis and requirements breakdown  
- Database design and record structure  
- Biometric capture and verification logic  
- UI development and workflow design  
- Examination verification and attendance handling  
- System testing and documentation  

---

## System Architecture

The system follows a controlled desktop-based architecture:

1. **User Interface Layer**  
   - Student registration forms  
   - Staff login and attendance screens  

2. **Biometric Layer**  
   - Fingerprint capture and template generation  
   - Fingerprint matching using GrFinger SDK  

3. **Application Logic Layer**  
   - Student eligibility checks  
   - Attendance validation  
   - Supervisor access control  

4. **Database Layer**  
   - Student records  
   - Biometric templates  
   - Course, venue, and attendance data  

All examination verification decisions are based on stored biometric data rather than manual confirmation.

---

## Development Notes

- This project was developed as an academic final year project.  
- The source code is private due to institutional use and SDK licensing constraints.  
- This repository exists to document the system design, features, and approach.  

For web and backend code samples, see my other public repositories.

---

## Contact

If you would like to discuss this project or review the system privately, feel free to reach out at: mail.devtjames@gmail.com
