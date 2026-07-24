---
name: Sovereign Estate
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
  on-surface-variant: '#44474d'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#75777e'
  outline-variant: '#c5c6cd'
  surface-tint: '#525f78'
  primary: '#000b21'
  on-primary: '#ffffff'
  primary-container: '#152238'
  on-primary-container: '#7d89a4'
  inverse-primary: '#bac7e4'
  secondary: '#5f5e5c'
  on-secondary: '#ffffff'
  secondary-container: '#e1dfdc'
  on-secondary-container: '#636360'
  tertiary: '#120a00'
  on-tertiary: '#ffffff'
  tertiary-container: '#2e1f00'
  on-tertiary-container: '#a68440'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d7e3ff'
  primary-fixed-dim: '#bac7e4'
  on-primary-fixed: '#0e1c31'
  on-primary-fixed-variant: '#3a475f'
  secondary-fixed: '#e4e2df'
  secondary-fixed-dim: '#c8c6c3'
  on-secondary-fixed: '#1b1c1a'
  on-secondary-fixed-variant: '#474745'
  tertiary-fixed: '#ffdea5'
  tertiary-fixed-dim: '#e9c176'
  on-tertiary-fixed: '#261900'
  on-tertiary-fixed-variant: '#5d4201'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  title-lg:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '500'
    lineHeight: '1.5'
    letterSpacing: 0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  section-padding-v: 120px
  section-padding-h: 24px
---

## Brand & Style
The design system is anchored in "Sober Luxury"—a philosophy that prioritizes restraint, heritage, and quiet confidence over loud ornamentation. It targets a high-net-worth international clientele who values reliability and architectural precision. 

The aesthetic is heavily influenced by **Premium Minimalism** and **Editorial Design**. It utilizes expansive white space to frame high-end real estate photography as art rather than mere listings. The UI acts as a silent gallery, providing a frictionless, prestigious environment that evokes an immediate sense of exclusivity and global permanence.

## Colors
The palette is dominated by **Deep Navy (#152238)** to establish authority and depth. This is balanced by **Off-white/Light Grey (#E8E6E3)** used for structural dividers and secondary surfaces to avoid the harshness of pure white.

**Subtle Gold (#C5A059)** is reserved strictly for micro-details: active navigation states, specific project callouts, or iconography. Backgrounds should primarily utilize pure white or the lightest neutral to maintain a breathable, airy editorial feel.

## Typography
The typography strategy creates a dialogue between tradition and modernity. **Playfair Display** provides the editorial authority for headings, using slightly tighter letter-spacing in larger formats to create a "locked-in" professional look. 

**Inter** is the functional backbone, providing maximum legibility for property data and descriptions. To maintain the premium feel, body text uses a generous line-height (1.6) and labels utilize wide tracking (10%) in all-caps to denote technical information and project statuses.

## Layout & Spacing
This design system employs a **Fixed Grid** model for desktop to ensure a curated, controlled viewing experience that mirrors a luxury print magazine. The central container is 1280px wide with a 12-column structure.

Vertical rhythm is intentionally "slow," with large 120px padding between sections to allow content to breathe. On mobile, margins reduce to 16px, and the layout collapses to a single column, prioritizing full-bleed property imagery. Transitions between sections should feel fluid and intentional, avoiding cluttered or dense information clusters.

## Elevation & Depth
Depth is conveyed through **Tonal Layers** rather than heavy shadows. The UI remains largely flat to preserve the minimalist aesthetic. 

When depth is required (e.g., for modal property details or the sticky header), a very soft, low-opacity Deep Navy shadow (opacity: 4%) or a simple 1px border in #E8E6E3 is used. This "Low-contrast Outline" approach keeps the focus on the architectural photography while providing enough structural definition to guide the user.

## Shapes
To reinforce the "Sober Luxury" and international corporate feel, the design system uses **Sharp (0px)** corners for all primary containers, buttons, and imagery. This architectural rigidity suggests stability and precision. 

Occasional use of circular buttons is permitted only for floating action elements (like the WhatsApp CTA) to provide a clear visual distinction from the structural UI components.

## Components

### Buttons & Navigation
*   **Primary Action:** Solid Deep Navy background with Off-white text. Sharp corners. No shadows.
*   **Secondary Action:** 1px Deep Navy border, transparent background.
*   **Sticky Header:** White background, subtle 1px bottom border (#E8E6E3). Logo on the left, centered navigation links in `label-sm` style, ES/EN toggle and WhatsApp CTA on the right.

### Project State Badges
*   Use a small dot icon + `label-sm` text.
*   **Available:** Deep Navy text/dot.
*   **Reserved:** Gold (#C5A059) text/dot.
*   **Sold:** Light Grey (#E8E6E3) text/dot.
*   **Under Construction:** Deep Navy outline badge.

### Cards & Imagery
*   **Property Cards:** Full-width imagery with minimal metadata overlay or positioned directly below. No borders or shadows on the card container; use whitespace to separate items.
*   **Floating WhatsApp:** A persistent circular button in the bottom right corner, utilizing the brand's Gold for the icon container to ensure it is visible without breaking the Navy/White harmony.

### Input Fields
*   Minimalist design: Only a bottom border (1px #E8E6E3). On focus, the border transitions to Deep Navy. Labels use `label-sm` and sit above the line.