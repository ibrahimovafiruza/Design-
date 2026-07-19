# Lumina Editorial — Design System

## Brand Identity & Vision
Lumina Editorial is a premium design system crafted for high-end portfolios, digital publications, and architecturally-focused interfaces. It blends mid-century modern warmth with contemporary editorial precision. The aesthetic is defined by "luxury through whitespace"—where every element is intentional, and the lack of clutter signals curation and authority.

- **Personality:** Confident, Precise, Quietly Authoritative, Intellectual.
- **Visual Strategy:** Typography-first hierarchy, aggressive whitespace, disciplined grids, and high-contrast color blocks.

---

## 01. Color Palette
The palette uses high-contrast natural tones grounded in "Deep Forest" and "Off-White," accented by high-energy digital tones.

### Foundation
- **Primary (Deep Forest):** `#08231f` — Used for text, dark-mode containers, and hero backgrounds.
- **Background (Off-White):** `#f9f9f9` — A paper-like neutral that reduces eye strain and feels more premium than pure white.
- **Surface Dim:** `#dadada` — Used for subtle dividers and secondary containers.

### Accents
- **Secondary (Electric Lime):** `#446819` — High-impact calls to action and critical highlights.
- **Tertiary (Royal Blue):** `#0d0075` — Interactive secondary elements.
- **Status (Accent Orange):** `#ba1a1a` — Error states and micro-indicators.

---

## 02. Typography
A mix of bold, expansive headlines and technical, precise metadata.

- **Headlines (Anybody):** Bold weights, tight letter-spacing. Used as a graphic element to anchor the page.
- **Body (Hanken Grotesk):** Geometric Swiss-style character. Airy line-height (1.6x) for maximum readability.
- **Metadata (JetBrains Mono):** Monospaced precision for labels, categories, and technical details.

| Role | Token | Size | Line Height | Tracking |
| :--- | :--- | :--- | :--- | :--- |
| Hero Headline | `display-lg` | 80px | 88px | -0.04em |
| Section Head | `headline-xl` | 48px | 56px | -0.02em |
| Card Title | `headline-lg` | 32px | 40px | -0.01em |
| Body Text | `body-md` | 16px | 26px | Normal |
| Labels | `label-md` | 14px | 20px | Normal |

---

## 03. Layout & Structure
A disciplined grid system that prioritizes "breathing room."

- **Desktop Grid:** 12-column grid | 80px margins | 32px gutters.
- **Mobile Grid:** 4-column grid | 24px margins | 16px gutters.
- **Vertical Spacing:** 160px gaps between major sections to enforce a "slow-paced," editorial reading experience.
- **Alignment:** Consistent left-alignment to maintain a strong vertical axis.

---

## 04. Shape & Depth
- **Corner Radius:** `8px (0.5rem)` standard for soft modernism. Interactive elements (buttons, chips) use `full` or `1rem` rounding.
- **Elevation:** Flat aesthetic. No traditional drop shadows. 
- **Separation:** Depth is created through tonal layering (e.g., Deep Forest section on an Off-White page) or 1px solid borders at 10% opacity.

---

## 05. Component Patterns
- **Buttons:** Solid Deep Forest with Off-White text. Hover state transitions to Electric Lime.
- **Navigation:** Transparent, persistent top bar with backdrop blur. Left-aligned brand logo with wide-spaced navigation links.
- **Project Cards:** Large-scale imagery (1:1 or 4:3) with typography below. Images include subtle geometric shape accents in background layers.
- **Footer:** Deep Forest background with high-contrast text. Minimalist layout with essential social links and copyright.
