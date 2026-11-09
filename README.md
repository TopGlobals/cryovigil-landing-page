# CryoVigil Landing Page

[![Static Website](https://img.shields.io/badge/website-static-blue.svg)](https://topglobals.github.io/cryovigil-landing-page/)
[![HTML5](https://img.shields.io/badge/HTML5-e34f26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6%2B-f7df1e?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

Marketing website for **CryoVigil**, the laboratory asset monitoring platform by **TopGlobals**.

---

## 📋 Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Architecture & Tech Stack](#architecture--tech-stack)
- [Directory Structure](#directory-structure)
- [Getting Started](#getting-started)
- [Deployment](#deployment)
- [Related Links](#related-links)
- [Team Members](#team-members)

---

## 🚀 About the Project

CryoVigil is an automated critical laboratory asset surveillance platform designed to help laboratories monitor freezers, incubators, and other storage units in real time.

This repository contains the public-facing landing page that introduces the platform, its capabilities, target audiences, pricing plans, and team. It is a static front-end project and does not contain the CryoVigil backend, database, or authentication implementation.

## ✨ Features

- Responsive marketing page for desktop, tablet, and mobile screens.
- English and Latin American Spanish language switching.
- Accessible responsive navigation with keyboard and screen-reader support.
- Product capabilities covering real-time alerts, compliance reporting, and centralized monitoring.
- Targeted content for research laboratories, hospitals and clinics, and pharmaceutical organizations.
- Pricing cards with links to the Web App subscription flows.
- Product and team video sections ready for video sources.
- Terms of Service and Privacy Policy pages.
- Social-sharing links for X and LinkedIn.

## 🛠️ Architecture & Tech Stack

The site is implemented as a lightweight static website with no build step or runtime server required.

- **Markup:** HTML5
- **Styling:** CSS3 with utility-style classes and responsive layouts
- **Behavior:** Vanilla JavaScript (ES6+)
- **Localization:** JavaScript translation dictionaries
- **Assets:** Local images in `assets/img/`
- **Deployment:** GitHub Pages or any static web host

### Directory Structure

```text
.
├── index.html             # Main landing page
├── privacy.html           # Privacy Policy
├── terms.html             # Terms of Service draft
├── css/
│   └── style.css          # Site styles and responsive layout
├── js/
│   ├── main.js            # Navigation, language switching, and sharing links
│   └── translations.js    # English and Latin American Spanish copy
└── assets/
    └── img/              # Logo, dashboard, compliance, and team images
```

## 🏁 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/TopGlobals/landing-page.git
cd landing-page
```

### 2. Open the Website

Because this is a static website, no dependency installation is required. Open `index.html` directly in a browser, or serve the project locally with any static file server.

For example, with Python:

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

## 🌐 Deployment

The public landing page is available at:

**https://topglobals.github.io/cryovigil-landing-page/**


## 👥 Team Members — TopGlobals

| Name | Role | GitHub Username |
| --- | --- | --- |
| Arizabal Condori, Jean Niels | Leader | [@JeanArizabal](https://github.com/JeanArizabal) |
| Homola, Tomas | Developer | [@Ch1L1](https://github.com/Ch1L1) |
| Reyes Munoz, Joaquin Leonardo | Developer | [@JoakoRM](https://github.com/JoakoRM) |
