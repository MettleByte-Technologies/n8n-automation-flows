# n8n Automation Flows

This repository contains a set of **n8n workflows** designed for automation across multiple use cases such as WhatsApp chatbot, LinkedIn profile webpage generation, email-based lead management, and project management.

## 📂 Workflows Included

### 1. WhatsApp Chatbot Flow
- Platform: WhatsApp (via n8n + Bubble.io Database)
- Functionality:
  - Handles user queries from WhatsApp.
  - Checks against Bubble.io database.
  - Responds dynamically with stored data.

**File:** `Whatsapp Chatbot flow.json`

---

### 2. LinkedIn Profile Webpage Flow
- Input: LinkedIn profile link.
- Functionality:
  - Scrapes LinkedIn profile details (via integration/API).
  - Generates a basic personal webpage.
  - Outputs structured data for UI rendering.

**File:** `AI Automation for Personalization of webpages.json`

---

### 3. Email Lead Closer Flow
- Trigger: Incoming email (watched via Gmail/IMAP).
- Functionality:
  - Checks if email is a lead.
  - Sends automated response to lead.
  - Stores lead details in Google Sheets.

**File:** `Lead Close Automation.json`

---

### 4. Automated Order & Provider Management
- Platform: n8n (Tally, Notion, Stripe, Email, SMS, Shipping API)
- Functionality:
  - Handles new customer orders end-to-end.
  - Creates order records and invoices.
  - Allocates providers and manages confirmations.
  - Sends shipping and tracking updates.
  - Notifies clients and providers at every stage.

**File:** `Automated Order & Provider Management.json`

---

### 5. Automated Resume Customization & Job Matching
- Platform: n8n (Google Docs, Apify, OpenAI, Google Sheets)
- Functionality:
  - Automatically fetches resume from Google Docs.
  - Uses Apify to scrape job listings from a provided search URL.
  - Analyzes job descriptions using OpenAI to check relevance with the candidate’s resume.
  - Customizes the resume based on the specific job requirements using AI.
  - Saves the newly customized resume back to Google Docs.
  - Logs each customized resume entry (job title, company, link, and document URL) in Google Sheets.

**File:** `Automatically fetches resume from Google Docs..json`



## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/MettleByte-Technologies/n8n-automation-flows.git

2. Import any JSON workflow into n8n:
    - Open n8n Editor → Import from File → choose the JSON file.

3. Configure credentials for:
    - Bubble.io Database
    - WhatsApp API (Twilio/Meta Business API)
    - Google Sheets API
    - Gmail/IMAP
    - OpenAI API
    - Slack API
    - Notion API

## 📌 Notes
    - These workflows are templates – update credentials and node settings as per your environment.

## 📝 License

This project is [MIT](https://github.com/MettleByte-Technologies/n8n-automation-flows/blob/main/LICENSE) licensed.

Copyright © 2025 [MettleByte-Technologies](https://github.com/MettleByte-Technologies).<br />
