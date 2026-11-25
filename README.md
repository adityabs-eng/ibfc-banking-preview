# IBFC - Integrated Banking & Financial Corporation
### Static Web Application for IBFC

Built as a high-fidelity, production-grade static web solution modeled on **VGM Consultants Limited** (`https://vgmconsult.com/`).

---

## 🌐 Live Preview Links

- **Home Page**: [http://localhost:3000/](http://localhost:3000/)
- **About Us**: [http://localhost:3000/about.html](http://localhost:3000/about.html)
- **Services**: [http://localhost:3000/services.html](http://localhost:3000/services.html)
- **Partner With Us**: [http://localhost:3000/partner.html](http://localhost:3000/partner.html)
- **Contact Us**: [http://localhost:3000/contact.html](http://localhost:3000/contact.html)

*(Server runs on port 3000 via `node server.js`)*

---

## 📁 File Structure

```text
Desktop/demo/
├── index.html        # Home page (Hero slider, Who We Are, 6 Core Features, Impact Counters, Partners)
├── about.html        # About Us (Interactive tabs: Our Story & Founders, Life at IBFC, Tech & ISO 27001)
├── services.html     # Services (Delinquent Debt Collection, Debt Initiation, Client Servicing, Proposal Form)
├── partner.html      # Partner With Us (Institutional Banking Alliances, Asset Classes, Onboarding, RFP Form)
├── contact.html      # Contact Us (Corporate HQ in Patna, Bihar, regional offices, inquiry form, Google Maps)
├── server.js         # Built-in lightweight local preview web server (zero dependencies)
├── css/
│   └── custom.css    # Polished styling, smooth scrolling, glassmorphism, animations
└── js/
    └── main.js       # Carousel slider, animated counters, tab switcher, mobile drawer, form modal
```

---

## 🎨 Design & Architectural Features

1. **Color Palette & Branding**:
   - Primary Corporate Navy: `#0a3b5c`
   - Dark Contrast Navy: `#06283f`
   - Primary Accent Light: `#0e5483`
   - Accent Gold/Amber: `#f59e0b`
   - Accent Sky Blue: `#0284c7`
   - Slate Neutral Surfaces: `#f8fafc` & `#ffffff`

2. **Full Responsive Interactivity**:
   - Automated 3-slide hero carousel with dots & arrows navigation.
   - Dynamic counter ticker: ₹750+ Cr recovered, 5,000+ staff, 25+ states, 20+ partner banks.
   - Interactive tabbed narrative on About Us page with mobile-adaptive dropdown selector.
   - Interactive contact forms with client-side feedback and success confirmation modal.
   - Mobile-responsive navigation drawer.
   - Embedded Google Maps for corporate headquarters.

---

## 🚀 How to Run the Server Anytime

Open PowerShell or terminal in `C:\Users\ASUS\Desktop\demo`:
```bash
node server.js
```
Then visit `http://localhost:3000` in your web browser.
