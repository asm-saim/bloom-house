# 🌸 Bloom House

> *Where Every Petal Tells a Story*

A clean, responsive flower shop landing page built with pure HTML and Tailwind CSS. Bloom House showcases a modern e-commerce storefront for a fictional flower & plant retailer — featuring a hero section, product grid, deals showcase, newsletter signup, and a fully structured footer.

**Live Demo:** [asm-saim.github.io/bloom-house](https://asm-saim.github.io/bloom-house/)

---

## 📸 Preview

![Bloom House Banner](assets/hero-flower.png)

---

## ✨ Features

- **Responsive Navigation** — Mobile-friendly navbar with logo, links, and cart icon via Font Awesome
- **Hero Section** — Bold headline with an accent-colored tagline and a full hero image
- **Product Grid** — Responsive 4-column flower/plant card grid with "Add to Cart" buttons
- **Flower & Plant Lover Section** — Two-column feature section with a trusted badge overlay
- **Latest Deals** — Asymmetric deal layout showcasing discounts (25%–60% off) with image overlays
- **Newsletter Signup** — Full-width CTA banner with an email subscription input
- **Footer** — Multi-column footer with logo, navigation links, and social media icons
- **Fully Responsive** — Adapts seamlessly from mobile to desktop using Tailwind breakpoints (`sm`, `md`, `lg`)

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **HTML5** | Page structure and semantics |
| **Tailwind CSS v4** | Utility-first styling via CDN |
| **Font Awesome** | Icon library (cart, etc.) |
| **Google Fonts / Inter** | Typography |

> No build tools or package manager required — this project runs entirely in the browser.

---

## 📁 Project Structure

```
bloom-house/
├── index.html          # Main HTML file (single-page layout)
├── tailwind.css        # Custom Tailwind configuration/overrides
└── assets/             # Images and icons

```

---

## 🚀 Getting Started

Since this project has no dependencies or build step, getting it running locally is straightforward.

**1. Clone the repository**

```bash
git clone https://github.com/asm-saim/bloom-house.git
cd bloom-house
```

**2. Open in browser**

Simply open `index.html` in any modern web browser:

```bash
# macOS
open index.html

# Windows
start index.html

# Linux
xdg-open index.html
```

Or use a local development server for a better experience:

```bash
# Using VS Code Live Server extension (recommended)
# Right-click index.html → "Open with Live Server"

# Using Python
python -m http.server 8000
# Then visit http://localhost:8000
```

---

## 🎨 Design Decisions

- **Color Palette:** Soft off-white background (`#F5F8FF`), warm orange accent (`#E95108`), and muted grey text (`#777a80`) create a fresh, botanical feel.
- **Typography:** Inter font gives the UI a clean, modern look appropriate for a lifestyle/retail brand.
- **Tailwind via CDN:** Using `@tailwindcss/browser@4` keeps the project zero-config and instantly runnable without a Node.js build pipeline.
- **Asymmetric Deal Layout:** The `grid-cols-5` deal section (2 stacked + 1 tall) adds visual hierarchy and draws attention to the featured product.

---

## 🗺️ Roadmap

Potential future enhancements:

- [ ] Functional shopping cart with JavaScript
- [ ] Product filtering and search
- [ ] Individual product detail pages
- [ ] Backend integration for newsletter subscriptions
- [ ] Accessibility improvements (ARIA labels, keyboard navigation)
- [ ] Dark mode support

---

## 🤝 Contributing

Contributions are welcome! To get started:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a Pull Request

---

## 📄 License

This project is open source. Feel free to use it for learning, personal projects, or as a template.

---

## 👤 Author

**asm-saim**
- GitHub: [@asm-saim](https://github.com/asm-saim)

---

<p align="center">Made with 🌺 by asm-saim</p>