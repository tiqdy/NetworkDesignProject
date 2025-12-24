# Network Design Project: BINUS University (Alam Sutera)

### 📌 Project Information
* **Author:** Atiqah Zahra Pramudya
* **Course:** Computer Networks (Odd Semester 2024/2025)
* **Location:** BINUS Alam Sutera (Floors 4, 5, and 6)

---

## 📖 Overview
This project details the design and simulation of a computer network infrastructure for the BINUS University Alam Sutera building. The objective was to design a reliable, scalable, and efficient network to support academic and operational activities.

The design includes:
* **Physical Infrastructure:** Device selection and cabling.
* **Logical Addressing:** VLSM Subnetting for IPv4 efficiency.
* **Routing:** Static Routing for secure inter-floor connectivity.
* **Services:** Application layer configuration (HTTP, DNS, SMTP).

---

## 🗺️ Network Topology
The network utilizes a **Star Topology** connected via a fiber optic backbone. This ensures high speed, stability, and ease of troubleshooting.

<div align="center">
  <img src="https://github.com/user-attachments/assets/5b3a91ee-6cd4-4915-b880-0401b2867fca" alt="Full Cisco Network Topology" width="800">
</div>

---

## ⚡ Connectivity Simulation
The following videos demonstrate successful packet transfer tests (ICMP/Ping) across the different floors.

### 4th Floor Connectivity Test
https://github.com/user-attachments/assets/4c3cb53b-7548-49d2-97bf-59927f1db8a3

### 5th Floor Connectivity Test
https://github.com/user-attachments/assets/7988f2be-5790-4cc6-a123-03a034a4e983

### 6th Floor Connectivity Test
https://github.com/user-attachments/assets/7c45654e-d15a-475b-95a1-adc70f792166

---

## 🌐 Application Layer Services
The network supports essential services configured on three dedicated servers: **DNS, Web (HTTP), and Email (SMTP)**.

### 1. Server Configuration
*Setup of the DNS, Web, and Email servers within the simulation.*
<div align="center">
  <img src="https://github.com/user-attachments/assets/04bb5fad-4ba5-478d-8c73-c1dba64390d8" alt="Server Setup" width="600">
</div>

<br>

### 2. Service Testing (Web & Email)
* **Left:** accessing the faculty announcement page via `computernetwork.com`.
* **Right:** Successful email exchange between users (`tiqa@gmail.com` to `catherine@gmail.com`).

<div align="center">
  <img src="https://github.com/user-attachments/assets/ca526a91-33a5-40e7-a4a0-c2a32557b42b" alt="HTTP Web Access" width="45%">
  &nbsp; &nbsp;
  <img src="https://github.com/user-attachments/assets/026e9f30-514e-4ee7-81f5-9d7f496d181b" alt="SMTP Email Test" width="45%">
</div>

---

## 🛠️ Technical Specifications

### 🔹 IP Addressing (VLSM)
Variable Length Subnet Masking was used to optimize IP allocation:
* **4th Floor:** `192.168.10.0`
* **5th Floor:** `192.168.20.0`
* **6th Floor:** `192.168.30.0`

### 🔹 Routing Protocol
**Static Routing** was implemented to provide:
* Fixed and controlled communication paths.
* Lower processing overhead on routers.
* Enhanced security.

### 🔹 Hardware Summary
* **Routers:** 11 Units
* **Switches:** 29 Units (Total across floors)
* **Cabling:** Fiber Optic (Backbone) & Copper Straight-Through/Crossover
