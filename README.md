# 🛡️ Fake Login Detector

A simple Python-based cybersecurity project that detects suspicious login behavior such as brute-force attacks, multiple IP usage, and rapid login attempts.

---

## 🚀 Features

- Detects multiple failed login attempts
- Flags logins from multiple IP addresses
- Detects rapid (bot-like) login behavior
- Easy to customize detection rules
- Beginner-friendly cybersecurity project

---

## 🧠 How It Works

The system stores login attempts per user and analyzes patterns such as:

- ❌ Number of failed login attempts  
- 🌍 Number of different IP addresses  
- ⚡ Time between login attempts  

If unusual behavior is detected, the system flags the user as suspicious.

fake-login-detector/
│
├── detector.py # Main detection logic
├── demo.py # Example usage
└── README.md # Project documentation

---

## ▶️ How to Run

### 1. Clone the repository
```bash
git clone https://github.com/your-username/fake-login-detector.git
cd fake-login-detector
## 📁 Project Structure

📌 Example Output
(True, 'Too many failed login attempts')

or

(False, 'Normal behavior')
