# data-ai-portfolio
# 🧠 Personal AI Assistant Workflow – Email, Calendar & Task Management (n8n)

This project is a multi-functional AI automation built using [n8n](https://n8n.io/) to act as a **personal productivity assistant**. It integrates key tools like Gmail, Google Calendar, OpenAI, and Telegram to help you stay focused, avoid overwhelm, and move your life and business forward — without getting lost in noise.

## 🚀 Features

### 📬 1. Email Management
- Fetches your latest emails
- Filters out promotional messages
- Summarizes the remaining emails with:
  - **Sender**
  - **Subject**
  - **Message date**
  - **Short summary** of the email content

### 📅 2. Calendar Management
- Retrieves upcoming calendar events
- Focuses only on relevant timeframes (e.g. today's events)
- Summarizes them clearly and sends a digest

### ✅ 3. Task Management
- Connects to a task database (via Baserow)
- Retrieves ongoing tasks
- Summarizes workload/project statuses

### 📇 4. Contact Info Retrieval
- Accesses your saved contacts
- Provides emails or phone numbers on demand

---

## 🛠 Tech Stack

| Tool            | Purpose                                 |
|-----------------|------------------------------------------|
| 🧠 OpenAI API   | Summarization + natural language responses |
| 📬 Gmail API    | Email data retrieval                     |
| 📅 Google Calendar | Event summaries                        |
| 📋 Baserow      | Task & contact database (Airtable alternative) |
| 🗣️ OpenAI STT   | Speech-to-text for voice interaction     |
| 💬 Telegram Bot | Interface for interaction and notifications |
| ⚙️ n8n          | Workflow orchestration and automation engine |

---

## 🎯 Why This Matters

This workflow saves time, reduces noise, and helps you act on **only what truly matters**:

- ❌ No more digging through cluttered inboxes
- ✅ Stay updated on meetings and tasks with minimal effort
- 🔔 Get only the summaries you need, when you need them
- ⚡ Helps fight procrastination and decision fatigue

It acts like your executive assistant, powered by AI.

---

## 🖼️ Screenshots

| Email Summary Flow | Telegram Output |
|--------------------|-----------------|
| ![flow](./screenshots/email-summary.png) | ![telegram](./screenshots/telegram-demo.png) |

---

## 📂 Files in This Folder

- `workflow.json` – Exported n8n workflow
- `screenshots/` – Visuals of the workflow and outputs

---

## 🔗 Demo / Deployment

Want to see a live version? Contact me.
---

## 🙋‍♂️ About Me

Hi, I'm **Arsh Singh**, a data analyst and AI automation builder focused on streamlining business processes and life admin with intelligent tools.  
🔗 [LinkedIn](www.linkedin.com/in/arshsingh291) • ✉️ arshaurora.ai@gmail.com
