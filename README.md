# 🛡️ WebKnight – Web & CLI Vulnerability Scanner with AI Feedback

![WebKnight Banner](https://github.com/ELMERIKH/Web-AI-Scanner/assets/96123439/39a147e4-6514-4772-8f4f-773beab046b9)

**WebKnight** is a lightweight, dual-mode (Web + CLI) vulnerability scanner designed to detect basic web application flaws like **SQL Injection, XSS, and CSS Injection**. It integrates with **AI (LLaMA API)** to provide intelligent suggestions and potential fixes for the vulnerabilities found.

> ⚠️ **Work in progress** – currently on hold, but updates will be coming soon!

---

## ✨ Features

- 🔍 Detects common vulnerabilities:
  - ✅ SQL Injection (SQLi)
  - ✅ Cross-Site Scripting (XSS)
  - ✅ CSS Injection
- 🌐 Web Interface using Flask
- 💻 Command Line support
- 🤖 AI feedback with fix suggestions
- 📋 Logs vulnerable parameters with context
- 🚀 Beginner-friendly setup

## Get Your AI API Key

Visit: https://www.llama-api.com

Paste your key inside AI.py:
```
headers = {
    "Authorization": "Bearer YOUR_API_KEY_HERE",
    "Content-Type": "application/json"
}
```
---

## 📦 Setup Instructions

```bash
git clone https://github.com/YourUsername/WebKnight.git
cd WebKnight
pip install -r requirements.txt
```
##Roadmap
-  Add website crawler for deeper scanning

- Support form-based testing (POST methods)

- Integrate CSRF and Clickjacking checks

- Export scan results as PDF/CSV

- Improve AI explanations with severity tags

- Redesign UI with alert categories
##Disclaimer
This tool is intended for educational and ethical testing only.
Do not scan any websites without proper authorization.
The developer is not responsible for any misuse.

## Developer
Santhoshkumar T
Cybersecurity Enthusiast | Builder | GFG Campus Mantri
📍 Chennai, India
🔗 [LinkedIn](https://www.linkedin.com/in/santhoshkumar-cyberexpert/)
🔗 [GitHub](https://github.com/santhosheyzz)

---


