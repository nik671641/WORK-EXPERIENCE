# 💼 Work Experience


## Python Developer "RDG Smart Solutions"  
**April 2025 – July 2025**
### 🔹 Telegram Bot with AI & Bitrix24 Integration  
Developed an **intelligent Telegram bot** for automated customer interactions.  

**Key Features:**  
✅ **Surveying** – Dynamic questionnaires stored in PostgreSQL.  
✅ **AI Chat** – Uses GPT-4 to answer questions, provide links, send videos.  
✅ **Bitrix24 Integration** – Automatically creates & updates deals, saves chat history.  
✅ **Interactive Inline Buttons** – Quick access to manager, payment, support.  

**Technologies:**  
- 🖥 Backend: Python (Aiogram, FastAPI)  
- 🗄 Database: PostgreSQL  
- 🤖 AI: OpenAI API (GPT-4)  
- 📊 CRM: Bitrix24 REST API  

🚀 Automates customer interactions, reduces manager workload, boosts sales conversion.  
- [🔗 Github Link](https://github.com/nik671641/TG_AI_Bitrix24)  
- *And about 6–8 more such bots.*  

---

## Project: Telegram Sales Bot (n8n → Bitrix24/CRM)

**Summary:**

Developed an automated lead onboarding flow in n8n integrated with Telegram and Bitrix24 CRM. The bot greets users, collects contact details via inline forms, validates inputs, and creates leads/deals in the CRM. Integrated an AI agent with OpenAI for handling user questions and added webhooks to trigger external storytelling sequences.

**Main Features:**

- Telegram flow with inline keyboards, branching (message, callback_query, command/text)
- Phone/email validation using regex with friendly retry prompts
- Lead data stored in PostgreSQL with upsert logic by chat_id
- Bitrix24 CRM integration: search/create contact, auto-create deals
- AI Agent built with LangChain + OpenAI (gpt-3.5-turbo) and short-term memory
- Links to payment and private channel upon user request

**n8n Tools & Nodes:**

- Telegram Trigger / Telegram (messages, inline buttons, answerCallbackQuery)
- IF / Switch (branching by JSON fields and prefixes)
- Postgres (select/insert/update with upsert)
- HTTP Request (Bitrix24 REST API, external webhooks)\
- LangChain Agent + OpenAI Chat Model (gpt-3.5-turbo) + Memory Buffer
- Regex for phone/email validation

**Tech stack:**
- n8n, Telegram Bot API, PostgreSQL, Bitrix24 REST, LangChain, OpenAI, Webhooks, Regex

---

### 🌐 My Sites
- [nik671641/RIVO](https://github.com/nik671641/RIVO/tree/main)  
- [nik671641/Mabel-by-human](https://github.com/nik671641/Mabel-by-human)  

---


## Python Developer (Freelance)  
**April 2024 – May 2024**

### 🔹 Telegram-bot for Inventory Accounting (Warehouse)  
- Created to **manage tools in the warehouse**.  
- Documentation in Russian:  
  - [📄 Работа на складе – Google Docs](https://docs.google.com/document/d/1Ah76NOdSGl2Pxfr-4IQi5ROajsIEykVLfzZHtOnFVw8/edit?tab=t.0)  
  - [📄 Как пользоваться ботом – Google Docs](https://docs.google.com/document/d/17tWUT4O_M2_L8pT45vN7OtW6X0f7rebURc5YvP0I5f0/edit?tab=t.0#heading=h.lzl87hau6bb7)  
- ⚠️ Code is incomplete on GitHub.  

---


**December 2023 – April 2024**

### Selected Projects:

---

### 🔹 Scraping Maxima website  
- Parsing data of all products: **name, price, description, ID, parameters**.  
- Parsed data stored in **Excel document**.  
- [🔗 Github Link](https://github.com/nik671641/ParsMaxsima)

---

### 🔹 Parsing Binance website  
- Obtaining data such as: **date, opening, maximum, minimum, closing, volume**.  
- Data written into a **CSV file** for ML team and crypto prediction.  
- [🔗 Github Link](https://github.com/nik671641/ForecastBTC/tree/main/ParsPrice)

---

### 🔹 Telegram-bot Name Engraving  
- Created for **engraving a name on a board**.  
- User enters a name → Bot generates photos with different fonts → User selects a font → Bot generates an image with name inside a chosen figure.  
- [🔗 Github Link](https://github.com/nik671641/Name_engraving)

---

### 🔹 Telegram-bot for Notes  
- `/add [ Note Text ]` → Saves note in PostgreSQL database.  
- `/getall` → Retrieves and displays all saved notes.  
- [🔗 Github Link](https://github.com/nik671641/PyTeleBot_Notes)

---

### 🔹 Google API Gateway Development  
Project to work with **Google Docs via API**. Three endpoints:  

1. **First Endpoint** – Extract raw content, plain text, word count, symbol count, image count, link count, links.  
2. **Second Endpoint** – Create Google Docs (`?title=document_title`), returns `document_id`, `link`.  
3. **Third Endpoint** – Assign roles to users (e.g., `write`, `comment`, `read`).  

⚠️ *Code cannot be provided.*  

---

# 🎓 Education
**Courses VANAR** (October 2022 – July 2023)  
- Python Fundamentals (40 hours)  
- Python Web Development with Django (50 hours)  

---

# 🌍 Languages
- 🇷🇺 Russian – Native  
- 🇬🇧 English – Conversational  
- 🇧🇬 Bulgarian – Conversational  
