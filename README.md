# Vancore Finance

An investor-facing website presenting Vancore Finance’s vision for a unified financial intelligence platform.

**[Visit the website](https://neha-smhs.github.io/vancore-finance/)**

> See your whole financial world. Then see what comes next.

## About the Project

Vancore Finance is building one intelligent system to connect financial data, reveal true net worth, protect liquidity and model tomorrow’s decisions.

The goal is to automate financial collection, valuation, categorisation and monitoring, giving users a complete picture of their finances to view, analyse and manage.

This repository contains the public presentation website. It does not contain the underlying financial platform.

## Product Vision

| Capability | Intended purpose |
|---|---|
| Financial Passport | Combine assets and liabilities into one consolidated net-worth figure. |
| Portfolio | Bring cash, investments, property and valuable possessions into a single financial record. |
| Vancore Valuator | Estimate alternative asset values using external pricing sources. |
| Tax Harvester | Automate transaction categorisation and estimated tax calculations. |
| Financial Independence Day | Project when passive portfolio income could cover living expenses. |
| Lumix | Support analyses, record updates and reminders through user-approved actions. |
| Anomaly Detection | Flag unusual spending patterns and unexpected cost increases. |
| Financial Calendar | Connect upcoming payments with available funds and liquidity alerts. |
| Financial Simulator | Explore how life changes could affect future wealth and cash flow. |
| Safe Withdrawal Rate Testing | Examine retirement withdrawals and portfolio longevity across market scenarios. |
| Live Tax Estimation | Estimate tax obligations and help users plan a liquidity buffer. |
| Personalised News Signals | Surface developments relevant to portfolio holdings and risk profiles. |

These capabilities are planned or in development. References to external pricing providers do not imply confirmed partnerships or live integrations. Financial projections, valuations and tax calculations are estimates.

## Website Features

- English and Polish language options.
- Responsive layouts for desktop, tablet and mobile.
- Interactive product module previews.
- Product vision, capabilities and development roadmap.
- Investor contact and closed-beta registration links.
- Static deployment through GitHub Pages.

## Technology

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts
- GitHub Pages

No framework, package installation or build step is required.

## Published Site Structure

The files required to serve the website are:

index.html
.nojekyll
assets/
styles.css
script.js
vancore-finance-logo.png

Keep the `assets` folder alongside `index.html`. The homepage uses relative paths to load its styling, scripts and logo.

## Run Locally

Clone the repository:

    git clone https://github.com/neha-smhs/vancore-finance.git
    cd vancore-finance

Start a local server using Python:

    python3 -m http.server 8000

Open http://localhost:8000 in your browser.

## Update the Website

- Edit `index.html` to change page structure and default English content.
- Edit `assets/styles.css` to update colours, typography and layouts.
- Edit `assets/script.js` to update translations and interactive behaviour.
- Replace `assets/vancore-finance-logo.png` to change the logo.

When changing translated content, update the corresponding language entries in `assets/script.js` and keep the HTML `data-i18n` keys consistent.

## Deployment

The website is published through GitHub Pages.

Repository settings:

- **Source:** Deploy from a branch
- **Branch:** `main`
- **Folder:** `/ (root)`

Commit changes to `main` to trigger a new deployment. Check the repository’s **Actions** tab for deployment status.

The `.nojekyll` file allows the site to be served as static files without Jekyll processing.

## Contact

- **Investor enquiries:** [beta@vancore.pl](mailto:beta@vancore.pl)
- **Closed beta:** [Register your interest](https://tally.so/r/Y5pY4z)
- **Website:** [Vancore Finance](https://neha-smhs.github.io/vancore-finance/)

---

Product visuals are illustrative and represent a platform under development. Website content is informational and does not constitute personalised financial or tax advice.
