# community-medicine-rescue-automation
A real-time AI-powered n8n workflow that connects people in need of emergency medicines with nearby pharmacies, NGOs, and volunteers through WhatsApp automation.

## Overview

Every day, many people struggle to find urgent medicines, while others (like NGOs or pharmacies) have extra stock available.  
This automation solves that problem by using **AI + automation** to bridge the gap — instantly and intelligently.

**Built using:**  
- [n8n](https://n8n.io/) — workflow automation  
- [Gemini AI](https://ai.google.dev/) — message parsing and understanding  
- [Google Sheets](https://workspace.google.com/products/sheets/) — lightweight database  
- [WhatsApp Cloud API](https://developers.facebook.com/docs/whatsapp) — real-time messaging

---

## What This Workflow Does

1. **Receives WhatsApp messages** from people requesting medicines.  
2. **Gemini AI** extracts details: medicine name, quantity, urgency, and location.  
3. **Google Sheets** is searched for nearby pharmacies/NGOs that have the medicine.  
4. **WhatsApp Cloud API** sends alerts to potential volunteers or pharmacies.  
5. The **first responder** to reply “Available” is assigned.  
6. The **requester receives confirmation** and contact info for pickup or delivery.

---

## Tech Stack

| Tool | Purpose |
|------|----------|
| n8n | Automation engine |
| Gemini AI | Text analysis & parsing |
| WhatsApp Cloud API | Messaging channel |
| Google Sheets | Data storage |
| JavaScript | Logic nodes in n8n |

---
