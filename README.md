Prodigy Society — Official Club Website

Premium production-ready multi-page website for Prodigy Society, the student-led innovation & technology club at Tilottama Campus, Tilottama Yogikuti, Rupandehi, Nepal.

Tech Stack





HTML5 (semantic, accessible)



CSS3 (custom properties, glassmorphism, responsive)



Vanilla JavaScript (no frameworks)

Pages







Page



File



Description





Home



index.html



Hero, counters, mission, events preview, testimonials, newsletter





About



about.html



Story, pillars, FAQ





Board



board.html



Board of Directors + Sub-Committee cards





Members



members.html



Membership info + member highlights





Events



events.html



Filterable event cards + countdown timers





Gallery



gallery.html



Masonry gallery + lightbox + filters





Contact



contact.html



Form (validated), map, social links





Admin



admin.html



Hidden dashboard (not in nav)

Design

Deep Ocean Skeuomorphic theme inspired by Apple / Framer / Vercel / Stripe / Linear.







Token



Value





Background



#0f1419





Cards



#192028





Accent



#4a9a8e





Text



#a8b2c1





Highlight



#72d3c6

Dark / light theme toggle with localStorage persistence.

Features





Interactive particle canvas background (home)



Animated counters, typing effect, card tilt, ripples



Custom cursor (desktop), scroll progress bar



FAQ accordion, testimonials carousel (drag)



Event filters & countdown timers



Gallery lightbox & category filters



Contact form + newsletter → localStorage



Loading screen, back-to-top, reveal-on-scroll



Fully responsive (desktop → mobile)



SEO: meta, Open Graph, Twitter Cards, structured data, robots.txt, sitemap.xml



WCAG-oriented: semantic HTML, ARIA, keyboard focus, contrast

Admin Panel

Access: open /admin.html (not linked in navigation).

Credentials (demo):





Username: admin



Password: prodigy2083

Uses sessionStorage for auth and localStorage as a simulated database for members, events, gallery URLs, announcements, newsletter subscribers, and contact messages.

Project Structure

prodigy-society/
├── index.html
├── about.html
├── board.html
├── members.html
├── events.html
├── gallery.html
├── contact.html
├── admin.html
├── robots.txt
├── sitemap.xml
├── README.md
├── assets/
│   ├── logo.png
│   └── campus.jpg
├── css/
│   ├── main.css          (imports all)
│   ├── variables.css
│   ├── base.css
│   ├── nav.css
│   └── components.css
└── js/
    ├── main.js
    └── particles.js

Deploy

Serve the folder as static files (any static host: Netlify, Vercel, GitHub Pages, Nginx, etc.).

# Local preview (Python)
cd prodigy-society
python -m http.server 8080
# open http://localhost:8080

Update sitemap.xml and Open Graph URLs to your production domain before going live.

Contact





Email: drewthecrewttc@gmail.com



Location: Tilottama Yogikuti, Rupandehi, Nepal



College: Tilottama Campus



© 2083 Prodigy Society · Tilottama Campus
