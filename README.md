![vscoed](https://img.shields.io/badge/make-6D00CC?style=for-the-badge&logo=make&logoColor=white) 
![vscoed](https://img.shields.io/badge/jira-0052CC?style=for-the-badge&logo=jira&logoColor=white) 
![vscoed](https://img.shields.io/badge/open_ai-00B5AD?style=for-the-badge&logo=openai&logoColor=white) 
![vscoed](https://img.shields.io/badge/manychat-000000?style=for-the-badge&logo=mezmo&logoColor=white) 
![vscoed](https://img.shields.io/badge/microsoft_forms-4285F4?style=for-the-badge&logo=googleforms&logoColor=white) 
![vscoed](https://img.shields.io/badge/microsoft_excel-34A853?style=for-the-badge&logo=googlesheets&logoColor=white) 
![vscoed](https://img.shields.io/badge/Outlook-0058A0?style=for-the-badge&logo=ru&logoColor=white) 


# 🎫 Ticket Automation Demo – Microsoft Forms + Excel + Make + Jira + Teams

This project demonstrates a complete **ticketing workflow** built with free tools and integrations, avoiding premium connectors.  
The system simulates a real IT ticketing process, from form submission to team collaboration, with a professional and verifiable flow.

---

## 🚀 Workflow Overview

1. **Ticket Submission (Microsoft Forms)**  
   - A user fills out a Microsoft Form with basic ticket details (name, email, type, priority, description).

2. **Data Storage (Excel Online via Power Platform)**  
   - Power Automate captures the form responses.  
   - Data is injected into an Excel file, acting as the central log.  
   - This file is also later updated with Jira ID and Teams channel link.

3. **Orchestration & Integration (Make)**  
   - Excel sends the data to Make.  
   - Make creates a **ticket in Jira**.  
   - Make creates a **dedicated Microsoft Teams channel** named after the ticket and posts a welcome message.  
   - Excel is updated with the **Jira issue ID**, the **link to Jira**, and the **Teams channel link**.  

4. **Notifications**  
   - An **email confirmation** is sent to the requester including:  
     - Jira ticket link  
     - Teams channel invitation link  
     - Jira project dashboard link (PM view)  

---

## 🧩 Tools & Technologies

- **Microsoft Forms** – Ticket entry  
- **Power Automate (Free tier)** – Transfers form responses into Excel  
- **Excel Online** – Central log for ticket data  
- **Make** – Integrations with Jira & Teams (free alternative to premium connectors)  
- **Jira Cloud (Free)** – Ticket management system  
- **Microsoft Teams** – Collaboration channel per ticket  
- **Email (Outlook)** – Confirmation and notifications  

---

## ⚡ Key Points

- **No premium connectors:** Jira integration was done with **Make** since Power Automate requires a premium license for Jira.  
- **Free ecosystem:** With Microsoft (Forms, Excel, Teams, Make, Jira), the workflow runs at zero cost.  
- **Alternative setup:** For a fully free solution, Microsoft services can be replaced with Google Workspace (Google Forms, Google Sheets, Google Chat/Slack).  

---

## 📊 Demo Flow

- User submits a request in **Microsoft Forms**  
- Data flows into **Excel Online** via **Power Automate**  
- **Make** creates the Jira ticket, Teams channel, and logs everything  
- Excel is updated with ticket metadata (Jira ID, Jira link, Teams link)  
- Requester receives a **formal email** with all links and confirmation  
- PMs can view the consolidated **Jira dashboard** for progress tracking  

---

## ✅ Benefits

- End-to-end automation with no human intervention  
- Simulates a **real IT support workflow**  
- 100% based on **free or freemium tools**  
- Extensible to other platforms (Slack, Google Chat, etc.)  

---

## ✅ Status

**Live demo available.**  
Tested on social media channels and integrated with Power Automate for confirmation and logging.

---

## 📬 Contact

For demos or collaboration:  
📧 [hydrai.connections@gmail.com](mailto:hydrai.connections@gmail.com)

---

