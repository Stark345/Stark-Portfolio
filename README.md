# Stark Portfolio &mdash; Modern Developer Portfolio Template (2026 Edition)

An ultra-modern, high-performance, dark-themed developer portfolio template engineered for **Full-Stack Engineers**, **AI/ML Developers**, and **Software Architects**. Designed with fluid micro-interactions, canvas particle physics, smooth momentum scrolling, and enterprise security.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Netlify Status](https://img.shields.io/badge/Netlify-Ready-00C7B7?logo=netlify&logoColor=white)](https://www.netlify.com/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

---

## ✨ Features

- **Karolina Hess-Inspired Hero Section**: 
  - Studio portrait card with cubic-bezier grayscale-to-color transition on hover.
  - Dynamic status badge ("Available for Opportunities") with pulsing neon radar dot.
  - Fluid fluid typography (`clamp()`) ensuring zero word overlapping across any display resolution.
- **Interactive Canvas 2D Before/After Reveal**:
  - Custom canvas cursor trail that dynamically reveals the crisp background image underneath.
- **Wireframe 3D Globe Visualization**:
  - Pure HTML5 Canvas 3D vector-math globe rotating with dynamic depth shading.
- **Categorized Work Filter**:
  - Instant client-side project filtering between *All*, *Full-Stack Web*, and *AI & Deep Learning*.
- **Inertial Momentum Smooth Scrolling**:
  - Powered by **Lenis** with native touch & fallback handling.
- **Bulletproof Contact Modal & Netlify Forms**:
  - Native AJAX submission with loading spinner state.
  - Built-in invisible honeypot field (`netlify-honeypot="bot-field"`) for automated spam bot defense.
  - Seamless local simulation mode (works offline and via `file:///` without CORS errors).
- **Enterprise-Grade Security**:
  - Pre-configured `_headers` file with anti-clickjacking (`X-Frame-Options: DENY`), MIME protection, and strict referrer policies.

---

## 📁 Repository Structure

```text
Stark-Portfolio/
├── assets/
│   └── images/
│       ├── profile.png        # High-res portrait (800x920)
│       └── profile.webp       # Optimized WebP portrait
├── _headers                   # Netlify security headers
├── .gitignore                 # Clean Git ignore rules
├── index.html                 # Complete single-page portfolio
└── README.md                  # Documentation
```

---

## 🚀 Quick Start & Customization

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/Stark-Portfolio.git
cd Stark-Portfolio
```

### 2. Replace Your Avatar
Drop your own portrait image into `assets/images/`:
- `profile.png` (800x920 recommended)
- `profile.webp` (for ultra-fast web delivery)

### 3. Customize Your Information
Open `index.html` and search for the following placeholder tags to personalize:
- **Name / Brand**: Search `XYZ.DEV` or `Developer Portfolio` &rarr; Replace with your name.
- **Social Links**: Search `your-username` &rarr; Replace with your GitHub, LinkedIn, and email URLs.
- **Academic / Highlights**: Update `Computer Science • 9.0 CGPA`.
- **Projects**: Replace the 8 template cards in `#works` with your project titles, tags, and repositories.

### 4. Deploy

#### Option A: 1-Click Netlify Drop (Fastest)
1. Go to [app.netlify.com](https://app.netlify.com/).
2. Drag and drop this repository folder into the Netlify deploy zone.
3. Your site is instantly live with working contact forms!

#### Option B: GitHub + Netlify CI/CD
1. Push this repository to your GitHub account:
   ```bash
   git remote add origin https://github.com/your-username/portfolio.git
   git branch -M main
   git push -u origin main
   ```
2. In Netlify, click **"Add new site" &rarr; "Import an existing project"** and select your repository.
3. Netlify will auto-deploy every time you push new updates!

---

## 🛡️ Security & Performance

- **Zero External Trackers**: No third-party analytics cookies or trackers.
- **CSP & Framing Protection**: `X-Frame-Options: DENY` prevents clickjacking.
- **Optimized Assets**: Modern WebP formats with fallback image loaders.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) &mdash; feel free to fork, adapt, and use it for your personal or commercial portfolio!
