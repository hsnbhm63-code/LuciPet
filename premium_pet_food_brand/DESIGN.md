---
name: Premium Pet Food Brand
colors:
  surface: '#f9f9ff'
  surface-dim: '#cfdaf2'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d8e3fb'
  on-surface: '#111c2d'
  on-surface-variant: '#4f4633'
  inverse-surface: '#263143'
  inverse-on-surface: '#ecf1ff'
  outline: '#817661'
  outline-variant: '#d3c5ac'
  surface-tint: '#795900'
  primary: '#795900'
  on-primary: '#ffffff'
  primary-container: '#fbbf24'
  on-primary-container: '#6c4f00'
  inverse-primary: '#f9bd22'
  secondary: '#a73a00'
  on-secondary: '#ffffff'
  secondary-container: '#fd651e'
  on-secondary-container: '#571a00'
  tertiary: '#006a61'
  on-tertiary: '#ffffff'
  tertiary-container: '#6ddacc'
  on-tertiary-container: '#005e56'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdf9f'
  primary-fixed-dim: '#f9bd22'
  on-primary-fixed: '#261a00'
  on-primary-fixed-variant: '#5c4300'
  secondary-fixed: '#ffdbce'
  secondary-fixed-dim: '#ffb599'
  on-secondary-fixed: '#370e00'
  on-secondary-fixed-variant: '#7f2b00'
  tertiary-fixed: '#89f5e7'
  tertiary-fixed-dim: '#6bd8cb'
  on-tertiary-fixed: '#00201d'
  on-tertiary-fixed-variant: '#005049'
  background: '#f9f9ff'
  on-background: '#111c2d'
  surface-variant: '#d8e3fb'
typography:
  display-hero:
    fontFamily: Vazirmatn
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 68px
  display-hero-mobile:
    fontFamily: Vazirmatn
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 48px
  headline-lg:
    fontFamily: Vazirmatn
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 52px
  headline-lg-mobile:
    fontFamily: Vazirmatn
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 38px
  headline-md:
    fontFamily: Vazirmatn
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 36px
  headline-sm:
    fontFamily: Vazirmatn
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Vazirmatn
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 32px
  body-md:
    fontFamily: Vazirmatn
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 28px
  body-sm:
    fontFamily: Vazirmatn
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Vazirmatn
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 22px
  label-md:
    fontFamily: Vazirmatn
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 20px
  label-sm:
    fontFamily: Vazirmatn
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
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
  margin: 2.5rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
---

## Brand & Style

The brand personality embodies care, warmth, premium organic nutrition, and joyful companionship. The visual tone bridges modern corporate clarity with appetizing vitality: high-energy warm hues derived from packaging graphics paired with pristine white and soft milky-cream canvases.

Target audiences include dedicated pet parents, veterinary partners, and premium pet store retailers seeking uncompromising ingredient purity and certified nutrition standards. The UI communicates reliability, freshness, and high nutritional value.

The design movement is **Modern Clean Minimalist with Organic Warmth**. It leverages spacious layout pacing, fluid natural curves reminiscent of the package wave graphics, clean iconography for nutritional benefits, and tactile micro-interactions that convey quality without clutter.

## Colors

The palette directly reflects the distinct packaging system shown in the product lines:

- **Primary (`#FBBF24` / Golden Amber):** The signature appetizing base hue representing vitality, joy, and sunny premium warmth. Used for primary highlights, badge accents, and conversion triggers.
- **Secondary (`#EA580C` / Warm Orange-Red):** High-energy, warm appetite stimulant found in the packaging crest and flavor flags. Applied to active buttons, urgent announcements, and key nutritional tags.
- **Tertiary (`#0D9488` / Fresh Leaf Green) & Category Blue (`#2563EB`):** Natural ingredient authenticity indicators (Green for natural gizzards/digestive care, Cobalt Blue for training treats/chicken heart, Crimson `#E11D48` for single-ingredient chicken neck/liver).
- **Neutrals & Surfaces:**
  - `surface-base`: `#FFFFFF` (Pure modern white for maximal readability).
  - `surface-warm`: `#FFFBEB` (Pale honey-cream for section differentiation).
  - `surface-subtle`: `#F8FAFC` (Cool neutral gray for technical tables and corporate specifications).
  - `text-primary`: `#0F172A` (Rich slate black for sharp contrast).
  - `text-secondary`: `#475569` (Balanced neutral slate for descriptions and nutritional subtext).

## Typography

The design system enforces **Vazirmatn** across all text layers with explicit right-to-left layout alignment (`dir="rtl"`). 

Typography characteristics:
- **Font Import:** Loaded directly via `@import url('https://fonts.googleapis.com/css2?family=Vazirmatn:wght@400;500;600;700;800&display=swap');`
- **Numeral Rendering:** Persian numeral glyphs (`font-feature-settings: "ss01"`) can be enabled for localized corporate data, phone numbers, and nutrition metrics.
- **Reading Rhythm:** Line-heights for Persian text require greater breathing space (1.6x to 1.8x) compared to Latin equivalents to prevent overlapping ascenders and descenders.
- **Weight Hierarchy:** Bold weights (700 and 800) deliver the brand's energetic personality on marketing banners and hero titles, while clean medium (500) and regular (400) weights optimize long-form ingredients reading.

## Layout & Spacing

A 12-column fluid grid system governs the layout, adjusting gracefully across breakpoints:
- **Desktop (≥ 1280px):** 12-column grid, max canvas width 1280px, 24px gutters, 40px outer safe margins.
- **Tablet (768px - 1279px):** 8-column grid, 20px gutters, 24px outer safe margins.
- **Mobile (< 768px):** 4-column grid, 16px gutters, 20px outer margins.

Spacial Rhythm:
- Spacing relies strictly on an 8pt-based rhythm scale (4px, 8px, 16px, 24px, 40px, 64px).
- Generous top/bottom whitespace (`space-2xl`) sets a premium corporate demeanor, avoiding visual clutter while honoring the vibrant colors of the packaging illustrations.
- RTL directional flow guides the eye naturally from top-right down to the bottom-left call-to-action blocks.

## Elevation & Depth

Visual depth is achieved through soft, warm-tinted ambient shadows and layered surfaces rather than stark, heavy drop shadows:

- **Surface Level 0 (Canvas):** Clean white (`#FFFFFF`) or warm creamy backdrop (`#FFFBEB`).
- **Surface Level 1 (Cards & Product Tiles):** `#FFFFFF` paired with an ultra-soft golden-tinted shadow: `box-shadow: 0 4px 20px -2px rgba(245, 158, 11, 0.08), 0 2px 6px -1px rgba(0, 0, 0, 0.04)`.
- **Surface Level 2 (Floating Navigation & Dropdowns):** Subtle translucent background (`backdrop-filter: blur(12px)` over 92% opacity white) with `box-shadow: 0 12px 32px -4px rgba(15, 23, 42, 0.08)`.
- **Surface Level 3 (Modals & Hero Badges):** High-elevation floating element with `box-shadow: 0 20px 40px -8px rgba(234, 88, 12, 0.16)`.
- **Borders:** Thin, barely visible borders using `#F1F5F9` or `#FEF3C7` (for highlighted cards) maintain structure without creating visual noise.

## Shapes

The shape system adopts a friendly yet controlled curvature that mirrors the organic waves of the packaging:
- **Base Components (Inputs, Small Badges):** 8px (`0.5rem`).
- **Product Cards & Panels (`rounded-lg`):** 16px (`1rem`).
- **Feature Banners & Dietary Callouts (`rounded-xl`):** 24px (`1.5rem`).
- **Pills & Status Chips:** Full pill (`9999px`) for product badges (e.g., "۱۰۰٪ طبیعی", "تک ماده‌ای").

## Components

### Buttons
- **Primary CTA:** Warm Orange (`#EA580C`) background, white text, 8px corner radius, hover transition with slight lift (`translateY(-2px)`) and subtle glow shadow (`rgba(234, 88, 12, 0.25)`).
- **Secondary CTA:** Golden Amber (`#FBBF24`) background with dark slate (`#0F172A`) bold text.
- **Outlined / Tertiary:** Transparent background, 1.5px border in `#CBD5E1`, text in `#334155`, hover state filled with `#FFFBEB`.

### Product & Treat Cards
- White background card with `rounded-lg` corners and soft ambient shadow.
- Top section presents product pouch photography with category accent badge (e.g., Cobalt Blue for training treats, Natural Green for gizzards).
- Product specs display nutritional icons (Dental Health, High Protein, Single Ingredient) in unified line-art style.
- RTL alignment: Thumbnail on right, text details and price on left.

### Badges & Nutrition Chips
- Pill-shaped (`rounded-full`) tags with soft pastel backgrounds and saturated text:
  - Natural / Herbal: Background `#ECFDF5`, Text `#047857`.
  - Single Ingredient: Background `#FEF2F2`, Text `#B91C1C`.
  - Energy / Treat: Background `#FFFBEB`, Text `#B45309`.

### Input Fields & Search Bars
- Background: `#F8FAFC`.
- Border: 1.5px solid `#E2E8F0`, transitioning to `#F59E0B` on focus with 0 0 0 3px `#FEF3C7`.
- Padding: 12px 16px with RTL text alignment and search icon anchored to the right edge.

### Dietary & Feature Tickers
- Horizontal carousel strips showcasing single-ingredient icons with clean micro-copy ("بدون مواد نگهدارنده", "سرشار از کلسیم", "مناسب همه نژادها") enclosed in clean circular frames.