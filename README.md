# Shopify App Review Showcase

**Turn Shopify app reviews into stunning social media images — no design tools needed.**

It is a lightweight, zero-dependency browser tool that lets you paste a customer review, style it with a gradient and card theme, and export a pixel-perfect image ready for Instagram, Stories, or any social channel — all from a single HTML file.

---

## ✨ Features

- **Live canvas preview** — every change reflects instantly on the right side
- **Fully offline** — runs as a single `index.html` file, no server or build step required
- **High-resolution exports** — PNG output at native resolution, sharp on all screens
- **42 gradient backgrounds** — hand-picked color pairs covering the full spectrum
- **Light & Dark card themes** — card background adapts to match the selected gradient
- **App logo integration** — show your Shopify app logo alongside the Shopify badge
- **Flexible display toggles** — individually show/hide profile icon, star rating, date, Shopify logo
- **3 export formats** — Square, Stories, and Landscape, each at social-standard dimensions
- **Inter + Poppins typography** — clean, modern font pairing for both UI and canvas output
- **Shopify favicon** — Shopify bag logo set as the browser tab icon

---

## 📐 Export Formats

| Format    | Dimensions   | Best For                        |
|-----------|--------------|---------------------------------|
| Square    | 1080 × 1080  | Instagram Feed, Facebook        |
| Stories   | 1080 × 1920  | Instagram & Facebook Stories    |
| Landscape | 1920 × 1080  | Twitter/X, LinkedIn, YouTube    |

---

## 🛠 How to Use

1. **Open** `index.html` in any modern browser (Chrome, Firefox, Safari, Edge)
2. **Fill in** the reviewer name, review date, and review content
3. **Set** the star rating by clicking the stars
4. **Toggle** display elements on or off using the switches
5. **Pick** a gradient background from the colour palette
6. **Choose** a card theme (Light or Dark)
7. **Select** an app logo to display alongside the Shopify badge (optional)
8. **Choose** your export format (Square / Stories / Landscape)
9. **Click** Download Image to save the PNG

No installation. No account. No internet required after the fonts load.

---

## 🎨 Customisation Options

### Reviewer
- Full reviewer name (used for the initials avatar and name on the card)
- Review date (formatted as `Month DD, YYYY` on the card)

### Display Toggles
| Toggle         | Description                                      |
|----------------|--------------------------------------------------|
| Profile icon   | Circular avatar with reviewer initials, gradient-filled matching the selected background |
| Star rating    | 1–5 stars using the SVG star shape               |
| Review date    | Muted date text at the bottom of the card        |
| Shopify logo   | Official Shopify bag logo, top-right of the card |

### App Logo
One app logo can be shown at a time alongside the Shopify badge. Available apps:

| App                         | Description                |
|-----------------------------|----------------------------|
| Zepto Product Personalizer  | Product customization       |
| InfinSEO                    | SEO Image Optimizer         |
| PopMan                      | Popups & Social Proof       |
| Zepto Sign Customizer       | Sign customization          |
| BoostlyCart                 | Cart Drawer & Upsell        |

When an app logo is selected alongside the Shopify logo, both are displayed side by side in the top-right corner of the card, vertically aligned with the reviewer name.

### Background Gradient
42 gradient presets rendered as rounded square swatches. The selected gradient also fills the profile icon avatar circle.

### Card Theme
- **Light** — soft tinted background derived from the selected gradient
- **Dark** — deep dark background derived from the selected gradient

---

## 🏗 Technical Details

- **Single file** — all HTML, CSS, and JavaScript in `index.html`
- **Canvas rendering** — the image is drawn on an HTML5 `<canvas>` element at full export resolution, then displayed scaled-down in the preview
- **Image loading** — Shopify logo and app icons are loaded via `crossOrigin = 'anonymous'` and cached in memory; all icons are preloaded on boot so switching is instant
- **Fonts** — Inter and Poppins loaded from Google Fonts; both are used on the canvas via the Canvas 2D text API
- **No dependencies** — no npm, no bundler, no framework

### Browser Support

| Browser | Support |
|---------|---------|
| Chrome  | ✅ Full |
| Firefox | ✅ Full |
| Safari  | ✅ Full |
| Edge    | ✅ Full |

---

## 📁 File Structure

```
index.html    ← The entire application (HTML + CSS + JS)
README.md     ← This file
```

---

## 🚀 Running Locally

Just open the file:

```bash
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

Or serve it with any static file server if you prefer:

```bash
npx serve .
# then open http://localhost:3000
```

---

## 📝 Licence

Internal tool. All rights reserved.
