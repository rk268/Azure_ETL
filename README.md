# ☁️ Rupak_Kulkarni_Azure_Weather Streaming App Project 🌩️

![Architecture Diagram](https://drive.google.com/uc?export=view&id=1bcpjSg2OHZxKy6bsZN5PvUNvUSS_GaGv)

Welcome to the **Azure Weather Streaming** project! This real-time data pipeline fetches live weather data through APIs and streams it through Azure services for real-time analytics, visualization, and alerts. 🌦️📊⚡

---

## 🔧 Tech Stack

- **🔄 Azure Event Hub** – Ingests real-time weather data from an API  
- **🧠 Azure Databricks** – Pre-processes and transforms the data  
- **⚡ Azure Functions** – Triggers lightweight operations  
- **📡 Azure Event Stream** – Streams events to downstream systems  
- **🔍 Kusto DB (Eventhouse)** – Stores and queries structured streaming data  
- **📈 Power BI** – Dashboards for visual insights and metrics  
- **📢 Data Activator** – Sends automated alerts and notifications  
- **🔐 Azure Key Vault** – Secure credential management  
- **💸 Azure Cost Management** – Tracks resource usage and cost optimization  

---

## 🚀 Pipeline Flow

1. **Live Weather API** 🌤️ – Continuously pulls weather data from a public source  
2. **Azure Databricks + Azure Functions** – Parses and formats the incoming data  
3. **Azure Event Hub** – Acts as the ingestion layer for streaming events  
4. **Event Stream** – Sends data to both storage and analytics systems  
5. **Kusto DB (Eventhouse)** – High-speed querying & aggregation of structured streaming data  
6. **Power BI** – Generates dynamic dashboards for operational monitoring  
7. **Data Activator** – Triggers real-time alerts for defined weather conditions (e.g., storm warnings)  
8. **Email Notifications** 📬 – Final user-facing alert layer  

---

## 📊 Use Case

> 🚨 "Imagine you need to alert emergency responders and city planners instantly when humidity or wind speed crosses a threshold — this system does exactly that, in real time!"

---

## 🔒 Security & Cost Management

- **Key Vault** handles all API keys and secrets securely 🔐  
- **Azure Cost Management** keeps track of budgets and resource utilization 💰  

---

## 📌 Highlights

- Real-time data streaming 💡  
- Event-driven architecture ⚙️  
- Scalable and secure Azure cloud components ☁️  
- Interactive Power BI dashboards 🖥️  
- Automated weather-based alerts 🌪️  

---

## 📬 Contact

Maintained by **Rupak Kulkarni**  
🔗 GitHub: [github.com/rk268](https://github.com/rk268)

---
