# Small Business Truth

A data-driven landing page exposing the economic disparities facing small business owners in America.

## Features

- **The Daily Squeeze** — 69% higher compliance costs, 90% higher tax compliance, 35% higher healthcare premiums
- **Tax Comparison** — You vs Forbes 400 billionaires
- **Buy, Borrow, Die** — How billionaires pay 0% forever
- **Tech Billionaire Corruption** — Musk ($38B+ subsidies), Thiel ($970M contracts), Ellison ($500B Stargate)
- **Healthcare Disadvantage** — 35% higher premiums, vicious talent cycle
- **Political Corruption** — $4.4B lobbying, same corporate sponsors fund both parties
- **American Dream Decline** — 90% (1940) → 50% (today) mobility

## Tech Stack

- [Astro](https://astro.build/) — Static site generator
- [Tailwind CSS](https://tailwindcss.com/) — Utility-first CSS
- Google Fonts (Outfit, Newsreader, IBM Plex Mono)

## Getting Started

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Project Structure

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── Hero.astro
│   │   ├── DailySqueeze.astro
│   │   ├── TaxComparison.astro
│   │   ├── TaxLoopholes.astro
│   │   ├── BuyBorrowDie.astro
│   │   ├── TechBillionaires.astro
│   │   ├── Healthcare.astro
│   │   ├── WhoWroteRules.astro
│   │   ├── WealthConcentration.astro
│   │   ├── BusinessPolls.astro
│   │   ├── AmericanDream.astro
│   │   ├── BottomLine.astro
│   │   └── Sources.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
├── astro.config.mjs
├── tailwind.config.mjs
└── package.json
```

## Sources

All statistics from verified, non-partisan sources including:
- Federal Reserve DFA Q2 2024
- IRS Statistics of Income 2024
- ProPublica Tax Investigations
- Washington Post Feb 2025
- U.S. Chamber of Commerce Q4 2024
- KFF Employer Health Benefits Survey 2024
- Harvard Opportunity Insights
- OpenSecrets 2024
- USAspending.gov
- SEC Tesla Proxy Statements

## Deployment

This site can be deployed to any static hosting platform:

```bash
npm run build
# Deploy the dist/ folder
```

Recommended platforms:
- [Vercel](https://vercel.com)
- [Netlify](https://netlify.com)
- [Cloudflare Pages](https://pages.cloudflare.com)

## License

MIT
