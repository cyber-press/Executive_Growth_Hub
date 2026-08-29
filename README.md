# Executive Growth Hub — Resources Library & Interactive Planning Suite

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Single Page Application](https://img.shields.io/badge/Architecture-Single%20Page%20App-059669.svg)](#architecture)

An all-in-one, zero-dependency executive business planning suite, interactive financial calculator toolkit, AI prompt repository, and fillable template library created for entrepreneurs, business founders, executives, and leaders.

---

## 🌟 Key Features

### 1. 🛠️ 8 In-Browser Interactive Business Worksheets & Calculators
* **💰 Budget & Profit Calculator**: Live calculation of one-time startup costs, monthly operating expenses, multiple revenue streams, automated net profit forecasting, savings allocation, and a dynamic visual cash-flow ratio bar.
* **🏷️ Pricing & Margin Calculator**: Calculates unit delivery costs (direct materials + labor hours & hourly rate + overhead allocation), target gross profit margin %, markup on cost %, and break-even sales volume for $5,000/mo and $10,000/mo net profit targets.
* **📄 1-Page Business Plan Builder**: Structured inputs for business idea, problem solved, target audience, core offer, and mission statement, generating a formatted live executive brief card.
* **📱 Social Media Content Planner**: 4-pillar content matrix (*Educational, Proof/Case Studies, Authority/Behind-the-Scenes, Direct Offer*) with multi-platform tags and a 7-day schedule generator.
* **🎯 Monthly Goal Tracker**: 30-day revenue targets, client acquisition quotas, 4-week execution milestones, and monthly retrospectives.
* **📊 SWOT Analysis Matrix**: 2x2 color-coded quadrant audit (*Strengths, Weaknesses, Opportunities, Threats*) with automated strategic action priorities (*S-O and W-T strategies*).
* **🎨 Brand Identity Generator**: Interactive tag chips for brand personality and voice, primary/accent color codes, tagline ideas, and customer guarantee brief.
* **🎯 Customer Persona Builder**: Detailed audience avatar profiling covering demographics, core frustrations, desired outcomes, and preferred buying channels.

### 2. 💱 Multi-Currency Switcher (`$` USD, `₦` NGN, `£` GBP, `€` EUR)
* Instant global currency toggle that updates all financial tables, unit costs, pricing models, break-even targets, and budget summaries in real time.
* Selected currency persists across browser sessions using `localStorage`.

### 3. 💾 Universal Auto-Save Engine
* All form fields, calculations, notes, and worksheets in the Interactive Suite automatically save to browser `localStorage` as you type.
* Includes a live `"✓ Auto-saved"` status badge and a one-click `"Clear Drafts"` option.

### 4. 🖨️ One-Click "Print / Save as PDF" Export
* Dedicated `🖨️ Print / PDF` buttons across all 8 live worksheet summary cards.
* Clean `@media print` styling formats the generated briefs into professional, single-page A4 documents while stripping away navigation and UI chrome.

### 5. 🧭 Business Stage Diagnostic Quiz
* 3-question diagnostic questionnaire evaluating business stage (*Idea, Startup, Growth, Restart, Scaling*), core challenge (*Clarity, Registration, Marketing, Money, Systems, AI*), and jurisdiction (*Nigeria, US, Cross-Border, General*).
* Generates a tailored step-by-step roadmap, recommended templates, and direct portal links.
* Includes **"Copy My Path"** and **"Ask for Help on WhatsApp"** with pre-filled, personalized messages.

### 6. ⚡ AI Business Result Generator
* Client-side prompt and strategic brief generator requiring no external API key.
* Supports 8 prompt modes and 4 jurisdiction contexts (*Nigeria CAC/FIRS, U.S. SBA/EIN, Cross-Border, General*) with real-time character counters and WhatsApp copy formatting.

### 7. 💬 20 Strategic AI Prompts Suite
* Complete catalog of 20 categorized business prompts (*Strategy, Planning, Branding, Marketing, Sales, Customer Service, Operations, Leadership, Finance*).
* Fast-filter pill buttons and one-click copy buttons with floating toast feedback.

### 8. 📥 Downloadable Fillable PDF Template Library
* Direct links to 8 fillable PDF worksheets and the complete ZIP template pack.
* Real-time search and category filtering with empty-state handling.

### 9. ⚖️ Financial & Legal Readiness (Nigeria & U.S. Compliance)
* Direct official links to government portals:
  * **Nigeria**: CAC Business Name & Company Search, FIRS TaxPro Max (TIN), SMEDAN, NAFDAC, SON.
  * **United States**: SBA 10-Step Guide, IRS Employer Identification Number (EIN), Small Business Tax Center.

### 10. 🚀 6-Step Launch Roadmap
* Checkable milestone tracker with real-time progress bar calculation and `localStorage` persistence.

---

## 📁 Repository Structure

```
Executive_Growth_Hub/
├── index.html          # Complete, standalone single-page application (HTML5, CSS3, JS)
├── README.md           # Repository documentation and overview
└── LICENSE             # MIT License
```

---

## 🚀 Getting Started

### Local Development / Quick Preview
Because the entire application is built with standard vanilla web technologies (HTML5, CSS3, and ES6 JavaScript), no build tools or package managers are required:

1. Clone or download the repository:
   ```bash
   git clone https://github.com/cyber-press/Executive_Growth_Hub.git
   cd Executive_Growth_Hub
   ```
2. Open `index.html` directly in any modern browser:
   * **macOS**: `open index.html`
   * **Windows**: `start index.html`
   * **Linux**: `xdg-open index.html`

### Deploying to GitHub Pages
1. Go to your repository settings on GitHub: `https://github.com/cyber-press/Executive_Growth_Hub/settings/pages`.
2. Under **Build and deployment** &rarr; **Branch**, select `main` (or `master`) branch and `/ (root)` folder.
3. Click **Save**. Your site will be live at `https://cyber-press.github.io/Executive_Growth_Hub/`.

---

## 🎨 Design System & Technologies

* **Typography**: Google Fonts — [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans) (Headings) & [Inter](https://fonts.google.com/specimen/Inter) (Body / UI).
* **Color Palette**:
  * Navy / Obsidian: `#081424`, `#0B1A2E`, `#122844`
  * Blue / Cobalt: `#2563EB`, `#1D4ED8`, `#EFF6FF`
  * Emerald: `#059669`, `#ECFDF5`
  * Amber / Rose: `#D97706`, `#E11D48`
  * Slate Neutrals: `#F8FAFC`, `#F1F5F9`, `#E2E8F0`, `#64748B`, `#0F172A`
* **Icons**: Inline SVG iconography (crisp, scalable, and zero external font dependencies).
* **Storage**: Browser `localStorage` API for state persistence.
* **Printing**: Custom `@media print` style definitions for executive document exports.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 🤝 Community & Support

* **Organization**: Executive Growth Hub
* **WhatsApp Community**: [+1 323 804 9326](https://wa.me/13238049326)
* **Email**: [press.amadu@gmail.com](mailto:press.amadu@gmail.com)
* **Location**: San Antonio, Texas
