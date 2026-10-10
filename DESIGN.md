---
name: Timber & Crema
colors:
  surface: '#fcf9f3'
  surface-dim: '#dcdad4'
  surface-bright: '#fcf9f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ed'
  surface-container: '#f0eee8'
  surface-container-high: '#ebe8e2'
  surface-container-highest: '#e5e2dc'
  on-surface: '#1c1c18'
  on-surface-variant: '#504440'
  inverse-surface: '#31312d'
  inverse-on-surface: '#f3f0ea'
  outline: '#827470'
  outline-variant: '#d3c3be'
  surface-tint: '#74584e'
  primary: '#090100'
  on-primary: '#ffffff'
  primary-container: '#2c1810'
  on-primary-container: '#9e7e73'
  inverse-primary: '#e3bfb2'
  secondary: '#994700'
  on-secondary: '#ffffff'
  secondary-container: '#fd934c'
  on-secondary-container: '#6c3000'
  tertiary: '#000301'
  on-tertiary: '#ffffff'
  tertiary-container: '#012214'
  on-tertiary-container: '#6a8c78'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbce'
  primary-fixed-dim: '#e3bfb2'
  on-primary-fixed: '#2a170f'
  on-primary-fixed-variant: '#5a4137'
  secondary-fixed: '#ffdbc8'
  secondary-fixed-dim: '#ffb68b'
  on-secondary-fixed: '#321300'
  on-secondary-fixed-variant: '#753400'
  tertiary-fixed: '#c6ebd3'
  tertiary-fixed-dim: '#abcfb8'
  on-tertiary-fixed: '#002112'
  on-tertiary-fixed-variant: '#2d4d3c'
  background: '#fcf9f3'
  on-background: '#1c1c18'
  surface-variant: '#e5e2dc'
typography:
  display-lg:
    fontFamily: Newsreader
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Newsreader
    fontSize: 38px
    fontWeight: '400'
    lineHeight: 46px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Newsreader
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Newsreader
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Newsreader
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  headline-sm:
    fontFamily: Newsreader
    fontSize: 22px
    fontWeight: '500'
    lineHeight: 30px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-caps:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  gutter-lg: 2rem
  margin: 1.5rem
  margin-md: 2.5rem
  margin-lg: 4rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system expresses the craft and warmth of high-end specialty roasting through an earthy, tactile editorial aesthetic. It balances the precision of specialty extraction with the comfort of a sunlit cafe neighborhood space.

### Brand Personality & Emotional Intent
- **Warm & Welcoming:** Generous whitespace, cream backgrounds, and amber accents elicit the sensory comfort of freshly steamed milk and roasted beans.
- **Artisanal & Methodical:** Refined editorial typography paired with structured specs reflects obsessive attention to origin, roast profiles, and extraction parameters.
- **Tactile & Natural:** Organic radius curves, subtle warm stone borders, and deep forest accents root the UI in raw materials—wood, ceramic, soil, and burlap.

### Visual Style
The design style mixes **Artisanal Minimalism** with **Tactile Editorial** design:
- Flat, tactile planes resting on low-contrast stone outlines rather than synthetic drop shadows.
- Editorial-led vertical rhythm with deliberate display typography, generous line-heights, and structured metadata chips.
- Micro-interactions that emphasize weighted, organic transitions (deliberate deceleration, gentle tint shifts).

## Colors

The palette draws directly from the sensory hallmarks of coffee cultivation and roasting:

- **Primary (`#2C1810` - Deep Roasted Espresso):** Used for primary typography, authoritative actions, core framing, and high-emphasis brand moments.
- **Secondary (`#B85D19` - Terracotta Amber):** Used for primary conversion triggers, roast level indicators, active tab indicators, and tasting note highlights.
- **Tertiary (`#264635` - Forest Pine):** Used for single-origin badges, sustainability certifications, direct-trade verification stamps, and active fulfillment states. An ambient dark tint (`#1B382B`) serves as contextual dark surface accents.
- **Neutral Surface (`#FBF8F2` - Steamed Oat Cream):** Canvas foundation providing an unbleached paper-like warmth that prevents clinical eye fatigue.
- **Borders & Dividers (`#E8E2D8` - Warm Stone):** Ghost outlines, structural borders, and subtle table rules that hold content together without harsh contrast.
- **Muted Body (`#615249` - Ground Husk):** Subdued secondary body text providing optimal legibility while maintaining a soft, natural contrast against the cream canvas.

## Typography

The type system pairs **Newsreader** (an authoritative, literary serif) with **Plus Jakarta Sans** (a clean, warm, highly legible geometric sans).

### Hierarchy Implementation Rules
- **Editorial Voice:** Headlines and pull quotes rely on Newsreader in Regular (400) and Medium (500) weights with optical sizing enabled. It gives coffee origin stories, farm provenance, and tasting notes an editorial, publication feel.
- **Functional Interface:** Interface navigation, bag weights, grind selectors, metadata fields, and transactional pricing strictly use Plus Jakarta Sans to maintain rapid scannability and structural clarity.
- **Caps & Badging:** The `label-caps` token is reserved for technical cupping descriptors (e.g., `ALTITUDE: 1,950M`, `PROCESS: ANAEROBIC NATURAL`), formatted in uppercase with positive letter spacing.

## Layout & Spacing

The layout philosophy uses a **12-column responsive fluid grid** anchored by structured max-width boundaries to preserve editorial breathing room.

### Form Factor Adaptations
- **Mobile (< 768px):** 4 columns. Gutter: `1rem` (`gutter-sm`). Canvas margin: `1.5rem` (`margin`). Product cards stack full width or collapse into horizontally scrolling carousels.
- **Tablet (768px – 1024px):** 8 columns. Gutter: `1.5rem` (`gutter`). Canvas margin: `2.5rem` (`margin-md`). Bag specs and filter controls adapt to 2-column distributions.
- **Desktop (> 1024px):** 12 columns. Gutter: `2rem` (`gutter-lg`). Canvas margin: `4rem` (`margin-lg`). Maximum container boundary is capped at 1280px to protect line lengths for long-form origin stories.

### Spacing Discipline
- Maintain generous vertical whitespace (`space-xl` and higher) between editorial vignettes.
- Keep structural metadata inside coffee cards compact (`space-xs` and `space-sm`) to form tight, disciplined informational units.

## Elevation & Depth

This design system avoids heavy digital drop shadows. Visual depth is established through **tactile surface layering, warm low-contrast outlines, and subtle ambient groundings**.

### Depth Layers
1. **Canvas Level (Floor):** Base `#FBF8F2` (Steamed Oat Cream).
2. **Surface Level 1 (Card & Module Containers):** White `#FFFFFF` or elevated cream `#F5EFE6` bordered with a 1px solid stroke of `#E8E2D8` (Warm Stone).
3. **Interactive Hover & Overlay:** Ambient warm shadow using the primary espresso tint rather than cool black:
   - `0 8px 24px -4px rgba(44, 24, 16, 0.08), 0 2px 6px -1px rgba(44, 24, 16, 0.04)`.
4. **Modal Dialogs & Slide-out Cart:** Pure surface paired with an espresso-tinted backdrop scrim:
   - Backdrop overlay: `rgba(44, 24, 16, 0.45)` with `backdrop-filter: blur(4px)`.

## Shapes

The shape scale is set to `2` (Rounded), generating soft, organic silhouettes reminiscent of ceramic mugs, tampers, and polished timber cafe bars.

### Radius Assignments
- **Core Elements (`0.5rem`):** Form inputs, tasting note chips, thumbnail containers, and specification tables.
- **Structural Cards (`rounded-lg` / `1rem`):** Coffee bean product cards, subscription bundles, brew guide tiles, and cafe location cards.
- **Featured Modules (`rounded-xl` / `1.5rem`):** Editorial hero blocks, origin highlight showcases, and modal panels.
- **Interactive Badges & Pill Buttons (`9999px`):** Status indicators, roast meter markers, and quick-add actions.

## Components

### Buttons
- **Primary:** Filled with `#2C1810` (Espresso) or `#B85D19` (Terracotta Amber for commerce CTAs), text in `#FBF8F2`, font `label-lg`. Padding: `0.75rem 1.75rem`. Border radius: `0.5rem`. Subtle hover elevation and gentle color warm-up.
- **Secondary / Outlined:** 1px border in `#2C1810` with transparent fill. Text in `#2C1810`. Hover transitions fill to `rgba(44, 24, 16, 0.04)`.
- **Ghost:** Text in `#B85D19`, zero border, subtle underline transition on hover.

### Chips & Badges
- **Tasting Notes:** Pill-shaped, background `#F5EFE6`, text `#615249`, 1px border `#E8E2D8`. Compact typography (`label-md`).
- **Roast & Origin Badges:** Background `#264635` (Forest Pine) with text `#FFFFFF` or terracotta background `#B85D19` with text `#FFFFFF`. Uses `label-caps`.

### Cards (Product & Origin)
- **Background:** `#FFFFFF` resting on `#FBF8F2`.
- **Border:** 1px solid `#E8E2D8`. Radius: `1rem`.
- **Structure:** Image container framed with `0.5rem` inset margin or edge-to-edge with top radius matching. Bottom metadata stack contains: Origin tag (`label-caps`), Coffee title (`headline-sm`), Tasting notes (flex row of chips), and price / quick-add row separated by a subtle `#E8E2D8` hairline border.

### Inputs & Selectors (Grind & Weight)
- **Text Fields:** `#FFFFFF` background, 1px border `#E8E2D8`, focused state transitions to 1.5px `#B85D19` with zero harsh glowing ring. Label set in `label-md`.
- **Segmented Grind Selectors (Whole Bean, Chemex, Espresso):** Radio buttons styled as segmented pill tiles. Selected state is filled with `#2C1810` and text `#FBF8F2`; unselected state is bordered with `#E8E2D8` with text `#615249`.

### Checkboxes & Radios
- **Control:** 18px box with `0.25rem` radius (or circle for radio).
- **Default:** 1.5px border `#E8E2D8` on white.
- **Checked:** Filled `#2C1810` with a sharp milk cream `#FBF8F2` icon.

### Local Store Indicator (Domain-Specific)
- Dedicated persistent component showing local roastery / cafe bar status. Includes a pulsating dot indicator (Forest Pine `#264635` when open, warm amber `#B85D19` when roasting, muted stone when closed) alongside current batch roast date and pickup availability window.