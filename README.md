# 🎮 Gamer Notification System

## 📌 Overview
This project is an automated workflow built using n8n that fetches the latest gaming news and sends notifications to Telegram.

## ⚙️ Features
- ⏰ Automatic execution every hour
- 🌐 Fetches real-time gaming news
- 🧹 Extracts and processes relevant data
- 🤖 AI-based classification (optional)
- 📲 Sends alerts to Telegram

## 🔄 Workflow
Cron → Fetch News → Extract → Split → Process → AI → Filter → Telegram


## 🚀 How to Run
1. Install n8n locally
2. Import `workflow.json`
3. Add credentials:
   - Telegram Bot Token
   - (Optional) OpenAI API Key
4. Execute workflow

## ⚠️ Note
AI node may require API credits. The system also works without AI.

## 🧠 Technologies Used
- n8n
- Telegram API
- OpenAI API (optional)

## 👨‍💻 Author
Vinay Ramaj
