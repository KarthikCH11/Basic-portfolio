<div align="center">

# ⚡ Engineering Portfolio Template

A modern, interactive portfolio website template for engineering students and professionals — featuring glassmorphism UI, 3D tilt cards, cursor-tracking spotlight, mobile-friendly navigation, and smooth scroll animations.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

[Report Bug](../../issues) · [Request Feature](../../issues)

</div>

---

## 🎯 Overview

A sleek, single-page portfolio template designed to showcase your skills, projects, and expertise in your engineering domain. Built with aesthetics in mind — no build tools required, just clean HTML/CSS/JS with Tailwind CSS via CDN.

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🌌 **Dark Glassmorphism UI** | Frosted-glass panels with gradient backgrounds and subtle noise textures |
| 🎯 **Cursor Spotlight** | Fixed radial gradient that follows cursor movement across the entire page |
| 🃏 **3D Tilt Cards** | Interactive cards with perspective transforms that respond to hover |
| 🔄 **Scroll Reveal** | Elements animate into view as you scroll using Intersection Observer |
| 💎 **Shimmer Text** | Animated gradient text effect on the hero name |
| 🔮 **Floating Chip Animation** | Semiconductor chip visual with orbital rings and glow effects |
| 📱 **Mobile Menu** | Full-screen slide-in navigation overlay with hamburger toggle for mobile devices |
| 📐 **Fully Responsive** | Adapts seamlessly from mobile to ultrawide displays |
| ⚡ **No Build Step** | No install or build required — just open `index.html` (uses CDN for Tailwind & fonts) |

## 🖼️ Sections

- **Hero** — Animated introduction with semiconductor chip visual and key domain highlights
- **About** — Background, interests, and engineering focus areas
- **Skills** — Technical and professional skills organized by domain
- **Projects** — Featured engineering projects with status badges
- **Contact** — Availability status and contact information

## 🚀 Getting Started

### Quick Start

```bash
# Clone the repository
git clone https://github.com/your-username/your-repo-name.git

# Navigate to the project
cd your-repo-name

# Open in your browser
start index.html        # Windows
open index.html         # macOS
xdg-open index.html     # Linux
```

> No build tools, package managers, or server setup needed. Just open the file!

### Using a Local Server (Optional)

For the best development experience:

```bash
# Using Python
python -m http.server 3000

# Using Node.js
npx serve .

# Using VS Code
# Install "Live Server" extension → Right-click index.html → "Open with Live Server"
```

## 🛠️ Customization

To make this portfolio your own, open `index.html` and replace the following placeholders:

| Placeholder | Where to find it | Replace With |
|-------------|------------------|--------------|
| `[Your Name]` | Hero heading, page title, footer copyright | Your full name |
| `YOURNAME` | Header logo text (before `.ECE`) | Your name in uppercase |
| `your.email@example.com` | Contact section (link + `mailto:`) | Your email address |
| `ECE` / `.ECE` | Header logo (`.ECE`), semiconductor chip graphic label, page `<title>`, footer tagline, hero bottom label, contact domains | Your branch abbreviation (e.g., `CSE`, `ME`, `EE`) |
| `Electronics & Communication Engineering` | Hero kicker badge, about section paragraph, page `<title>` | Your full branch/major name |
| `Embedded Systems`, `VLSI Design`, `IoT`, etc. | Hero description, about text, skills cards, projects, contact domains card | Your own domain-specific skills, projects, and focus areas |

You can also update the **color palette**, **project descriptions**, and **professional skills** to match your background.

### Color Palette

| Variable | Value | Usage |
|----------|-------|-------|
| `--accent` | `#6ee7ff` | Primary accent (sky cyan) |
| `--accent-2` | `#8b5cf6` | Secondary accent (violet) |
| `--bg` | `#050816` | Background base |
| `--text` | `#e7eefc` | Primary text |
| `--muted` | `#9aa9c7` | Secondary text |

## 🌐 Deployment

To deploy on **GitHub Pages**:

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Under **Source**, select `main` branch and `/ (root)`
4. Your site will be live at `https://your-username.github.io/your-repo-name/`

## 📁 Project Structure

```
your-repo-name/
├── index.html          # Complete single-file portfolio
└── README.md           # Project documentation
```

## 🧰 Built With

- **[Tailwind CSS](https://tailwindcss.com/)** — Utility-first CSS via CDN
- **[Geist Font](https://vercel.com/font)** — Clean sans-serif typography
- **[JetBrains Mono](https://www.jetbrains.com/lp/mono/)** — Monospace font for code/labels
- **Vanilla JavaScript** — Scroll reveals, 3D tilt, cursor tracking, mobile menu, and animations

## 📄 License

This project is open source — feel free to use it for your own portfolio.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](../../issues).

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

<div align="center">

**If you found this useful, give it a ⭐!**

</div>
