⛓️ ChainMe — Spell Your Name in Crypto
=====================================

Transform your name into an iconic chain of cryptocurrency symbols with ChainMe, a vibrant single-page web app for the crypto-curious.

## Description

ChainMe is a fun, interactive web app that converts each letter of your name into a unique cryptocurrency symbol. Watch as 26 crypto symbols burst across your screen in a mesmerizing opening animation, then generate personalized crypto cards for your name. Download a high-quality image, share it on social media, and celebrate your inner blockchain enthusiast.

## Features

✨ **Opening Animation** — All 26 crypto symbols burst from the center in a spectacular spiral, scatter across the background, and continuously drift with gentle floating motion.

🎴 **Flip Card Reveal** — Input your name and watch as letter cards flip one by one, each revealing a unique crypto symbol, ticker, and project name with satisfying 3D animations and tick sounds.

📥 **Download Your Chain** — Generate a beautiful, shareable PNG image of your name in crypto with watermarks, grid background, and professional styling. Perfect for profile pictures or sharing.

🔗 **Share Instantly** — Tweet your creation directly to Twitter/X or copy a shareable link to send to friends.

📖 **Alphabet Reference** — Explore the complete 26-letter crypto alphabet with an expandable reference legend showing each symbol's ticker and project name.

🎆 **Confetti Celebration** — Burst confetti in crypto colors when your name is fully revealed.

## How to Use

1. **Open** — Simply open `index.html` directly in your web browser. No server or installation required.
2. **Enter Your Name** — Type your name (or any text with letters A-Z) in the input field.
3. **Generate** — Click the "Generate ⚡" button or press Enter to see your name transformed into crypto symbols.
4. **Download** — Click "Download Your Chain" to save a PNG image of your creation.
5. **Share** — Tweet it, copy the link, or regenerate to try another name.

## Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — Glassmorphism design, 3D transforms, keyframe animations
- **Vanilla JavaScript** — No frameworks or build tools
- **Canvas API** — Image generation and download
- **Web Audio API** — Procedurally generated tick sounds
- **Google Fonts** — Orbitron (headings) and Space Grotesk (body)

### Key Technologies Used

| Technology | Purpose |
|------------|---------|
| CSS `transform-style: preserve-3d` | 3D flip card effect |
| CSS `backdrop-filter: blur()` | Glassmorphism panel styling |
| Canvas 2D Context | PNG image generation |
| Web Audio API | Procedural tick sound synthesis |
| CSS Keyframes | Burst, float, and shimmer animations |
| Web Animations API | Confetti particle effects |

## Design System

- **Background** — Near-black (`#0a0a0f`) with subtle animated grid
- **Primary Accent** — Bitcoin orange (`#F7931A`)
- **Secondary Accent** — Ethereum purple-blue (`#627EEA`)
- **Typography** — Orbitron for crypto-style headings, Space Grotesk for body text
- **Panel Style** — Glassmorphism with frosted glass effect, 20px blur, semi-transparent border

## Crypto Alphabet

Each letter (A–Z) maps to a cryptocurrency:

| Letter | Symbol | Ticker | Project | Color |
|--------|--------|--------|---------|-------|
| A | 🔷 | ADA | Cardano | `#0033AD` |
| B | ₿ | BTC | Bitcoin | `#F7931A` |
| C | 🔵 | CRO | Cronos | `#002D74` |
| D | Ð | DOGE | Dogecoin | `#C2A633` |
| E | Ξ | ETH | Ethereum | `#627EEA` |
| ... | ... | ... | ... | ... |
| Z | ⓩ | ZEC | Zcash | `#F4B728` |

See the full alphabet by clicking the "📖 Alphabet" button in the bottom left.

## Features in Detail

### Opening Animation
On page load, all 26 crypto symbols start clustered at the center of the screen and explode outward in a swirling spiral motion. Each symbol lands at a random position and begins an infinite gentle floating animation, creating an immersive background that never stops drifting.

### 3D Flip Card Animation
When you generate your name, black cards appear instantly for each letter. They flip one by one (staggered 150ms apart) with a smooth 3D rotation, revealing the crypto symbol on the back along with the ticker, letter, and project name. A glow pulse runs across all cards after the reveal.

### Canvas Image Download
Click "Download Your Chain" to generate a professional PNG image featuring:
- Dark background with radial gradient glow
- All letter cards rendered side by side
- ChainMe watermark (top-left)
- chainme.app watermark (bottom-right)
- Subtle grid background pattern
- Filename: `chainme-[NAME].png`

### Mobile Responsive
The entire app is optimized for desktop, tablet, and mobile devices. Cards scale responsively, and the UI panel adapts to smaller screens.

## Browser Compatibility

Works in all modern browsers supporting:
- CSS Grid & Flexbox
- CSS 3D Transforms
- Canvas 2D API
- Web Audio API
- ES6 JavaScript

Tested on:
- ✅ Chrome/Chromium
- ✅ Firefox
- ✅ Safari
- ✅ Edge

## Files

```
.
├── index.html      (Complete single-page app — HTML + CSS + JS)
└── README.md       (This file)
```

No build process, no dependencies, no server required. Just open `index.html` in your browser!

## Screenshots

_Add screenshots here after deploying:_
- Opening animation with floating symbols
- Input panel with "Chain My Name" prompt
- Flip card reveal in progress
- Completed name with download button
- Downloaded PNG image example

## Future Enhancements

- Leaderboard of popular names
- Custom color themes
- Animated GIF export
- Sound effects toggle
- Dark/light mode
- Name history / saved chains

## Built with ❤️ for the crypto community

Transform your identity. Embrace the blockchain. **Be ChainMe.**

---

**License** — Open source and free to use.

**Questions?** — Check out the code, fork it, and make it your own!
