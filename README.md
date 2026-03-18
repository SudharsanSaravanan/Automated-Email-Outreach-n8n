# Automated Email Outreach (n8n)

## Overview

This project demonstrates an automated email outreach workflow built using n8n. It integrates Google Sheets, Google Docs, and Gmail to send personalized emails automatically based on new data entries.

The system is designed to reduce manual effort, ensure consistency in communication, and enable scalable outreach for businesses.

---

## Workflow Architecture 

Google Sheets → Google Docs → n8n → Gmail

- **Google Sheets**: Stores client details such as Name and Email  
- **Google Docs**: Contains the email template
- **n8n Workflow**: Processes data, injects values into the template, and prepares the message  
- **Gmail**: Sends personalized emails automatically  

---

## How It Works

1. A new row is added to Google Sheets  
2. The workflow is triggered automatically  
3. Email template is fetched from Google Docs  
4. Client details are mapped and injected into the template  
5. The final personalized email is sent via Gmail  

---

## Features

- Automated email sending on new data entry  
- Dynamic template editing via Google Docs  
- Personalized email content using placeholders  
- HTML email formatting with responsive design  
- Scalable workflow suitable for bulk outreach  

---

## Use Cases

- Small businesses managing cold outreach  
- Startups automating lead communication  
- Agencies maintaining consistent email campaigns  

---
