# Adewetan Tag & Title

An interactive, mobile-friendly Maryland tag and title reference website. The project organizes common vehicle-service information into searchable guides while clearly labeling details that still require official verification.

## Live website

[adewetantagandtitle.com](https://adewetantagandtitle.com)

## Project status

This is a pre-launch business concept and portfolio project. It does not currently accept real appointments, payments, or sensitive customer documents. Adewetan Tag & Title is not affiliated with MDOT MVA.

## Features

- Searchable Maryland service guides
- Title-transfer document planning
- Registration and renewal guidance
- Tag and license-plate reference information
- Duplicate-title guidance
- Salvage and rebuilt-vehicle roadmaps
- Mobile and remote-service planning
- Official MDOT MVA source links
- Clear verification and fee-boundary notices
- Responsive desktop and mobile layouts
- Pre-launch booking and payment demonstrations

## Technology

- TypeScript
- React 19
- Next.js 16
- Vinext and Vite
- Cloudflare Workers-compatible runtime
- Tailwind CSS tooling with custom CSS design

## Run locally

Prerequisites:

- Node.js 22.13 or newer
- npm

Install and start the development server:

```bash
npm install
npm run dev
```

Create a production build:

```bash
npm run build
```

## Main project structure

```text
app/
  page.tsx                    Main interactive landing page
  service-guides.ts          Structured guide content
  services/[slug]/page.tsx   Dedicated service-guide pages
  globals.css                Responsive visual system
public/                       Static assets
worker/                       Cloudflare-compatible entry point
```

## Information policy

Vehicle rules, forms, eligibility, fees, and processing requirements can change. The website links to official Maryland sources and uses verification labels where transaction-specific confirmation is still required. Users should verify all details directly with MDOT MVA before acting.

## Contact

- Website: [adewetantagandtitle.com](https://adewetantagandtitle.com)
- GitHub: [@dadewetan](https://github.com/dadewetan)

## License

This repository is provided as a portfolio and educational project. No license for commercial reuse is granted unless one is added explicitly.
