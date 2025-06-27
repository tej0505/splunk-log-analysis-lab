# 🔍 Splunk SSH Log Analysis Lab

This project demonstrates how to use Splunk to detect and analyze failed SSH login attempts from a Kali Linux system. It simulates a real-world security operations center (SOC) use case using live logs and a custom dashboard.

---

## 📚 Overview

- ✅ Ingests `/var/log/auth.log` using Splunk Free
- ✅ Extracts attacker IPs and usernames using SPL and `rex`
- ✅ Detects brute-force login attempts by frequency
- ✅ Visualizes threats using Splunk Dashboard Studio

---

## 📊 Dashboard Panels

| Panel Name                        | Description                                          |
|----------------------------------|------------------------------------------------------|
| 🔹 Failed SSH Logins by IP       | Bar chart showing failed login sources              |
| 🔹 Total Failed Login Count      | Single-value panel for total failed attempts        |
| 🔹 Failed Logins by Username     | Bar chart showing which usernames were targeted     |

---

## 📁 Project Structure

splunk-log-analysis-lab/
├── queries/
│ ├── failed_login_by_ip.spl
│ ├── total_failed_count.spl
│ └── failed_login_by_username.spl
├── screenshots/
│ ├── panel_failed_by_ip.png
│ ├── panel_total_failed.png
│ └── full_dashboard.png
├── README.md


---

## 💻 Tools Used

- 🔸 **Splunk Enterprise (Free Edition)**
- 🔸 **Kali Linux**
- 🔸 **Search Processing Language (SPL)**
- 🔸 **rsyslog / SSH logging**
- 🔸 **Dashboard Studio (Splunk Web UI)**

---

## 📸 Screenshots

### 🔹 Dashboard Overview

![Screenshot_2025-06-26_14_10_59](https://github.com/user-attachments/assets/b44e7c5f-2c92-41a0-832b-3e48d5c8da5f)

### 🔹 Panel: Failed by IP

![Screenshot_2025-06-26_14_18_11](https://github.com/user-attachments/assets/bf3ab55c-22f8-4601-803d-daf44569d87c)


### 🔹 Panel: Total Login Failures

![Screenshot_2025-06-26_22_20_54](https://github.com/user-attachments/assets/4da0c7c4-0b1e-4fbf-b201-0f8a4cd0d062)


---

## 🚀 Learning Outcome

> This hands-on lab helped me:
> - Understand how SIEM tools like Splunk work
> - Build regex-based SPL queries
> - Visualize login attack patterns in dashboards
> - Simulate brute-force login attempts for detection

---

## 🔗 Author

**Tejas Mahale**  
Cybersecurity Enthusiast | TryHackMe | Bugcrowd | Splunk Learner  
📧 [www.linkedin.com/in/tejas-mahale0508]  
🌐 [https://github.com/tej0505](https://github.com/tej0505)
