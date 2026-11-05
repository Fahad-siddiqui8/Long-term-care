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

## Image Asset Inventory (100% Local & Matched)

Every image referenced in `index.html` matches a local, tracked file in the `images/` directory:

| Image File | Description | Section Usage |
| :--- | :--- | :--- |
| **`ellen_headshot.jpg`** | Official headshot of Ellen Atkins, CLTC | Header logo badge, About card, Footer brand |
| **`ellen_portrait.jpg`** | Nathan Mah Photography portrait from FB | About Us collage tall card |
| **`fb_care_1.jpg`** | Authentic care consultation photo from FB | Hero showcase image & About collage card |
| **`fb_care_2.jpg`** | Authentic senior care support photo from FB | About Us bottom collage card |
| **`fb_care_3.jpg`** | Authentic caregiver interaction photo from FB | Local fallback asset |
| **`fb_cover.jpg`** | Official Facebook page cover banner | Brand asset |
| **`why_choose_us.jpg`** | Senior in wheelchair with nurse | "Why Choose Us" showcase card with glass badge |
| **`business_planning.jpg`** | Financial & policy planning documents | Hero text card & Connect form background |
| **`business_consulting.jpg`** | Client consultation & handshake | About Us text card & Process header background |
| **`business_healthcare.jpg`** | Healthcare records & clinical advisory | "Why Choose Us" text box background |
| **`business_testimonials.jpg`**| Client advisory partnership consultation | Testimonials panoramic section background |
| **`business_office.jpg`** | Corporate executive consulting office | "We're Here for You" connect info background |
| **`client_avatar_1.jpg`** | Testimonial client avatar (Chad Gibbons) | Live testimonial carousel review 1 |
| **`client_avatar_2.jpg`** | Testimonial client avatar (Sarah Glover) | Live testimonial carousel review 2 |
| **`client_avatar_3.jpg`** | Testimonial client avatar (David Hastings) | Live testimonial carousel review 3 |
| **`client_avatar_4.jpg`** | Testimonial client avatar (Margie Frazier) | Live testimonial carousel review 4 |

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
