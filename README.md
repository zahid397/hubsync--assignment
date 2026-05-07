# ⚡ HubSync — Tax & Accounting Platform
### WordPress UI Implementation from Figma Design

![HubSync](https://img.shields.io/badge/HubSync-Tax%20%26%20Accounting%20Platform-1A5FFF?style=for-the-badge&logo=wordpress&logoColor=white)
![WordPress](https://img.shields.io/badge/WordPress-6.x-21759B?style=for-the-badge&logo=wordpress&logoColor=white)
![Elementor](https://img.shields.io/badge/Elementor-Free-92003B?style=for-the-badge&logo=elementor&logoColor=white)
![Status](https://img.shields.io/badge/Status-Live-10B981?style=for-the-badge)

---

## 🌐 Live Site

> **[https://phenomenal-ostrich-e6e0d6.instawp.site/](https://phenomenal-ostrich-e6e0d6.instawp.site/)**

> ⚠️ **Note:** InstaWP free hosting shows a splash screen on first visit.
> Click **"Continue to Site"** once to access the full HubSync implementation.
> Screenshots are included in the `/screenshots` folder for quick reference.

---

## 🎨 Design Reference

| Resource | Link |
|----------|------|
| 📐 Figma Design | [HubSync Figma File](https://www.figma.com/design/fGuo6UhYJQwoRnbQtjucTa/Hubsync?node-id=2651-27870) |
| 🌐 Live Site | [phenomenal-ostrich-e6e0d6.instawp.site](https://phenomenal-ostrich-e6e0d6.instawp.site/) |

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **WordPress 6.x** | Core CMS platform |
| **Hello Elementor** | Lightweight base theme |
| **Elementor Free** | Page builder — all layouts |
| **WPForms Lite** | Contact & demo booking forms |
| **WP Fastest Cache** | Performance optimization |
| **Custom CSS** | Global styles via Appearance → Customize |
| **Vanilla JavaScript** | Modal interactions, auth system, localStorage |

---

## 📄 Pages Built

| Page | Description | Status |
|------|-------------|--------|
| 🏠 **Home** | Hero, logos, services, stats, awards, CTA, footer | ✅ Complete |
| 📖 **About** | Company info, why choose, team intro, video | ✅ Complete |
| 💼 **Case Study** | Client success stories, testimonials | ✅ Complete |
| 👥 **Team** | John McGowan, Paul Madarasz, Don Terry, Betsy Weissman | ✅ Complete |
| 📰 **News** | Blog, press releases, announcements | ✅ Complete |
| 🎓 **Learn** | Videos, PDFs, webinars, brochures | ✅ Complete |
| ✉️ **Engagement Letter Wizard** | Feature page with calculator | ✅ Complete |
| 🔐 **e-Sign** | e-Signature solution page | ✅ Complete |
| 🌐 **Gateway** | Integrated platform page | ✅ Complete |
| 📞 **Contact / Book a Demo** | Demo booking form | ✅ Complete |
| 🔒 **Privacy Policy** | Legal page | ✅ Complete |
| 📋 **Terms of Use** | Legal page | ✅ Complete |

---

## ✨ Features Implemented

### 🎯 Design Fidelity
- ✅ Pixel-perfect implementation matching Figma design
- ✅ Color palette: `#1A5FFF` primary, `#0D1B3E` dark navy, `#EBF0FB` background
- ✅ Typography: Inter font (Google Fonts) — 300 to 900 weights
- ✅ Floating rounded header with sticky scroll behavior
- ✅ Pill badges, blue checkmark bullets, card hover effects
- ✅ Infinite scrolling client logo marquee

### 📱 Responsive Design
- ✅ **Desktop** — 1200px+ full layout
- ✅ **Tablet** — 768px–1024px adapted grid
- ✅ **Mobile** — 375px+ single column, hamburger menu

### ⚙️ Admin Functionality (Bonus)
- ✅ All sections editable via **WP Admin → Pages → Edit with Elementor**
- ✅ Global styles managed via **Appearance → Customize → Additional CSS**
- ✅ Navigation editable via **Appearance → Menus**
- ✅ Site identity (logo, tagline) via **Appearance → Customize → Site Identity**

### 🔐 Interactive Features
- ✅ **Book a Demo** modal — form with validation + success state
- ✅ **Login / Register** system — localStorage-based auth
- ✅ **Sign In** with demo credentials: `demo@hubsync.com` / `demo123`
- ✅ **User avatar** with dropdown menu after login
- ✅ **Toast notifications** for all user actions
- ✅ **Smooth scroll** navigation between sections
- ✅ **Scroll-triggered** fade-in animations

---

## 🎨 Design System

```css
/* Colors */
--primary:     #1A5FFF   /* Blue */
--dark:        #0D1B3E   /* Navy */
--background:  #EBF0FB   /* Light Blue */
--white:       #FFFFFF   /* Cards */
--text:        #4A5568   /* Body text */

/* Typography */
Font Family:   Inter (Google Fonts)
H1:            56px / 800 weight
H2:            42px / 800 weight
Body:          15px / 400 weight / 1.7 line-height

/* Border Radius */
Cards:         12–14px
Buttons:       50px (pill)
Header:        20px (floating)
```

---

## 📁 Project Structure

```
hubsync-wordpress-task/
│
├── 📄 README.md                    ← This file
├── 🌐 live-link.txt                ← Live site URL
├── 💻 hubsync.html                 ← Complete standalone HTML5 app
│
└── 📁 screenshots/
    ├── home-desktop.png            ← Home page — desktop
    ├── home-mobile.png             ← Home page — mobile
    ├── about-page.png              ← About page
    ├── solution-page.png           ← Solution page
    ├── navigation.png              ← Nav with dropdown
    ├── login-modal.png             ← Login modal
    └── book-demo-modal.png         ← Book demo modal
```

---

## 🚀 How to Run Locally

### Option 1 — Open HTML file directly
```bash
# Download hubsync.html and open in browser
open hubsync.html
# or double-click the file
```

### Option 2 — WordPress local setup
```bash
# 1. Install Local by Flywheel (free)
# https://localwp.com

# 2. Create new WordPress site

# 3. Install plugins:
#    - Hello Elementor (theme)
#    - Elementor
#    - WPForms Lite
#    - WP Fastest Cache

# 4. Import pages from /wp-export if provided
#    OR follow the build steps in /docs/setup.md
```

---

## 📊 Performance

| Metric | Score |
|--------|-------|
| Plugins Installed | 3 (lightweight) |
| CSS Approach | Global custom CSS + Elementor inline |
| Caching | WP Fastest Cache enabled |
| Images | Optimized, lazy loaded |
| Mobile Score | Responsive breakpoints at 768px, 480px |

---

## 👨‍💻 Developer

**Zahid Hasan**

| | |
|--|--|
| 📧 Email | zh05698@gmail.com |
| 🐙 GitHub | [github.com/zahid397](https://github.com/zahid397) |
| 🌐 Portfolio | [zahidportfilio.vercel.app](https://zahidportfilio.vercel.app) |
| 📍 Location | Dhaka, Bangladesh |

---

## 📝 Submission Notes

This task was completed as part of the **Full Stack Developer** application for **Get Levrg Bangladesh Ltd**.

- **Figma design** was implemented faithfully using WordPress + Elementor
- **No paid plugins** were used — 100% free tools
- **Interactive features** (modals, auth, animations) built with vanilla JavaScript
- **localStorage** used as a fake backend for demo booking and user registration
- All **admin sections** are editable from the WordPress dashboard without touching code

---

*Built with ❤️ by Zahid Hasan — May 2026*
