---
name: Atmospheric Precision
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#e3beb7'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#aa8983'
  outline-variant: '#5a413b'
  surface-tint: '#ffb4a5'
  primary: '#ffb4a5'
  on-primary: '#650a00'
  primary-container: '#bd2e15'
  on-primary-container: '#ffdad3'
  inverse-primary: '#b4280f'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#c8c6c5'
  on-tertiary: '#313030'
  tertiary-container: '#656464'
  on-tertiary-container: '#e4e1e1'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad3'
  primary-fixed-dim: '#ffb4a5'
  on-primary-fixed: '#3e0400'
  on-primary-fixed-variant: '#8e1300'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
  surface-deep: '#050505'
  surface-elevated: '#121212'
  ink-muted: '#808080'
  accent-vibrant: '#BD2E15'
typography:
  display-xl:
    fontFamily: Syne
    fontSize: 120px
    fontWeight: '800'
    lineHeight: 110px
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Syne
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Syne
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
  headline-md:
    fontFamily: Syne
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  body-lg:
    fontFamily: Epilogue
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 32px
  body-md:
    fontFamily: Epilogue
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-mono:
    fontFamily: Epilogue
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.1em
  link-nav:
    fontFamily: Syne
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  grid-margin: 4rem
  grid-gutter: 1rem
  section-gap: 8rem
  card-padding: 2rem
  stack-sm: 0.5rem
  stack-md: 1.5rem
---

## Brand & Style

The design system embodies a fusion of **Technical Brutalism** and **High-Fashion Editorial**. It is designed for high-end portfolio experiences, creative agencies, and technical fashion brands that require a "dark-mode-first" aesthetic with surgical precision.

The personality is authoritative, sophisticated, and unapologetically bold. It leans into high-contrast visuals where deep, near-black voids are punctuated by razor-sharp typography and vibrant, aggressive accents. The experience should feel like a premium digital gallery—expansive, rhythmic, and meticulously ordered.

Key visual pillars:
- **Atmospheric Depth:** A foundation of layered near-blacks and subtle grain textures.
- **Typographic Dominance:** Large-scale, expressive headlines that act as structural elements.
- **Technical Rigor:** Tight grid alignment, monospaced metadata, and hairline borders.

## Colors

The palette is centered on a "void" concept. The background is not true black, but a deep, atmospheric charcoal (`#0A0A0A`) that allows for subtle layering.

- **Primary Accent:** A sharp, blood-red (`#BD2E15`) used sparingly for high-impact calls to action, focus states, and critical highlights.
- **Typography:** Pure white (`#FFFFFF`) for primary headers to ensure maximum contrast, and muted grays for secondary metadata.
- **Containers:** Background elements use slightly lighter "elevated" blacks (`#121212`) to create separation without relying on traditional shadows.
- **Accents:** Use vibrant red for interaction triggers (hover states, active navigation) and as a decorative "laser line" in grid dividers.

## Typography

This design system treats type as a textural element. **Syne** is used for all display and headline roles, chosen for its avant-garde shapes and variable-width feeling. **Epilogue** provides a technical, clean counterpoint for body copy and metadata.

- **Display Text:** Use `display-xl` for hero sections and marquee-style backgrounds. These should be set with tight letter spacing.
- **Technical Metadata:** Labels and utility links should use `label-mono`, often paired with hairline dividers to reinforce the "precision" aspect.
- **Hierarchical Contrast:** Pair very large Syne headlines with significantly smaller Epilogue body text to create an editorial, high-fashion layout rhythm.

## Layout & Spacing

The layout follows a **Strict Modular Grid**. It utilizes expansive whitespace to frame content, alternating between dense clusters of information and large, open "breathing zones."

- **Desktop (1440px+):** 12-column fluid grid with wide 4rem margins.
- **Mobile (375px):** 4-column grid with 1.5rem margins.
- **Gutter Strategy:** Gutters are kept tight (`1rem`) to create a "connected" technical feel, while gaps between major sections are intentionally oversized (`8rem`) to heighten the sense of luxury.
- **Card Layouts:** Use a "Masonry-Editorial" mix where card heights vary based on content, creating a rhythmic, non-linear scroller.

## Elevation & Depth

Depth in this system is achieved through **Tonal Layering** and **High-Contrast Outlines** rather than soft shadows.

- **Surface Tiers:** Backgrounds are `#0A0A0A`, while primary interactive cards are `#121212`.
- **Ghost Borders:** Use 1px solid borders in `#1A1A1A` (low contrast) or `#BD2E15` (high contrast for focus) to define containers.
- **Glassmorphism:** Reserved exclusively for navigation overlays. Use a `20px` backdrop blur with a `10%` white tint to maintain legibility over dark backgrounds.
- **Visual Stacking:** Elements should feel "precision-milled." When items overlap (e.g., images peaking out of card boundaries), they should have sharp edges and no drop shadows, creating a collage-like editorial effect.

## Shapes

The shape language is **Strict and Technical**. 

- **Primary Radius:** Use a subtle `0.25rem` (Soft) radius for most UI elements (buttons, inputs, small cards). This provides just enough softness to feel modern without losing the "precision" edge.
- **Inner Elements:** Nested elements (like image containers within cards) should have a slightly smaller radius or be completely sharp (`0px`) to create a professional, architectural feel.
- **Interactive States:** Buttons may transition from `rounded-sm` to a more sharp-edged appearance on hover to signal a "locking in" interaction.

## Components

### Buttons
- **Primary:** Solid `#BD2E15` with white text. Sharp corners or minimal radius. High-intensity hover effect (e.g., color shift to black with red border).
- **Secondary:** Ghost style with a 1px white border. Text in Syne Semibold.

### Cards (Portfolio)
- Background: `#121212`.
- Content: Full-bleed imagery on top, followed by metadata in `label-mono` and titles in `headline-md`. 
- Hover: Image scale-up (subtle) and border color shift to the primary red.

### Navigation
- A floating "pill" at the bottom of the viewport or a stark, top-aligned bar.
- Use backdrop-blur (`20px`) and hairline white borders.

### Lists & Tables
- Used for technical specifications or "services" sections. 
- Use 1px horizontal dividers (`#1A1A1A`) and monospaced number markers (e.g., 01, 02, 03).

### Inputs
- Underline-only style or very dark filled containers (`#050505`). 
- Focus state triggers a 1px `#BD2E15` bottom border.