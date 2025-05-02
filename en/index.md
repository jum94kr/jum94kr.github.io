---
layout: default
title: "Hi, I'm Jum!"
lang: en
---

## 👋 Welcome!

I’m a professional **Network & Cloud Engineer** with deep experience in **AWS, Azure, and GCP**, as well as advanced expertise in **VPN, IPsec, SSLVPN**, and cloud-based infrastructure automation.

---

## 💼 Projects

### 🔧 AWS AutoConnect  
A fully automated tool developed in collaboration with the AWS VPN team to establish IPsec VPN connections between on-premise equipment and AWS with just a single click.

**Features**  
- Auto-fetching and applying AWS Customer Gateway / Site-to-Site VPN details  
- Enables direct VPN configuration from on-premise devices  
- Secure API authentication using Cross Account Access  

**My Role**  
- Designed automation logic for collecting and applying necessary VPN info  
- Performed connectivity testing and troubleshooting between AWS and on-prem environments  
- Implemented secure access from on-premise to AWS via API calls  
- Hardened API architecture using Cross Account structures

---

### 🌐 Cloud VPN Throughput Measurement  
A project to build performance testing environments across AWS, Azure, and GCP for measuring throughput of VPN, Firewall, and SSLVPN connections between virtual machines and on-premise devices.

**Highlights**  
- Designed isolated multi-cloud network environments for VPN testing  
- Built routing, security groups, and VPC subnets  
- Set up VPN Gateway and Customer Gateway across platforms  
- Integrated Spirent TestCenter for performance analysis  
- Diagnosed and resolved real-world VPN throughput issues

---

### ✈️ Flight Schedule  
[🔗 Site](https://flight-lookup.vercel.app/) | [💻 GitHub](https://github.com/jum94kr/flight-lookup)

An individual project to explore API integration and UI development using modern web stacks.

**Tech Highlights**  
- API integration via API Hub  
- Developed with React, styled-components, and TypeScript  
- Focused on modularity, scalability, and maintainability  
- Emphasized real-time data display and user-friendly design

---

## 🛠 Experience, Skills & Education

This section is auto-rendered from data files just like the Korean version.

{% if site.data.experience.size > 0 %}
{% include experience.html %}
{% endif %}

{% if site.data.skill.size > 0 %}
{% include skill.html %}
{% endif %}

{% if site.data.education.size > 0 %}
{% include education.html %}
{% endif %}
