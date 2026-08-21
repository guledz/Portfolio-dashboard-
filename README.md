# Portfolio-dashboard
 Guled Hassen — Portfolio Command Center
Live Demo: https://guledz.github.io/Portfolio/

📌 About This Project
A world‑class, award‑level personal portfolio website for Guled Hassen — Engineer, Digital Creator, and Developer. This single‑file HTML portfolio is designed as a premium digital identity experience combining engineering precision, cinematic motion, and editorial design with metallic gold accents.

The portfolio showcases multidisciplinary work across engineering, web development, digital products, business systems, UI/UX, digital marketing, and creative technology — all within a sophisticated, dark‑themed, fully responsive single‑page experience.

✨ Key Features
Cinematic Opening Sequence — 11‑second rising title animation with metallic gold light sweep

Custom Profile Avatar — Upload your photo or use a local profile.jpg file

A4 Print‑Ready CV — Generate a perfectly formatted CV with your photo, ready to print or download as PDF

Dynamic Project Showcase — Filterable project grid with live status badges and case study modals

Multidisciplinary Identity — Editorial‑style "Think. Build. Transform." section with skill tags

Capabilities & Services — Interactive capability cards with hover‑reveal descriptions

Professional Timeline — Experience section with structured background entries

Premium Navigation — Glass‑morphism floating nav with gold hover states

Custom Cursor — Desktop‑only premium cursor with interactive hover effects

Scroll‑Triggered Animations — Smooth reveal animations powered by IntersectionObserver

Fully Responsive — Optimized for 320px → 2560px screens

Reduced Motion Support — Respects prefers-reduced-motion preferences

Accessibility — Semantic HTML, ARIA labels, keyboard navigation, skip link

Single‑File Architecture — Everything (HTML, CSS, JS) contained in one index.html

🛠️ Technologies Used
Technology	Purpose
HTML5	Semantic structure
CSS3	Custom properties, animations, responsive grid
Vanilla JavaScript	IntersectionObserver, localStorage, dynamic rendering
Google Fonts (Inter)	Premium typography
html2canvas	PDF generation for CV
No frameworks. No Bootstrap, Tailwind, React, Vue, or Angular. Pure, lightweight, performant vanilla code.

📁 File Structure
text
/
├── index.html          # Complete portfolio (HTML + CSS + JS)
├── profile.jpg         # Your profile photo (place in same folder)
└── README.md           # This file
🚀 Deployment (GitHub Pages)
Fork or clone this repository.

Replace profile.jpg with your own photo (same filename, same folder).

Customize the data inside the <script> tags:

projects array — update with your own projects

services array — update your service offerings

experience array — update your professional background

contactData — update your contact information

Enable GitHub Pages in your repository settings (branch: main, folder: /).

Visit https://yourusername.github.io/Portfolio/

🖼️ Profile Image Setup
The portfolio looks for profile.jpg in the root folder by default. You can:

Replace the file with your own photo (name it profile.jpg)

Upload a photo via the gold camera icon on the avatar (stored in your browser's localStorage)

Double‑click the avatar to revert from uploaded photo back to profile.jpg

📄 CV Generation
Click the CV button in the hero section to open a print‑ready A4‑formatted CV that includes:

Your profile photo

Professional summary

Experience timeline

Skills & capabilities

Selected projects

Contact information

From the CV overlay, you can:

Print directly

Download as PDF (using html2canvas)

Close to return to the portfolio

🎨 Design Philosophy
This portfolio is built around the following design principles:

Typography‑First — Large, bold, editorial typography as the primary visual

Sophisticated Space — Generous negative space, deep charcoal backgrounds

Gold as Accent — Metallic gold used sparingly for emphasis and prestige

Cinematic Motion — Smooth, purposeful animations with professional easing

Editorial Composition — Feels like a premium technology magazine, not a template

Engineering Precision — Clean, structured, purposeful code and layout

📱 Responsive Breakpoints
Breakpoint	Optimization
2560px	Widescreen desktop
1440px	Standard desktop
1024px	Small desktop / landscape tablet
768px	Portrait tablet
430px	Large phone
390px	Standard phone
375px	Small phone
320px	Minimal phone support
♿ Accessibility
Semantic HTML elements

Proper heading hierarchy (h1 → h6)

Keyboard navigation support

Visible focus states

ARIA labels on interactive elements

Reduced‑motion media query support

Skip‑to‑content link

🚦 Performance
Lightweight — single file under 100KB (excluding fonts)

No external dependencies except Google Fonts & html2canvas (loaded conditionally)

CSS animations preferred over JavaScript for motion

IntersectionObserver for scroll‑triggered reveals

LocalStorage for avatar persistence

📄 License
MIT License — feel free to use, modify, and distribute.

🙋‍♂️ Author
Guled Hassen
Engineer · Digital Creator · Developer
LinkedIn · Portfolio · Telegram

⭐ Support
If you find this portfolio template useful, please consider starring the repository and sharing it with others!

Built with ❤️ and vanilla code.

