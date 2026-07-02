Oakstead Light Foundation — Website
A clean, responsive homepage for Oakstead Light Foundation, an NGO delivering sexual and reproductive health rights (SRHR) education and mental health outreach across Zombo, Pakwachi, and Nebbi districts in West Nile, Uganda.
Built as a static prototype (single HTML file, no build step) to serve as the visual reference for the full platform, which includes volunteer registration, donation processing, and admin dashboards.
Preview
Open index.html in any browser — no server or dependencies required.
Sections
Section
Description
Hero
Dawn/horizon-themed intro with mission statement and primary CTAs (Donate / Volunteer)
About
Foundation story, mission, and core values
Services
Three core programs — SRHR Education, Mental Health Outreach, Community Empowerment — each tagged by district
Projects
Blog-style updates from the field (Zombo, Pakwachi, Nebbi), featuring a spotlighted project card
Contact
Contact details, district location pins, and a message form
Footer
Quick links, program locations, newsletter signup, and social links
Design system
Palette: deep indigo #14213D · sunrise amber #E8A33D · warm ivory #FBF8F2 · forest green #435E3A
Typography: Fraunces (display) + Inter (body), loaded via Google Fonts
Motif: a recurring sunrise/horizon mark ties back to the Foundation's name, used in the hero, section eyebrows, and project thumbnails
Fully responsive down to mobile (breakpoints at 900px and 720px), with a collapsible nav menu
Respects prefers-reduced-motion
Tech
Plain HTML, CSS, and vanilla JS — no framework, no build tools, no dependencies beyond the Google Fonts CDN. Everything lives in index.html.
Known limitations / next steps
Contact form is static. It doesn't send anywhere yet — wire it up to a form service (e.g. Formspree) or a backend endpoint.
Project cards are hardcoded. To let non-developers post updates, migrate this section to a CMS-driven loop (see Roadmap).
Newsletter signup is static — needs an email provider integration (Mailchimp, Buttondown, etc.).
Images are currently illustrative SVGs rather than real photos; swap in program photography when available.
Roadmap
This prototype is the first step toward the full platform described in the project's technical proposal, which includes:
[ ] Volunteer registration with Super Admin approval workflow
[ ] Secure donation processing (gateway-tokenized, e.g. Stripe/PayPal/Flutterwave)
[ ] Three role-based dashboards: Volunteer/Donor, Admin, Super Admin
[ ] Donation receipts and history per volunteer
[ ] CMS-driven Projects/Blog section
[ ] Migration target: WordPress + Elementor + GiveWP (or a custom PHP/Node build)
License
© 2026 Oakstead Light Foundation. All rights reserved.
