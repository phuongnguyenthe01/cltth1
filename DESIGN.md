---
name: Nurturing Botanical Atelier
colors:
  surface: '#fff8f5'
  surface-dim: '#ebd6c7'
  surface-bright: '#fff8f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff1e8'
  surface-container: '#ffeadb'
  surface-container-high: '#fae4d4'
  surface-container-highest: '#f4dfcf'
  on-surface: '#241910'
  on-surface-variant: '#58413c'
  inverse-surface: '#3a2e23'
  inverse-on-surface: '#ffeee1'
  outline: '#8c716b'
  outline-variant: '#dfc0b8'
  surface-tint: '#a8381d'
  primary: '#a8371c'
  on-primary: '#ffffff'
  primary-container: '#c94f32'
  on-primary-container: '#ffffff'
  inverse-primary: '#ffb4a3'
  secondary: '#7a5739'
  on-secondary: '#ffffff'
  secondary-container: '#fecea8'
  on-secondary-container: '#795638'
  tertiary: '#586151'
  on-tertiary: '#ffffff'
  tertiary-container: '#707a68'
  on-tertiary-container: '#020601'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad2'
  primary-fixed-dim: '#ffb4a3'
  on-primary-fixed: '#3d0700'
  on-primary-fixed-variant: '#872006'
  secondary-fixed: '#ffdcc2'
  secondary-fixed-dim: '#ecbe99'
  on-secondary-fixed: '#2d1601'
  on-secondary-fixed-variant: '#604024'
  tertiary-fixed: '#dce6d1'
  tertiary-fixed-dim: '#c0cab6'
  on-tertiary-fixed: '#161e11'
  on-tertiary-fixed-variant: '#40493a'
  background: '#fff8f5'
  on-background: '#241910'
  surface-variant: '#f4dfcf'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 58px
    letterSpacing: -0.01em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 34px
    fontWeight: '600'
    lineHeight: 42px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  label-md:
    fontFamily: Be Vietnam Pro
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Be Vietnam Pro
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-md: 1.5rem
  gutter-lg: 2rem
  margin: 1rem
  margin-md: 2rem
  margin-lg: 3.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies an intimate, premium, and deeply nurturing educational aesthetic tailored for Vietnamese parents seeking mindful pre-primary and elementary guidance in Hanoi. The ethos balances the gentleness of early childhood development with academic rigor, pedagogical reliability, and handcrafted care.

### Core Visual Language
- **Tactile Warmth & Paper Craft:** Evoking high-grade cream drawing paper, cloth-bound children's books, and sunlit Hanoi classroom corners. Interfaces prioritize tactile warmth over clinical digital minimalism.
- **Botanical Balance:** Soft sage greens and earthy terra-cotta tones harmonize to convey holistic growth, natural curiosity, and grounded patience.
- **Cultivated Elegance:** Typography honors Vietnamese tone marks and diacritics with graceful proportions, avoiding both austere corporate stiffness and juvenile, cartoonish clutter.

## Colors

The palette establishes an emotional landscape of safety, warmth, and attentive pedagogical care. Contrast complies with WCAG AA guidelines for legibility, ensuring clear reading for parents reviewing curriculums and progress reports on high-density mobile screens.

### Palette Roles
- **Primary Accent (`#C94F32` - Burnt Terra Cotta):** Reserved strictly for primary action buttons, active navigation markers, key notifications, and conversion highlights.
- **Secondary Tone (`#795638` - Earthy Heritage Brown):** Applied to core headings, subheadings, key structural dividing accents, and prominent badge text.
- **Tertiary Tone (`#DCE6D1` - Muted Sage):** Provides gentle framing, subtle status badges (e.g., developmental milestones, completed modules), pill chips, and secondary card fills.
- **Neutral Foreground (`#45382D` - Deep Umber):** Replaces harsh pure black for all body copy, forms, and microcopy to maintain softness while retaining high contrast against pale backgrounds.
- **Canvas & Surface Backgrounds:** 
  - Primary Base Canvas: `#F7F1D8` (Warm Cream)
  - Secondary / Card Surface: `#FFFDF5` (Ivory Vellum)
  - Floating Highlight Surface: `#FFFFFF` (Pure Cotton)
  - Border & Hairline Rules: `#E8DFCA` (Pressed Parchment)

## Typography

The type system blends literary serif poise with modern readability tailored specifically to the Vietnamese writing system.

- **Editorial Headings (Playfair Display):** Conveys academic legacy, classical warmth, and personalized tutoring attentiveness. Rendered in `#795638` with deliberate line heights to guarantee that diacritics such as dấu ngã, dấu hỏi, and dấu nặng remain distinct and uncrowded.
- **Body & Functional Microcopy (Be Vietnam Pro):** Chosen for its native optimization of Vietnamese typography, rendering tone marks with balanced optical spacing and clean geometry across both web and native viewports.
- **Rhythm & Line Height:** Line heights are maintained between 1.5x and 1.625x for paragraph text to ensure comfortable reading of longer developmental logs and pedagogical narratives.

## Layout & Spacing

The layout philosophy follows a structured fluid grid inspired by traditional stationery layouts and editorial lookbooks.

### Grid & Breakpoints
- **Mobile (< 768px):** 4 columns, `margin` of 1rem (`16px`), `gutter` of 1rem (`16px`). Single-column card sequences for pedagogical timelines and enrollment steps.
- **Tablet (768px – 1023px):** 8 columns, `margin-md` of 2rem (`32px`), `gutter-md` of 1.5rem (`24px`).
- **Desktop (1024px+):** 12 columns, max-width constrained to `1200px` centered, `margin-lg` of 3.5rem (`56px`), `gutter-lg` of 2rem (`32px`). Multi-column dashboards for child learning progress and appointment scheduling.

### Spacing Rules
- Elements breathe through consistent increments of 4px and 8px.
- Section paddings utilize `space-xl` combined with canvas tint shifts (`#F7F1D8` to `#FFFDF5`) to segment topics without stark borders.

## Elevation & Depth

Visual hierarchy uses physical paper layering, soft borders, and warm diffused light rather than cold digital drop shadows.

### Elevation Tiers
- **Flat (Canvas):** `#F7F1D8` background sits at base layer 0. No shadow.
- **Level 1 (Card & Section Containers):** `#FFFDF5` surfaces resting over `#F7F1D8`, bounded by a 1px solid `#E8DFCA` border and an ambient warm shadow: `0 2px 8px -2px rgba(121, 86, 56, 0.05), 0 1px 3px 0 rgba(121, 86, 56, 0.03)`.
- **Level 2 (Active Cards & Floating Modules):** `#FFFFFF` surfaces with subtle border `#E8DFCA` and elevated ambient glow: `0 8px 24px -4px rgba(121, 86, 56, 0.08), 0 2px 6px -1px rgba(121, 86, 56, 0.04)`.
- **Level 3 (Modal Sheets & Parent Consultation Drawers):** High-opacity `#FFFDF5` containers framed with `0 16px 36px -6px rgba(69, 56, 45, 0.12)`.

## Shapes

The shape system employs roundedness level 2 (moderate organic rounding), mirroring soft cornered books, wooden developmental blocks, and natural curves.

- **Standard Elements (0.5rem / 8px):** Input fields, interactive chips, small buttons, and dropdown menus.
- **Medium Panels (1rem / 16px - `rounded-lg`):** Course catalog cards, student diary entries, progress snapshot blocks.
- **Large Wrappers (1.5rem / 24px - `rounded-xl`):** Hero containers, parent testimonial quotes, image frames with soft botanical masks.
- **Pills (Full Radius):** Reserved solely for category badges, active status indicators (e.g., "Lớp 1 Chuẩn Bị"), and circular icon triggers.

## Components

### Buttons
- **Primary Action (Burnt Orange CTA):** Solid `#C94F32` background, `#FFFFFF` text, `rounded-md` (8px). Subtle hover transition deepening to `#B54328`. Focus ring: 2px offset in `#C94F32`.
- **Secondary Action (Warm Umber Outline):** Border 1.5px solid `#795638`, transparent background, `#795638` text. Hover fills with `#FFFDF5` and text shifts to `#45382D`.
- **Tertiary / Botanical Gentle:** `#DCE6D1` background, `#45382D` text. Ideal for secondary consultation requests or bookmarking developmental advice.

### Cards
- **Base Curriculum Card:** Base fill `#FFFDF5`, 1px outline in `#E8DFCA`, `rounded-lg` (16px). Padding set to `space-lg` (24px). Internal card headers use `#795638` in Playfair Display.
- **Progress Card:** Surface `#FFFFFF`, featuring a left border accent (4px solid `#DCE6D1` or `#C94F32`) to denote learning track categories.

### Inputs & Form Fields
- Surface: `#FFFDF5` with a 1px solid `#E8DFCA` border, `rounded-md` (8px).
- Typography: `#45382D` for input values; placeholder in `#795638` at 60% opacity.
- Focus State: Border color transitions to `#C94F32` with a 3px soft ambient ring `rgba(201, 79, 50, 0.15)`.

### Chips & Badges
- **Milestone Chip:** Background `#DCE6D1`, text `#45382D`, full pill radius, font size `label-md` (`12px`).
- **Session Tag:** Background `#F7F1D8`, border 1px solid `#E8DFCA`, text `#795638`.

### Checkboxes & Radios
- Unchecked: 1.5px border `#E8DFCA`, background `#FFFDF5`, `rounded-sm` (4px for checkbox, full circle for radio).
- Checked: Fill `#C94F32` with a crisp white tick/dot.

### Pedagogical Milestone Timeline
- Continuous 2px vertical guide rail rendered in `#E8DFCA`.
- Node markers use small 12px circular pips filled with `#DCE6D1` and bounded by a 2px `#795638` halo on active milestones.