---
name: Lumina Editorial
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#414846'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#727876'
  outline-variant: '#c1c8c5'
  surface-tint: '#49645e'
  primary: '#08231f'
  on-primary: '#ffffff'
  primary-container: '#1f3934'
  on-primary-container: '#87a39c'
  inverse-primary: '#b0cdc5'
  secondary: '#446819'
  on-secondary: '#ffffff'
  secondary-container: '#c1ee8e'
  on-secondary-container: '#486d1d'
  tertiary: '#0d0075'
  on-tertiary: '#ffffff'
  tertiary-container: '#1a00b3'
  on-tertiary-container: '#9191ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cbe9e1'
  primary-fixed-dim: '#b0cdc5'
  on-primary-fixed: '#04201b'
  on-primary-fixed-variant: '#324c46'
  secondary-fixed: '#c4f091'
  secondary-fixed-dim: '#a8d478'
  on-secondary-fixed: '#0f2000'
  on-secondary-fixed-variant: '#2d5000'
  tertiary-fixed: '#e2dfff'
  tertiary-fixed-dim: '#c2c1ff'
  on-tertiary-fixed: '#0b006b'
  on-tertiary-fixed-variant: '#2b1bd7'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Anybody
    fontSize: 80px
    fontWeight: '700'
    lineHeight: 88px
    letterSpacing: -0.04em
  display-lg-mobile:
    fontFamily: Anybody
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Anybody
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Anybody
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 32px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  margin-mobile: 24px
  margin-desktop: 80px
  gutter: 32px
  section-gap: 160px
---
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

