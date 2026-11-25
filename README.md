# Integrated Banking & Financial Corporation (IBFC)
### Enterprise Static Web Platform & Institutional Client Portal

[![Website Status](https://img.shields.io/badge/Status-Production%20Ready-success?style=for-the-badge&logo=vercel)](https://adityabs-eng.github.io/ibfc-banking-preview/)
[![License](https://img.shields.io/badge/License-Proprietary-blue?style=for-the-badge)](LICENSE)
[![ISO Certification](https://img.shields.io/badge/ISO-9001%3A2015%20%7C%2027001%3A2022-gold?style=for-the-badge)](https://adityabs-eng.github.io/ibfc-banking-preview/about.html)

A high-performance, enterprise-grade static website engineered for **Integrated Banking & Financial Corporation (IBFC)**, a premier financial intermediary and debt resolution powerhouse headquartered on **Fraser Road, Patna, Bihar**.

Modeled after tier-one institutional banking service providers (such as *VGM Consultants Limited* - `https://vgmconsult.com/`), this web application demonstrates pan-India operations spanning **25+ states**, ₹750+ Cr recovered quarterly, a 5,000+ strong workforce, and alliances with **20+ Tier-1 Private & Public Sector Banks**.

---

## 🌐 Live Client Preview & Navigation

| Page | Description | Primary Capabilities |
| :--- | :--- | :--- |
| **[Home](index.html)** | Corporate Gateway & Hero Showcase | Auto-rotating Hero Carousel, Dynamic KPI Tickers (₹750+ Cr, 5000+ Staff, 25+ States), Core Solutions Grid, Client Testimonials |
| **[About Us](about.html)** | Heritage, Founders & Governance | Patna Corporate Story (Founded 2014), Leadership Biographies, 10-Year Milestones, Interactive Culture & ISO 27001 Tech Infrastructure |
| **[Services](services.html)** | Specialized B2B Financial Offerings | Delinquent Debt Recovery (Soft calling to Hard collections), Retail Debt Initiation & Sourcing, Inbound Client Servicing & Third-Party Verification (TPV) |
| **[Partner With Us](partner.html)** | Institutional Banking Alliances | Institutional RFP Submission Engine, Asset Class Breakdown (Auto, MSME, Cards, Personal, Agri), 4-Step Onboarding Process |
| **[Contact Us](contact.html)** | Nationwide Presence & Inquiries | Patna Corporate HQ Address & Telephony, Direct Departmental Routing, Interactive Google Map Integration, Rapid Response Contact Form |

---

## 📱 Mobile & Responsive Architecture

The platform has been meticulously engineered and stress-tested across all device viewports:

1. **Mobile Experience (< 768px)**:
   - **Pure CSS 3-Line Hamburger Menu (☰)**: Built with zero font-dependency using hardware-accelerated CSS elements (`<span class="w-5 h-0.5 bg-slate-800">`), guaranteeing 100% visual rendering reliability on every network condition.
   - **Unified Left-Sliding Off-Canvas Drawer**: A single, fluid sidebar slides in from the left containing primary pages, in-page section jump links under the current active page, a direct **Request Proposal** action CTA, and Patna HQ corporate details.
   - Auto-closing upon link selection, backdrop tap, or `Escape` key press with body scroll lock.

2. **Tablet Experience (768px – 1023px, iPad / Tablets)**:
   - Restored clean horizontal navigation row with proportional `10px–16px` link gaps without crowding or text clipping.
   - Balanced, equal-height card grids (`tablet-card`, `tablet-equal-height`) with consistent `1.25rem` padding.
   - Pinned top-right header CTA (`[ Request Proposal ]`) accessible at all screen widths.

3. **Desktop Experience (1024px+)**:
   - Sticky glassmorphic navigation header with dynamic scroll elevation.
   - High-contrast corporate typography and smooth micro-interactions.

---

## 🛠️ Technology Stack & Zero-Dependency Design

- **Structure**: Semantic HTML5 (W3C validated, SEO & accessibility-optimized, full OpenGraph metadata).
- **Styling**: Tailwind CSS v3 (via CDN) paired with custom corporate design tokens (`css/custom.css`).
- **Icons**: Font Awesome v6.5.1 (with fallback pure CSS UI icons).
- **Client Scripting**: Vanilla ECMAScript 6+ (`js/main.js` - zero external dependencies or framework overhead):
  - Autoplay Carousel with Pause-on-Hover
  - IntersectionObserver-powered Counter Animations
  - Off-Canvas Mobile Drawer Controller
  - Interactive Tabbed Interface Switcher
  - Form validation with animated feedback modal
- **Development Server**: Built-in zero-dependency Node.js HTTP server (`server.js`).

---

## 📁 Repository Directory Map

```text
├── index.html              # Corporate Homepage & Executive Summary
├── about.html              # Our Story, Founders, Milestones & Culture
├── services.html           # Core Offerings: Collection, Sourcing, TPV
├── partner.html            # Institutional RFP & Bank Alliances Portal
├── contact.html            # Fraser Road, Patna HQ, Map & Telephony
├── README.md               # Production Documentation & Deployment Manual
├── server.js               # Lightweight Node.js local preview server
├── css/
│   └── custom.css          # Corporate theme tokens, tablet card polish, animations
└── js/
    └── main.js             # Slider, drawers, animated tickers, modals
```

---

## 🚀 Local Development Setup

To run the project locally on your machine:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/adityabs-eng/ibfc-banking-preview.git
   cd ibfc-banking-preview
   ```

2. **Start the local server**:
   ```bash
   node server.js
   ```

3. **Access the web application**:
   Open your browser and navigate to:
   ```text
   http://localhost:3000
   ```

---

## 🌐 Deploying to GitHub Pages (Option A)

This project is a 100% static web application that requires zero build steps or compilation:

1. Push your code to the `main` branch:
   ```bash
   git push -u origin main
   ```
2. In your GitHub repository, navigate to **Settings** > **Pages**.
3. Under **Build and deployment** > **Source**, select **Deploy from a branch**.
4. Under **Branch**, select `main` and folder `/ (root)`, then click **Save**.
5. Your website will be live at:
   ```text
   https://adityabs-eng.github.io/ibfc-banking-preview/
   ```

---

## 🏛️ Corporate Information

- **Entity**: Integrated Banking & Financial Corporation (IBFC)
- **Corporate Headquarters**: Plot No. 12, Fraser Road, Patna, Bihar - 800001, India
- **Telephony**: +91 612 250 8800
- **Institutional Inquiries**: info@ibfcconsult.com / partnerships@ibfcconsult.com
- **Accreditations**: ISO 9001:2015 Quality Management | ISO/IEC 27001:2022 Information Security Management

---
*© 2026 Integrated Banking & Financial Corporation (IBFC). All rights reserved.*
