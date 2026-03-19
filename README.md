# Automated Email Outreach System (n8n) ✨

## Overview

This project demonstrates an advanced automated email outreach workflow built using n8n. It integrates Google Sheets, Google Docs, and Gmail to send personalized emails automatically, with added data validation and status tracking.

The system reduces manual effort, improves reliability, and enables scalable outreach for freelancers, startups, and small businesses.

---

## Workflow Architecture 

Google Sheets → Google Docs → n8n → IF Validation → Gmail → Update Status

- Google Sheets: Stores client details (Name, Email, Sent status)  
- Google Docs: Contains the editable email template  
- n8n Workflow: Processes data and personalizes content  
- IF Condition: Validates input data before sending  
- Gmail: Sends personalized emails  
- Update Row: Tracks email status  

---

## How It Works

1. A new row is added to Google Sheets  
2. The workflow is triggered automatically  
3. Email template is fetched from Google Docs  
4. Client details are mapped and injected into the template  
5. Input data is validated:
   - Name must not be empty  
   - Email must not be empty  
   - Email must be in valid format  
6. Based on validation:
   - Valid → Email sent → Status updated to YES  
   - Invalid → Skipped → Status updated to WAITING  

---

## Features

- Automated email sending on new data entry  
- Input validation using IF conditions  
- Status tracking (Sent / Waiting)  
- Dynamic template editing via Google Docs  
- Personalized email content using placeholders  
- HTML email formatting  
- Scalable workflow for bulk outreach  

---

<img width="1521" height="646" alt="image" src="https://github.com/user-attachments/assets/1e8514ad-95a3-480c-a780-11ac96ae5635" />

## Use Cases

- Freelancers automating cold outreach  
- Agencies running email campaigns  
- Startups managing lead communication  
- Small businesses scaling customer engagement  
