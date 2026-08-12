# 💎 Handmade Jewelry Landing Page

A modern, responsive, and accessible landing page for a handmade jewelry brand, showcasing unique artisan creations, craftsmanship story, product gallery, and customer testimonials.

---

## 🌐 Live Demo

👉 **[View Website (GitHub Pages)](https://ivan-kyznetsov.github.io/jewerly-project/)**

---

## 📋 Project Overview

**Handmade Jewelry** is a landing page designed to highlight the beauty, sustainability, and story behind artisan-crafted jewelry. 

### Key Sections:
* **Header & Hero Section** — Prominent branding, navigation, and primary call-to-action ("Order Now").
* **About Us (`#about-us`)** — The craftsmanship story, artisan background, and sustainable approach.
* **Benefits (`#benefits`)** — Core value propositions: Unique Design, Quality & Reliability, and A Story in Every Detail.
* **Gallery Showcase (`#gallery`)** — Highlighting featured pieces (bracelets, pendants, rings, floral items).
* **Testimonials (`#testimonials`)** — Customer reviews with rating stars and rich visual imagery.
* **Contacts (`#contacts`)** — Direct contact channels (Email, Phone, Office location map link) and order form.
* **Footer** — Social media links, quick links, and copyright metadata.

---

## 🛠 Key Technical Highlights & Features

### 1. 🖼️ Advanced Image Optimization (Responsive & Retina-ready)
* **`<picture>` Tag & Art Direction:** Utilizes adaptive picture elements to serve distinct images tailored for mobile and desktop screens, delivering an optimal layout while saving bandwidth.
* **High-DPI Display Support (Retina 2x):** Implements `srcset` attributes with `1x` and `2x` pixel density descriptors for crisp rendering on Apple Retina screens and modern mobile displays.
* **CLS Prevention (Cumulative Layout Shift):** All key images feature explicit `width` and `height` attributes or aspect ratios to eliminate content jumping during load time.
* **Native Lazy Loading (`loading="lazy"`):** Improves First Contentful Paint (FCP) and initial page load speed by deferring off-screen image loading in lower sections.

### 2. ♿ Accessibility (A11y) & Semantic Markup
* **Clean Semantic HTML5 Structure:** Leverages native semantic tags (`<header>`, `<main>`, `<section>`, `<nav>`, `<footer>`, `<blockquote>`, `<cite>`) to enhance SEO, code readability, and screen reader navigation.
* **Enhanced ARIA Attributes:** 
  * `aria-label` used on icon links, buttons, and logo elements for clear assistive technology feedback.
  * `role="img"` and `aria-label="Rating: X out of 5 stars"` for accessible visual star rating rendering.
* **External Link Security:** All outgoing links enforce `rel="noopener noreferrer"` alongside `target="_blank"` for improved performance and security.

### 3. ⚡ Performance & Build Optimization
* **Resource Hints (`preconnect`):** Pre-connects to Google Fonts domain (`fonts.googleapis.com` & `fonts.gstatic.com`) to optimize web font fetch speeds.
* **Vector Graphics (SVG):** Logos and icons are embedded as SVGs to ensure minimal file size and flawless resolution independence across high-density displays.
* **Asset Cache Busting:** Modern build tooling appends unique content hashes to static assets (CSS/JS/Images), guaranteeing immediate cache invalidation upon project redeployments.

### 4. 📱 UX, Responsive Design & Interactivity
* **Mobile Drawer Navigation:** Mobile-friendly drawer menu providing smooth touch interactions for smaller screens.
* **Smooth Anchor Scrolling:** Seamless in-page navigation jumping directly to relevant sections (`#about-us`, `#benefits`, `#gallery`, `#testimonials`, `#contacts`).
* **Modular Card Layouts:** Clean, responsive grid and flexbox structures for testimonials, gallery cards, and benefit listings.

---

## 🚀 Tech Stack

* **HTML5** (Semantic structure & ARIA accessibility)
* **CSS3** (Flexbox, Grid, Media Queries, Custom Properties)
* **Vite / Modern Bundler** (Asset hashing & build pipeline)
* **Git & GitHub Pages** (Version control and automated deployment)
