<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b0c10,50:1f2833,100:0b0c10&height=160&section=header&text=PassVault&fontSize=52&fontColor=66fcf1&fontAlignY=42&desc=Password%20Strength%20Analyzer%20%2B%20Secure%20Generator&descAlignY=62&descSize=16&animation=fadeIn" width="100%"/>

<br/>

[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://github.com/MishitaDodani)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://github.com/MishitaDodani)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://github.com/MishitaDodani)
[![Security](https://img.shields.io/badge/Web%20Crypto%20API-00C4CC?style=for-the-badge&logo=letsencrypt&logoColor=white)](https://github.com/MishitaDodani)

<br/>

> *"A password is like a toothbrush — choose a good one, don't share it, and change it regularly."*

</div>

---

## 🔐 What is PassVault?

**PassVault** is a fully client-side web application that helps users analyze the strength of their passwords in real time and generate cryptographically secure ones — all without sending a single character to any server.

Built with a dark hacker aesthetic using **JetBrains Mono** and **Syne** fonts, it feels at home in a security toolkit.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🔍 **Real-time Strength Analysis** | Instantly scores password strength as you type |
| 📊 **Entropy Calculation** | Computes Shannon entropy in bits for precise measurement |
| ⏱️ **Crack Time Estimator** | Estimates how long a brute-force attack (10B guesses/sec) would take |
| ✅ **8 Security Checks** | Validates length, case, digits, symbols, repeats and more |
| 🎲 **Secure Password Generator** | Uses `crypto.getRandomValues()` — no `Math.random()` |
| 🎛️ **Customizable Generation** | Adjust length (8–64), toggle A–Z, a–z, 0–9, symbols, exclude ambiguous chars |
| 📋 **One-click Copy** | Copy generated password to clipboard instantly |
| ↩️ **Use Generated Password** | Load generated password directly into the analyzer |
| 👁️ **Show / Hide Toggle** | Reveal or mask password input on demand |

---

## 🧠 How Strength is Scored

Password entropy is calculated as:

```
Entropy (bits) = length × log₂(character_pool_size)
```

| Entropy | Strength | Color |
|---|---|---|
| < 25 bits | 🔴 Very Weak | Red |
| 25–39 bits | 🟠 Weak | Orange |
| 40–54 bits | 🟡 Fair | Yellow |
| 55–69 bits | 🟢 Strong | Green |
| 70+ bits | 🩵 Excellent | Cyan |

Crack time is estimated assuming **10 billion guesses per second** (modern GPU brute-force benchmark).

---

## 🛡️ Security Checks

The analyzer runs **8 live checks** on every keystroke:

```
✔  8+ characters          ✔  12+ characters
✔  Uppercase (A–Z)        ✔  Lowercase (a–z)
✔  Numbers (0–9)          ✔  Symbols (!@#…)
✔  No repeated chars      ✔  16+ characters
```

---

## 🚀 Getting Started

No installation. No dependencies. No server.

```bash
# Clone the repo
git clone https://github.com/MishitaDodani/PassVault.git

# Open in browser
open password_strength_checker_generator.html
```

Or just **drag and drop** the `.html` file into any browser. That's it. ✅

---

## 🗂️ Project Structure

```
PassVault/
│
├── password_strength_checker_generator.html   # Complete app (HTML + CSS + JS)
└── README.md                                  # You are here
```

Everything is self-contained in a single file — no frameworks, no build tools, no npm.

---

## 🔧 Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox, transitions) |
| Logic | Vanilla JavaScript (ES6+) |
| Randomness | Web Crypto API — `crypto.getRandomValues()` |
| Fonts | JetBrains Mono + Syne (Google Fonts) |

---

## 🎯 Concepts Demonstrated

This project showcases practical knowledge relevant to **web application security** and **secure development**:

- 🔐 **Cryptographically secure randomness** — using `crypto.getRandomValues()` instead of insecure `Math.random()`
- 📐 **Shannon entropy** — mathematically measuring password unpredictability
- 🛡️ **Password policy enforcement** — length, complexity, and pattern checks
- 🧩 **Authentication security** — understanding what makes credentials vulnerable
- 💻 **Secure coding practices** — client-side only, zero data transmission, no storage

---

## 📸 Preview

```
┌─────────────────────────────────────────┐
│  PASSWORD VAULT                         │
│  // strength analyzer + secure generator│
│                                         │
│  [ ANALYZE PASSWORD ]                   │
│  ●●●●●●●●●●●●  👁  ✕               │
│                                         │
│  ▓▓▓▓▓░  STRONG          72 bits       │
│                                         │
│  ✔ 8+ chars   ✔ 12+ chars             │
│  ✔ uppercase  ✔ lowercase             │
│  ✔ numbers    ✔ symbols               │
│  ✔ no repeats ✔ 16+ chars             │
│                                         │
│  estimated crack time: 4.2M years      │
│                                         │
│  [ GENERATE PASSWORD ]                  │
│  Length ──●───────── 20                │
│  [A–Z] [a–z] [0–9] [!@#] [no 0OlI]   │
│  [ Generate Secure Password ]           │
│                                         │
│  kR#9mPx@2nZqL$vTw8j  📋  ✔          │
└─────────────────────────────────────────┘
```

---

## 👩‍💻 Author

<div align="center">

**Mishita Dodani**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mishita-dodani-381664253/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/MishitaDodani)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:mishitadodani068@gmail.com)

Cybersecurity Enthusiast | Penetration Tester in Training*

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b0c10,50:1f2833,100:0b0c10&height=100&section=footer&animation=fadeIn" width="100%"/>

⭐ **Star this repo if you found it useful!**

</div>
