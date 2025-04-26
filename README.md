# Job Filling Agent (AI Powered) 🦿

This is a web scraping and AI automation bot that automates the process of job applications on LinkedIn. It searches for jobs relevant to you, answers all application questions, customizes your resume based on the collected job information (skills, description, company details), and applies to the job. It can apply to 100+ jobs in under 1 hour.

---

## ✨ Content
- [Introduction](#job-filling-agent-ai-powered-)
- [Demo Video](#demo-video)
- [Install](#⚙️-how-to-install)
- [Configure](#-how-to-configure)
- [Contributor Guidelines](#-contributor-guidelines)
- [Features](#-feature-list)
- [Updates](#🗓️-major-updates-history)
- [Disclaimer](#📜-disclaimer)
- [Terms and Conditions](#🏦-terms-and-conditions)
- [License](#⚖️-license)
- [Socials](#🐧-socials)
- [Community Support](#👌-community-support)

---

## 🎥 Demo Video
> [Demo Video](https://www.youtube.com/@uddit748)

[![Watch the demo](https://img.youtube.com/vi/dQw4w9WgXcQ/0.jpg)](https://www.youtube.com/@uddit748)

Click on the image above or use this link to watch how it works!

---

## ⚙️ How to Install
1. Install [Python 3.10+](https://www.python.org/downloads/).
2. Install necessary packages:
```bash
pip install undetected-chromedriver pyautogui setuptools openai flask-cors flask
```
3. Install [Google Chrome](https://www.google.com/chrome/).
4. Clone the repo:
```bash
git clone https://github.com/UDDITwork/job-filling-agent.git
cd job-filling-agent
```
5. Set up Chrome Driver if needed or run `windows-setup.bat` inside `/setup/`.
6. Follow configuration steps below.

---

## 🔧 How to Configure
- Edit `/config/personals.py` to set your personal information.
- Edit `/config/questions.py` for predefined answers.
- Edit `/config/search.py` to set job search filters.
- Edit `/config/secrets.py` for LinkedIn credentials and OpenAI key.
- Edit `/config/settings.py` for bot behavior.
- Place your resume at the configured location.
- Run the bot:
```bash
python runAiBot.py
```
- To manage history, run UI:
```bash
python app.py
```
Open `http://localhost:5000` in your browser.

---

## 👨‍💻 Contributor Guidelines
- Only pull requests to `community-version` are accepted.
- Follow code styling, function typing, and documentation norms.
- Validate new config variables properly.
- Attestation format is required inside your code commits.

---

## 🌟 Feature List
- Auto login
- Auto search, easy apply
- Customizable job filters
- Skill extraction (in development)
- Humanized mouse and click behavior
- Save applied jobs info in Excel
- Error handling and retries
- Headless browser support
- Future: ChatGPT powered auto-resume generator (planned)

---

## 🗓️ Major Updates History
- Latest patches for LinkedIn updates
- OpenAI API integration frameworks added
- Skill extraction from job descriptions implemented

---

## 📜 Disclaimer
**This tool is for educational purposes only.**
Please ensure compliance with LinkedIn's terms of service. All usage is at your own risk.

---

## 🏦 Terms and Conditions
- Review LinkedIn scraping policies.
- No warranties or guarantees provided.
- Full responsibility of use lies with the user.

---

## ⚖️ License
Distributed under the GNU Affero GPLv3 License. See [LICENSE](LICENSE) for more information.

---

## 🐧 Socials
- **GitHub**: [UDDITwork](https://github.com/UDDITwork)
- **LinkedIn**: [lorduddit-](https://linkedin.com/in/lorduddit-)
- **Portfolio**: [PORTFOLIO-Uddit](https://udditwork.github.io/PORTFOLIO-Uddit/)
- **YouTube**: [@uddit748](https://www.youtube.com/@uddit748)
- **ResearchGate**: [ResearchGate Profile](https://www.researchgate.net/profile/Uddit)


## 👌 Community Support
- For queries and discussions, open an issue on [GitHub Discussions](https://github.com/UDDITwork/job-filling-agent/discussions).


---

_Developed and customized by Mr. Uddit, inspired by modern AI automation challenges._
