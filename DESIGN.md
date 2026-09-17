---
name: Botanical Dermo-Cosmetics
colors:
  surface: '#faf9f6'
  surface-dim: '#dbdad7'
  surface-bright: '#faf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f1'
  surface-container: '#efeeeb'
  surface-container-high: '#e9e8e5'
  surface-container-highest: '#e3e2e0'
  on-surface: '#1a1c1a'
  on-surface-variant: '#424844'
  inverse-surface: '#2f312f'
  inverse-on-surface: '#f2f1ee'
  outline: '#727973'
  outline-variant: '#c2c8c2'
  surface-tint: '#486555'
  primary: '#456253'
  on-primary: '#ffffff'
  primary-container: '#5e7b6b'
  on-primary-container: '#f5fff7'
  inverse-primary: '#aecebb'
  secondary: '#506358'
  on-secondary: '#ffffff'
  secondary-container: '#d0e5d8'
  on-secondary-container: '#54675d'
  tertiary: '#555e59'
  on-tertiary: '#ffffff'
  tertiary-container: '#6e7772'
  on-tertiary-container: '#f6fff8'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#caead6'
  primary-fixed-dim: '#aecebb'
  on-primary-fixed: '#032014'
  on-primary-fixed-variant: '#304d3e'
  secondary-fixed: '#d3e7db'
  secondary-fixed-dim: '#b7cbbf'
  on-secondary-fixed: '#0d1f17'
  on-secondary-fixed-variant: '#384b41'
  tertiary-fixed: '#dce5df'
  tertiary-fixed-dim: '#c0c9c3'
  on-tertiary-fixed: '#151d1a'
  on-tertiary-fixed-variant: '#404944'
  background: '#faf9f6'
  on-background: '#1a1c1a'
  surface-variant: '#e3e2e0'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-section:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '500'
    lineHeight: 44px
    letterSpacing: 0.08em
  headline-section-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '500'
    lineHeight: 34px
    letterSpacing: 0.06em
  title-card:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  stat-number:
    fontFamily: Plus Jakarta Sans
    fontSize: 38px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.01em
  body-large:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-default:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-muted:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-uppercase:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.12em
  button-text:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  margin: 2rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1.25rem
  space-lg: 2.5rem
  space-xl: 4.5rem
---

## Brand & Style

This design system is tailored for an organic botanical dermo-cosmetic brand centered on rare natural extracts like White Turmeric. The aesthetic fuses pure clinical dermatology with organic zen tranquility. It evokes purity, medical-grade scientific trust, gentle replenishment, and restorative calm.

The visual style blends refined **organic minimalism** with subtle **tactile earthiness**. It mirrors the visual language of high-end skincare packaging sitting on raw stone plinths: serene pastel washes, gentle sage-tinted light, generous breathing room (whitespace), crisp editorial line weights, and polished geometric precision contrasted against organic tactile product imagery.

## Colors

The palette is derived directly from botanical foliage, healing mint tones, and porcelain mineral shades:

- **Primary (`#6C8A79` - Sage Moss):** A muted, comforting botanical green used for key actions, brand titles, focused accents, and primary buttons.
- **Secondary (`#2C3E35` - Deep Forest Charcoal):** A rich, grounded forest dark used for high-contrast primary typography, secondary actions, and micro-branding elements.
- **Tertiary (`#DCE5DF` - Pale Mint Porcelain):** A soft, calming background wash used for hero containers, floating product cards, and delicate pill badges.
- **Neutral (`#FAF9F6` - Warm Alabaster Ivory):** An ivory canvas tone that brings warmth and an organic linen feel, preventing the sterile harshness of clinical pure whites.

Functional highlights and accents incorporate muted earth stone (`#A29988`) for natural grounding and soft translucent greens (`rgba(108, 138, 121, 0.08)`) for state interactions.

## Typography

The system utilizes **Plus Jakarta Sans** across all roles to achieve the clean, contemporary Scandinavian-Asian skincare identity present in modern cosmeceuticals:
- **Display and Hero Titles:** Rendered in bold or extra-bold weights with tight tracking for confident brand presence.
- **Section Headers:** Set with generous letter-spacing (`0.06em` to `0.08em`) and uppercase styling to create airy, museum-quality clarity.
- **Body & Product Narrative:** Balanced in medium line heights (`1.5` to `1.6`) with softened dark tones (`#4A5B52`) to ensure comfortable readability.
- **Clinical Proof Points & Metrics:** Large, clean geometric numeric rendering for rapid statistical digestion.

## Layout & Spacing

The layout is built around a relaxed **12-column fixed grid system** centered on a maximum container width of `1200px` for desktop and fluid responsive containers for smaller screens.

- **Vertical Rhythm:** Deliberately expansive vertical spacing (`space-xl: 4.5rem` to `6rem`) between landing sections allows the organic aesthetic and imagery to breathe.
- **Section Margins:** Desktop outer margin is `2rem` (expanding on ultra-wide viewports), while mobile margins contract to `1.25rem`.
- **Content Alignment:** Alternating split hero arrangements (text on left, pedestal product on right), balanced 4-column metric bars, and centered testimonial carousels.

## Elevation & Depth

Visual depth is achieved through **ambient soft daylight shadows** and **tonal layering** rather than rigid drop shadows or harsh outlines:

- **Surface Tiers:**
  - Base canvas uses `#FAF9F6` (Warm Alabaster).
  - Feature product pods and highlight cards use `#FFFFFF` or pale botanical pastel washes (`#DCE5DF`).
- **Ambient Diffusion:** Floating cards and interactive hover states feature extra-diffuse, low-contrast shadows tinted with soft forest hues: `0 16px 36px -12px rgba(44, 62, 53, 0.07)`.
- **Tactile Plinth Grounding:** Visual focal points use authentic stone, travertine, or porcelain pedestals placed beneath cosmetic flacons, visually anchoring items directly to the page surface.

## Shapes

The geometric architecture relies on **Soft (`roundedness: 1`)** primitives, balancing architectural restraint with skin-friendly softness:
- Standard buttons, text fields, and thumbnail containers utilize gentle `0.25rem` to `0.375rem` corners.
- Category circle selectors and active radio markers use full `9999px` circular geometry to mirror biological droplets and organic symmetry.
- Feature picture cards may adopt asymmetrical rounded corners (e.g., rounded top-right or diagonal soft chamfers) reflecting the smooth curves of natural pebble stones.

## Components

### Buttons
- **Primary:** Filled in `#6C8A79` with crisp white text. Soft corner radii (`4px`), `12px 24px` padding. Subtle brightness lift and deep diffuse elevation on hover.
- **Secondary / Ghost:** `#2C3E35` solid background with white text, or clean border outlines (`1px solid #6C8A79`) with `#2C3E35` text for understated alternative choices.

### Circular Category Selectors
- Dedicated product type indicators (e.g., Cream, Serum, Lotion) feature a `72px x 72px` circular porcelain dish (`#FAF9F6` with subtle inner ring) housing clean single-weight botanical line icons, accompanied by uppercase labels beneath.

### Metric / Proof Banners
- Horizontal bands containing numerical validation (e.g., customer metrics, percentage satisfaction) structured as 4 columns with large sage numerals and muted charcoal labels.

### Input Fields & Subscriptions
- Form controls feature clean white surfaces with a thin `1px solid #DCE5DF` border, smooth `4px` corners, and muted placeholder typography. When focused, they display a soft `#6C8A79` ring without aggressive outlines.

### Testimonial Cards
- Wide, light-ivory elevated cards with centered quote motifs, circular profile thumbnails overlapping the top edge, and paired sage quotation graphics.

### Selection Pills & Radios
- Clean radio pill selectors with small circular indicators to switch between product sizes (e.g., 30ml, 50ml) without visual clutter.