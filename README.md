<div align="center">

# 🛡️ URL Threat Scanner

### Real-Time URL Threat Intelligence Platform

Analyze any website using **7+ live threat intelligence services**, **AI-powered security analysis**, **SSL validation**, and **heuristic detection**.

<p>

![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-18+-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-4-000000?style=for-the-badge&logo=express)
![Vite](https://img.shields.io/badge/Vite-5-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

</p>

> **A full-stack cybersecurity platform that scans URLs in real time using multiple threat intelligence providers and AI reasoning.**

---

### 📸 Preview

> Replace this placeholder with your application screenshot.

<p align="center">
<img src="https://placehold.co/1000x520/0f172a/00ffe0?text=URL+Threat+Scanner" width="95%">
</p>

</div>

---

# ✨ Features

- 🛡️ Scan URLs using multiple threat intelligence services
- 🤖 AI-powered threat explanation
- ⚡ Parallel API scanning
- 📊 Dynamic risk score (0–10)
- 🌍 Domain & IP intelligence
- 🔒 SSL Certificate validation
- 📸 Website screenshot capture
- 📜 Scan history
- 📄 Export reports
- 🚦 Rate limiting
- 🔐 Secure backend API

---

# 🔍 Threat Intelligence Sources

| Service | Purpose | API Key |
|----------|----------|----------|
| 🦠 URLhaus | Malware database | ❌ |
| 🔬 VirusTotal | Multi-engine malware scan | ✅ |
| 🌐 URLScan.io | Browser & page analysis | ✅ |
| 🔴 Google Safe Browsing | Malware & phishing detection | ✅ |
| 🎣 PhishTank | Verified phishing URLs | ❌ |
| 🏛️ RDAP | Domain ownership | ❌ |
| 🔒 SSL Analysis | Certificate validation | ❌ |
| 🧠 Heuristic Engine | Pattern detection | ❌ |

---

# 🤖 AI Analysis

The platform automatically generates an easy-to-understand security report using AI.

### Primary AI
- 🚀 Grok (xAI)

### Fallback AI
- ✨ Gemini

AI provides:

- Threat explanation
- Risk summary
- Recommended actions
- Interactive security chat

---

# 📁 Project Structure

```text
url-threat-scanner/
│
├── backend/
│   ├── server.js
│   ├── routes/
│   ├── services/
│   ├── history.json
│   ├── .env
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── pages/
│   │   ├── components/
│   │   ├── hooks/
│   │   ├── utils/
│   │   └── assets/
│   └── package.json
│
└── README.md
```

---

# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/url-threat-scanner.git

cd url-threat-scanner
```

---

## Backend

```bash
cd backend

npm install

npm run dev
```

---

## Frontend

```bash
cd frontend

npm install

npm run dev
```

---

# ⚙️ Environment Variables

Create

```text
backend/.env
```

```env
PORT=4000

GROK_API_KEY=

GEMINI_API_KEY=

VIRUSTOTAL_API_KEY=

URLSCAN_API_KEY=

GOOGLE_SAFE_BROWSING_API_KEY=
```

---

# 🌐 Running

Backend

```bash
cd backend

npm run dev
```

Frontend

```bash
cd frontend

npm run dev
```

Open

```
Frontend
http://localhost:3000

Backend
http://localhost:4000
```

---

# 📡 API Endpoints

| Method | Endpoint | Description |
|---------|----------|-------------|
| POST | `/api/scan` | Scan URL |
| POST | `/api/ai/chat` | AI Assistant |
| GET | `/api/history` | Scan History |
| DELETE | `/api/history` | Delete History |
| GET | `/api/health` | Health Check |

---

# 🧪 Example Scan

```text
Threat Score

9.2 / 10

HIGH RISK

✔ Malware detected
✔ Phishing database match
✔ Invalid SSL Certificate
✔ Newly Registered Domain
✔ Suspicious URL Pattern
```

---

# 🔐 Security

- API keys stored only on backend
- No secrets exposed to frontend
- Input validation
- Secure API proxy
- Rate limiting
- Error handling
- Environment variables

---

# 💻 Tech Stack

### Frontend

- React
- Vite
- Axios
- Tailwind CSS

### Backend

- Node.js
- Express
- Axios
- dotenv

### AI

- Grok
- Gemini

### Threat Intelligence

- VirusTotal
- URLhaus
- URLScan
- Google Safe Browsing
- PhishTank
- RDAP
- SSL Validation

---

# 🚀 Future Improvements

- User authentication
- PDF reports
- Email alerts
- Browser extension
- Bulk URL scanning
- Threat trends dashboard
- Dark mode
- Docker deployment

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the project

2. Create your feature branch

```bash
git checkout -b feature/new-feature
```

3. Commit

```bash
git commit -m "Add new feature"
```

4. Push

```bash
git push origin feature/new-feature
```

5. Open a Pull Request

---

# 📄 License

Licensed under the **MIT License**.

---

# 👨💻 Author

### Muhammad Harib

Cybersecurity • Full Stack Development • AI

---

<div align="center">

If you found this project useful,

⭐ **Please consider giving it a Star on GitHub!**

</div>
