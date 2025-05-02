---
layout: default
title: "Hi, I'm Jum!"
lang: en
---

## 👋 Hello!

Welcome to my English portfolio. I'm a passionate **Network & Cloud Engineer**, with experience in **AWS, Azure, GCP**, and deep understanding of **VPN, IPSec, and enterprise networking**.

---

## 💼 Projects

{% include about.html %}
{% if site.data.projects.size > 0 %}
{% include projects.html %}
{% endif %}

---

## 🛠 Experience & Skills

{% if site.data.experience.size > 0 %}
{% include experience.html %}
{% endif %}

{% if site.data.skill.size > 0 %}
{% include skill.html %}
{% endif %}

---

## 🎓 Education

{% if site.data.education.size > 0 %}
{% include education.html %}
{% endif %}
