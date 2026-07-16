<div align="center">

# Danish Butt — Developer Portfolio

**A modern, dual-theme, fully self-contained single-file portfolio — built with pure HTML, CSS & JavaScript.**

<br>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

![License](https://img.shields.io/badge/License-MIT-22d3ee?style=flat-square)
![Made with love](https://img.shields.io/badge/Made%20with%20%E2%9D%A4%EF%B8%8F%20by-Danish%20Butt-6366f1?style=flat-square)

<br>

### [🔗 View Live Portfolio](https://danish-butt.vercel.app/)

</div>

---

## 📑 Table of Contents

- [Preview](#-preview)
- [Overview](#-overview)
- [Key Features](#-key-features)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Deployment](#-deployment)
- [Customization](#-customization)
- [License](#-license)
- [Author](#-author)

---

## 📸 Preview

<!-- TODO: Add screenshots in screenshots/ folder -->

<table>
  <tr>
    <td align="center"><b>🌙 Dark Mode</b></td>
    <td align="center"><b>☀️ Light Mode</b></td>
  </tr>
  <tr>
    <td><img src="./screenshots/dark.png" alt="Portfolio — dark mode" width="100%"></td>
    <td><img src="./screenshots/light.png" alt="Portfolio — light mode" width="100%"></td>
  </tr>
</table>

<div align="center">
  <b>📱 Mobile View</b><br><br>
  <!-- TODO: Add screenshots/mobile.png -->
  <img src="./screenshots/mobile.png" alt="Portfolio — mobile view" width="320">
</div>

---

## 📋 Overview

This is the personal portfolio of **Danish Butt**, a Full Stack MERN Developer from Multan, Pakistan — currently working at Work Edge LTD and pursuing a BS in Computer Science at AIR University. It showcases production deployments, professional experience across MERN, Next.js and ASP.NET Core, and featured projects including a live enterprise vendor management platform.

The entire site ships as **one self-contained `index.html` file**: every line of CSS and JavaScript is inline, and even the profile photo is embedded as a Base64 data URI. The only external requests are two CDN links (Google Fonts and Font Awesome). No frameworks, no build step, no dependencies to install — clone it, open it, it runs.

Under the hood it implements a polished **"Deep Ocean / Arctic" dual-theme system** that defaults to the visitor's OS preference and cross-fades smoothly on toggle, an interactive canvas particle network in the hero, terminal-styled typing animation, scroll-driven reveal choreography via `IntersectionObserver`, and a fully responsive layout — all in vanilla JavaScript.

---

## ✨ Key Features

- 🌗 **Dual light/dark theme** — follows the system `prefers-color-scheme` by default, remembers the visitor's manual choice for the session, animated sun/moon toggle with a 360° rotation and a smooth 0.3s color cross-fade site-wide
- 🎇 **Interactive hero** — canvas particle network that reacts to the cursor, staggered headline entrance, JSX-styled name (`<Danish Butt/>`), and a terminal-style `$ whoami` typing effect cycling through roles
- 🖼️ **Embedded profile photo** — Base64 data URI inside a gradient-ring frame with theme-aware glow, plus an automatic "DB" initials fallback if the image ever fails
- 🌀 **Scroll choreography** — `IntersectionObserver`-powered reveal animations with stagger delays, animated stat counters (roles, deployments, technologies), and active nav-link highlighting while scrolling
- 🧭 **Sticky glass navbar** — shrinks on scroll with backdrop blur; on mobile, an animated hamburger opens a slide-in drawer with overlay and Escape-key support
- 💼 **Real content sections** — About with info card, categorized tech-stack grid with brand-colored code-token chips, vertical experience timeline, three detailed project cards (tech badges, feature lists, live/source links), and an education stack
- 📄 **Downloadable CV** — one-click download of `Danish-Butt-CV.pdf` via a relative link
- ✉️ **Contact section** — form with a `mailto:` handoff (pre-filled subject and body) plus direct email, phone, GitHub and LinkedIn links
- 📱 **Fully responsive** — flawless from 320px phones to wide desktops; the hero photo reflows above the intro on small screens
- 🔍 **SEO ready** — meta description, keywords, author, Open Graph and Twitter Card tags, semantic HTML5 landmarks, inline SVG favicon
- ♿ **Accessible** — ARIA labels and live regions, keyboard-visible focus rings, WCAG AA color contrast in both themes, full `prefers-reduced-motion` support
- 🍬 **Extra polish** — loading animation, cursor glow (desktop only), scroll-to-top button, gradient custom scrollbar, faint engineering-paper dot-grid texture that adapts to both themes

---

## 🧰 Tech Stack

| Technology | Purpose |
|---|---|
| **HTML5** | Semantic structure, SEO meta, Open Graph tags |
| **CSS3** | Custom properties (theming), Grid/Flexbox, glassmorphism, animations |
| **Vanilla JavaScript (ES6+)** | Theme engine, canvas particles, typing effect, `IntersectionObserver` reveals, counters, mobile menu |
| **Google Fonts** (CDN) | Space Grotesk (display), Inter (body), JetBrains Mono (code accents) |
| **Font Awesome 6** (CDN) | Iconography across all sections |
| **Vercel** | Hosting & deployment of the live site |

---

## 📁 Project Structure

```
Web-Portfolio/
├── index.html            # The entire website — all CSS & JS inline, photo embedded
├── Danish-Butt-CV.pdf    # CV served by the "Download CV" button
├── screenshots/          # README preview images (dark.png, light.png, mobile.png)
├── LICENSE               # MIT License
└── README.md             # You are here
```

---

## 🚀 Getting Started

```bash
# 1. Clone the repository
git clone https://github.com/DanishButt586/Web-Portfolio.git

# 2. Open it
cd Web-Portfolio
```

Then simply **open `index.html` in any modern browser** — that's it. No installs, no build step.

> 💡 Optional: for auto-reload while editing, use the **Live Server** extension in VS Code (right-click `index.html` → *Open with Live Server*).

---

## 🌐 Deployment

The live site is deployed on **[Vercel](https://vercel.com)**. To deploy your own fork:

1. **Fork** this repository to your GitHub account
2. Sign in to Vercel with GitHub and click **Add New → Project**
3. **Import** the forked repo — no framework preset or build settings needed (it's static)
4. Click **Deploy** — your site is live on a `*.vercel.app` URL in seconds

Every subsequent `git push` redeploys automatically.

---

## 🎨 Customization

Everything lives in `index.html` — search for these spots:

| What | Where |
|---|---|
| **Theme colors** | The `:root` block (dark "Deep Ocean" palette) and `[data-theme="light"]` block (light "Arctic" palette) at the top of the `<style>` tag — accent gradient, backgrounds, text colors are all CSS variables |
| **Content** | Each section is clearly marked with `<!-- ===== SECTION ===== -->` comment banners (Hero, About, Tech Stack, Experience, Projects, Education, Contact) |
| **Profile photo** | The `<img>` inside `.photo-frame` in the hero — replace the Base64 `src` with your own image (or a relative path); a "DB" initials fallback renders if it fails |
| **CV file** | Drop your PDF next to `index.html` and keep the name `Danish-Butt-CV.pdf`, or update the `href` on the Download CV button |
| **Typing roles** | The `roles` array in the `<script>` section |

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](./LICENSE) file for details. You're free to use, modify and distribute it; a credit back is always appreciated.

---

## 👤 Author

<div align="center">

### **Danish Butt**
**Full Stack MERN Developer**

<br>

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-danish--butt.vercel.app-22d3ee?style=for-the-badge)](https://danish-butt.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-DanishButt586-181717?style=for-the-badge&logo=github)](https://github.com/DanishButt586)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-DanishButt-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/DanishButt)
[![Email](https://img.shields.io/badge/Email-Danishnaveed212%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Danishnaveed212@gmail.com)

<br>

**⭐ Star this repo if you found it helpful!**

</div>
