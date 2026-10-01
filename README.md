# 📧 Daily Email Triage and Digest Agent

An AI-powered email automation workflow built using **n8n, Gmail, Google Gemini, and Telegram**.  
The system automatically analyzes emails, categorizes them based on priority, and sends a daily summary to the user through Telegram.

## 🎯 Goal

The main goal of this project is to reduce the time spent manually checking emails by automatically identifying important information and providing a simple daily digest.

## 🚀 Objectives

- Automatically collect emails from Gmail.
- Analyze email content using AI.
- Categorize emails into:
  - 🔴 Urgent
  - 🟡 Important
  - 🟢 Normal
- Generate a concise summary of the emails.
- Send the final summary to the user through Telegram.

## ⚙️ Technologies Used

- **n8n** – Workflow automation
- **Gmail** – Email collection
- **AI Agent** – Email analysis and processing
- **Google Gemini** – AI language model
- **Telegram** – Sends the final daily digest

## 🔄 Workflow

```text
Schedule Trigger
       ↓
     Gmail
       ↓
   Aggregate
       ↓
    AI Agent
       ↓
 Google Gemini
       ↓
    Telegram
