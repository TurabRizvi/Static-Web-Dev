<div align="center">

# 🏎️ Luxury Motorsports — Static Web Development

**A sleek, fully responsive Porsche dealership website built with pure HTML & CSS.**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Static Site](https://img.shields.io/badge/Type-Static%20Website-success?style=for-the-badge)](https://en.wikipedia.org/wiki/Static_web_page)

*Built by **Syed Turab Rizvi***

---

### 📺 [▶ Watch the Live Demo on LinkedIn](https://www.linkedin.com/posts/turab-rizvi-1b6719376_luxury-motorsports-is-a-sleek-fully-responsive-ugcPost-7354864378552201216-H1ru/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAF0CwtoBQtsWQ54NSmXU7ibwlv9EY5qiWko)

</div>

---


## 🌟 Overview

**Luxury Motorsports** is a fully static, multi-page website that simulates a high-end Porsche dealership experience. Built entirely with HTML, CSS, and vanilla JavaScript — no frameworks, no libraries — it showcases clean front-end development with interactive features, responsive layout, and a polished visual identity.

The site goes beyond a simple landing page: it features a working car configurator, dynamic model variant switching, and a complete browsing experience across 10+ pages.

---

## ✨ Features

| Feature | Detail |
|---|---|
| 🚗 Car Catalog | 10 Porsche models with individual detail pages |
| ⚡ Dynamic Variant Switcher | Switch between 911 GT3 RS, GT2 RS, and Turbo S — specs update live |
| 🎨 Car Configurator | Choose rims, body kit & spoiler — preview image updates in real time |
| 📱 Responsive Design | Optimized for desktop and mobile viewports |
| 🖼️ Hero Sections | Full-width visual hero on homepage, models, and about pages |
| 📬 Contact Form | Name, email, and message fields with showroom details |
| 🧭 Consistent Navigation | Shared nav across all pages with active state highlighting |

---

## 📄 Pages

| Page | File | Description |
|---|---|---|
| 🏠 Home | `Index.html` | Hero, featured cars gallery, welcome section, about snippet |
| 🚘 Models | `models.html` | Full Porsche catalog with customization-available labels |
| 🔍 911 Variants | `car8.html` | Dynamic switcher for GT3 RS, GT2 RS & Turbo S |
| 🔧 Customize | `customize.html` | Live car configurator with combo image preview |
| ℹ️ About | `about.html` | Mission, vision, and story sections |
| 📞 Contact | `contact.html` | Contact form + showroom address & phone |
| 🏎️ Model Pages | `car1–car7.html` | Individual detail pages for each Porsche model |

---

## 🚗 Car Models

| # | Model | Page |
|---|---|---|
| 1 | Porsche 959 | car1.html |
| 2 | Porsche 968 | car2.html |
| 3 | Porsche 993 GT2 | car3.html |
| 4 | Porsche 964 Carrera RS | car4.html |
| 5 | Porsche 550 Spyder | car5.html |
| 6 | Porsche 901 Prototype | car6.html |
| 7 | Porsche 912 | car7.html |
| 8 | 911 GT3 RS | car8.html |
| 9 | 911 GT2 RS | car8.html |
| 10 | 911 Turbo S | car8.html |

---

## 🎨 Customization Engine

The `customize.html` page features a live car configurator. Every combination of options maps to a unique preview image — updated instantly with JavaScript, no page reload.

| Option | Choices |
|---|---|
| 🔩 Rim | Classic Alloy / RS Spyder |
| 🚙 Body Kit | Standard / Widebody |
| 💨 Spoiler | Ducktail / GT Wing |

Each of the 8 possible combinations maps to a unique combo image (`combo1.jpg` – `combo8.jpg`).

---

## 🏎️ 911 Variant Switcher

The flagship detail page (`car8.html`) dynamically updates all content when the user selects a variant from the dropdown — no page reload, pure JavaScript.

| Spec | GT3 RS | GT2 RS | Turbo S |
|---|---|---|---|
| **Price** | $223,800 | $293,200 | $230,400 |
| **Engine** | 4.0L Flat-6 NA | 3.8L Twin-Turbo | 3.7L Twin-Turbo |
| **Horsepower** | 518 hp | 700 hp | 640 hp |
| **0–60 mph** | 3.0 sec | 2.7 sec | 2.6 sec |
| **Top Speed** | 184 mph | 211 mph | 205 mph |
| **Transmission** | 7-speed PDK | 7-speed PDK | 8-speed PDK |
| **Drivetrain** | RWD | RWD | AWD |

---

## 🛠️ Tech Stack

| Technology | Role |
|---|---|
| **HTML5** | Page structure and semantic markup |
| **CSS3** | Styling, layout, hero sections, card grids, responsive design |
| **Vanilla JavaScript** | Variant switcher, customization configurator, combo image mapping |

> No frameworks. No libraries. No build tools. Pure front-end fundamentals.

---

## 📁 Project Structure

```
Luxury-Motorsports/
│
├── Index.html               # Homepage
├── models.html              # Full model catalog
├── car1.html – car7.html    # Individual model pages
├── car8.html                # 911 variants with dynamic switcher
├── customize.html           # Live car configurator
├── about.html               # About Us page
├── contact.html             # Contact form & showroom info
│
├── CSS/
│   └── style.css            # Global stylesheet (~14KB)
│
└── Images/
    ├── hero.jpg             # Homepage hero
    ├── 911gt3.png           # Model images
    ├── 911gt2.png
    ├── 911turbos.png
    ├── 959.png / 968 / 993 / 964 / 550 / 901 / 912 ...
    ├── combo1.jpg – combo8.jpg   # Configurator previews
    ├── about.jpg / about2.jpg / about3.jpg
    └── logo.png
```

---

## 🎨 Design Highlights

- **Hero Sections** — Full-width image banners with centered headline and CTA button on the homepage and models page
- **Card Grid Layout** — CSS grid-based car cards that are clickable and navigate to detail pages
- **Active Nav States** — Current page is highlighted in the navigation bar via `class="active"`
- **Customization Labels** — "Customization Available" badge overlaid on the three flagship 911 cards
- **Mobile-Responsive** — Viewport meta tag and fluid layouts ensure the site works across screen sizes
- **Consistent Footer** — Copyright footer present on all pages

---

## 📬 Contact & Showroom

| Detail | Info |
|---|---|
| 📍 Address | 123 Carrera Lane, Speed City, CA |
| 📧 Email | support@luxurymotorsports.com |
| 📞 Phone | +92-333-555-2134 |

---

<div align="center">

*Luxury Motorsports — Where Speed Meets Elegance.*

**[▶ Watch the Demo](https://www.linkedin.com/posts/turab-rizvi-1b6719376_luxury-motorsports-is-a-sleek-fully-responsive-ugcPost-7354864378552201216-H1ru/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAF0CwtoBQtsWQ54NSmXU7ibwlv9EY5qiWko)**

</div>
