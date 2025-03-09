# Automate Your Emails Using Python - Build A Payment Reminder & Schedule Your Scripts Online (FREE)

Are you still manually sending emails to your customers and clients? This project helps you send automated reminders effortlessly using Python. You can schedule your emails and deploy your script online for free, eliminating the need for expensive email automation tools.

## Features
- Automate email reminders with Python.
- Schedule and deploy scripts online.
- Free alternative to paid email automation services.

## Architecture
![Architecture](./Architecture.png?raw=true "Architecture")

## Requirements
Install the dependencies with pip:
```bash
pip install pandas python-dotenv
```

[FOR WINDOWS] Install the Deta CLI by opening PowerShell and entering:
```bash
  iwr https://get.deta.dev/cli.ps1 -useb | iex
```

## Setting Up Google Sheets
Use the **Google Sheet** template for invoice data tracking: ⤵ <br/>
[Google Sheets Template](https://pythonandvba.com/sheets-invoice-data) <br/>
![Google Sheets](/google_sheets_invoice_data.png?raw=true "Google Sheets")

## Deployment
**Official Documentation:** [Deta Deployment Guide](https://docs.deta.sh/docs/micros/getting_started) <br/>

### Steps for Deployment (Windows)
1) Login via the Deta CLI:
```bash
  deta login
```
2) Create a new microservice (only once):
```bash
  deta new --python email_automation
```
3) Upload environment variables:
```bash
  deta update -e .env
```
4) Deploy your app:
```bash
  deta deploy
```
5) Set the cron job for scheduling (e.g., run every minute):
```bash
  deta cron set "1 minute"
```

## Environment Variables
To run this project, add the following variables to your `.env` file:
```bash
EMAIL=<your_email>
PASSWORD=<your_email_password>
```

## Future Enhancements
- Integrate WhatsApp and LinkedIn automation.
- Add AI-based categorization for email responses.
- Implement logging and analytics for better tracking.

## About Me
This project was developed by **Chandu Pichika**. I specialize in **MERN Stack Development** and automation solutions. Feel free to explore my other projects:

### **Other Projects**
- **[YouTube Video Downloader](https://github.com/Pichikachandu/youtube-downloader)** – A tool to download videos from YouTube playlists and channels.
- **[Health & Wellness Chatbot](https://github.com/Pichikachandu/health-chatbot)** – AI-based chatbot for health recommendations.
- **[Classroom Management System]– A full-stack system for teachers and students.

### **Connect with Me**
- 🌐 **Portfolio:** [My Portfolio](https://pichikachandu.netlify.app/)
- 💼 **LinkedIn:** [Chandu Pichika](https://www.linkedin.com/in/Pichika-chandu/)
- 📺 **GitHub:** [GitHub Profile](https://github.com/Pichikachandu)
- 📧 **Email:** chandupichika0@gmail.com

## Support My Work
If you found this project useful, consider supporting me by **starring the repo on GitHub** or buying me a coffee! ☕

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/your-profile)

---
Got feedback or suggestions? Feel free to reach out to me via LinkedIn or email. 🚀

