# 🚀 Job Filling Agent: AI-Powered Autonomous Job Applier

![Build Status](https://img.shields.io/badge/build-success-brightgreen)
![Python Version](https://img.shields.io/badge/python-3.10%2B-blue)
![License](https://img.shields.io/badge/license-AGPLv3-lightgrey)
![Status](https://img.shields.io/badge/status-Active-brightgreen)

---

> "An AI agent that automates job applications, personalizes resumes, answers questions, and helps you land interviews — All while you sleep!" 😎

---

## 📍 About This Project

**Job Filling Agent** is a fully autonomous AI bot that applies for jobs on LinkedIn. It personalizes applications using OpenAI, configures job filters based on user preferences, automates resume selection, answers company questions, and saves all application histories with professional logging and Excel tracking.

With this, applying to 100+ jobs per hour becomes effortless!

---

## 📑 Table of Contents
- [Demo Video](#-demo-video)
- [Features](#-features)
- [How to Install](#-how-to-install)
- [How to Configure](#-how-to-configure)
- [Tech Stack](#-tech-stack)
- [License](#-license)
- [Author](#-author)
- [Socials](#-socials)
- [Community Support](#-community-support)

---

## 🎥 Demo Video
[![Watch the Demo](https://img.youtube.com/vi/gMbB1fWZDHw/0.jpg)](https://youtu.be/gMbB1fWZDHw)

▶️ [Click here to watch the live demo](https://youtu.be/gMbB1fWZDHw)

---

## ✨ Features

- 🧠 **AI-Powered Resume Customization**
- 🔍 **Auto Job Search and Filter Application**
- 📝 **Automatic Form Filling and Question Answering**
- 📂 **Job Application Logs and Tracking**
- 🛡️ **Human-like Behavior with Stealth Mode**
- 📈 **Mass Job Application Automation (100+ Jobs/Hour)**
- 🖥️ **Optional Local Web UI for Viewing History**

---

## ⚙️ How to Install

```bash
# 1. Clone the Repository
$ git clone https://github.com/UDDITwork/job-filling-agent.git
$ cd job-filling-agent

# 2. Install Dependencies
$ pip install undetected-chromedriver pyautogui setuptools openai flask-cors flask

# 3. Install Google Chrome (latest version)
# 4. (Optional) Setup Chromedriver if stealth mode disabled

# 5. Ready to Configure!
```

---

## 🔧 How to Configure

- `config/personals.py` ➔ Personal information (name, address, etc.)
- `config/questions.py` ➔ Answer templates for applications
- `config/search.py` ➔ Job search filters
- `config/secrets.py` ➔ LinkedIn credentials and OpenAI key (optional)
- `config/settings.py` ➔ Behavior settings (stealth mode, background running, etc.)

🛠️ Then run:
```bash
$ python runAiBot.py
```

🌐 To manage history via web UI:
```bash
$ python app.py
# Open http://localhost:5000
```

---

## 🧰 Tech Stack

| Technology | Description |
|:-----------|:------------|
| ![Python](https://img.shields.io/badge/Python-3.10+-blue) | Core Programming Language |
| Selenium / Undetected Chromedriver | Browser Automation |
| Flask | Web Application for History Tracking |
| OpenAI | Resume and Cover Letter Generation |
| Excel / Pandas | Data Management and Logging |

---

## 📜 License

Distributed under the AGPLv3 License.  
See [LICENSE](LICENSE) for more information.

---

## 👨‍💻 Author

Developed with passion and precision by **Mr. Uddit**.

- [GitHub: UDDITwork](https://github.com/UDDITwork)
- [LinkedIn: lorduddit-](https://linkedin.com/in/lorduddit-)
- [Portfolio Website](https://udditwork.github.io/PORTFOLIO-Uddit/)
- [YouTube Channel](https://www.youtube.com/@uddit748)
- [ResearchGate Profile](https://www.researchgate.net/profile/Uddit)

---

## 🔗 Socials

[![GitHub](https://img.shields.io/badge/GitHub-UDDITwork-black?logo=github)](https://github.com/UDDITwork)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-LordUddit-blue?logo=linkedin)](https://linkedin.com/in/lorduddit-)
[![Portfolio](https://img.shields.io/badge/Portfolio-Udditwork-green?logo=githubpages)](https://udditwork.github.io/PORTFOLIO-Uddit/)
[![YouTube](https://img.shields.io/badge/YouTube-Uddit748-red?logo=youtube)](https://www.youtube.com/@uddit748)
[![ResearchGate](https://img.shields.io/badge/ResearchGate-Uddit-teal?logo=researchgate)](https://www.researchgate.net/profile/Uddit)

---

## 🙌 Community Support

- 📚 For support, open a discussion at: [GitHub Discussions](https://github.com/UDDITwork/job-filling-agent/discussions)
- 📩 For personal queries, feel free to connect via LinkedIn.

---

> _"Empowering Job Seekers through Automation and Intelligence — by Mr. Uddit."_ 🚀
