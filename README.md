# KoriX Digital Studio

Professional web design agency website built for rapid client acquisition and onboarding.

## Features

- **Services & Pricing** — Website, Branding, E-Commerce, AI Services with Starter/Growth/Pro tiers
- **Bundle Packages** — Startup Launch Pack, Restaurant Digital Pack, Full Stack Business
- **Portfolio Section** — 3 showcase cards (ready for client mockups)
- **Client Intake Form** — 3-step modal form (project type, timeline, budget, contact info)
- **AI Chat Widget** — FAQ bot with lead capture and discovery call booking
- **Team Profiles** — Kori, Atelier, Atlas, Vega
- **Mobile Responsive** — Optimized for all devices
- **Zero Dependencies** — Plain HTML/CSS/JS, instant load (61KB, 0.6s)

## Tech Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Forms:** Embedded modal (no external tool required)
- **Chat Widget:** Self-contained FAQ bot with lead capture
- **Deployment:** Static hosting (GitHub Pages, Netlify, Vercel, or any CDN)

## Customization

### Update Services & Pricing
Edit the `services` array in the HTML (search for `const services = [`).

### Add Portfolio Images
Replace placeholder images in the portfolio section with your mockups.

### Connect Forms to Email
The contact form and intake form currently log to console. Use Formspree, EmailJS, or a backend API.

### Link Calendly
Update the discovery call links (search for `calendly.com`).

## Deployment

### GitHub Pages
1. Go to repo Settings → Pages
2. Select "Deploy from a branch" → main
3. Site will be live at `https://koriaryan1432.github.io/korix-digital-studio`

### Netlify / Vercel
1. Connect your GitHub repo
2. Set publish directory: `.` (root)
3. Deploy

## Performance

- **Size:** 61KB (single HTML file)
- **Load Time:** 0.6s (on 4G)
- **Lighthouse Score:** 95+ (no external dependencies)

---

**Built with ❤️ by Atlas (Full-Stack Engineer)**