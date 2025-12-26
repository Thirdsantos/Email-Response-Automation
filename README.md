# n8n Workflow: Automated Inquiry Management

## Overview
This n8n workflow automates the handling of inquiries, providing real-time logging, spam filtering, and AI-generated responses. It integrates **Supabase**, **Gemini LLM**, and email automation to streamline communication and improve efficiency.

---

## Features

- **Automated Logging:** Inquiries are automatically stored in a Supabase database for record-keeping and analysis.
- **Spam Filtering:** Prevents repeated inquiries from the same sender within 5 minutes, ensuring only valid inquiries are processed.
- **Webhook Integration:** Extracts relevant information from incoming webhooks for processing.
- **AI-Powered Email Generation:** Uses Gemini AI to compose emails based on inquiry content.
- **HTML & CSS Formatting:** Generated emails are styled with inline CSS for professional presentation.
- **Real-Time Automation:** Ensures timely responses and consistent workflow execution.

---

## Workflow Steps

1. **Webhook Trigger**
   - Receives incoming inquiries.
   
2. **Spam Check**
   - Checks if the sender has submitted an inquiry within the last 5 minutes.
   - Blocks the inquiry if it's flagged as spam.

3. **Database Logging**
   - Stores inquiry data in Supabase for tracking and analytics.

4. **Information Extraction**
   - Parses the webhook content to extract key information for response.

5. **AI Response Generation**
   - Sends the extracted information to Gemini LLM.
   - Generates a contextual and accurate email reply.

6. **Email Formatting**
   - Applies HTML and inline CSS for professional-looking emails.

7. **Email Dispatch**
   - Sends the formatted response to the sender.

---

## Technology Stack

- **n8n** – Workflow automation platform  
- **Supabase** – Database for logging inquiries  
- **Gemini LLM** – AI model for generating responses  
- **HTML & Inline CSS** – Email formatting  
- **Webhook Integration** – For real-time inquiry reception  

---

## Benefits

- Automates repetitive tasks and reduces manual intervention  
- Ensures professional and consistent email responses  
- Protects against spam and duplicate inquiries  
- Maintains a full record of inquiries for analytics  
- Demonstrates integration of AI with workflow automation  

---

## Repository

[View n8n Workflow Repository](Your n8n repository link here)

---

