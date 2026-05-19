# ★ The Common Sense Party
### *"We have it in our power to begin the world over again."* — Thomas Paine, 1776

![License](https://img.shields.io/badge/license-CC%20BY--SA%204.0-gold)
![Status](https://img.shields.io/badge/status-active-brightgreen)
![Built With](https://img.shields.io/badge/built%20with-pure%20HTML%2FCSS%2FJS-blue)
![No Framework](https://img.shields.io/badge/framework-none-lightgrey)
![Philosophy](https://img.shields.io/badge/philosophy-Constitutional%20Libertarian-gold)

---

## 🇺🇸 What Is This?

The **Common Sense Party** is a complete, financed, and constitutionally grounded political manifesto — presented as a beautiful, single-file static HTML marketing site.

Born from a deep conviction that neither the Democratic Party nor the Republican Party has offered a coherent, honest, and *complete* alternative to the current broken system, this project lays out a pragmatic libertarian platform designed to appeal to **every class, every background, and every political tradition** — from libertarians and homesteaders to progressives and environmentalists.

Inspired by **Thomas Paine** (born February 9, 1737), whose *Common Sense* pamphlet lit the fuse of the American Revolution with logic, clarity, and moral courage.

Built on the persuasion frameworks of:
- **Walter Lippmann** — controlling the "pictures in their heads"
- **Edward Bernays** — emotional anchors, not just arguments
- **Harold Lasswell** — who gets what, when, and how
- **John Dewey** — radical transparency as civic empowerment

---

## 📋 The Manifesto — Core Pillars

| Pillar | Policy |
|--------|--------|
| 💰 **Taxation** | Zero income tax · Zero property tax · Zero inheritance tax · VAT 5–45% tiered |
| 🏥 **Healthcare** | Mutual A (employers) + Mutual B (citizens) · Members govern · 6% overhead |
| 👴 **Retirement** | Capitalization replacing Social Security · $10k birth account · LPP 100% heritable |
| 🏛️ **Government** | 10% flat Corporate Tax · National Sovereign Wealth Fund ($18T by Year 20) |
| ⚔️ **Defense** | $500B national defense only · Close 750+ foreign bases · Zero foreign wars |
| 📚 **Education** | LibertyLearn — free open-source K–12 with AI tutor · 10th Amendment to States |
| 🌿 **Environment** | Oasis America Initiative · Drone seeding · Swales · Desalination at scale |
| 💊 **Health (MAHA)** | 7yr patent max · Big Food tort liability · 45% sin tax on ultra-processed |
| 🌍 **Immigration** | 4-stage merit system · Contribute first · Welcome builders |
| 🗣️ **Free Speech** | Liberty Square — 1st Amendment global public square · Open source · No ads |
| 🔐 **Privacy** | FOSS government systems · Open-source tax database · No IRS |
| 🏔️ **Nature** | Right to Nature on all BLM public lands · Allemannsrätten American style |

---

## 🚀 Getting Started

### The site is a single self-contained HTML file.

```bash
git clone https://github.com/YOUR_USERNAME/common-sense-party.git
cd common-sense-party
open csp_v3.html          # macOS
xdg-open csp_v3.html      # Linux
start csp_v3.html         # Windows
```

Or simply drag `csp_v3.html` into any browser. **No server required. No dependencies. No build step.**

---

## 📁 Repository Structure

```
common-sense-party/
│
├── csp_v3.html              # Main site — single file, zero dependencies
├── README.md                # This file
├── LICENSE                  # CC BY-SA 4.0
├── CONTRIBUTING.md          # How to contribute policy ideas
├── CHANGELOG.md             # Version history
│
├── manifesto/               # Full manifesto in Markdown (coming soon)
│   ├── 01-taxation.md
│   ├── 02-healthcare.md
│   ├── 03-retirement.md
│   ├── 04-sovereign-fund.md
│   ├── 05-defense.md
│   ├── 06-education.md
│   ├── 07-environment.md
│   ├── 08-immigration.md
│   └── 09-liberty-square.md
│
├── data/                    # Budget data in machine-readable formats
│   ├── budget_current.json
│   ├── budget_csp.json
│   ├── revenue_sources.json
│   └── retirement_projections.json
│
├── i18n/                    # Translations (help wanted!)
│   ├── fr/                  # French
│   ├── es/                  # Spanish
│   ├── de/                  # German
│   └── README_translations.md
│
└── assets/                  # Future: logos, open graph images, favicon
    └── og-image.png
```

---

## 🔢 Key Numbers at a Glance

| Metric | Status Quo | Common Sense Party |
|--------|-----------|-------------------|
| **Federal income tax** | Up to 37% | **$0 — abolished** |
| **Family annual gain** | — | **+$30,800/year** |
| **Retirement (10% contrib, 40yr, probable 4%)** | ~$1,907/mo (SS, 2032: $1,428) | **$3,657/month** |
| **Corporate tax** | 21% | **10% flat** |
| **Federal budget** | $6,900B | **$3,030B** |
| **Healthcare family cost** | $25,572/year | **~$12,000/year** |
| **Drug prices (generic)** | 10–100× markup | **-40 to -60%** |
| **Sovereign Wealth Fund (Year 20)** | $0 | **$18 trillion** |
| **Foreign wars** | Ongoing | **Zero** |
| **Property tax (federal)** | Yes | **$0 — abolished** |
| **Inheritance tax (federal)** | Yes | **$0 — abolished** |

---

## 🛠️ Technical Details

The site is intentionally built with **zero JavaScript frameworks, zero CSS frameworks, zero dependencies** — in the spirit of the manifesto itself: simple, transparent, and self-sufficient.

| Aspect | Choice | Why |
|--------|--------|-----|
| HTML | Semantic HTML5 | Accessible, parseable |
| CSS | Custom properties + Grid/Flex | No Bootstrap bloat |
| JS | Vanilla (~80 lines) | Scroll reveal + debt counter + tabs |
| Fonts | Google Fonts (Cormorant Garamond, DM Mono, Outfit) | Single CDN call |
| Dependencies | **Zero** | True FOSS spirit |
| Size | ~130KB HTML | Loads in <200ms anywhere |

### Browser Support
Chrome 80+, Firefox 75+, Safari 13+, Edge 80+. Fully responsive down to 320px.

---

## 💡 Ideas for Expansion

This project is a foundation. Here are directions the community could take it:

### 🔧 Technical

- [ ] **Retirement Calculator** — Interactive JS widget: input salary + contribution % → see guaranteed/probable/target capital
- [ ] **Budget Visualizer** — D3.js or Chart.js pie/sankey chart of current vs CSP spending
- [ ] **VAT Calculator** — "What will my grocery bill actually cost?" calculator
- [ ] **Sovereign Fund Simulator** — Watch the fund grow year by year interactively
- [ ] **Dark Mode** — Toggle between ink-dark (current) and parchment-light theme
- [ ] **PDF Export** — Print-ready version of the manifesto
- [ ] **Progressive Web App** — Offline-capable, installable on mobile
- [ ] **Open Graph / Twitter Cards** — Social sharing meta tags

### 🌍 Content

- [ ] **Multi-language support** — French, Spanish, German, Portuguese (pull requests welcome)
- [ ] **State-level policies** — How the 10th Amendment transfers work state by state
- [ ] **Historical appendix** — Founding documents that back each policy claim
- [ ] **FAQ section** — Address the 20 most common objections
- [ ] **Case studies** — Estonia (digital government), Norway (sovereign fund), France (mutuelles), Chile (capitalization), India (patent reform)
- [ ] **Timeline view** — 20-year transition plan visualized

### 🏛️ Political Tools

- [ ] **Petition system** — Collect signatures in support of specific policies
- [ ] **Debate mode** — Side-by-side CSP vs. Democrat vs. Republican on each issue
- [ ] **"Find your CSP" quiz** — Which pillar resonates most with you?
- [ ] **Precinct map** — Community organizing tool by zip code
- [ ] **Volunteer portal** — Sign up to spread the word

### 📊 Data & Transparency

- [ ] **Live federal debt counter API** — Replace static estimate with Treasury TreasuryDirect API
- [ ] **Budget comparison API** — JSON endpoints for all budget data
- [ ] **Policy amendment tracker** — GitHub Issues as a living policy debate platform

---

## 🤝 Contributing

All contributions welcome — especially:

**Policy contributions:** Open an Issue with the label `policy-proposal`. Describe the change, the constitutional basis, and the fiscal impact. Community votes via 👍/👎 reactions.

**Code contributions:** Fork → branch → PR. Please keep the zero-dependency philosophy — no npm, no webpack, no React. The HTML must remain a single deployable file.

**Translations:** See `i18n/README_translations.md`. Each language gets its own folder with the full site translated.

**Data contributions:** Add to the `data/` folder in JSON format. All numbers must cite public sources.

```bash
# Fork the repo, then:
git checkout -b feature/your-feature-name
# Make your changes
git commit -m "feat: add retirement calculator widget"
git push origin feature/your-feature-name
# Open a Pull Request
```

See [CONTRIBUTING.md](CONTRIBUTING.md) for the full guide.

---

## 📜 The Philosophical Lineage

This manifesto draws from a rich tradition of constitutional and libertarian thought:

| Thinker | Contribution to CSP |
|---------|-------------------|
| **Thomas Paine** (1737–1809) | Common sense as the highest political argument · Citizen sovereignty |
| **Thomas Jefferson** | 10th Amendment · Minimal federal government · States as laboratories |
| **James Madison** | Checks and balances · Federalism as competition |
| **Frédéric Bastiat** (1801–1850) | The broken window fallacy · Unseen economic consequences |
| **Gustave de Molinari** (1819–1912) | First anarcho-capitalist · Competition in security services |
| **Friedrich Hayek** | Denationalization of money · Spontaneous market order |
| **Murray Rothbard** | Non-Aggression Principle · Capitalization over redistribution |
| **Ron Paul** | Sound money · Non-interventionism · End the IRS |
| **Milton Friedman** | Negative income tax concept · School vouchers · Deregulation |
| **Henry George** | Land value and speculation (partially addressed via 0.025% symbolic tax) |

---

## 🔑 License

This project is licensed under **Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)**.

You are free to:
- **Share** — copy and redistribute in any medium or format
- **Adapt** — remix, transform, and build upon the material for any purpose

Under the following terms:
- **Attribution** — Give appropriate credit and link to this repository
- **ShareAlike** — Distribute your contributions under the same license

In the spirit of Thomas Paine, who refused to copyright *Common Sense* so that every printer in the colonies could distribute it freely — **ideas belong to everyone.**

---

## ⚠️ Disclaimer

This is a political philosophy and policy platform presented for public debate and democratic engagement. All budget figures are estimates based on publicly available federal data (Congressional Budget Office, Treasury, CBO, IRS Statistics of Income). The projections are models, not guarantees. The authors encourage independent verification of every number.

This project does not accept corporate donations, PAC money, or lobbying contributions — in keeping with the manifesto's own principles.

---

## 🌟 Star This Repository

If you believe America deserves a genuine third option — one that is honest about the math, grounded in the Constitution, and designed to benefit every American regardless of political background — **star this repository** and share it.

Thomas Paine distributed *Common Sense* for free. We're doing the same.

> *"These are the times that try men's souls."* — Thomas Paine, The Crisis, 1776

---

<div align="center">

**★ The Common Sense Party**

*Not Left. Not Right. Constitutional.*

[View the Site](https://YOUR_USERNAME.github.io/common-sense-party) · [Read the Manifesto](#) · [Contribute](#contributing) · [Translations](#)

</div>
