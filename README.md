# AI-Driven Smart Inventory Monitoring Agent (n8n + LLM Automation)

An AI-powered inventory monitoring system that automatically detects low stock levels, updates inventory records in real time, and triggers intelligent alerts for supply chain teams.

The system integrates **workflow automation, LLM agents, and voice notifications** to enable proactive inventory management and prevent stockouts.

---

## System Architecture

This system is built using an **event-driven automation pipeline** powered by n8n.

Workflow process:

1. **Google Sheets Trigger**
   - Detects new stock transactions in real time.

2. **Stock Processing Engine**
   - JavaScript node calculates updated inventory values.
   - Updates master inventory sheet automatically.

3. **Low Stock Detection**
   - Checks whether stock falls below the defined threshold.

4. **AI Agent Analysis**
   - LLM agent analyzes inventory data and generates contextual alerts.

5. **Notification System**
   - Sends Telegram alerts to operations teams.
   - Generates voice notifications using Gemini Text-to-Speech.

---

## Key Features

- Real-time inventory monitoring  
- Automated stock calculations and updates  
- Intelligent low-stock detection  
- AI-powered decision support using LLM agents  
- Instant Telegram notifications  
- Voice alerts generated using Gemini Text-to-Speech  
- Event-driven automation workflow using n8n  

---

## Tech Stack

- **n8n** – Workflow automation platform  
- **Claude Sonnet (Anthropic)** – AI reasoning agent  
- **Google Sheets API** – Inventory data source  
- **Telegram Bot API** – Alert notifications  
- **Gemini Text-to-Speech** – Voice alert generation  
- **JavaScript** – Inventory processing logic  
- **HTTP APIs** – External integrations  

---

## Workflow Overview

1. Warehouse staff logs inventory transactions in **Google Sheets**
2. The **n8n workflow detects updates instantly**
3. Inventory values are recalculated automatically
4. The system checks if stock falls below threshold
5. AI agent analyzes the situation and generates alerts
6. Operations team receives notifications via **Telegram and voice alerts**

---

## Example Alert

🚨 **LOW STOCK ALERT**

Product: Refined Sunflower Oil  
Location: Trichy Depot  
Current Stock: 7 Units  

Recommendation:  
Reorder immediately to avoid stockout.  
Estimated supplier lead time: 48 hours.

---

## Use Cases

- Warehouse inventory monitoring  
- Supply chain automation  
- Retail stock management  
- Manufacturing inventory tracking  
- Smart procurement systems  

---

## Future Improvements

- ERP integration  
- Demand forecasting using ML models  
- Automatic purchase order generation  
- Multi-warehouse inventory optimization  
- Inventory analytics dashboards  

---

## Author

**Nithin V**

AI & Machine Learning Enthusiast focused on building intelligent systems combining **automation, AI agents, and real-world decision support**.

GitHub:  
https://github.com/Nithinah

---

## License

This project is licensed under the **MIT License**.
