# 🎃 All Hallows' Eve - Obsidian Theme

A Halloween theme for Obsidian. Pumpkin orange, candle glow, and spooky elegance. Dark and light modes. For those who want their notes to feel like a haunted night 👻

---

## 📑 Table of Contents

- [✨ Features](#features)
- [📸 Screenshots](#screenshots)
- [📦 Installation](#installation)
- [🎨 Color Palette](#color-palette)
- [🛠️ Customization](#customization)
- [💡 Share Your Ideas](#ideas)
- [✨ Extra Effects You Can Add](#effects)
- [📝 Credits](#credits)

---

<a id="features"></a>

## ✨ Features

- 🎃 Pumpkin orange palette with candle glow accents
- 🌅 Gradient across headings — from bright pumpkin to dark ember
- 🌓 Dark and light mode support
- 📜 Gothic-inspired typography: Forum, Ruslan Display, Marmelad, JetBrains Mono
- 🎯 WCAG-compliant contrast for accessibility
- ✨ High contrast code syntax highlighting
- 🖊️ Smooth animations and transitions

---

<a id="screenshots"></a>

## 📸 Screenshots

### Dark Mode

![Dark Mode](img/dark.png)

### Light Mode

![Light Mode](img/light.png)

---

<a id="installation"></a>

## 📦 Installation

### From Obsidian Community Themes

1. Open Obsidian Settings
2. Go to **Appearance** → **Themes** → **Manage**
3. Find All Hallows Eve in the community store
4. Click **Install** and then **Use**

> **Note:** The theme has been submitted for review to the Obsidian community store and is awaiting moderation. 🎃

### Manual Installation

1. Download the `theme.css` and `manifest.json` files
2. Create a folder called `All Hallows Eve` in your `.obsidian/themes/` directory
3. Place both files in this folder
4. Enable the theme in Obsidian Settings → Appearance → Themes

---

<a id="color-palette"></a>

## 🎨 Color Palette

### Heading Gradient

| Heading | Dark Theme | Light Theme | Mood           |
| ------- | ---------- | ----------- | -------------- |
| H1      | `#ff7518`  | `#b84a08`   | Bright pumpkin |
| H2      | `#e86810`  | `#a83a00`   | Pumpkin        |
| H3      | `#d45a08`  | `#903000`   | Dark pumpkin   |
| H4      | `#c04a00`  | `#782800`   | Burnt pumpkin  |
| H5      | `#a83a00`  | `#602000`   | Deep orange    |
| H6      | `#8a2a00`  | `#481800`   | Almost brown   |

### Base Colors

| Element    | Dark Theme | Light Theme |
| ---------- | ---------- | ----------- |
| Background | `#1a1410`  | `#e4d8c0`   |
| Text       | `#f0d8b8`  | `#2e1a08`   |
| Accent     | `#ff7518`  | `#b84a08`   |
| Candle     | `#ffb347`  | `#c9853a`   |

---

<a id="customization"></a>

## 🛠️ Customization

### Changing Colors

You can customize the theme by editing the CSS variables in `theme.css`:

```css
--halloween-pumpkin: #ff7518; /* Change to your preferred pumpkin */
--halloween-pumpkin-dark: #d45a08; /* Change to your preferred dark pumpkin */
--halloween-candle: #ffb347; /* Change to your preferred candle glow */
```

### Recommended Accent Color

For the best experience, set your Obsidian accent color to:

- **RGB:** `255, 117, 24`
- **HEX:** `#ff7518`

> **Note:** The theme hardcodes accent colors, so user settings will be overridden.

---

<a id="ideas"></a>

## 💡 Share Your Ideas

Have an idea for a new feature or a spooky detail you'd love to see in All Hallows' Eve? I'd love to hear it!

You can share your suggestions by:

- 🐛 Opening an [issue on GitHub](https://github.com/RamenOfficialGovPatsy/All-Hallows-Eve/issues)
- ✉️ Sending a message through the [Obsidian forum](https://forum.obsidian.md)

Your ideas help make this theme spookier for everyone! 🎃👻

---

<a id="effects"></a>

## ✨ Planned Effects

These are effects that will be added to the theme in future updates:

| Effect                             | Description                               | How to implement                      |
| :--------------------------------- | :---------------------------------------- | :------------------------------------ |
| 🎃 **Icons in collapsible blocks** | 🎃 (collapsed) / 👻 (expanded)            | `summary::before { content: "🎃 "; }` |
| 🕸️ **Spider web borders**          | Light web pattern on borders              | `border-image` with SVG web           |
| 🕯️ **Candle flicker**              | Pulsing glow on active tabs               | `@keyframes` with `box-shadow`        |
| 👻 **Ghostly appearance**          | Smooth note appearance with slight offset | `@keyframes fadeIn` with `translateY` |
| 🦇 **Bat cursor**                  | Bat icon instead of cursor                | `cursor: url(...)`                    |
| 🍬 **Colored tags**                | Different colors for different tag types  | `a.tag[href*="..."]`                  |
| 🌕 **Moon in corner**              | Semi-transparent moon in top-right corner | `::after` with `position: fixed`      |
| 💀 **Skulls as list markers**      | Custom `::marker`                         | `ul li::marker { content: "💀 "; }`   |
| 🎃 **Pumpkin dividers**            | Gradient with pumpkin tones               | `background: linear-gradient(...)`    |

Stay tuned for updates! 🎃👻

---

<a id="credits"></a>

## 📝 Credits

- Inspired by Halloween nights, pumpkin lanterns, and candlelight
- Typography: Forum, Ruslan Display, Marmelad, JetBrains Mono
- Designed for spooky, atmospheric, and comfortable note-taking

---

**Enjoy the spooky All Hallows' Eve vibes! 🎃👻**
