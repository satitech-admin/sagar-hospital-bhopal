# Sagar Multispeciality Hospital — Digital Experience Prototype

[![Live Preview](https://img.shields.io/badge/Live%20Preview-Open%20Website-188B73?style=for-the-badge&logo=github)](https://htmlpreview.github.io/?https://raw.githubusercontent.com/satitech-admin/sagar-hospital-bhopal/main/index.html)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Open%20After%20Activation-0A3B46?style=for-the-badge&logo=github)](https://satitech-admin.github.io/sagar-hospital-bhopal/)

> **Independent concept demo**, not the official SMH website. Patient bookings, medical records, and live doctor availability are not connected. Never enter patient data into prototype workflows.

## Premium redesign (October 30, 2026)
- Cinematic dark-teal hero with animated orbit, image composition, floating appointment card, micro-interactions and CTA
- Continuous speciality marquee with hover pause
- Interactive quick-access tiles, featured speciality panels with hover transitions
- Editorial care-story section and animated three-step patient journey
- Three-image interactive facility concept gallery: manual previous/next, thumbnail selection and optional auto-slide
- IntersectionObserver scroll reveals and top scroll-progress indicator
- FAQ accordions, reduced-motion support, mobile-first responsive reflow
- Live FAQ chat, doctor-team filtering, searchable departments and booking handoff retained
- Illustrative photography, not official hospital images; replace after hospital approval

## Mobile responsiveness update (October 30, 2026)
- Mobile-first responsive styles tested at source/syntax level (not yet browser/device QA).
- Hamburger navigation with aria-expanded state, Escape close and touch-sized controls.
- Responsive photo heroes, cinematic hero composition and correctly stacked content.
- Single-column department/doctor cards on phones, two-column quick links when space permits.
- Responsive gallery thumbnails, forms, CTAs, footer and repositioned WhatsApp/chat buttons.
- 320px narrow-device layout and reduced-motion support.

## Features
- Responsive multi-page experience using hash-based routing (GitHub Pages-friendly)
- Home, About, Departments, Doctors, OPD Appointment Demo, Patient Guide, Contact
- Premium medical visual design, loading screen, icon cards, motion, smooth marquee, mobile navigation
- Searchable departments, filterable team directory (placeholder teams—not actual doctor identities)
- Appointment selection demo with **real booking handoff to the official hospital portal**, no fake slot confirmation
- Rule-based 24/7 FAQ assistant demo for hospital information, not medical advice
- Verified hospital contact links, emergency click-to-call, map directions
- Reduced-motion support, semantic markup, form validation

## Preview / deployment
**Live Preview** button above uses a public HTML-preview service and may behave differently from production hosting. To host on GitHub Pages, enable **Settings → Pages → Deploy from a branch → main → /(root)**. After activation, the GitHub Pages button should work. No claim is made that Pages has already been enabled.

Local: open `index.html` directly in a browser or run `python -m http.server 8000` and visit http://localhost:8000.

## Before actual hospital launch
1. Get written approval for brand identity, logo, official photos and published content.
2. Verify exact doctor names, credentials and OPD schedules with SMH.
3. Integrate an authenticated scheduling API and hospital-approved database; enforce conflict-free bookings, cancellation, notifications and audit logging.
4. Implement role-based access, consent, encryption, security reviews and applicable health-data protection requirements before storing patient records.
5. Replace FAQ demo with an approved knowledge base and monitored escalation workflow.
6. Complete accessibility, security, mobile, browser and end-to-end testing.

Hospital source: https://www.smhbhopal.com/
Official patient booking: https://patient-portal.smhbhopal.com/book-appointment

Design and prototype: Maa Sati Technologies.
