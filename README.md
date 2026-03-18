# Cybersecurity Awareness Comic Generation — Narrative Dataset

This repository contains the curated fraud narrative dataset and generated comic outputs used in the paper:



---

## Dataset Description

Ten cybersecurity fraud narratives covering common fraud typologies encountered in the Indian digital payments ecosystem. Narratives are derived from publicly available cybersecurity awareness materials published by the Indian Cybercrime Coordination Centre (I4C), Reserve Bank of India (RBI), and the Cyber Dost initiative of the Ministry of Electronics and Information Technology, Government of India.

| Story | File | Fraud Typology | Victim |
|-------|------|----------------|--------|
| 01 | story_01_online_gaming_scam.txt | Fake In-Game Purchase / UPI Fraud | Aarav |
| 02 | story_02_otp_bank_impersonation.txt | Vishing / Fake Bank Officer / OTP Theft | Arun |
| 03 | story_03_farmer_bank_details.txt | Social Engineering / Accidental Transfer Pretext | Shankar |
| 04 | story_04_loan_app_blackmail.txt | Predatory Loan App / Morphed Image Blackmail | Priya |
| 05 | story_05_pension_otp_fraud.txt | Government Impersonation / OTP Theft | Shanta Devi |
| 06 | story_06_fake_sponsorship.txt | Social Media Advance Fee Fraud | Riya & Akash |
| 07 | story_07_fake_job_offer_sameer.txt | Fake HR / Training Fee Scam | Sameer |
| 08 | story_08_fake_job_offer_rohit.txt | Fake Part-Time Job Ad / Registration Fee | Rohit |
| 09 | story_09_electricity_malicious_app.txt | Utility Impersonation / Remote Access Malware | Arvind |
| 10 | story_10_upi_qr_code_scam.txt | Fake Buyer / QR Code Payment Reversal | Meera |

---

## Generated Comics

Generated 2x4 panel awareness comics for each narrative are provided in the `/outputs` folder. All panels were synthesized in zero-shot mode using FLUX.1-dev with no character-specific training data or identity reference images.

---

