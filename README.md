# 🦷 Oracare Dental Clinic Website

A modern, responsive, and dynamic dental clinic website built using **React** and **Tailwind CSS**, showcasing services, appointment booking, and informational content to promote Oracare’s brand and services online.

![React](https://img.shields.io/badge/React-19.x-blue)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-4.x-teal)
![Deployment](https://img.shields.io/badge/Deployed-Cloudflare%20Pages-green)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

---

## 📘 Table of Contents

| Section                    | Description                                     |
| -------------------------- | ----------------------------------------------- |
| Project Overview           | High-level summary of project purpose and goals |
| Features                   | Key features and functionalities                |
| Tech Stack                 | Technologies used in the project                |
| Getting Started            | Setup instructions for running locally          |
| Appointment Email Workflow | How form submissions are handled                |
| Live Demo                  | Hosted live version of the website              |
| Credits                    | Acknowledgements and author information         |
| License                    | Licensing and usage terms                       |

---

# 🚀 Project Overview

**Oracare** is a fictional dental clinic website designed to represent a real-world client project. It features a clean UI, organized content structure, responsive design, and interactive features such as dynamic service pages and a working contact form.

The goal is to present a **professional, trustworthy, and user-friendly digital presence** for the clinic that works seamlessly across all devices.

---

# 🧩 Features

* ✅ Fully responsive layout with **Tailwind CSS**
* 🗂️ Service categories with **nested routing and detailed subpages**
* 📅 **Appointment booking form** with input validation
* 📧 **Automated email notifications using EmailJS**

  * Admin receives a **detailed appointment request email**
  * User receives a **confirmation email**
* 📍 Embedded **Google Maps** integration for clinic location
* 💬 **Confirmation modal** after successful form submission
* 🌐 **SEO-friendly structure**
* ⚡ **Fast loading performance** with optimized assets
* 🦷 Clean and modern UI designed for **healthcare service websites**

---

# 🛠️ Tech Stack

| Technology       | Usage                                   |
| ---------------- | --------------------------------------- |
| React            | Frontend framework                      |
| React Router     | Client-side routing                     |
| Tailwind CSS     | Utility-first styling framework         |
| EmailJS          | Handles appointment email notifications |
| Lucide Icons     | Lightweight icon library                |
| Cloudflare Pages | Hosting and deployment                  |

---

# 📨 Appointment Email Workflow

```
User submits appointment form
        ↓
EmailJS processes the request
        ↓
Admin receives appointment details via email
        ↓
User receives appointment confirmation email
```

This ensures the clinic team is notified instantly while the patient receives confirmation of their request.

---

# 📬 Getting Started

## 1. Clone the repository

```bash
git clone https://github.com/gursharancodes/oracare.git
cd oracare
```

---

## 2. Install dependencies

```bash
npm install
```

---

## 3. Set up EmailJS

1. Create a free account at **https://www.emailjs.com/**
2. Create an Email Service and Email Template
3. Copy the following credentials:

* Service ID
* Template ID
* Public Key

4. Replace the placeholders inside the contact form component.

---

## 4. Run the development server

```bash
npm run dev
```

---

## 5. Build for production

```bash
npm run build
```

---

# 🤝 Credits

Designed and developed by:

**Gursharan Singh**

GitHub:
https://github.com/gursharanme

---

# 📄 License

This repository is intended for **personal portfolio** and **educational demonstration** purposes only.

**Commercial use is not permitted without explicit written permission from the author.**
