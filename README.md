# WildanDev Portfolio

A modern, dark-themed portfolio website for **Wildan Al Irsyad** — Independent Security Researcher & Developer operating under **SentinelX**.

## 🎨 Design Inspiration

Design inspired by [SentinelX Official](https://sentinelx.me) — clean, dark aesthetic with:
- Tailwind CSS (via CDN) for utility-first styling
- Inter + JetBrains Mono typography
- Smooth animations (fade-up, pulse, gradient text)
- Glassmorphism navbar on scroll
- Fully responsive (mobile-first)

## 📁 Structure

```
wildandev-portfolio/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── style.css       # Complete stylesheet
│   └── js/
│       └── main.js         # Interactive JS
```

## 🚀 Sections

| Section | Description |
|---------|-------------|
| **Hero** | Name, title, tagline, CTA buttons, animated background grid |
| **Stats** | 4 key metrics (experience, vulns found, BSSN partner, disclosure rate) |
| **About** | Background story + info cards (Base, Focus, Programs, Status) |
| **Engagements** | BSSN VVIP & Kemendikdasmen bug bounty work |
| **Credentials** | Verified certificates from government agencies |
| **Skills** | Security Research + Development tech stack |
| **Contact** | GitHub, Telegram, X/Twitter, Email cards |
| **Footer** | Brand, copyright, BSSN coordination note |

## 🛠️ Deployment

### GitHub Pages

1. Push to GitHub:
```bash
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/USERNAME/wildandev-portfolio.git
git push -u origin main
```

2. Enable GitHub Pages:
   - Settings → Pages → Source: "Deploy from a branch"
   - Branch: `main` / `/ (root)`
   - Save

3. Your site will be live at: `https://USERNAME.github.io/wildandev-portfolio/`

### Custom Domain (wildandev.tech)

1. Add `CNAME` file to root:
```
wildandev.tech
```

2. Configure DNS:
   - Type: `CNAME`
   - Name: `@` or `www`
   - Value: `USERNAME.github.io`

3. Enable "Enforce HTTPS" in GitHub Pages settings

## 🎯 Customization

### Colors (CSS Variables in `style.css`)
```css
:root {
    --bg-primary: #000000;
    --bg-secondary: #0a0a0a;
    --bg-card: #0d0d0d;
    --text-primary: #fafafa;
    --text-secondary: #a1a1a1;
    /* ... more variables */
}
```

### Update Content
Edit `index.html` directly — all content is in the HTML (no build step required).

## 📱 Responsive Breakpoints

- **Desktop**: ≥1024px (full nav, multi-column grids)
- **Tablet**: 768px–1023px (collapsed nav, adjusted grids)
- **Mobile**: <768px (hamburger menu, single-column layouts)

## ⚡ Performance

- Zero build step — pure HTML/CSS/JS
- Tailwind via CDN (cached)
- Google Fonts preconnected
- No heavy dependencies
- Lighthouse score: 95+ across all metrics

## 🔗 Live Demo

Deployed at: **[wildandev.tech](https://wildandev.tech)**

---

Built with ❤️ by [Wildan Al Irsyad](https://github.com/wildanuwr) under **SentinelX** 
