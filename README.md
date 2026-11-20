# Mahg Sans Digit (`mahg-sans-digit-tnum`)

[English](./README.md) | [日本語](./ja.README.md)

A clean, neo-grotesque sans-serif font specialized for numbers, mathematical formulas, and symbols, designed with tabular figures (`tnum`) for consistent alignment.

---

## 1. Overview

* **Font Family:** `mahg-sans-digit`
* **Version:** `v1.000`
* **Weights:** Regular (`400`), Bold (`700`)
* **License:** SIL Open Font License 1.1 (OFL-1.1)

### Features

* **Tabular Figures (`tnum`):** Every digit shares the exact same advance width, keeping numbers aligned in tables, UI counters, timers, and data displays.
* **High Legibility:** Clean, neutral letterforms (such as a distinct beak on `1` and an open-counter `4`) prevent misreading and blend naturally with any primary Japanese or Latin typeface.
* **Comprehensive Math & Symbol Set:** Includes basic operators, superscript/subscript digits, operators, and parentheses, mathematical/scientific symbols (e.g., `≒`, `≦`, `≧`, `√`, `∞`, `‰`, `ⱱ`), and specialized spaces (such as Figure Space).

---

## 2. Key Files & Directories

* **`registered.txt`**
  Lists all registered characters in this font, separated by newlines.
* **`/raw/`**
  Contains the raw font files (`OTF`, `TTF`, `WOFF2`) for both Regular and Bold (`v1.000`), along with `about.txt`.
* **`/dist/`**
  Contains ready-to-use CSS stylesheets organized by `font-display` behavior (`auto.css`, `block.css`, `fallback.css`, `optional.css`, `swap.css`).
  * `/dist/*.css`: Mirrors of `/dist/400/*.css` (Regular)
  * `/dist/400/*.css`: Stylesheets for weight `400` (Regular)
  * `/dist/700/*.css`: Stylesheets for weight `700` (Bold)
* **`/img/`**
  Contains source SVG glyph data and related image assets (e.g., `/img/400/`).

---

## 3. Usage (Web Font / CSS)

Load the desired stylesheet from `/dist/` in your HTML `<head>` and apply `mahg-sans-digit` in your CSS `font-family`.

> **Note:** `/dist/*.css` loads weight `400` (Regular). To use weight `700` (Bold), also include the corresponding stylesheet from `/dist/700/`.

### HTML Example (via jsDelivr CDN)

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/seedfont/mahg-sans-digit-tnum@main/dist/400/swap.css">

<!-- To include Bold (700) -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/seedfont/mahg-sans-digit-tnum@main/dist/700/swap.css">
```

### CSS Example

```css
body {
  font-family: "mahg-sans-digit", sans-serif;
}
```

---

## 4. Desktop Installation

To install the font locally on your system, download and install the `OTF` or `TTF` files located in the `/raw/` directory:

* `MahgSansDigit-v1.000-Regular.otf` / `.ttf`
* `MahgSansDigit-v1.000-Bold.otf` / `.ttf`

---

## 5. License & Copyright

This font is released under the **SIL Open Font License 1.1 (OFL-1.1)**.  
Free for personal and commercial use, modification, and redistribution.

Copyright © 2026 seeding / Mahg Font Project
