# RESONANCE — Premium Headphone Store

A modern, fully responsive e-commerce front-end for a premium audio brand. Built with vanilla HTML, CSS, and JavaScript — no frameworks, no dependencies beyond Google Fonts and Font Awesome.

---

## Pages

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Hero, features, promo banner, newsletter |
| Headphones | `headphones.html` | Product grid with filters, sorting, cart |
| Support | `support.html` | FAQ accordion, contact form, help topics |

---

## Features

- **Sticky navbar** — slides in on scroll with blur backdrop
- **Hamburger menu** — animated, works on all three pages
- **Product filters** — filter by category, features, and max price
- **Sort bar** — sort products by price or name
- **Cart counter** — persists across sessions via `localStorage`
- **FAQ accordion** — click-to-expand with smooth animation
- **FAQ search** — live search highlights matching cards
- **Scroll animations** — `IntersectionObserver`-based fade-in
- **Typewriter effect** — animated hero headline
- **Newsletter form** — client-side feedback on submit
- **Contact form** — validation and success state
- **Back-to-top button** — appears after scrolling
- **Fully responsive** — tested at 320px, 480px, 768px, 1024px+

---

## Tech Stack

- HTML5 / CSS3 / Vanilla JavaScript
- [Google Fonts — Poppins](https://fonts.google.com/specimen/Poppins)
- [Font Awesome 6.5](https://fontawesome.com/)
- No build tools — open `index.html` directly in a browser

---

## Project Structure

```
Resonance-Final-Product/
├── index.html          # Home page
├── headphones.html     # Shop / product listing page
├── support.html        # Support, FAQ, and contact page
├── assets/             # Images and icons
│   ├── headphone.png
│   ├── image.png / image1.png / image2.png
│   ├── 1.png – 6.png   # Product images
│   ├── insta.png / fb.png / twitter.png
│   └── pngegg.png      # Favicon
└── styling/
    ├── home.css
    ├── headphones.css
    └── support.css
```

---

## How to Run

No installation needed. Just clone and open:

```bash
git clone https://github.com/ZidaneNC/Resonance-Final-Product.git
cd Resonance-Final-Product
open index.html   # macOS
# or double-click index.html on Windows/Linux
```

---

## Screenshots

### Home
![Home page](assets/headphone.png)

### Shop
![Headphones page](assets/image2.png)

---

## License

This project is for educational/portfolio purposes.
