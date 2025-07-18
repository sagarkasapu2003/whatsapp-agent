WhatsApp AI Agent – n8n Workflow

This repository contains an **n8n workflow** that connects a WhatsApp bot with **Google Gemini AI** for intelligent responses. It also integrates with **Google Drive** and uses **Simple Memory** (context memory) to maintain conversation flow.

---

## Features

- Responds to WhatsApp messages using **Google Gemini AI**
-  Maintains conversation context using **Simple Memory**
- Uploads and retrieves files from **Google Drive**
-  Can send automated email responses (optional)
-  Easily extendable for CRM, scheduling, knowledge base, etc.

---

## 🛠️ Prerequisites

You must have:

- [n8n](https://n8n.io/) installed (Cloud or Docker/self-hosted)
- A [Google Cloud API key](https://console.cloud.google.com/) with access to Gemini/Gemini Pro
- A WhatsApp Business API provider (e.g., [Twilio](https://www.twilio.com/whatsapp) or Meta)
- Google Drive API credentials (OAuth2 or Service Account)

---

##  How to Import the Workflow

1. Open your n8n editor (e.g., `http://localhost:5678`)
2. Click the menu (☰) → **Import**
3. Choose `whatsapp_ai_agent.json` from this repo
4. Configure the credentials:
   - Gemini (Google PaLM/Gemini API)
   - WhatsApp Webhook (via HTTP trigger or API)
   - Google Drive
5. Save and activate the workflow

---

##  Workflow Overview

"# whatsapp-agent" 
