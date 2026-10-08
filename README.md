# LH Capital — Private Wealth Advisory Website

A modern, high-performance, luxury web platform built for **LH Capital** (Dubai, United Arab Emirates). Re-architected from the ground up using **Apple design system principles** (deep OLED dark mode, SF Pro/Inter typography, frosted glassmorphism, Cupertino rounded squircles, hairline borders, and subtle champagne gold accents).

Fully optimized for instant zero-dependency deployment to **Vercel** via **GitHub**.

---

## 🌟 Key Features & Design Enhancements

- **Apple Frosted Glass Navigation**: Sticky navbar with `backdrop-filter: blur(20px)` and responsive mobile drawer.
- **Atmospheric DIFC Hero**: Cinematic Dubai skyline background with ambient spotlight, Dubai UAE badge, and dual gold-glow CTA buttons.
- **Credo Values Strip**: Ticker of core philosophies (`INDEPENDENT`, `RESEARCH-DRIVEN`, `RISK-CONSCIOUS`, `CLIENT-FOCUSED`, `LONG-TERM THINKING`).
- **The Problem Bento**: 5 glassmorphic problem cards (`Market Noise`, `Emotional Decisions`, `Poor Risk Management`, `Financial Scams`, `Lack of Strategy`) with custom SVG iconography.
- **4 Core Advisory Pillars**: Investment Advisory, Trading & Tactical Advisory, Economic & Market Intelligence, and Wealth Advisory with interactive tags and pathway flows.
- **The LH Framework**: 5-step structured process (`01 DISCOVER` → `02 DIAGNOSE` → `03 DESIGN` → `04 DEPLOY` → `05 REVIEW`) emphasizing *"The Doctor of Financial Health"*.
- **Target Audience**: 4 distinct client segments including dedicated recovery guidance for *Rebuilding Investors*.
- **Founder & Leadership**: Dedicated profile of Samor Joseph (Founder & Managing Director), wealth management professional since 2018 and endurance athlete/triathlete, articulating his core philosophy:
  > *"Structure over impulse, consistency over intensity, and the long game over the quick win."*
- **Why LH Capital Trust Matrix**: 6-grid differentiator cards.
- **Business Model & Engagement Tiers**: 4 transparent pricing tiers (Advisory, Tactical Advisory, Institutional, Research & Intelligence) with regulatory disclaimers.
- **LH Insights**: Interactive topic category filter (`Macro`, `Equities`, `Commodities`, `Markets`, `Digital Assets`, `Trading`) and interactive SVG financial charts.
- **Dubai & Global Vision**: Orbital visual diagram connecting Research, Advisory, Technology, Institutional Partnerships, Financial Intelligence, and Global Expansion.
- **Consultation Request Form**: Direct lead capture form with validation, dropdown selectors, capital range indicators, and Apple-grade confirmation modal.
- **Regulatory Disclaimers & Footer**: Complete legal, licensing, and compliance statements for UAE financial authorities.

---

## 📁 Project Structure

```
├── index.html                   # Semantic HTML5 Master Document
├── vercel.json                  # Vercel deployment & security headers configuration
├── README.md                    # Deployment & documentation guide
├── .gitignore                   # Git configuration
├── styles/
│   ├── apple-tokens.css         # Apple design system CSS variables & tokens
│   └── main.css                 # Responsive layout, glassmorphism, & animations
├── scripts/
│   └── main.js                  # Frosted nav, tabs filtering, modal, & smooth scroll
├── assets/
│   ├── dubai-hero.jpg           # High-res DIFC Dubai night skyline
│   ├── founder-sj.jpg           # Executive portrait of Founder SJ
│   └── brand/                   # Official logo, letterhead, and business cards
└── docs/
    └── reference/
        ├── LH_Capital_Reference.pdf     # Source PDF saved in workspace editor
        └── reference-blueprint.md       # Full OCR & content checklist from the PDF
```

---

## 🚀 How to Deploy to Vercel via GitHub

### Step 1: Initialize Git & Commit
Run these commands in your terminal from this project directory:

```bash
git init
git add .
git commit -m "Initial commit: LH Capital Apple-inspired website ready for Vercel"
```

### Step 2: Push to Your GitHub Repository
1. Go to [GitHub](https://github.com/new) and create a new repository (e.g. `lh-capital-website`).
2. Link and push your code:

```bash
git remote add origin https://github.com/YOUR_USERNAME/lh-capital-website.git
git branch -M main
git push -u origin main
```

### Step 3: Deploy on Vercel
1. Log into [Vercel](https://vercel.com).
2. Click **Add New...** → **Project**.
3. Select your `lh-capital-website` GitHub repository.
4. Framework Preset: Leave as **Other** (Zero build step needed! Instant global edge deployment).
5. Click **Deploy**.
6. Your website will be live worldwide in under 15 seconds!

### Step 4: Connect Custom Domain (`lhcapital.ae`)
1. In your Vercel Project Dashboard, navigate to **Settings** → **Domains**.
2. Enter `lhcapital.ae` (and `www.lhcapital.ae`).
3. Follow Vercel's instructions to add the DNS records (A record / CNAME) at your domain registrar.
4. SSL certificates will be generated automatically.
