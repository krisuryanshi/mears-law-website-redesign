# Mears Law Website Redesign 🌐  
**Riipen Industry Project – Frontend Web Development**

## Overview
This project is a redesign of the Mears Law website completed as part of a [Riipen Level UP](https://levelup.riipen.com) industry project. Students work directly with real companies, and the goal here was to update the firm's website while keeping it professional, clear, and easy for clients to use.

The work focused on the frontend. This included site structure, navigation, and layout changes built in Next.js. Updates were made over time based on team discussion and client feedback, with an emphasis on consistency and readiness for deployment.

A live demo for this repository is deployed on Vercel, with the firm's official website included for reference.

**Demo:** https://mearslaw-ten.vercel.app  
**Client Website (Reference):** https://www.mearslaw.ca

---

## Project Goals
The redesign focused on a few clear goals:

- Simple and consistent navigation  
- Clear layouts for key informational pages  
- A shared header and footer across the site  
- Analytics and basic SEO support  
- A visual style appropriate for a law firm  

---

## Key Features
- Responsive header and footer used across all routes  
- Pages for About, Services, Careers, Offices, Contact, and Privacy  
- Consultation booking page accessible from the navigation  
- Cookie notice and privacy terms  
- Google Analytics 4 integration  
- Sitemap and robots configuration for search engines  
- Public demo deployed on Vercel  

---

## Tech Stack
- Next.js (App Router)  
- React  
- JavaScript  
- CSS Modules  
- Google Analytics 4  
- Vercel  

---

## My Contributions
*This project was completed as part of a Riipen team. The points below describe my individual contributions.*

**Krish Suryavanshi**

- Built the site header and footer, including navigation and branding  
- Created and updated pages such as About, Offices, Careers, Contact, and Privacy  
- Improved layout consistency across the site through iterative changes  
- Added a table of contents to the Privacy page to improve readability  
- Updated footer styling, branding, and icon usage  
- Integrated Google Analytics 4  
- Took part in regular team meetings and client check-ins  

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
- This repository reflects a collaborative team project  
- The Vercel deployment linked above corresponds to this code  
- The client's official website is included for reference and may differ slightly  
- Commit history includes work from multiple contributors  
- The focus of this project was frontend layout and navigation rather than backend systems  
