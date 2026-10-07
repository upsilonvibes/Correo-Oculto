# 💌 Correo-Oculto

**A personalized, client-side digital letterbox crafted for intimate, chapter-based personal prose.**

[![License: MIT](https://img.shields.io/badge/License-MIT-pink.svg)](https://opensource.org/licenses/MIT)
[![Deploy with Vercel](https://img.shields.io/badge/Deploy-Vercel-000000?logo=vercel&logoColor=white)](https://vercel.com/)
[![Stack: Vanilla JS](https://img.shields.io/badge/Stack-Vanilla%20JS-F7DF1E?logo=javascript&logoColor=black)](#%EF%B8%8F-technology-stack)
[![Design: Glassmorphism](https://img.shields.io/badge/Design-Glassmorphism-e91e63)](#-ambient-ui--experience)


## 📋 Overview

**Correo-Oculto** (*Hidden Mail*) is an ultra-lightweight, client-side digital letterbox application. Built on a single static architecture, it authenticates intended recipients, opens a personal mailbox timeline, and dynamically renders individual letters inside a dedicated reading room—all without full page reloads or server infrastructure.

Whether sharing personal reflections, milestone journals, or multi-media visual memories, **Correo-Oculto** packages digital correspondence into a calm, elevated, and intimate reading space. 🕊️

---

## ✨ Key Features

| Feature | Description |
| :--- | :--- |
| 🔐 **Access Gate** | A client-side name and secret-key lookup system that controls access to each configured mailbox. |
| 💌 **Mailbox Timeline** | Chronologically sorted entries (`#01`, `#02`, `#03`) automatically surfacing the newest letter first. |
| 📖 **Dynamic Reading Room** | Single-page view routing that updates titles, letter bodies, and media seamlessly. |
| 🎬 **Media Attachments** | Native support for embedded **YouTube** video players and **Spotify** tracks inside letters. |
| 🖼️ **Polaroid Memory Gallery** | Responsive grid display for image collections styled with classic polaroid aesthetics. |
| 💬 **Direct WhatsApp Reply** | Pre-configured CTA buttons that initiate WhatsApp chats with tailored pre-filled messages. |
| 🌸 **Ambient Visual Experience** | CSS floating particles, glassmorphism containers, soft gradients, and envelope animations. |
| 📱 **Mobile-First Responsive** | Optimized fluid typography and layout breakpoints for desktop, tablet, and mobile screens. |
| ⚡ **Zero-Backend Architecture** | 100% client-side data handling—deployable in seconds on any static edge host. |

---

## 🛠️ Technology Stack

* **HTML5** — Semantic, accessible layout scaffolding and reading container anchors.
* **CSS3** — Custom keyframe animations, glassmorphism design system, flex/grid layouts, and responsive media queries.
* **Vanilla JavaScript (ES6+)** — Client-side authentication, state management, permanent letter numbering, array sorting, dynamic DOM rendering, and mailbox/reading-room navigation.
* **External Integrations** — iFrame embeds for YouTube/Spotify and custom deep-linking for WhatsApp API.

---

## 📐 Project Structure

```text
correo-oculto/
│
├── index.html       # Structural layout blueprint & root UI container
├── styles.css       # Design tokens, keyframe animations & glassmorphism system
├── router.js        # Recipient lookup, secret-key validation & DOM renderer
│
└── README.md        # Technical documentation & project guide