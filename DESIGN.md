---
name: Cerrajería GL
colors:
  surface: '#f7f9fc'
  surface-dim: '#d8dadd'
  surface-bright: '#f7f9fc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f7'
  surface-container: '#eceef1'
  surface-container-high: '#e6e8eb'
  surface-container-highest: '#e0e3e6'
  on-surface: '#191c1e'
  on-surface-variant: '#44474d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f4'
  outline: '#75777e'
  outline-variant: '#c4c6ce'
  surface-tint: '#4d5f7d'
  primary: '#000615'
  on-primary: '#ffffff'
  primary-container: '#0b1f3a'
  on-primary-container: '#7587a7'
  inverse-primary: '#b5c7ea'
  secondary: '#7e5700'
  on-secondary: '#ffffff'
  secondary-container: '#feb300'
  on-secondary-container: '#6a4800'
  tertiary: '#000801'
  on-tertiary: '#ffffff'
  tertiary-container: '#00250b'
  on-tertiary-container: '#009b46'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#b5c7ea'
  on-primary-fixed: '#071c36'
  on-primary-fixed-variant: '#364764'
  secondary-fixed: '#ffdeac'
  secondary-fixed-dim: '#ffba35'
  on-secondary-fixed: '#281900'
  on-secondary-fixed-variant: '#5f4100'
  tertiary-fixed: '#66ff8e'
  tertiary-fixed-dim: '#3de273'
  on-tertiary-fixed: '#002109'
  on-tertiary-fixed-variant: '#005322'
  background: '#f7f9fc'
  on-background: '#191c1e'
  surface-variant: '#e0e3e6'
typography:
  display-hero:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 54px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 38px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 30px
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-action:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '700'
    lineHeight: 22px
    letterSpacing: 0.01em
  label-badge:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  numeral-display:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-desktop: 2.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
---

## Brand & Style

This design system is tailored for an emergency and residential locksmith workshop located in Rosario, Argentina. In critical lock-out or break-in situations, users experience immediate stress, vulnerability, and cognitive overload. The UI prioritizes absolute clarity, swift reassurance, rapid contact routes, and neighborhood familiarity.

The aesthetic blends **Modern Utilitarian** structure with **Tactile High-Accessibility**. Visual weight is allocated systematically: immediate utility elements (phone dialers, WhatsApp triggers, location badges) receive bold tactile hierarchy, while secondary workshop capabilities (transponder keys, duplicate services, safe opening) reside on clean, organized containers. The tone evokes technical precision, verified legitimacy, and immediate human relief.

## Colors

- **Primary (`#0B1F3A` - Deep Marine Blue):** Establishes institutional weight, safety, and operational credibility. Used for primary typography, authoritative headers, key iconography, and dark utility bars.
- **Secondary (`#FFB400` - Energetic Amber/Yellow):** High-urgency focal point engineered for maximum contrast against deep blue and white. Dedicated to direct emergency phone call-to-actions, arrival estimates, and high-priority action alerts.
- **Tertiary (`#25D366` - WhatsApp Green):** Frictionless channel for sharing live GPS location and photographic evidence of damaged locks. Exclusively reserved for instant messaging conversion buttons and live presence indicators.
- **Neutral Surface (`#F4F6F9` - Light Warm Slate):** Soft background alternative to stark white (`#FFFFFF`) to prevent eye fatigue while defining distinct card sections.
- **Borders & Dividers (`#E2E8F0`):** Subtle boundaries to delineate actionable zones without creating heavy visual noise.

## Typography

The typography leverages **Inter** for its neutral grotesque proportions, unambiguous numerical clarity, and exceptional legibility across high-glare outdoor mobile contexts.

- **Hero & Emergency Titles:** Set with tighter negative letter spacing and heavy weights (`800`) to communicate immediacy and strength.
- **Contact Numbers:** Rendered using tabular figures to ensure phone numbers and neighborhood wait times read immediately at a glance.
- **Body & Captions:** Ample line heights maintain readability under stressed scanning behaviors.

## Layout & Spacing

A 12-column responsive fluid grid governs desktop displays (max container width: `1200px`), collapsing to a single-column layout on mobile devices (`< 768px`) with persistent thumb-accessible bottom action drawers.

- **Mobile Viewport Priority:** Spacing is condensed vertically (`margin: 1rem`) to keep the primary call triggers above the natural thumb fold.
- **Touch Ergonomics:** Component gaps (`space-md`) prevent accidental dial touches while ensuring interactive surface areas hit a minimum of 48px height.
- **Desktop Rest:** Section separations employ generous padding (`space-2xl`) to provide calm visual pacing for non-emergency inquiries (workshop catalog, lock brands, pricing transparency).

## Elevation & Depth

Visual hierarchy uses **tonal layer stacking with soft, tinted ambient drop shadows** rather than harsh structural borders.

- **Level 0 (Canvas):** Pure `#FFFFFF` and `#F4F6F9` base layers.
- **Level 1 (Cards & Workshop Shelves):** Resting surfaces elevated with a subtle outline (`1px solid #E2E8F0`) and ambient shadow: `box-shadow: 0 4px 16px -2px rgba(11, 31, 58, 0.06)`.
- **Level 2 (Emergency CTAs & Floaters):** High-touch bottom emergency bars and action chips: `box-shadow: 0 8px 24px -4px rgba(255, 180, 0, 0.35)` for urgent dialers, and `0 8px 24px -4px rgba(37, 211, 102, 0.30)` for WhatsApp widgets.
- **Level 3 (Modal Alerts & Live Status Overlays):** Grounded overlays: `box-shadow: 0 16px 32px -8px rgba(11, 31, 58, 0.16)`.

## Shapes

The design uses balanced **Level 2 Roundedness** (`0.5rem` / `8px` baseline). 

- **Cards and Containers:** `rounded-lg` (`1rem` / `16px`) creates approachable, non-aggressive frames.
- **Emergency Action Buttons:** `rounded-xl` (`1.5rem` / `24px`) or complete pill radius for bottom fixed sticky triggers, delivering a modern native-app mobile utility feel.
- **Trust Badges & Chips:** Compact `0.5rem` (`8px`) corners maintain high structural compactness.

## Components

### Emergency Action Buttons
- **Primary Urgent Call Button:** Full-width mobile component. Background `#FFB400`, label in `#0B1F3A` (`label-action`), accompanied by an immediate phone receiver icon. Active states darken subtly with tactile downward press feedback (`transform: translateY(1px)`).
- **Direct WhatsApp Conversion Button:** Background `#25D366`, typography `#FFFFFF`. Includes a sub-label stating *"Envianos foto o ubicación actual"*.

### Live Status Badges
- Inline pill components indicating real-time availability: green pulse indicator dot (`#25D366`) paired with copy like *"En guardia ahora en Rosario"* or *"Móvil libre en zona centro: demora aprox 15-25 min"*.

### Emergency Locksmith Cards
- Clean `#FFFFFF` cards with `#E2E8F0` borders containing service categories: *Apertura de Casas*, *Cerrajería Automotor*, *Apertura de Cajas Fuertes*, and *Cambio de Combinaciones*. Feature immediate price hints and estimated dispatch arrival times.

### Floating Mobile Action Bar
- Sticky anchor locked to the viewport base on mobile screens. Features a split 50/50 layout: "Llamar Urgente" (Amber) and "WhatsApp" (Green), ensuring zero friction navigation regardless of scroll position.

### Neighborhood Coverage Selector
- Interactive chip list representing Rosario districts (Centro, Pichincha, Echesortu, Fisherton, Alberdi, Tiro Suizo) allowing the user to view localized response times immediately.