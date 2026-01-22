[readme.md](https://github.com/user-attachments/files/24797928/simple_readme.md)
# Smart Event Scheduler 📅

> AI-powered agent built with Microsoft Copilot Studio that automatically extracts events from photos, PDFs, and links, then schedules them in your calendar.

[![Microsoft Copilot](https://img.shields.io/badge/Built%20with-Microsoft%20Copilot%20Studio-blue)](https://copilotstudio.microsoft.com)
[![Azure AI](https://img.shields.io/badge/Powered%20by-Azure%20AI-0078D4)](https://azure.microsoft.com)

---

## 🎯 What It Does

- 📷 **Upload a photo** of your schedule → Events automatically added to calendar
- 📄 **Share a PDF** invitation → All details extracted and scheduled
- 🔗 **Paste an event link** → Information fetched and calendar entry created
- ⏰ **Smart reminders** set automatically for events and to-dos

## 📊 Results

| Metric | Achievement |
|--------|-------------|
| Time Saved | **70%** reduction in manual entry |
| Accuracy | **92%** event extraction rate |
| User Effort | **2.1** questions per event |

---

## 🚀 Quick Setup

### 1. Create Agent in Copilot Studio
1. Go to [copilotstudio.microsoft.com](https://copilotstudio.microsoft.com)
2. Create new agent: "Smart Event Scheduler"
3. Copy instructions from `system-prompt.txt`
4. Enable: Web search, File upload, Microsoft 365 connector

### 2. Test with Sample Data
Use the files in `test-data/` folder to test the agent

### 3. Publish
Publish the agent and start using it!

---

## 💻 Technology Stack

- **Platform:** Microsoft Copilot Studio
- **AI Model:** Azure OpenAI (GPT-4)
- **OCR:** Azure Computer Vision
- **Calendar:** Microsoft Graph API

---

## 📁 Repository Contents

```
├── system-prompt.txt          # Agent instructions (copy this to Copilot Studio)
├── test-data/                 # 6 sample documents for testing
├── screenshots/               # Demo images
└── PROJECT_DOCUMENTATION.pdf  # Full project report
```

---

## 🧪 Testing

Upload any test file from `test-data/` to your agent:
- `conference-flyer.png` - Multi-day event
- `email-invitation.txt` - Event with to-dos
- `meeting-schedule.png` - Recurring meetings
- `board-meeting.pdf` - Formal agenda
- `networking-event.png` - Simple event
- `dentist-reminder.txt` - Basic appointment

---

## 📄 Full Documentation

See [PROJECT_DOCUMENTATION.pdf](PROJECT_DOCUMENTATION.pdf) for complete project details including:
- Problem statement
- System architecture
- Algorithm details
- Results & analysis
- Future scope

---

## 👨‍💻 Author

**[Anuska_Sarkar]**  
[IITM] - [DATA_SCIENCE_AND_APPLICATIONS]  
Email: [hbee8559@gmail.com]

---

## 🔗 Links

- [Microsoft Copilot Studio](https://copilotstudio.microsoft.com)
- [Project Documentation](PROJECT_DOCUMENTATION.pdf)
- [Azure AI Services](https://azure.microsoft.com/en-us/products/ai-services)

---

**⭐ Star this repo if you find it helpful!**
