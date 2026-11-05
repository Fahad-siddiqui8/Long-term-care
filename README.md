# Long Term Care From Ellen (Ellen Atkins, CLTC)

A modern, full-width glassmorphic website created for **Long Term Care From Ellen**, operated by **Ellen Atkins, CLTC** (Certified in Long-Term Care) in Greensboro, North Carolina.

Based on the official Facebook business profile ([facebook.com/ltcfromellen](https://www.facebook.com/ltcfromellen)) and custom design reference brief.

---

## Features

- **Full-Width Glassmorphic Layout:** 1420px max-width container system with frosted glass panels, ambient glow spheres, and specular reflections (`backdrop-filter: blur(...)`).
- **Authentic Facebook Assets:** Official headshots, Nathan Mah Photography portraits, and community care images from Ellen's Facebook page.
- **Business Stock Photography:** High-resolution stock images incorporated into text container backgrounds, title typography (`background-clip: text`), and ambient section backdrops.
- **Interactive UI Components:**
  - Sticky glass header with navigation
  - Floating frosted review badges
  - 4-item live testimonial carousel
  - Interactive FAQ accordion
  - Booking & consultation modal with form validation
  - Animated toast notifications
  - Responsive mobile drawer menu & back-to-top button
- **Standalone & Offline-Ready:** Zero build steps required; works immediately in any modern browser.

---

## Business Information

- **Owner / Advisor:** Ellen Taylor Atkins, CLTC
- **Specialty:** Certified Long-Term Care Planning & Extended Care Services
- **Location:** 2401 Madison Avenue, Greensboro, NC 27403
- **Phone:** (336) 292-2236
- **Email:** ltc@ellenatkins.com
- **Facebook:** [https://www.facebook.com/ltcfromellen](https://www.facebook.com/ltcfromellen)

---

## Quick Start & Local Preview

Open `index.html` directly in any web browser, or run a local static server:

```bash
# Using Node.js
npx serve .

# Or using Python
python -m http.server 3000
```

---

## Deployment

### GitHub Pages
1. Push to your repository `main` branch.
2. Go to **Settings > Pages** in your GitHub repository.
3. Select `Branch: main` and `/ (root)`, then click **Save**.

### Vercel
Deploy with 1-click via the Vercel CLI or Dashboard:
```bash
npx vercel
```
