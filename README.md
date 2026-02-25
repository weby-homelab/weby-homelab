<p align="center">
  <a href="README_ENG.md">
    <img src="https://img.shields.io/badge/🇬🇧_English-00D4FF?style=for-the-badge&logo=readme&logoColor=white" alt="English README">
  </a>
  <a href="README.md">
    <img src="https://img.shields.io/badge/🇺🇦_Українська-FF4D00?style=for-the-badge&logo=readme&logoColor=white" alt="Українська версія">
  </a>
</p>

<br>

# 🌌 WEBy Home Lab: Інфраструктурна Матриця

<p align="center">
  <img src="https://img.shields.io/badge/Infrastructure-as--Code-blueviolet?style=for-the-badge&logo=ansible" alt="IaC">
  <img src="https://img.shields.io/badge/Security-Zero--Trust-red?style=for-the-badge&logo=cloudflare" alt="Security">
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/2026-Ready-yellow?style=for-the-badge" alt="Year">
</p>

Ласкаво просимо до центрального вузла екосистеми **WEBy Home Lab** — автоматизованої, безпечної та відмовостійкої інфраструктури, що об'єднує хмарні ресурси та локальні кластери в єдиний живий організм.

Тут зберігається інтелект моєї лабораторії: від конфігурацій безпеки до систем моніторингу критичної ситуації в Києві.

Доступна також [Англійська версія документації](README_ENG.md).

---

## 🚀 Основні проекти

### ⚡ [Flash Monitor Kyiv](https://github.com/weby-homelab/flash-monitor-kyiv) (Флагман)
**Уніфікована автономна система енергомоніторингу та безпеки.**
- **Статус:** 🟢 **v1.4.14 Active** (Основна система)
- **Суть:** Повне об'єднання функцій моніторингу світла, повітряних тривог та якості повітря (AQI) в одному Docker-контейнері.
- **Фішка:** Розрахунок точності графіків до секунди, підтримка PWA та автономний парсинг Yasno/ДТЕК.

### 📊 [Light Monitor Kyiv](https://github.com/weby-homelab/light-monitor-kyiv)
- **Статус:** ⛔ **Archived** (Роботу на сервері зупинено, функціонал інтегровано у Flash Monitor).

### 🛡️ [Security Monitor Kyiv](https://github.com/weby-homelab/security-monitor-kyiv)
- **Статус:** ⛔ **Archived** (Роботу на сервері зупинено, функціонал інтегровано у Flash Monitor).

### 📞 [VoIP Installer](https://github.com/weby-homelab/voip-installer)
- **Суть:** Автоматизоване розгортання захищеної телефонії Asterisk 22 у Docker.

---

## 🖥️ Апаратний Стек

| Вузол | Локація | Роль | ОС / Гіпервізор |
| :--- | :--- | :--- | :--- |
| **HTZNR (Primary)** | Німеччина | Edge Services, Flash Monitor | Ubuntu 24.04 LTS |
| **IONOS-VPS** | Європа | Backup VoIP, DNS, Turnserver | Debian (Tmux Hardened) |
| **PRXMX-02** | Home Lab | Центральне ядро, NAS, AdGuard | Proxmox VE 9.1 |
| **PRXMX-01** | Home Lab | Backup Node (Battery Monitored) | Proxmox VE (Laptop) |

---

## 🗺️ Дорожня карта 2026

- [ ] **Infrastructure as Code:** Повний перехід на Ansible плейбуки для всіх серверів.
- [ ] **AI Integration:** Впровадження Gemini API для інтелектуального аналізу логів та безпеки.
- [ ] **Observability:** Стек Prometheus + Grafana для візуалізації стану «заліза».

---
<p align="center">
  ✦ 2026 WEBy Home Lab ✦ Made with ❤️ in Kyiv
</p>
