<div align="center">

# 🛡️ URL Threat Scanner

### Real-Time URL Threat Intelligence Platform

**Scan any URL against 7+ live threat intelligence sources — powered by AI.**

[![Node.js](https://img.shields.io/badge/Node.js-18+-339933?style=flat-square&logo=node.js&logoColor=white)](https://nodejs.org)
[![React](https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react&logoColor=black)](https://react.dev)
[![Vite](https://img.shields.io/badge/Vite-5-646CFF?style=flat-square&logo=vite&logoColor=white)](https://vitejs.dev)
[![Express](https://img.shields.io/badge/Express-4-000000?style=flat-square&logo=express&logoColor=white)](https://expressjs.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](LICENSE)

<br/>

![URL Threat Scanner](https://placehold.co/900x480/0f172a/00ffe0?text=URL+Threat+Scanner+%E2%80%94+Security+Intelligence+Platform)

</div>

---

## ✨ What is URL Threat Scanner?

**URL Threat Scanner** is a full-stack cybersecurity intelligence platform that analyzes any URL in real time using multiple threat intelligence sources, SSL inspection, domain analysis, heuristic detection, and AI reasoning.

It helps detect:
- Phishing websites
- Malware-hosting domains
- Suspicious or newly registered domains
- Invalid or expired SSL certificates
- Malicious URL patterns

---

## 🔍 Threat Intelligence Sources

| Source | Type | Key Required |
|---|---|---|
| 🦠 URLhaus | Malware database | No |
| 🔬 VirusTotal | Multi-engine scan | Yes |
| 🌐 URLScan.io | Live browser analysis | Yes |
| 🔴 Google Safe Browsing | Phishing & malware detection | Yes |
| 🎣 PhishTank | Verified phishing URLs | No |
| 🏛️ RDAP | Domain information | No |
| 🔒 SSL Analysis | Certificate validation | No |
| 🧠 Heuristic Engine | Pattern detection | No |

---

## 🤖 AI-Powered Analysis

- **Grok (xAI)** — primary AI engine  
- **Gemini (Google)** — fallback engine  

Features:
- Threat summarization
- Risk explanation
- Interactive AI chat after scan

---

## 🚀 Features

- ⚡ Parallel multi-source scanning
- 📊 Risk score (0–10 scale)
- 📈 Visual risk breakdown
- 🖼️ Website screenshot capture
- 🌍 Domain & IP metadata
- 🏷️ Source-level verification status
- 📜 Scan history system
- 📄 Exportable reports
- 🔒 Rate limiting protection
- 🛡️ Secure backend (no exposed API keys)

---

## 🗂️ Project Structure

```bash
url-threat-scanner/
├── backend/
│   ├── server.js
│   ├── .env (not committed)
│   ├── history.json
│   └── package.json
│
└── frontend/
    ├── src/
    │   ├── pages/
    │   ├── components/
    │   └── utils/
    └── package.json

    
---

## ⚙️ Setup

### 1. Clone repo
```bash
git clone https://github.com/yourusername/url-threat-scanner.git
cd url-threat-scanner


## ⚙️ Installation & Setup

### 📦 Install dependencies

**Backend**
```bash
cd backend
npm install


**Frontend**

cd frontend
npm install