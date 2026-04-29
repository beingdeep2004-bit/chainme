⛓️ ChainMe — Crypto Portfolio Generator
==========================================

A beautifully minimal, Apple GlassOS-inspired crypto portfolio builder. Create stunning shareable portfolio cards with your favorite crypto assets.

## Overview

ChainMe is a elegant single-page web app designed with Apple's GlassOS aesthetic. Create a portfolio of crypto assets (Bitcoin, Solana, Ethereum, Polymarket, Kalshi, MegaETH, FTX) with smooth animations, beautiful cards, and downloadable images.

**Live Demo:** https://chainme.vercel.app

## Features

✨ **Opening Animation**
- All 7 crypto logos burst outward from a glowing center in perfect synchronization
- Logos float continuously in the background with subtle drift motion
- Ultra-clean, minimalist presentation with low opacity

🎴 **Apple GlassOS Design**
- Frosted glass panels with backdrop blur
- Soft colors: cool blues, whites, and grays
- San Francisco font system for Apple-native typography
- Subtle shadows and smooth transitions throughout

🚀 **Portfolio Generation**
- Enter a portfolio name and select crypto assets
- Black cards flip one-by-one with satisfying 3D animations
- Each card reveals the official crypto logo and name
- Procedural tick sounds on each flip (Web Audio API)

📥 **GlassOS-Styled Download**
- Generate professional portfolio image
- Apple GlassOS aesthetic with gradient background
- Original crypto logos with official colors
- Perfect for sharing and profile pictures

🔗 **Sharing & Social**
- One-click Twitter/X share with pre-filled message
- Copy shareable portfolio link
- URL parameter support for sharing portfolios

🎆 **Polish & Details**
- Confetti burst on portfolio reveal
- Smooth animations throughout
- Mobile-responsive design
- System font stack for native appearance

## How to Use

1. **Open** — Visit https://chainme.vercel.app in any modern browser
2. **Enter Portfolio Name** — Type a name (e.g., "My Web3 Stack")
3. **Create** — Click the Create button or press Enter
4. **Watch** — See your portfolio cards flip with smooth animations
5. **Download** — Save a beautiful portfolio image
6. **Share** — Share on Twitter or copy the link

## Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — GlassOS design, 3D transforms, backdrop blur
- **Vanilla JavaScript** — No frameworks, no dependencies
- **Canvas API** — Image generation and download
- **Web Audio API** — Procedural tick sound generation
- **System Fonts** — Apple San Francisco, Outfit from Google Fonts

### Key Technologies

| Technology | Purpose |
|------------|---------|
| CSS `backdrop-filter: blur()` | GlassOS frosted glass effect |
| CSS `transform-style: preserve-3d` | 3D card flip animations |
| Canvas 2D Context | Portfolio image rendering |
| Web Audio API | Procedural audio synthesis |
| CSS Keyframes | Burst, float, and shimmer animations |

## Design System

**Colors:**
- Background: Linear gradient from `#ffffff` → `#ececf1`
- Primary Blue: `#0066cc` → `#0052a3`
- Success Green: `#34c759` → `#2db84c`
- Text: `#1d1d1f` (Apple system black)
- Subtle: `rgba(0, 0, 0, 0.06)` (glass transparency)

**Typography:**
- Headings: System San Francisco, 700 weight
- Body: -apple-system, BlinkMacSystemFont, Outfit
- Letter-spacing: -0.5px (tight kerning)

**Components:**
- Panels: `rgba(255, 255, 255, 0.7)` with `backdrop-filter: blur(40px)`
- Borders: `1px solid rgba(0, 0, 0, 0.08)`
- Shadows: `0 20px 60px rgba(0, 0, 0, 0.06)` (subtle depth)
- Border Radius: 28px (large, rounded corners)

## Supported Crypto Assets

- **₿** Bitcoin (`#F7931A`)
- **◎** Solana (`#14F195`)
- **Ξ** Ethereum (`#627EEA`)
- **⬟** Polymarket (`#5294E2`)
- **◆** Kalshi (`#1E90FF`)
- **✦** MegaETH (`#6366F1`)
- **❌** FTX (`#E74C3C`) — with red strikethrough

Use the first letters of each asset name to build your portfolio:
- `B` for Bitcoin
- `S` for Solana
- `E` for Ethereum
- `P` for Polymarket
- `K` for Kalshi
- `M` for MegaETH
- `F` for FTX

**Example:** Type `BSEP` to create a Bitcoin + Solana + Ethereum + Polymarket portfolio.

## File Structure

```
chainme/
├── index.html          (Complete app — HTML + CSS + JS)
└── README.md           (This file)
```

No build process. No dependencies. No server. Just open `index.html` or visit the live demo.

## Browser Support

Works in all modern browsers with support for:
- CSS Backdrop Filter
- CSS 3D Transforms
- Canvas 2D API
- Web Audio API
- ES6 JavaScript

**Tested on:**
- ✅ Chrome/Chromium (latest)
- ✅ Safari (latest)
- ✅ Firefox (latest)
- ✅ Edge (latest)

## Features in Detail

### Opening Animation
On page load, all 7 crypto logos burst outward from the center of the screen in a smooth spiral motion. Each logo lands at a random position and then floats continuously with gentle up-and-down drift, creating an immersive, living background.

### 3D Card Flip
Enter a portfolio name and create it. Black cards appear instantly for each letter. They flip one-by-one (130ms stagger) with a smooth 3D CSS rotation, revealing official crypto logos and names. Each flip triggers a subtle procedurally-generated tick sound.

### GlassOS Design
Every element follows Apple's GlassOS design language:
- Frosted glass panels with 40px backdrop blur
- Minimal color palette (blues, whites, grays)
- Soft shadows and subtle borders
- Generous spacing and rounded corners
- San Francisco font system

### Image Download
Click "Download Portfolio" to render a professional image featuring:
- Apple GlassOS gradient background
- All portfolio cards side-by-side
- Official crypto logos and colors
- Subtle grid pattern
- ChainMe watermark
- Filename: `chainme-[PORTFOLIO].png`

### Mobile Responsive
Fully responsive design adapts beautifully to:
- Desktop (optimized layout)
- Tablet (adaptive spacing)
- Mobile (single-column, scaled cards)

## Roadmap

- [ ] Add more crypto assets (100+ altcoins)
- [ ] Custom color themes
- [ ] Export as SVG
- [ ] Portfolio templates
- [ ] Light/Dark mode toggle
- [ ] Animated GIF export
- [ ] Blockchain integration (store portfolios on-chain)

## Built with ❤️ for the Crypto Community

A minimal, beautiful way to celebrate your crypto portfolio.

**Transform your identity. Embrace Web3. ChainMe.**

---

**License** — MIT. Open source and free to use.

**Questions?** Check the code, fork it, remix it. Make it your own.
