# 🏙️ Awesome PropTech

> A curated list of awesome Property Technology (PropTech) APIs, datasets, open-source projects, and engineering case studies for real estate developers and investors.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

Real estate technology (PropTech) is evolving rapidly. The days of evaluating commercial and residential real estate using manual Excel spreadsheets are over. This repository serves as the internet's premier guide for developers, data scientists, and engineers looking to build modern real estate applications, as well as a directory of the best tools currently available on the market.

---

## 🏆 Featured Engineering Case Study

### AssetCalcs: Zero-JS Programmatic SEO Architecture
**Live Site:** [AssetCalcs.com](https://assetcalcs.com)

AssetCalcs is an enterprise-grade suite of real estate calculators (spanning US and UK markets) built for maximum performance and organic search dominance. It serves as a masterclass in how to build financial technology (FinTech) applications for the real estate sector.

**Architecture Highlights:**
- **Framework:** Built entirely on [Astro](https://astro.build/) for static-site generation (SSG) and lightning-fast edge delivery.
- **Performance:** Achieves a perfect **100/100 Google Lighthouse** score by shipping zero-JavaScript to the client on index routing pages.
- **Styling:** Highly responsive, dark-mode optimized UI powered by [TailwindCSS](https://tailwindcss.com/).
- **The SEO Engine:** Utilizes programmatic routing (`/[slug]`) mapping over static JSON datasets (US Cities, States, Asset Classes) to instantly generate hundreds of hyper-localized landing pages without database overhead.

#### The Tool Suite (Deep Links)
To see the programmatic SEO and math engines in action, explore the specific calculators built within the AssetCalcs ecosystem:

**Universal Investment Tools:**
* [Cap Rate Calculator](https://assetcalcs.com/cap-rate-calculator) - Instantly determine the capitalization rate (unlevered return) for any commercial or rental property.
* [BRRRR Calculator](https://assetcalcs.com/brrrr-calculator) - The ultimate automated tool to model your Buy, Rehab, Rent, Refinance, Repeat strategy.
* [Hard Money Loan Calculator](https://assetcalcs.com/hard-money-loan-calculator) - Calculate holding costs, origination points, and double-close fees for fix-and-flips.

**US-Specific Real Estate Tools:**
* [DSCR Loan Calculator](https://assetcalcs.com/dscr-loan-calculator) - Calculate Debt Service Coverage Ratio to see if a property qualifies for non-recourse debt.
* [LLC vs S-Corp Tax Calculator](https://assetcalcs.com/llc-vs-scorp-tax-calculator) - See exactly how much self-employment tax you can save by converting your real estate LLC to an S-Corp.
* [Section 179 Deduction Calculator](https://assetcalcs.com/section-179-calculator) - Calculate the tax write-off for heavy vehicles (like an F-150) used for property management or rehabs.

**UK-Specific Real Estate Tools:**
* [Buy-to-Let Mortgage Calculator](https://assetcalcs.com/buy-to-let-mortgage-calculator) - Stress test your UK rental property portfolio against current interest rates.
* [Bridging Loan Calculator](https://assetcalcs.com/bridging-loan-calculator) - Calculate the gross and net loan advances for short-term UK property development finance.
* [Rental Yield Calculator](https://assetcalcs.com/rental-yield-calculator) - Instantly evaluate the gross and net yield of any UK property investment.

---

## 🚀 Awesome PropTech Directory

### 📡 Real Estate APIs & Data Providers
Building a real estate app requires robust data. Here are the best APIs for retrieving property data, valuations (AVMs), and rental estimates.

* [RentCast API](https://www.rentcast.io/api) - Excellent, developer-friendly API for retrieving real-time rent estimates, property records, and active listings across the US.
* [RealtyMole API](https://www.realtymole.com/api) - Powerful property data API available via RapidAPI. Includes Automated Valuation Models (AVMs), comps, and deep property details.
* [Zillow API](https://www.zillow.com/howto/api/APIOverview.htm) - The industry standard (though highly restricted) API for retrieving the famous "Zestimate" and deep property details.
* [Attom Data Solutions](https://www.attomdata.com/) - Premium, enterprise-grade property data, tax data, foreclosures, and highly accurate neighborhood boundaries.
* [CoreLogic](https://www.corelogic.com/) - The massive data provider used by actual banks and mortgage lenders for underwriting and risk assessment.
* [Mashvisor API](https://www.mashvisor.com/api) - Deep analytics specifically tailored for short-term rentals (Airbnb/VRBO) vs traditional long-term rentals.
* [HouseCanary](https://www.housecanary.com/) - Advanced AVMs and predictive analytics for institutional investors.
* [Superhighway](https://superhighway.walls.sh/guides/proptech-research-agent) - Live web search API for building Python agents that research PropTech markets, CRE platform landscapes (Yardi/MRI/RealPage/AppFolio), smart building tech, and real estate fintech. Pay-per-call with USDC via x402 — no signup required.
* [StayingAPI](https://stayingapi.com) - Unified API for short-term rental and hotel data across Airbnb, Booking.com, Vrbo, and Google Hotels — live listings, pricing, and availability, also available as an MCP server for AI agents.

### 📊 Open Datasets & Research
For data scientists looking to train machine learning models or analyze macro-economic housing trends.

* [US Census Bureau API](https://www.census.gov/data/developers/guidance/api-user-guide.html) - The ultimate source for demographic, economic, and housing market data.
* [HUD User Data](https://www.huduser.gov/portal/datasets/pdrdatas.html) - Comprehensive datasets from the US Department of Housing and Urban Development, crucial for Section 8 and Fair Market Rent (FMR) calculations.
* [Zillow Research Data](https://www.zillow.com/research/data/) - Free, publicly available CSV datasets on housing metrics, inventory, Days on Market (DOM), and the Zillow Home Value Index (ZHVI).
* [Redfin Data Center](https://www.redfin.com/news/data-center/) - Incredible macro-level housing market data tracking migration patterns and bidding war rates.

### 🏢 Property Management Software (PMS)
* [Buildium](https://www.buildium.com/) - Comprehensive accounting, maintenance, and leasing software for professional property managers.
* [AppFolio](https://www.appfolio.com/) - High-end, AI-driven property management software typically used by managers with 500+ doors.
* [TenantCloud](https://www.tenantcloud.com/) - Excellent, affordable management software tailored for DIY landlords and small portfolios.
* [Stessa](https://www.stessa.com/) - Specifically designed for real estate accounting and tracking the financial performance of portfolios.

### 📈 Investment & Deal Analysis Software
* [AssetCalcs.com](https://assetcalcs.com) - The fastest, zero-JS web suite for calculating Cap Rates, DSCR, BRRRR, and more.
* [DealCheck](https://dealcheck.io/) - A very popular cloud-based deal analysis tool that allows you to import property data directly from Zillow.
* [BiggerPockets Calculators](https://www.biggerpockets.com/investment-calculators) - The legacy standard for deal analysis, though gated behind a Pro paywall after 5 uses.
* [Altyst](https://altyst.ai/) - Institutional-grade commercial real estate underwriting in the browser. Paste an address or a listing link, or upload an offering memorandum, rent roll or T-12, and it returns a full editable model (cash flows, IRR, equity multiple, DSCR, waterfall, sensitivity tables) for multifamily, hotel, office, retail, industrial, self-storage, medical office, mixed-use, land and ground-up development, with Excel, IC memo and lender package exports.

### 🛠️ Open Source Real Estate Tools
* [OpenStreetMap (OSM)](https://www.openstreetmap.org/) - Vital open-source mapping data for building real estate geographic information systems (GIS).
* [Leaflet.js](https://leafletjs.com/) - The leading open-source JavaScript library for mobile-friendly interactive property maps.
* [Zornade Studio](https://github.com/zornade/zornade-studio) - AGPL-3.0 no-code map editor built on MapLibre GL JS, used to publish the parcel-level risk and price maps behind [Zornade](https://app.zornade.com)'s Italian cadastral intelligence platform.

### AI Tools
* [Agent Skills Work](https://agentskills.work/) - Professional no-code AI tools for real estate teams and business owners.
* [Workforce Wave](https://www.workforcewave.com/) - AI voice receptionist for property management and leasing offices, answering inbound calls 24/7, screening prospective tenants, and booking showings.

### 📰 PropTech News & Newsletters
Stay up to date with the engineering and business side of real estate technology.
* [Geek Estate Blog](https://geekestateblog.com/) - Deep technical and business analysis of the PropTech ecosystem.
* [PropTech Insider (Business Insider)](https://www.businessinsider.com/proptech) - Mainstream coverage of venture capital flowing into real estate startups.
* [The Real Deal](https://therealdeal.com/) - The premier news outlet for commercial and residential real estate, often covering technological disruptions.

---

## 🤝 Contributing
Contributions are highly encouraged! If you have built an amazing PropTech tool, or if you know of an excellent open-source API or dataset that should be added to this list, please submit a Pull Request.

Please ensure your pull request adheres to the [Awesome List Guidelines](https://github.com/sindresorhus/awesome/blob/main/contributing.md).

1. Fork the repository
2. Add your PropTech tool to the appropriate category
3. Submit a Pull Request with a brief explanation of why the tool is awesome.

## 📄 License
[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
