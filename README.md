PII Detection & Data Anonymization Pipeline

## 📌 Overview
This project implements a *Python-based pipeline* to automatically detect and redact *Personally Identifiable Information (PII)* from structured datasets (CSV files).  
It ensures compliance with data privacy regulations (GDPR, HIPAA, etc.) by *masking, substituting, or redacting sensitive fields* such as:

- Phone numbers  
- Aadhaar numbers  
- Passport numbers  
- UPI IDs  
- Email addresses  
- Postal addresses & PIN codes  
- Device IDs & IP addresses  

The output is a *redacted dataset* that can be safely used for analytics, ML model training, or data sharing without risking sensitive data exposure.  

---

## ⚙ Features
- ✅ *Regex-based detection* for accurate PII identification  
- ✅ *Custom anonymization functions* for phones, Aadhaar, passports, UPI, and emails  
- ✅ *CSV ingestion & redaction pipeline* with minimal memory overhead  
- ✅ *Summary statistics* on processed records & detected PII  
- ✅ *Automated redacted output* saved as CSV for downstream usage  

---

## 📊 Dataset Results (from sample run)
- *Total records processed:* 500  
- *Records flagged with PII:* 291 (~58%)  
- *Sensitive fields detected:* 299  
- *Records with multiple PII elements:* 83  

---

## 🛠 Tech Stack
- *Python 3.9+*  
- Built-in libraries: csv, json, re, ast, pathlib  

---
