---
name: Sialkot Motors
colors:
  surface: '#0b1325'
  surface-dim: '#0b1325'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e1f'
  surface-container-low: '#131b2e'
  surface-container: '#181f32'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3448'
  on-surface: '#dbe2fb'
  on-surface-variant: '#d8c3ad'
  inverse-surface: '#dbe2fb'
  inverse-on-surface: '#283043'
  outline: '#a08e7a'
  outline-variant: '#534434'
  surface-tint: '#ffb95f'
  primary: '#ffc174'
  on-primary: '#472a00'
  primary-container: '#f59e0b'
  on-primary-container: '#613b00'
  inverse-primary: '#855300'
  secondary: '#c1c7cf'
  on-secondary: '#2b3137'
  secondary-container: '#41474e'
  on-secondary-container: '#afb6bd'
  tertiary: '#51e77b'
  on-tertiary: '#003915'
  tertiary-container: '#2bca62'
  on-tertiary-container: '#004f20'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffddb8'
  primary-fixed-dim: '#ffb95f'
  on-primary-fixed: '#2a1700'
  on-primary-fixed-variant: '#653e00'
  secondary-fixed: '#dde3eb'
  secondary-fixed-dim: '#c1c7cf'
  on-secondary-fixed: '#161c22'
  on-secondary-fixed-variant: '#41474e'
  tertiary-fixed: '#6bff8f'
  tertiary-fixed-dim: '#4ae176'
  on-tertiary-fixed: '#002109'
  on-tertiary-fixed-variant: '#005321'
  background: '#0b1325'
  on-background: '#dbe2fb'
  surface-variant: '#2d3448'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 26px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies the executive stature and precision engineering of an ultra-premium automotive marketplace tailored for the discerning collector and luxury buyer in Pakistan. The aesthetic fuses Modern Architectural Minimalism with Glassmorphism, balancing dark obsidian depth with high-luminance ice silver and electric gold accents. 

Visual interactions should evoke high-performance machinery: frictionless, refined, authoritative, and secure. The system avoids visual clutter, favoring sweeping atmospheric gradients, frosted dark-slate surfaces, and high-contrast typography designed to showcase vehicle silhouettes, certification standards, and high-value transactions with understated prestige.

## Colors

The foundation is built upon deep cosmic navies and rich obsidians, creating a theatrical showroom floor for automotive assets:

- **Surface Base (`#0B1325`) & Surface Elevated (`#0F172A`)**: Provide an absorbing, noise-free midnight backdrop that maximizes dynamic contrast.
- **Primary Accent (`#F59E0B` to `#D97706`)**: Electric amber/gold reserved strictly for high-intent actions, transaction price points in PKR, star ratings, and verified status marks.
- **Secondary Chrome (`#E2E8F0`)**: An icy metallic sheen utilized for secondary headers, fine structural dividers, chassis spec iconography, and muted borders.
- **Tertiary Utility (`#22C55E`)**: A vibrant emerald green reserved exclusively for instant verified dealer handshakes, active availability tags, and native WhatsApp integration points.
- **Surface Overlays**: Semi-transparent slate layers (`rgba(15, 23, 42, 0.75)`) calibrated with backdrop-filter blurs to yield an executive glass appearance.

## Typography

Typography establishes an architectural balance between the geometric luxury of Plus Jakarta Sans and the clinical, data-dense clarity of Inter:

- **Headlines & Badges (Plus Jakarta Sans)**: Rendered in semi-bold and bold weights to project executive presence. Tighter tracking (`-0.02em`) is applied to `headline-xl` and `headline-lg` to create a commanding, high-end editorial feel across vehicle hero showcases.
- **Body & Specs (Inter)**: Handles technical vehicle specifications, PKR currency tallies, mileage metrics, and registration credentials. Line heights are spaced generously to preserve legibility against dark slate surfaces.
- **Numbers & Metrics**: All numerical data (PKR currency values, model years, engine cubic capacities) utilize tabular figures to ensure effortless scanning across comparison matrices and inventory feeds.

## Layout & Spacing

The layout is anchored by a structured 12-column responsive fluid grid designed for expansive automotive viewports:

- **Desktop (1200px+)**: 12 columns with a `3rem` canvas margin and `1.5rem` gutters. Inventory grids use balanced 3-column cards (`col-span-4`) with an optional 4-column master search panel.
- **Tablet (768px - 1199px)**: 8 columns with a `2rem` canvas margin and `1.25rem` gutters. Inventory views shift into a 2-column card orientation (`col-span-4`).
- **Mobile (< 768px)**: 4 columns with a `1.25rem` margin and `1rem` gutters. Horizontal scrolling pill carousels handle quick-filters (make, model, city registration), with single-column cards (`col-span-4`) for vehicle listings.

Structural padding strictly adheres to the 8px baseline rhythm (`space-sm`, `space-md`, `space-lg`, `space-xl`), allowing high-definition automotive photography to breathe against deep obsidian canvas margins.

## Elevation & Depth

Visual depth is achieved through layered tonal surfaces, dark glassmorphism, and colored ambient lighting rather than standard drop shadows:

- **Level 0 (Showroom Floor)**: Base canvas `#0B1325`. Non-elevated, flat deep midnight background.
- **Level 1 (Card & Module Layer)**: Background `#0F172A` at 85% opacity with `backdrop-filter: blur(16px)` and a 1px perimeter outline (`rgba(226, 232, 240, 0.08)`).
- **Level 2 (Dropdowns, Sheets, & Sticky Navbars)**: Background `#0B1325` at 80% opacity with `backdrop-filter: blur(24px)`, anchored by an ultra-diffused amber-tinted shadow: `0 20px 40px -15px rgba(0, 0, 0, 0.7), 0 0 1px 1px rgba(245, 158, 11, 0.15)`.
- **Level 3 (Modals & Full Lightbox Viewers)**: Solid midnight tone with a high-depth ambient wash: `0 32px 64px -12px rgba(0, 0, 0, 0.9)`.
- **Specular Highlights**: Glass edges feature an asymmetrical top border highlight (`rgba(255, 255, 255, 0.12)`) simulating direct overhead showroom spotlighting.

## Shapes

The design system employs a refined curvature profile (`roundedness: 2` base) calibrated to harmonize with contemporary automotive industrial design:

- **Listing & Feature Cards**: Standardized on `rounded-2xl` (1.5rem), providing a smooth exterior frame that matches aerodynamic body styling.
- **Interactive Controls & Inputs**: Form fields, segmented filters, and standard CTAs utilize `rounded-lg` (1rem) for an ergonomic, tactile touch target.
- **Badges, Pills, & Status Tags**: Fully rounded pill shapes (`rounded-full`) to delineate metadata tags from structural layout containers.
- **Image Frames**: Vehicle media viewports inherit the inner radius curvature of their parent card, utilizing `overflow-hidden` with uniform inner boundary clipping.

## Components

### Buttons & Primary Actions
- **Primary CTA**: Background `#F59E0B` graduating subtly to `#D97706`, high-contrast obsidian text (`#0B1325`), bold Plus Jakarta Sans, `rounded-lg`. Hover states introduce an outer luminous aura (`0 0 20px rgba(245, 158, 11, 0.4)`).
- **WhatsApp Direct Connect**: High-contrast emerald green background (`#22C55E`), pure white typography, integrated native WhatsApp vector glyph, styled with tactile micro-interactions for instant regional engagement.
- **Secondary Ghost Controls**: Transparent fill, 1px perimeter border in `#E2E8F0` at 20% opacity, pure white text, transitioning to white/10% fill on hover.

### Vehicle Inventory Cards
- Crafted with `rounded-2xl` frosted slate tiles. 
- Integrated 16:9 aspect ratio media container equipped with progressive image loading.
- Floating upper badges: Verification checkmark on the top-left; PKR price badge in high-luminance amber on the top-right.
- Structural lower spec grid: Monospaced/Inter indicators for engine capacity (e.g., "3.0L Twin-Turbo"), mileage ("12,000 km"), transmission ("Automatic"), and domestic registration locality ("Sialkot Registered / Punjab Plate").

### Precision Filter Controls
- Dark slate pill carousels for fast vehicle brand selection (e.g., Porsche, Audi, Mercedes-Benz, Land Rover).
- Dual-thumb range sliders for PKR price indexing and year filters with metallic silver rails and electric amber drag indicators.
- Segmented switchers with smooth ambient transitions for selecting transmission and fuel type.

### Badges & Status Chips
- **Verified Dealer**: Deep slate pill with a vivid emerald `#22C55E` indicator dot and subtle silver text.
- **Pakistani Regional Specs**: High-contrast tag with ice-silver border denoting domestic import duty status, auction sheet score (e.g., "Grade 5A"), and biometric verification readiness.
- **Specialty Flags**: Amber metallic gradient tag reserved for "Featured" and "Consignment Reserve" vehicles.

### Form Inputs & Search Arrays
- Height: 48px baseline.
- Obsidian dark surfaces (`#070D18`) with 1px inset borders in `rgba(226, 232, 240, 0.15)`.
- Active focus state triggers an ice-silver border transition and subtle amber glow ring (`0 0 0 3px rgba(245, 158, 11, 0.2)`).
- Clear placeholder typography in muted silver (`#94A3B8`).