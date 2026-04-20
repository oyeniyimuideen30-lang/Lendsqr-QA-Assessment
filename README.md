# Adjutor API Assessment - Project Goodness Credit

## 📌 Project Overview
This repository contains the comprehensive Quality Assurance assessment of **Adjutor** (Lendsqr’s API service). The evaluation was conducted from the perspective of a QA Engineer at **Goodness Credit Limited** to determine the platform's suitability for integration with our lending applications.

This project covers the full testing lifecycle: manual test case design, API automation, performance benchmarking, and security vulnerability discovery.

---

## 📂 Repository Contents
* `Lendsqr_Adjutor_API_Automation.json`: Postman collection containing automated test scripts for Goodness Credit core requirements (BVN & Bank Account).
* `QA_Master_Report_Link`: Link to the exhaustive Google Sheet covering Tasks 1, 3, and 4.

---

## 📊 Summary of Findings

### 1. Manual Testing (Task 1)
Designed **35+ test cases** covering the end-to-end onboarding requirements for the Goodness Credit integration.
* **Result:** Validated Signup, Login, and API Key management.

### 2. Automation Results (Task 2)
* **Status:** 75% Pass Rate.
* **Critical Fail:** `POST /v2/verification/bvn` returned a **500 Internal Server Error**, a blocking issue for identity verification.

### 3. Performance & Security (Tasks 3 & 4)
* **Latency:** Identified 4s+ delay on GET endpoints; recommended caching to ensure a responsive user experience.
* **Security:** Identified **Information Exposure** (SQL Leak), posing a risk to Goodness Credit Limited’s data integrity.

---

## 🔗 Project Links
* **Detailed QA Master Sheet:** [View Google Sheet](https://docs.google.com/spreadsheets/d/1hUz4bdMBMWazgXAcey99tLCAiXuofiA-b4t61QKWk_U/edit?usp=sharing)
* **Loom Video Presentation:** [view the l;oom video here] (https://www.loom.com/share/f766eabf92f74c75a6eda2bc98c19932)

---

## 👨‍💻 Author
**Muideen Oyeniyi** 
*Quality Assurance Engineer*
**08104334688**
