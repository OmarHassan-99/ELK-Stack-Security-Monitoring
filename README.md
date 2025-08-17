# ELK Stack Security Monitoring Lab

## 📌 Overview
This project demonstrates how to set up and configure an **ELK Stack** (Elasticsearch, Kibana, Fluent Bit, Winlogbeat) to collect, process, and visualize logs for **security monitoring**.  
It serves as a practical **lab guide** for students, SOC analysts, and cybersecurity enthusiasts looking to gain hands-on experience with **log management and SIEM-based detection**.

## 🚀 Features
- Install & configure **Elasticsearch** and **Kibana** on Ubuntu  
- Configure **Fluent Bit** for log forwarding  
- Configure **Winlogbeat** for Windows event logs  
- Integrate data sources into the ELK pipeline  
- Create **KQL detection rules** in Kibana SIEM  
- Simulate & detect suspicious activity (e.g., disabling firewall)  

## 🛠️ Requirements
- VMware / VirtualBox  
- Ubuntu 20.04/22.04/24.04 ISO  
- Windows 10/11 ISO  
- 16 GB RAM, 60 GB Disk, 4 CPU cores  


**The project is organized into six main phases:**
1. **Elasticsearch** – Install and configure the core engine that indexes and stores log data.  
2. **Kibana** – Deploy the visualization interface and connect it with Elasticsearch.  
3. **Integration** – Link Kibana with Elasticsearch using enrollment tokens and verification codes.  
4. **Fluent Bit** – Configure log forwarding from Linux systems into Elasticsearch.  
5. **Winlogbeat** – Forward Windows event logs to Elasticsearch for centralized monitoring.  
6. **Threat Detection** – Create custom KQL rules in Kibana SIEM and simulate suspicious activity (e.g., disabling the firewall) to generate alerts.  

Together, these phases deliver a fully functional ELK Stack for log ingestion, visualization, and basic security monitoring.  

##  Author
- **Omar Hassan**  
[LinkedIn](https://www.linkedin.com/in/omar-hassan9999/)  


