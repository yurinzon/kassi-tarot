# 🔮 KASSI TAROT — Premium Celestial Web Experience

An Awwwards-tier, premium mystical web application designed and built for **Kassi Tarot**. This is a standalone, high-fidelity experience featuring immersive cosmic visuals, fluid **GSAP** micro-interactions, hardware-accelerated **3D card shuffles**, and a fully interactive **HTML5 canvas particle engine**.

---

## 💫 Interactive Features

### 1. The Celestial Hero Portal
Designed in strict accordance with premium mystical design guidelines (Obsidian Purple, Foil Gold, and CSS Film Grain velvet textures).
* **GSAP Page Intro:** Smooth, staggered entry animations of all HUD cards and elements on page load.
* **Canvas Plasma Ball:** A custom, interactive HTML5 canvas particle emitter representing a glowing crystal ball. Particles swirl dynamically, react to mouse movements, and burst into a glittering cascade of golden stars on click.
* **3D Tarot Simulator:** Clicking the crystal ball triggers a smooth GSAP card deal and shuffle animation. A 3D-flippable Rider-Waite card emerges and floats above the orb, which can be clicked to flip in 3D using spring physics, revealing detailed, empowering, psychological tarot interpretations in Hebrew.
* **Astro/Zodiac Sky Map:** Beautiful astrological dials and constellation circles slowly rotating behind the majestic gold-leaf header.
* **Floating Runes:** Fine line-art SVGs of zodiac glyphs (Pisces, Scorpio, Libra, Aries, Gemini, Sagittarius) floating with smooth, organic vertical drift and rotational sway.
* **Glassmorphic Menu Card:** Left-aligned menu list with foil-gold hover states. Clicking any item automatically scrolls to the booking section and pre-selects the corresponding layout in the form (e.g., clicking "LOVE" selects "love" spread).

### 2. Editorial Cosmic Blog
A high-end editorial blog showcasing Cassie's spiritual and psychological tarot articles. It features large serif fonts, generous leading, and drop-caps, rendering in a beautiful glassmorphic modal drawer with gold trims when clicked.

### 3. The Private Altar (Booking Form)
A tactile, beautifully padded booking form in Hebrew with concentric double-bezel borders and gold-leaf inputs, allowing clients to submit personalized reading requests.

---

## 🛠️ Technology Stack & Libraries

* **Markup & Styles:** HTML5, Tailwind CSS v4 (CDN)
* **Animation & Motion:** GSAP (GreenSock Animation Platform) + ScrollTrigger (CDN)
* **Interactivity:** Custom HTML5 Canvas Particle System, 3D CSS transform-style preserve-3d
* **Assets:** Physical high-resolution Rider-Waite Major & Minor Arcana deck JPGs under `public/tarot-deck/`
* **Typography:** `Cinzel` (luxury serif headings), `Cormorant Garamond` (elegant editorial body), and `Heebo` (clean Hebrew sans-serif)

---

## 🚀 Getting Started

### Local Preview
Since the project is a lightweight, zero-dependency, local-first HTML application, you can run it without any package managers!
Simply open **`index.html`** in any web browser to experience the magic immediately.

### Deployment on Vercel
This repository is 100% cloud-ready for free, instant deployments on the **Vercel Platform**:
1. Go to [vercel.com](https://vercel.com) and sign in with your GitHub account.
2. Click **Add New** → **Project**.
3. Import the `yurinzon/kassi-tarot` repository.
4. Click **Deploy**. Vercel will automatically build and host your Kassi Tarot website globally with automatic SSL!

---

## 🛡️ License & Credits
Apache-2.0. Handcrafted with meticulous double-bezel spatial design, designed by **Kassi Tarot**, and engineered by **Hermes Agent**.
