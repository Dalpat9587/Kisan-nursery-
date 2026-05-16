# 🌿 Kisan Nursery — Website

A professional, fully responsive static website for **Kisan Nursery**, a landscaping and gardening business owned by **Narayan Patel**.

---

## 📋 Overview

| Detail | Info |
|---|---|
| **Business** | Kisan Nursery |
| **Owner** | Narayan Patel |
| **Phone** | +91 93518 67987 |
| **Type** | Static HTML/CSS Website |
| **File** | `kisan-nursery.html` |

---

## 🗂️ Sections

1. **Navbar** — Sticky top navigation with logo and Book Now CTA
2. **Hero** — Full-screen banner with headline, buttons and live stats
3. **Trust Bar** — Five key credibility points
4. **About** — Story, overlapping images and feature highlights
5. **Services** — Six service cards on a dark green background
6. **Gallery** — Mosaic image grid with hover captions
7. **How We Work** — 4-step process timeline
8. **Why Choose Us** — Image with stats overlay and reasons list
9. **Plants Showcase** — Four plant category cards
10. **Testimonials** — Three client reviews with ratings
11. **Clients** — Four client type cards
12. **CTA Banner** — Mid-page call-to-action
13. **Contact** — Info card + booking form with service selector
14. **Footer** — Links, services and contact columns

---

## 🚀 Getting Started

No build tools or dependencies required. It's a single self-contained HTML file.

```bash
# Just open in any browser
open kisan-nursery.html
```

Or drag and drop `kisan-nursery.html` into your browser.

---

## 🌐 Deployment

### Option 1 — GitHub Pages
```bash
git init
git add kisan-nursery.html README.md
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/kisan-nursery.git
git push -u origin main
# Then enable GitHub Pages in repo Settings → Pages
```

### Option 2 — Netlify (Drag & Drop)
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop the `kisan-nursery.html` file into the deploy area
3. Your site is live instantly

### Option 3 — Any Web Host
Upload `kisan-nursery.html` via FTP or cPanel File Manager to your hosting's `public_html` folder.

---

## ✏️ Customization

### Change Phone Number
Search and replace all instances of `919351867987` with your number:
```
919351867987  →  91XXXXXXXXXX
```

### Change Colors
Edit the CSS variables at the top of the `<style>` block:
```css
:root {
  --forest: #0a4020;   /* Dark green — navbar, headings */
  --leaf:   #1a7a3c;   /* Mid green — accents */
  --mint:   #2ecc71;   /* Bright green — buttons, highlights */
  --gold:   #c9a84c;   /* Gold — optional accent */
}
```

### Change Images
Images are loaded from [Unsplash](https://unsplash.com). Replace any `src` URL with your own image URL or a local file path:
```html
<!-- Before -->
<img src="https://images.unsplash.com/photo-XXXX">

<!-- After (local file) -->
<img src="images/my-garden.jpg">
```

### Add/Edit Services
Find the `.services-grid` section and copy a `.service-card` block:
```html
<div class="service-card">
  <div class="service-num">07</div>
  <div class="service-icon-wrap">🪴</div>
  <h3>Your New Service</h3>
  <p>Description of the service goes here.</p>
</div>
```

---

## 📱 Responsive Breakpoints

| Breakpoint | Layout |
|---|---|
| `> 1100px` | Full desktop layout |
| `900px – 1100px` | 2-column services and plants |
| `640px – 900px` | Single column, stacked grids |
| `< 640px` | Mobile — nav links hidden, full stack |

---

## 🔧 Tech Stack

- **HTML5** — Semantic structure
- **CSS3** — Custom properties, Grid, Flexbox, animations
- **Google Fonts** — Cormorant Garamond + DM Sans
- **Unsplash** — Stock photography (replace with real photos)
- **WhatsApp API** — `wa.me` deep link for direct chat

---

## 📞 WhatsApp Integration

The floating button and WhatsApp CTA link directly to WhatsApp chat:
```
https://wa.me/919351867987
```
Replace the number to update all WhatsApp links at once using find & replace.

---

## 📄 License

This website was built for **Kisan Nursery**. All rights reserved © 2026 Kisan Nursery.
