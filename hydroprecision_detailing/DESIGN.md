---
name: HydroPrecision Detailing
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#44474d'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#74777e'
  outline-variant: '#c4c6ce'
  surface-tint: '#4b5f7f'
  primary: '#000d21'
  on-primary: '#ffffff'
  primary-container: '#0c2340'
  on-primary-container: '#778bad'
  inverse-primary: '#b3c7ec'
  secondary: '#00677d'
  on-secondary: '#ffffff'
  secondary-container: '#50d9fe'
  on-secondary-container: '#005c70'
  tertiary: '#140b00'
  on-tertiary: '#ffffff'
  tertiary-container: '#302000'
  on-tertiary-container: '#b58100'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d5e3ff'
  primary-fixed-dim: '#b3c7ec'
  on-primary-fixed: '#031c38'
  on-primary-fixed-variant: '#334766'
  secondary-fixed: '#b3ebff'
  secondary-fixed-dim: '#4cd6fb'
  on-secondary-fixed: '#001f27'
  on-secondary-fixed-variant: '#004e5f'
  tertiary-fixed: '#ffdea9'
  tertiary-fixed-dim: '#ffba27'
  on-tertiary-fixed: '#271900'
  on-tertiary-fixed-variant: '#5e4100'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
  display-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 34px
    fontWeight: '800'
    lineHeight: 42px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 12px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.25rem
  gutter-mobile: 0.75rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes a high-performance, ultra-clean aesthetic tailored for a premier Portuguese automotive washing and detailing center. The core identity synthesizes industrial precision with the fluid, refreshing clarity of high-pressure water and immaculate finishes.

### Visual Language & Aesthetic Direction
- **Style Archetype:** Modern Technical Clean with Hydro-Luminance. Surfaces leverage crisp whites, polished slate neutrals, and deep petrol navy substrates accented by luminous aqua bursts and energetic yellow signals.
- **Atmosphere:** Spotless, dynamic, technical, and dependable. The interface feels like a spotless professional detailing bay: precision-engineered, free of clutter, bright, and impeccably maintained.
- **Audience & Tone:** Geared toward daily drivers and auto enthusiasts in Portugal who demand meticulous care, rapid transparency, and frictionless digital booking. Tone is professional, clear, energetic, and authoritative.

## Colors

The palette directly mirrors the sensory landscape of elite vehicle detailing: water, pressure, protective coatings, and clear warning/rating highlights.

### Palette Architecture
- **Primary (`#0C2340` - Deep Petrol Navy):** Anchors navigation bars, primary CTAs, titles, and structural framing. Imparts security, mechanical authority, and depth.
- **Secondary (`#00B4D8` - Aqua Hydro Blue):** Evokes pure water flow, active wash cycles, and high-gloss shine. Applied to secondary interactive triggers, active tabs, progress loaders, and service highlights.
- **Tertiary (`#FFB703` - Energetic Amber):** Represents performance badges, VIP packages, instant discount callouts, customer rating stars, and express slot warnings.
- **Neutral (`#64748B` - Slate Core):** Delivers balanced optical weight across borders, inactive states, metadata, and supporting microcopy without muddying the clean white base.
- **Surface & Canvas:**
  - `surface-canvas`: `#F8FAFC` (Pure atmospheric light gray-blue)
  - `surface-card`: `#FFFFFF` (Clinical spotless white)
  - `surface-tint`: `#E0F2FE` (Subtle water wash tint for row alternating and selected states)
  - `text-strong`: `#071526`
  - `text-muted`: `#475569`

## Typography

Plus Jakarta Sans powers all typographical levels, delivering geometric clarity with wide horizontal proportions and contemporary cutouts.

- **Numerals & Metrics:** Pricing, bay timers, duration badges, and license plate selectors utilize bold weights (`700` and `800`) to guarantee instant legibility under natural glare or mobile handheld scenarios.
- **Hierarchy Enforcement:** Uppercase styling is reserved strictly for `label-sm` badges and telemetry indicators (e.g., `BAY OCCUPIED`, `EXPRESS PACK`, `CERAMIC PRO`).
- **European Formatting:** Numerical values must retain standard PT-PT notation (e.g., `24,50 €` with non-breaking spaces).

## Layout & Spacing

The layout model is anchored on an 8-point base grid built for fluid reactivity across desktop, tablet, and mobile devices.

### Grid & Breakpoints
- **Desktop (1024px+):** 12-column layout, `margin` of `2rem` (capped at max-width `1280px`), `gutter` of `1.25rem`. Two-column flows dedicate 65% width to service discovery and 35% width to sticky booking carts.
- **Tablet (768px – 1023px):** 8-column layout, `gutter` of `1rem`, responsive multi-card carousels for detailing tiers.
- **Mobile (< 767px):** 4-column layout, `margin-mobile` of `1rem`, `gutter-mobile` of `0.75rem`. Bottom-anchored sticky checkout sheets and horizontal snap-scroll carousels for vehicle category selectors.

### Spacing Philosophy
Dense technical data (e.g., treatment time, water pressure specs, chemical safety notes) leverages `space-xs` and `space-sm`. Structural cards and checkout steps breathe with `space-lg` and `space-xl` padding to preserve an orderly, premium washroom feel.

## Elevation & Depth

Depth in this system avoids heavy muddy drops. It instead replicates light refraction through pristine glass and polished clear-coat paintwork.

### Depth Scales
- **Level 0 (Flat / Recessed):** `#F1F5F9` surfaces with no shadow. Used for disabled calendar slots, empty wash bay timelines, and inner vehicle diagram zones.
- **Level 1 (Resting Cards):** Background `#FFFFFF`, border `1px solid rgba(100, 116, 139, 0.12)`, shadow: `0 2px 8px -2px rgba(12, 35, 64, 0.05), 0 1px 3px -1px rgba(12, 35, 64, 0.03)`.
- **Level 2 (Hover / Active Cards):** Background `#FFFFFF`, border `1px solid rgba(0, 180, 216, 0.3)`, shadow: `0 10px 24px -4px rgba(12, 35, 64, 0.08), 0 4px 8px -2px rgba(0, 180, 216, 0.12)`.
- **Level 3 (Modals / Sticky Booking Trays):** Shadow: `0 20px 32px -8px rgba(12, 35, 64, 0.16), 0 8px 16px -4px rgba(12, 35, 64, 0.08)`.
- **Gloss Glow (Interactive Accents):** Highlighting prime time slots or selected luxury ceramic services leverages a soft aqua diffuse aura: `box-shadow: 0 0 16px 2px rgba(0, 180, 216, 0.25)`.

## Shapes

The design system employs a roundedness scale set to Level 2 (Rounded: base `0.5rem`, `rounded-lg` at `1rem`, `rounded-xl` at `1.5rem`).

- **Base Components (`0.5rem` / 8px):** Form inputs, buttons, calendar time pills, vehicle type tokens.
- **Containers & Cards (`1rem` / 16px):** Service tiers, booking summary containers, customer review panels, and photo comparison sliders.
- **Overlays & Dialogs (`1.5rem` / 24px):** Bottom drawers on mobile, scheduling modal dialogues, and promotional splash wrappers.
- **Full Pill (`9999px`):** Status indicator tags, vehicle license plate placeholders, and live queue badges.

## Components

### Buttons
- **Primary:** Background `#0C2340`, text `#FFFFFF`, radius `8px`. Hover: `#163A66` with Level 1 elevation. Active: scale 0.98.
- **Secondary (Water Action):** Background `#00B4D8`, text `#071526` (extra bold), radius `8px`. Focus ring: `3px solid rgba(0, 180, 216, 0.45)`.
- **Tertiary Accent (Flash Deals / Urgent Slots):** Background `#FFB703`, text `#071526`.
- **Outline / Ghost:** Border `1.5px solid #CBD5E1`, text `#0C2340`, transparent surface.

### Chips & Filters
- **Vehicle Type Selector (Moto, Ligeiro, SUV, Comercial):** 44px touch targets with embedded line iconography. Inactive: `#F8FAFC` background with `#E2E8F0` border. Active: `#0C2340` background, `#FFFFFF` text, aqua outline glow.
- **Tag Badges:** Font size `10px` uppercase, tracked `+0.05em`, radius `9999px`, padding `4px 10px`.

### Service Status Indicators (Live Bay Monitor)
- **Available / Livre:** Pill with pulsating green-emerald dot (`#10B981`) and muted slate text.
- **In Progress / Em Lavagem:** Pulsating aqua dot (`#00B4D8`) with progress bar micro-fill on card header.
- **Busy / Ocupado:** Solid slate-red dot (`#EF4444`).

### Cards & Service Packages
- **Detailing Tier Card:** Level 1 elevation. Contains package name, vehicle category badge, breakdown checklist with custom aqua check icons, duration estimate (`⏱ 45 min`), and amber rating stars (`★ 4.9`).
- **Featured Card Variant:** Border `2px solid #00B4D8` with top banner reading "MAIS POPULAR ALHOS VEDROS" in tertiary amber.

### Input Fields & Selectors
- **Inputs:** Height 48px, radius `8px`, `#F8FAFC` fill, `#CBD5E1` border. Focused: `#FFFFFF` fill, `#0C2340` border, `3px` aura in `rgba(0, 180, 216, 0.2)`.
- **Portuguese Plate Input:** Specialized format block `[ 00 - AA - 00 ]` with mono-spaced numerals and authentic yellow band support.

### Booking & Scheduling Matrix
- **Time Slot Pill:** Compact 72px x 40px grid item. Available: White surface with slate border. Selected: Solid `#00B4D8` with white bold typography. Disabled: `#F1F5F9` with strikethrough time.