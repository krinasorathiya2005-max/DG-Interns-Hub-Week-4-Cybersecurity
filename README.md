# DG-Interns-Hub-Week-4-Cybersecurity
Week 4 Cyber Security Internship – Virtual Lab, Network Security, Nmap and Wireshark Practical
# 🔐 Cyber Security Internship – Week 4

## Basic Network Setup & Initial Security Testing

This repository contains my **Week 4 practical work** completed as part of my **Cyber Security Internship with DG Interns Hub**.

The practical focused on building a controlled virtual security lab and performing basic network security testing using **Kali Linux, Nmap, Wireshark, and a web server**.

---

## 🎯 Objectives

* Create a basic virtual security lab
* Configure communication between attacker and target machines
* Deploy and verify a basic web server
* Identify open ports and running services using Nmap
* Capture and analyze network traffic using Wireshark
* Understand HTTP, DNS and ICMP traffic
* Identify basic security observations
* Document practical work with screenshots and evidence

---

## 🧪 Lab Environment

| Component           | Purpose                             |
| ------------------- | ----------------------------------- |
| VirtualBox / VMware | Virtualization Platform             |
| Kali Linux          | Security Testing / Attacker Machine |
| Windows/Linux       | Target Machine                      |
| Apache / Nginx      | Web Server                          |
| Nmap                | Network Scanning                    |
| Wireshark           | Packet Analysis                     |

### Lab Flow

```text
Kali Linux
    │
    │  Virtual Lab Network
    │
    ▼
Target Windows/Linux
    │
    ▼
Web Server
```

---

## 🔎 Practical Tasks

### 1. Virtual Lab & Network Setup

A controlled virtual network was created using VirtualBox/VMware. Kali Linux was configured as the security-testing machine and a Windows/Linux virtual machine was used as the target.

Connectivity between the machines was verified using basic network commands and ping testing.

---

### 2. Web Server Configuration

A basic web service was configured on the target machine using Apache/Nginx.

The web server was started and verified by accessing the target machine's IP address from the lab network.

---

### 3. Nmap Network Scanning

Nmap was used to identify open ports and running services on the authorized lab target.

#### Commands Used

```bash
nmap <TARGET-IP>
```

```bash
nmap -sV <TARGET-IP>
```

The `-sV` scan was used to identify service and version information associated with discovered ports.

---

### 4. Wireshark Traffic Analysis

Wireshark was used to capture and analyze network packets generated within the lab.

The following traffic types were studied:

* ICMP
* DNS
* HTTP

Display filters were used to focus on specific types of network traffic.

```text
icmp
```

```text
dns
```

```text
http
```

---

## 🛡️ Security Observations

During the practical, the following security concepts were observed:

* Open ports represent network-accessible services.
* Unnecessary services can increase the attack surface.
* Service/version information can help identify software requiring security review.
* Web services should be securely configured.
* Packet captures provide visibility into network communication.
* Network security testing should always remain within an authorized scope.

---

## 📸 Evidence & Screenshots

The `Screenshots` folder contains practical evidence from the lab.

### Screenshot Categories

* Virtual Lab
* Network Configuration
* Web Server
* Nmap
* Wireshark

---

## 📄 Report

The complete detailed practical report is available in the **Report** folder.

**Report:** `Week-4-Cyber-Security-Internship-Report.docx`

---

## 🧠 Key Learning Outcomes

Through this practical, I gained hands-on understanding of:

* Creating a controlled virtual security lab
* Network configuration and connectivity
* Basic web-server deployment
* Network reconnaissance using Nmap
* Packet capture and analysis using Wireshark
* HTTP, DNS and ICMP traffic
* Security observations and evidence documentation
* Responsible and authorized security testing

---

## ⚠️ Ethical & Safety Note

All security-testing activities were performed in a **controlled and authorized laboratory environment**.

Security tools such as Nmap and Wireshark should only be used against systems for which proper authorization has been obtained.

---

## 🚀 Internship Progress

**Week 4 Completed ✅**

This practical strengthened my foundation in **Network Security, Network Reconnaissance, Packet Analysis and Ethical Security Testing**.

Looking forward to continuing my cybersecurity learning journey through upcoming practical tasks.

---

### 🏷️ Technologies & Tools

`Kali Linux` `Nmap` `Wireshark` `VirtualBox` `VMware` `Apache` `Nginx` `Network Security` `Cyber Security`
