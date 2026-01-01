# Mears Law Website Redesign 🌐  
**Riipen Industry Project – Frontend Web Development**

## Overview
This project is a redesign of the Mears Law website completed as part of a [Riipen Level UP](https://levelup.riipen.com) industry project, a short-term paid internship program where students work directly with real companies on real projects. The goal was to modernize the firm’s web presence while keeping the site professional, clear, and easy to navigate for clients.

The work focuses on frontend structure, navigation, and page-level UI improvements within a real, collaborative Next.js codebase. Changes were made iteratively based on team discussions and client feedback, with attention to polish, consistency, and deployment readiness rather than one-off demos.

A live demo corresponding to this repository is deployed on Vercel, with the firm’s official website included for reference.

**Demo:** https://mearslaw-ten.vercel.app  
**Client Website (Reference):** https://www.mearslaw.ca

---

## Project Goals
The redesign focused on a few core priorities:

- Clear, consistent navigation across all pages  
- Improved layout and readability for key informational routes  
- A shared header and footer to unify the site structure  
- Production-ready touches such as analytics and SEO basics  
- A clean visual identity aligned with a professional law firm  

---

## Key Features
- Responsive header and footer used across all routes  
- Dedicated pages for About, Services, Careers, Offices, Contact, and Privacy  
- Consultation booking page accessible from the navigation bar  
- Cookie notice and privacy terms for compliance and transparency  
- Google Analytics 4 integration for traffic tracking  
- SEO support through sitemap and robots configuration  
- Public demo deployment via Vercel  

---

## Tech Stack
- Next.js (App Router)
- React
- JavaScript
- CSS Modules
- Google Analytics 4
- Vercel (deployment)

---

## My Contributions
*This project was completed as part of a Riipen team. The section below describes my individual contributions.*

**Krish Suryavanshi**

- Designed and implemented the site-wide header and footer, including navigation and branding  
- Created and redesigned core pages including About, Offices, Careers, Contact, and Privacy  
- Improved UI consistency and layout across multiple routes through iterative refinement  
- Added a table of contents to the Privacy page to improve readability  
- Refined footer design and updated branding and icon usage  
- Integrated Google Analytics 4 tracking to support production readiness  
- Contributed consistently over several weeks through coordinated team and client check-ins  

---

## Deployment Notes
- Local development runs at `localhost:3000` and is used for testing and iteration  
- The Vercel link above reflects this repository and serves as the primary demo  
- The official Mears Law website is included for reference and may differ slightly depending on deployment timing and configuration  

---

## Repository Structure
```
mears-law-website-redesign/
│
├── public/                     # Publicly served static assets
│ ├── Lawyers-Video.mp4         # Background video used on site sections
│ ├── Night-City.mp4            # Primary hero background video
│ ├── Night-City-Old.mp4        # Older hero video version
│ ├── file.svg                  # UI icon
│ ├── globe.svg                 # UI icon
│ ├── next.svg                  # Default Next.js asset
│ ├── vercel.svg                # Default Vercel asset
│ ├── window.svg                # UI icon
│ └── images/                   # Image assets used across the site
│ ├── law1.jpg                  # Page/section image
│ ├── law2.jpg                  # Page/section image
│ ├── law3.jpg                  # Page/section image
│ └── mears-logo.png            # Firm logo
│
├── src/app/                    # Next.js App Router source
│ ├── favicon.ico               # Site favicon
│ ├── globals.css               # Global styles applied site-wide
│ ├── layout.js                 # Root layout (header, footer, metadata)
│ ├── page.js                   # Home page route
│ ├── robots.js                 # Robots.txt configuration
│ ├── sitemap.js                # Sitemap generation for SEO
│ ├── GAListener.jsx            # Google Analytics page-view tracking
│ │
│ ├── components/               # Reusable UI components
│ │ ├── Header.js               # Site header and navigation
│ │ ├── Footer.js               # Site footer and links
│ │ ├── CookieNotice.jsx        # Cookie consent banner
│ │ ├── CookieNotice.css        # Styles for cookie notice
│ │ ├── hero.js                 # Home hero section component
│ │ ├── hero.css                # Styles for hero section
│ │ ├── OurValues.js            # “Our Values” section component
│ │ ├── OurValues.css           # Styles for values section
│ │ ├── AISearchResults.js      # UI for AI search results
│ │ ├── MicrosoftForm.js        # Embedded Microsoft form component
│ │ ├── containers.js           # Layout container helpers
│ │ └── containers.module.css   # Container styles
│ │
│ ├── lib/                      # Shared logic and helper data
│ │ ├── geminiAIService.js      # Gemini AI service wrapper
│ │ └── trainingData.js         # AI prompt and Q&A training data
│ │
│ ├── api/                      # API routes
│ │ └── ai-search/              # AI search endpoint
│ │ └── route.js                # Server-side handler for AI search
│ │
│ ├── about/                    # About page route
│ │ ├── layout.js               # About layout wrapper
│ │ └── page.js                 # About page content
│ │
│ ├── services/                 # Services page route
│ │ ├── layout.js               # Services layout wrapper
│ │ └── page.js                 # Services page content
│ │
│ ├── careers/                  # Careers page route
│ │ ├── layout.js               # Careers layout wrapper
│ │ └── page.js                 # Careers page content
│ │
│ ├── contact/                  # Contact page route
│ │ ├── layout.js               # Contact layout wrapper
│ │ └── page.js                 # Contact page content
│ │
│ ├── offices/                  # Offices page route
│ │ ├── layout.js               # Offices layout wrapper
│ │ └── page.js                 # Offices page content
│ │
│ ├── privacy/                  # Privacy / terms route
│ │ ├── PrivacyTerms.css        # Privacy page styling
│ │ ├── layout.js               # Privacy layout wrapper
│ │ └── page.js                 # Privacy page content
│ │
│ ├── book/                     # Book Consultation route
│ │ ├── BookConsultation.js     # Booking form logic/component
│ │ └── page.js                 # Booking page route
│ │
│ └── newsletter/               # Newsletter signup route
│ └── page.js                   # Newsletter page content
│
├── .gitignore                  # Git ignore rules
├── README.md                   # Project documentation
├── jsconfig.json               # Path aliases and JS tooling config
├── next.config.mjs             # Next.js configuration
├── package-lock.json           # Locked dependency versions
├── package.json                # Dependencies and npm scripts
└── test-ai-api.js              # Local script for testing the AI API
```

---

## Notes
- This repository reflects a collaborative, production-style workflow rather than a standalone demo  
- Commit history includes work from multiple contributors and iterative updates over time  
- The primary focus of this project was frontend structure, layout, and polish rather than backend systems  
