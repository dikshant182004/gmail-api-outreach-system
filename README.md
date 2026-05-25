# 📧 Email Outreach Automation (Colab Notebook)

A Python-based **Google Colab notebook project** that automates structured email outreach using the **Gmail API + OAuth authentication**.  

It is designed for **learning, experimentation, and responsible outreach workflows** using CSV/Excel-based contact lists.

---

## 🚀 Project Overview

This project demonstrates how to:

- Authenticate Gmail securely using OAuth 2.0 in Google Colab
- Read HR/contact data from Excel or CSV files
- Personalize email messages dynamically
- Send emails using Gmail API
- Implement rate limiting to avoid spam detection
- Maintain logs of sent and failed emails

---

## 📂 How It Works (Colab Flow)

1. Upload `credentials.json` (Google Cloud OAuth file)
2. Upload HR contact file (CSV/Excel)
3. Run notebook cells step-by-step
4. Authenticate via Google login link
5. Emails are sent in controlled batches (e.g., 100/day)
6. Logs are stored for tracking

---

## ⚙️ Tech Stack

- Python
- Google Colab
- Gmail API
- Google OAuth 2.0
- Pandas
- Email MIME libraries
- Logging system

---

## 📊 Features

- ✔ Gmail OAuth authentication (secure login flow)
- ✔ Works directly inside Google Colab
- ✔ Supports Excel / CSV contact files
- ✔ Personalized email generation
- ✔ Rate limiting (safe sending behavior)
- ✔ Email success/failure logging
- ✔ Batch-controlled sending (e.g., 100 emails/day)

---

## 📁 Required Files

You need to upload the following inside Colab:

- `credentials.json` → From Google Cloud Console
- HR contact file → `.csv` or `.xlsx`

---

## 🔐 Google Cloud Setup

### 1. Create OAuth Credentials
- Go to: https://console.cloud.google.com/
- Enable **Gmail API**
- Go to **APIs & Services → Credentials**
- Create **OAuth Client ID (Desktop App)**
- Download `credentials.json`

---

### 2. Configure OAuth Consent Screen
- Set user type as **External**
- Add your Gmail under **Test Users**
- Save configuration

---

## ▶️ How to Run

1. Open the notebook in Google Colab
2. Upload required files (`credentials.json` + dataset)
3. Run all cells sequentially
4. Authenticate using the generated Google link
5. Start sending emails

---

## ⚠️ Safety Guidelines

- Recommended limit: **~100 emails/day**
- Some emails may bounce due to invalid or outdated contacts
- Always clean and verify contact lists before sending
- Use responsibly and avoid spam behavior

---

## 📌 Use Cases

- Job application outreach (AI/ML, software roles)
- Recruiter communication
- Networking automation
- Learning Gmail API + workflow automation

---

## 📎 Notes

- This project is built for **educational and portfolio purposes**
- Works entirely inside **Google Colab environment**
- No external server required

---

## ⭐ Connect

If you find this useful:

- ⭐ Star the repo
- 🔗 Connect on LinkedIn
- 💬 Share feedback or improvements

---

## 📜 License

For educational use only. Users are responsible for ethical and compliant usage.
