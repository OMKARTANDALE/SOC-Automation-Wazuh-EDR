# 🛡️ SOC Automation using Wazuh SIEM/EDR & Shuffle SOAR

An end-to-end Security Operations Center (SOC) automation project that demonstrates real-time threat detection using **Wazuh SIEM/EDR** and automated incident response using **Shuffle SOAR**.

---

## 📖 Overview

This project demonstrates how a modern Security Operations Center (SOC) can detect and respond to threats automatically using open-source technologies.

A Windows 11 endpoint is monitored using Sysmon and the Wazuh Agent. A credential dumping attack is simulated using Mimikatz. Wazuh detects the malicious activity, forwards the alert to Shuffle through a webhook, and Shuffle automatically sends an email notification.

This project demonstrates SIEM monitoring, EDR, detection engineering, and SOAR automation in a practical lab environment.

---

## 🏗️ Architecture

![Architecture](architecture/architecture.png)

---

## 🚀 Features

- Real-time Endpoint Monitoring
- Wazuh SIEM/EDR
- Sysmon Log Collection
- Credential Dumping Detection
- Shuffle SOAR Automation
- Webhook Integration
- Automated Email Notification

---

## 💻 Tech Stack

| Tool | Purpose |
|------|---------|
| Windows 11 | Endpoint |
| Ubuntu Server | Wazuh Server |
| Wazuh | SIEM / EDR |
| Sysmon | Endpoint Monitoring |
| Shuffle | SOAR |
| Mimikatz | Attack Simulation |

---

## 🔄 Workflow

```
Windows Endpoint
        │
        ▼
     Sysmon
        │
        ▼
   Wazuh Agent
        │
        ▼
  Wazuh Manager
        │
        ▼
 Security Alert
        │
        ▼
     Webhook
        │
        ▼
 Shuffle SOAR
        │
        ▼
 Email Notification
```

---

## 📸 Screenshots

### Wazuh Dashboard

![](screenshots/01-dashboard.png)

### Connected Agent

![](screenshots/02-agent.png)

### Mimikatz Execution

![](screenshots/03-mimikatz.png)

### Wazuh Alert

![](screenshots/04-alert.png)

### Shuffle Workflow

![](screenshots/06-workflow.png)

### Email Notification

![](screenshots/08-email.png)

---

## ✅ Results

| Test | Status |
|------|--------|
| Wazuh Installed | ✅ |
| Agent Connected | ✅ |
| Sysmon Logging | ✅ |
| Mimikatz Detected | ✅ |
| Alert Generated | ✅ |
| Shuffle Triggered | ✅ |
| Email Notification Sent | ✅ |

---

## 📂 Repository Structure

```
SOC-Automation-Wazuh-EDR/
├── docs/
├── screenshots/
├── architecture/
├── wazuh/
├── shuffle/
├── attack-simulation/
└── README.md
```

---

## 📄 Documentation

Detailed project documentation is available in:

`docs/SOC_Automation_Report.pdf`

---

## 👨‍💻 Author

**Omkar Dinkar Tandale**

- 📧 omkartandale004@gmail.com
- 💼 LinkedIn: https://www.linkedin.com/in/omkar-tandale-562699235/
- 🐙 GitHub: https://github.com/OMKARTANDALE/
