# 🟦 B2B Leadgenerierung — Marketing Automation Suite

This workflow automates the entire B2B lead generation process — from searching for companies to creating personalized e-mails and sending them automatically.

---

## ⚙️ Purpose
To streamline and scale B2B client acquisition by combining **data scraping, AI-based writing, and automated outreach** in one unified n8n system.

---

## 🧩 Workflow Structure

| Module | Description | Technologies |
|---------|-------------|---------------|
| 🔹 Google Maps Lead Finder | Finds companies by type or name and stores them in Google Sheets | RapidAPI, Google Sheets |
| 🔹 Apollo.io Scraper | Extracts leads and business data from Apollo.io | Apify, HTTP Requests |
| 🔹 Website Analyzer | Analyzes websites and extracts key information | Firecrawl, Perplexity |
| 🔹 AI Email Writer | Generates personalized outreach e-mails | OpenRouter (Gemini), LangChain |
| 🔹 Outlook Sender | Sends e-mails automatically and updates status | Microsoft Outlook API |

---

## 🧠 Logic Overview
1. **Form Input** → User enters company type and region.  
2. **Data Collection** → RapidAPI and Apify collect company info and contacts.  
3. **Website Analysis** → Firecrawl scrapes websites, Perplexity summarizes content.  
4. **AI Writing** → LLM (Gemini/OpenRouter) generates tailored e-mail text.  
5. **Automated Sending** → Outlook sends messages and marks them as sent in Google Sheets.  

---

## 📊 Result
✅ Up to **300 leads per day** collected and contacted automatically.  
✅ Personalized messages increase engagement and response rates.  
✅ Manual marketing workload reduced by **80–90%**.  

---

## 🧰 Tech Stack
- **n8n** (core workflow engine)  
- **RapidAPI**, **Apify**, **Firecrawl**, **Perplexity**, **OpenRouter**  
- **Google Sheets**, **Microsoft Outlook API**

---

## 📄 Files
- `B2B_Leadgenerierung.json` – complete workflow  
- `README.md` – project overview (this file)

---

© 2025 — Art | Automation Engineer & AI Workflow Architect
