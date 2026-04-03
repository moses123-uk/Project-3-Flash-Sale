# 📧 Project 3: High-Impact Flash Sale Template

**Category:** Promotional / E-commerce Marketing  
**Goal:** To drive immediate revenue through a time-sensitive 10% discount offer with a bold, mobile-first visual hierarchy.

### 🛠️ Technical Highlights
* **High-Impact Hero Typography:** Implemented an 80px bold headline using inline-styled `<span>` tags, optimized to scale gracefully on mobile devices without breaking the container.
* **Conversion-Centric UI:** Featured a high-contrast `#FFBA00` (Yellow) and `#000000` (Black) color palette to draw immediate attention to the "10% Off" offer.
* **Bulletproof CTA System:** Built a VML-backed "Read More" button to ensure the primary call-to-action remains visible and clickable in Outlook 2016-2019, even with images disabled.
* **Liquid Logic Integration:** Prepared with placeholder logic `{% if %}` to allow for dynamic discount tiers based on user segments (VIP vs. Standard).

### 📱 Performance & Rendering
* **Retina-Ready Assets:** Optimized hero imagery with `width="600"` and `height="auto"` to maintain pixel-perfect clarity on high-resolution smartphone screens.
* **Dark Mode Optimization:** Used transparent PNG social icons and logo strokes to ensure visibility across both Light and Dark mode OS environments.
* **Fluid Layout:** Designed with a 100% width table structure to ensure zero horizontal scrolling on narrow devices (iPhone SE/Mini).

---
**Technical Solution:** Solved the "Disappearing Button" issue in Outlook by wrapping the CTA in a VML round-rect container with a fallback HTML button for web clients.
