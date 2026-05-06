<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:5b72f0,50:9b6df5,100:EA4335&height=200&section=header&text=FeeTrack&fontSize=80&fontColor=ffffff&fontAlignY=38&desc=AI-Powered%20School%20Fee%20Management%20Dashboard&descAlignY=60&descSize=20&animation=fadeIn" width="100%"/>

<br/>

[![Made with HTML](https://img.shields.io/badge/Made%20with-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/Styled%20with-CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/Powered%20by-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Gemini AI](https://img.shields.io/badge/Google-Gemini%20AI-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://ai.google.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

<br/>

> 🎓 **FeeTrack** is a sleek, dark-themed, single-file school fee management dashboard built for **Greenfield Public School**. It combines real-time student tracking with **Google Gemini AI** to auto-generate personalized fee reminder messages — all with zero backend, zero database.

<br/>

</div>

---

## ✨ Live Preview

<div align="center">

| 🏠 Dashboard | 👤 Add Student |
|:---:|:---:|
| ![Dashboard](screenshots/dashboard.png) | ![Add Student](screenshots/add-student.png) |

| 💳 Record Payment | 📋 Student Records |
|:---:|:---:|
| ![Payment](screenshots/payment.png) | ![Records](screenshots/records.png) |

| 🤖 AI Bulk Reminders |
|:---:|
| ![AI Reminders](screenshots/ai-reminders.png) |

</div>

---

## 🌟 Features

<div align="center">

```
╔══════════════════════════════════════════════════════════════════╗
║                    🚀  CORE CAPABILITIES                         ║
╠══════════════════════════════════════════════════════════════════╣
║  📊  Live Dashboard Stats      🔍  Smart Search & Filters        ║
║  👨‍🎓  Student Management        💰  Payment Recording             ║
║  📅  Due Date Tracking         📈  Visual Progress Bars          ║
║  🤖  Gemini AI Reminders       📋  Overdue Alerts                ║
║  📱  Responsive Design         🌙  Dark Mode UI                  ║
╚══════════════════════════════════════════════════════════════════╝
```

</div>

### 🔢 Dashboard Analytics
- **Total Students** — enrolled count across all classes
- **Fees Collected** — live sum with fully-paid student count
- **Outstanding Balance** — real-time calculation of pending dues
- **Overdue Students** — instant count needing urgent attention
- **Collection Rate Progress Bar** — visual percentage tracker

### 👩‍🏫 Student Management
- ➕ Add students with full details — name, class/section, total fee, amount paid, due date, parent info
- ✏️ Edit any student record inline
- 🗑️ Delete students with confirmation
- 🔎 Filter by **All / Overdue / Pending / Paid** status
- 🔍 Live search by student name or class

### 💳 Payment Recording
- Record partial or full payments
- Choose payment mode: **Cash / Online / Cheque / DD**
- Add receipt/reference numbers
- Tracks remaining balance in real-time

### 🤖 Gemini AI Bulk Reminders
- Connect your **Google Gemini API key** (stored only in browser memory)
- Target: **Overdue only**, **Pending only**, or **Both**
- Choose message tone: **Polite & Friendly**, **Formal & Firm**, or **Urgent**
- Generates a smart, personalized WhatsApp-ready broadcast message
- One-click copy to clipboard
- Graceful fallback if API is unavailable

---

## 🛠️ Tech Stack

<div align="center">

| Technology | Purpose | Details |
|:---:|:---:|:---:|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) | Structure | Semantic, single-file app |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) | Styling | Custom properties, animations, glassmorphism |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | Logic | Vanilla JS, no frameworks |
| ![Google Fonts](https://img.shields.io/badge/Syne%20%2B%20DM%20Sans-4285F4?style=flat-square&logo=google-fonts&logoColor=white) | Typography | Syne (headings) + DM Sans (body) |
| ![Font Awesome](https://img.shields.io/badge/Font%20Awesome-528DD7?style=flat-square&logo=font-awesome&logoColor=white) | Icons | v6.5 icon set |
| ![Gemini AI](https://img.shields.io/badge/Gemini%20AI-4285F4?style=flat-square&logo=google&logoColor=white) | AI Engine | `/v1beta/models/gemini-pro` via REST |

</div>

---

## 🚀 Getting Started

### 📥 Installation

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/feetrack.git

# 2. Navigate into the project
cd feetrack

# 3. Open in browser — NO build step needed!
open index.html
# or just double-click index.html
```

> ✅ That's it. It's a **100% static, zero-dependency** app!

---

### 🔑 Connecting Gemini AI (Optional)

To unlock AI-powered reminders:

1. Visit [aistudio.google.com/apikey](https://aistudio.google.com/apikey)
2. Generate a free API key
3. Paste it into the **"Connect Google Gemini AI"** field in the dashboard
4. Click **"Connect & Test"**
5. Your key lives only in **browser memory** — never sent to any server

---

## 📁 Project Structure

```
feetrack/
│
├── 📄 index.html          ← Entire app (HTML + CSS + JS in one file)
├── 📂 screenshots/        ← App screenshots for README
│   ├── dashboard.png
│   ├── add-student.png
│   ├── payment.png
│   ├── records.png
│   └── ai-reminders.png
└── 📄 README.md           ← You are here!
```

---

## 🎨 Design System

<div align="center">

| Token | Color | Usage |
|:---:|:---:|:---:|
| `--accent` | ![#5b72f0](https://via.placeholder.com/14/5b72f0/5b72f0.png) `#5B72F0` | Primary actions, links |
| `--accent2` | ![#9b6df5](https://via.placeholder.com/14/9b6df5/9b6df5.png) `#9B6DF5` | Gradients, highlights |
| `--green` | ![#0fd98b](https://via.placeholder.com/14/0fd98b/0fd98b.png) `#0FD98B` | Paid / success states |
| `--yellow` | ![#f5c518](https://via.placeholder.com/14/f5c518/f5c518.png) `#F5C518` | Pending / warning states |
| `--red` | ![#ff4565](https://via.placeholder.com/14/ff4565/ff4565.png) `#FF4565` | Overdue / error states |
| `--bg` | ![#08090d](https://via.placeholder.com/14/08090d/08090d.png) `#08090D` | Page background |
| `--card` | ![#111420](https://via.placeholder.com/14/111420/111420.png) `#111420` | Card surfaces |

</div>

---

## 📸 Screenshots Guide

> Add your screenshots to a `/screenshots` folder in the repo root:

```bash
mkdir screenshots
# Then copy your 5 screenshots:
# dashboard.png, add-student.png, payment.png, records.png, ai-reminders.png
```

---

## 🧪 Sample Data

FeeTrack ships with **15 pre-loaded students** across Classes 6–9 with realistic Indian names, fee amounts (₹10,500–₹15,000), and mixed payment statuses — so you can explore every feature immediately without entering test data.

---

## 🔮 Roadmap

- [ ] 📤 Export to CSV / PDF
- [ ] 🔔 Browser push notifications for due dates
- [ ] 📊 Monthly collection charts
- [ ] 🌐 Multi-school / multi-year support
- [ ] 🔐 LocalStorage persistence across sessions
- [ ] 📲 PWA (installable offline app)

---

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

```bash
# Fork the repo, then:
git checkout -b feature/amazing-feature
git commit -m "feat: add amazing feature"
git push origin feature/amazing-feature
# Open a Pull Request
```

---

## 📄 License

```
MIT License — feel free to use, modify, and distribute.
© 2026 FeeTrack · Built for Greenfield Public School
```

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:EA4335,50:9b6df5,100:5b72f0&height=120&section=footer&animation=fadeIn" width="100%"/>

**Built with ❤️ for educators · Powered by Google Gemini AI**

⭐ Star this repo if FeeTrack helped you!

[![GitHub stars](https://img.shields.io/github/stars/YOUR_USERNAME/feetrack?style=social)](https://github.com/YOUR_USERNAME/feetrack)
[![GitHub forks](https://img.shields.io/github/forks/YOUR_USERNAME/feetrack?style=social)](https://github.com/YOUR_USERNAME/feetrack)

</div>
