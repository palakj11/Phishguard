# 🛡️ PhishGuard

PhishGuard is an intelligent phishing detection system that analyzes URLs, web content, and user inputs to identify potential scams and malicious activity using AI and heuristic techniques.

---

## 🚀 Features

* 🔍 URL and domain analysis (WHOIS + parsing)
* 🤖 AI-based phishing detection (Transformers)
* 🌐 Web scraping for suspicious content
* 🔐 Google OAuth authentication
* 🎙️ Audio & multilingual input support
* 📊 Risk scoring system for scam detection

---

## 🏗️ Project Structure

```
phishguard/
│
├── app.py                  # Main Flask application
├── client_secret.json      # Google OAuth credentials (DO NOT SHARE)
│
├── templates/              # HTML templates
├── static/                 # CSS, JS
│
├── myenv/                  # Virtual environment (excluded)
└── README.md               # Documentation
```

---

## ⚙️ Installation

```bash
git clone https://github.com/yourusername/phishguard.git
cd phishguard

python -m venv myenv
source myenv/bin/activate   # Windows: myenv\Scripts\activate

pip install -r requirements.txt
```

---

## 🔐 Environment Setup

Instead of storing secrets in files, use environment variables:

```bash
export GOOGLE_CLIENT_ID=your_client_id
export GOOGLE_CLIENT_SECRET=your_client_secret
```

---

## ▶️ Run the App

```bash
python app.py
```

Visit:

```
http://localhost:5000
```

---

## ⚠️ Security Notice

Never upload:

* `client_secret.json`
* `.env`
* Any API keys or tokens

---

## 📊 Use Cases

* Phishing website detection
* Scam analysis tools
* Cybersecurity dashboards
* AI-based fraud detection

---

## 📌 Future Improvements

* Real-time browser extension
* Email phishing scanner
* ML model improvements
* Cloud deployment

---

## 👨‍💻 Author

PhishGuard Security Project
