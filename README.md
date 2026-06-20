**Kundana Lam — Portfolio Website**

A personal portfolio website built to showcase my work as a Data Analyst & Web Developer.

Live site:** https://kundana-portfolio.vercel.app/**


**About**

This is a single-page portfolio presenting my background, technical skills, projects, hackathon experience, and certifications. The design follows a premium, minimal aesthetic — clean typography, generous whitespace, and subtle motion — inspired by modern product sites like Stripe and Apple.

The entire site is built as one self-contained index.html file: no frameworks, no build tools, no external JavaScript libraries. Just HTML, CSS, and vanilla JS.

**Features**

FeatureDetailsDark modeToggle in the navbar; preference is saved and persists across visitsResponsive layoutBuilt mobile-first with CSS Grid & Flexbox; adapts from desktop down to small screens, including a slide-out mobile menuScroll animationsSections fade and rise into view using the Intersection Observer APIAnimated countersKey stats (projects shipped, hackathons attended, CGPA) count up when scrolled into viewSticky navbarBackground blur and shadow appear on scroll; smooth in-page navigation to each sectionSelf-contained assetsProfile photo and resume are embedded directly as base64 — no external file dependencies

**Sections**


Hero — introduction and quick stats
About — bio and technical skill groups (languages, analytics/ML, web development)
Education — degree, institution, and current standing
Projects — work pulled from GitHub repositories plus independent Python projects
Journey — a timeline of milestones: coursework, independent builds, and hackathons
Achievements & Certifications — courses, workshops, and competition results
Contact — email, phone, social links, and resume download


**Design System**


Typography: Fraunces for display headings, Inter for body text, JetBrains Mono for labels and stats
Color theme: Blue accent on a light/dark neutral base, controlled entirely through CSS custom properties for easy theming
Layout: CSS Grid for section structure, Flexbox for component-level alignment
Motion: CSS transitions and the Intersection Observer API for scroll-triggered reveals — no animation libraries


**Tech Stack**


HTML5 — semantic markup
CSS3 — custom properties, Grid, Flexbox, no CSS framework
Vanilla JavaScript — dark mode persistence, scroll reveals, animated counters, mobile navigation
Google Fonts — the only external dependency


**File Structure**

.
├── index.html      # Full site: markup, styles, and scripts in one file
└── README.md

**Contact**


Email: kundanalam07@gmail.com
LinkedIn: linkedin.com/in/kundana-lam
GitHub: github.com/kundanalam
