# 🌐 Personal Website

This repository contains the source code for my personal website hosted via GitHub Pages.

The site presents:

- Professional profile
- Curriculum (online view + downloadable PDF)
- Technical skills and tools
- Featured embedded systems projects
- Contact information
- Multilingual support (English / Spanish)
- Basic analytics tracking (Google Analytics 4)

---

## 🚀 Overview

This is a static website built using:

- HTML5
- CSS3
- No frontend framework (vanilla approach)
- Responsive layout (CSS Grid)
- Google Analytics (GA4 custom event tracking)

It is designed to be lightweight, maintainable, and deployment-ready via GitHub Pages.

---

## 🌍 Languages

The site supports two languages:

- English → `/en/`
- Spanish → `/es/`

Language switching is handled through static routing and flag-based navigation.

---

## 📂 Project Structure

```
.
├── index.html              # Root entry (English default)
├── en/
│   └── index.html
├── es/
│   └── index.html
├── pages/
│   ├── en/
│   │   └── Curriculum.html
│   └── es/
│       └── Curriculum.html
├── files/
│   ├── CV.pdf
│   ├── en/CV.pdf
│   └── es/CV.pdf
├── images/
│   ├── profile.jpeg
│   ├── spain-flag.png
│   └── uk-flag.png
├── styles/
│   └── style.css
└── LICENSE
```

---

## 📊 Analytics

Google Analytics 4 is integrated with:

- CV download tracking
- Curriculum page view tracking
- Language-aware event tagging

Custom events:
- `download_cv`
- `view_cv_page`

Tracking uses `transport_type: 'beacon'` for reliability.

---

## 🧠 Design Philosophy

The website follows a simple engineering approach:

- No frameworks
- No build system
- No external dependencies (except GA and fonts)
- Fully static deployment
- Easy portability

The structure emphasizes clarity, maintainability, and minimalism.

---

## 🛠 Deployment

This site is deployed using **GitHub Pages**.

To deploy updates:

```bash
git add .
git commit -m "your message"
git push origin main
```

GitHub Pages automatically serves the updated content.

---

## 📄 License

MIT License
