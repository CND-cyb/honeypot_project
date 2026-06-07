## 🍯 Honeypot Project

### About the Project

The primary goal of this project is to expose dummy vulnerable services to observe malicious actors, gather Threat Intelligence, and document current attack vectors targeting public-facing servers.

---

### Core Objectives

*   **Isolated Deployment:** Create a contained environment on DigitalOcean Droplets with zero risk to other infrastructure.
*   **Data Collection:** Record brute-force login attempts, capture downloaded malware, and analyze the commands executed by attackers.
*   **Visualization:** Centralize and process logs to extract statistics on attack trends (geolocation, most tested passwords, etc.).
*   **Automation:** Streamline the provisioning and teardown of the infrastructure to ensure security.

---

### Tech Stack

| Component | Technology | Role in the Project |
| :--- | :--- | :--- |
| **Infrastructure** | DigitalOcean (Droplets) | Public cloud hosting |
| **Honeypot Software** | *[T-Pot]* | Service simulation (SSH, Telnet, HTTP) |
| **Monitoring** | *[Wazuh]* | Log analysis and data visualization |

---
