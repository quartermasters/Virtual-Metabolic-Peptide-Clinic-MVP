# 💊 Virtual Metabolic & Peptide Clinic – MVP

> A lifestyle-first, mobile-optimized digital clinic for women’s metabolic and cognitive health, built by [Quartermasters FZC](https://www.quartermasters.me) for a confidential health client.

---

## 🧠 Project Overview

This is the MVP version of a virtual health platform integrating microdosed GLP-1s, nutrition coaching, cognitive optimization, and peptide therapy. It is designed for women navigating insulin resistance, PCOS, hormonal weight gain, and neuroinflammation.

The platform routes users through two core pathways:
- **Educational Modules** via [Thinkific](https://www.thinkific.com)
- **Clinical Care Services** via [Practice Better](https://www.practicebetter.io)

All integrations are designed with **HIPAA/PHIPA-conscious architecture**, with **zero PHI stored** on this site.

---

## 🚀 Live Deployment

> Coming Soon — Will be deployed on [Netlify](https://www.netlify.com) or [Vercel](https://vercel.com)

---

## 📁 Project Structure

```
virtual-clinic-mvp/
├── public/            # Static assets (images, videos, docs)
├── src/               # Core site code
│   ├── pages/         # Main page files (HTML or Astro components)
│   ├── components/    # Reusable UI blocks
│   ├── styles/        # Global and modular CSS
│   └── scripts/       # JS for forms, CTA, behavior
├── static/            # SEO files (sitemap, robots.txt)
├── .env               # API keys & form endpoints (not committed)
├── README.md          # Project overview
└── package.json       # Build configuration (if using Astro)
```

---

## ✨ Features

- ⚡ Static, lightweight, mobile-first frontend
- 🔒 Secure Thinkific + Practice Better integrations
- 🧾 Email capture via Mailchimp or ConvertKit
- 📄 Embedded PDFs and explainer videos
- 🧠 Dual CTA navigation for “Education” vs “Clinical Care”
- 🔐 HIPAA/PHIPA-friendly – no PHI storage
- 📈 SEO & Analytics-ready (Fathom or GA4)
- 🧩 Modular component system (ready for growth)

---

## 🛠️ Tech Stack

| Layer       | Tool / Library              |
|-------------|-----------------------------|
| Frontend    | HTML / CSS / JS (or Astro)  |
| Hosting     | Netlify / Vercel            |
| Forms       | Netlify Forms / ConvertKit  |
| Analytics   | Fathom (preferred) / GA4    |
| CMS         | None (MVP)                  |
| Integrations| Thinkific + Practice Better |

---

## 🔧 Setup & Deployment

### Clone the Repo
```bash
git clone https://github.com/quartermasters/Virtual-Metabolic-Peptide-Clinic-MVP.git
cd Virtual-Metabolic-Peptide-Clinic-MVP
```

### Install Dependencies (if Astro or other framework used)
```bash
npm install
```

### Development Server
```bash
npm run dev
```

### Build for Production
```bash
npm run build
```

### Deploy
Push to GitHub → Netlify/Vercel auto-deploys from `main`

---

## 🔐 Compliance & Privacy

- No PHI is stored or processed within this site
- Practice Better handles all patient health data
- Thinkific hosts all learning modules securely
- SSL, self-hosted fonts, and cookie consent enabled
- Follows HIPAA and PHIPA best practices

---

## 💡 Post-MVP Vision

- [ ] Blog module (markdown-based)
- [ ] Smartwatch integration (Oura/Fitbit/Apple Health)
- [ ] Member dashboard via Thinkific API
- [ ] Self-assessment quizzes and lead gen tools
- [ ] Multilingual support (EN + FR)

---

## 👥 Credits

Built and maintained by:

**Quartermasters FZC**  
📍 Dubai, UAE  
🌐 [www.quartermasters.me](https://www.quartermasters.me)  
✉️ hello@quartermasters.me

---

## 📄 License

This project is proprietary. All rights reserved by the client. Contact Quartermasters FZC for licensing, expansion, or customization requests.
