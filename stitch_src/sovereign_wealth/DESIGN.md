---
name: Sovereign Wealth
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#414844'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#717973'
  outline-variant: '#c1c8c2'
  surface-tint: '#3f6653'
  primary: '#012d1d'
  on-primary: '#ffffff'
  primary-container: '#1b4332'
  on-primary-container: '#86af99'
  inverse-primary: '#a5d0b9'
  secondary: '#2c694e'
  on-secondary: '#ffffff'
  secondary-container: '#aeeecb'
  on-secondary-container: '#316e52'
  tertiary: '#550007'
  on-tertiary: '#ffffff'
  tertiary-container: '#7b0b13'
  on-tertiary-container: '#ff817a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c1ecd4'
  primary-fixed-dim: '#a5d0b9'
  on-primary-fixed: '#002114'
  on-primary-fixed-variant: '#274e3d'
  secondary-fixed: '#b1f0ce'
  secondary-fixed-dim: '#95d4b3'
  on-secondary-fixed: '#002114'
  on-secondary-fixed-variant: '#0e5138'
  tertiary-fixed: '#ffdad7'
  tertiary-fixed-dim: '#ffb3ae'
  on-tertiary-fixed: '#410004'
  on-tertiary-fixed-variant: '#8b191d'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display-hero:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.04em
  currency-stat:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 30px
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
  space-xl: 2rem
---

## Brand & Style
The design system establishes a high-trust, editorial-grade financial atmosphere combining the utilitarian precision of contemporary fintech flagships (Wise, Revolut) with the understated elegance of private wealth management. 

Targeted at modern investors and affluent digital natives, the interface prioritizes clarity, calm authority, and frictionless transacting. The design language merges Nordic minimalism with tactile depth: expansive soft off-white workspaces, deep forest green anchoring points, precise typography, and soft, organic card elevations. The emotional tone avoids cold, speculative crypto tropes in favor of enduring stewardship, discretion, and effortless execution.

## Colors
The color architecture relies on high-contrast natural tones that impart stability and organic growth:

- **Primary (`#1B4332`)**: Deep Forest Green serves as the primary ground for high-priority actions, header anchors, key branding elements, and high-value metric highlights.
- **Secondary (`#2D6A4F`) & Accent Mint (`#40916C`)**: Used for progressive positive trends, deposits, completed flow state indicators, and active filters.
- **Tertiary (`#D9534F`)**: Muted Warm Terracotta reserved for outflows, debit transactions, risk parameters, and negative delta variances, replacing abrasive neon reds with a sophisticated editorial warm tone.
- **Neutral Canvas (`#F8F9FA`)**: An ultra-soft off-white canvas preventing retinal fatigue while providing clean contrast against pure white (`#FFFFFF`) card surfaces.
- **Surface Ivory (`#F3F4F1`)**: Utilized for secondary grouping trays, segmented controls, and nested list containers.
- **Text & Borders**: Primary text utilizes near-black carbon (`#111915`), secondary text uses slate-sage (`#5A6860`), and structural dividers are calibrated to an ultra-thin 1px border (`#E5E8E3`).

## Typography
The system is built entirely on `Inter` with optical tracking dialed to emulate premium native iOS typography (San Francisco Pro feel). 

- **Numeric Rendering**: Financial tables, balances, and transaction ledgers must activate tabular figures (`font-variant-numeric: tabular-nums;`) to maintain vertical column parity.
- **Hierarchy Structure**: High-denomination balances leverage `display-hero` with tight negative tracking (`-0.03em`), generating an authoritative focal point.
- **Labels & Micro-data**: Overline labels and badge indicators utilize semi-bold uppercase tracking (`0.02em` to `0.04em`) to ensure legibility on compact mobile screens.

## Layout & Spacing
The layout follows an 8pt architectural rhythm anchored by a 4-column layout on mobile devices (`<600px`), shifting to an 8-column layout on tablets (`600px - 1024px`) and a 12-column fixed-max layout (`1200px` max-width) on desktop surfaces.

- **Mobile Viewports**: Canvas outer margin is pinned to `margin` (16px), giving cards full horizontal presence while maintaining a disciplined gutter between modular grid items.
- **Vertical Rhythm**: Section separation follows a strict scale: 8px between closely coupled meta-elements, 16px between list items and input fields, and 24px to 32px between distinct domain modules (e.g., Accounts Overview into Wealth Allocations).
- **Safe Area Insets**: Bottom sheets and fixed floating execution bars explicitly respect native iOS home-bar clearances with an automated `env(safe-area-inset-bottom) + 12px` offset.

## Elevation & Depth
Visual hierarchy avoids overt flat-brutalism and harsh drop shadows, employing multi-stop ambient shadows layered over translucent, border-delimited planes:

- **Level 0 (Canvas Base)**: `#F8F9FA` uniform background.
- **Level 1 (Card & Module Layer)**: Pure `#FFFFFF` or Ivory `#F3F4F1` surface framed with a 1px solid border (`rgba(27, 67, 50, 0.06)`), combined with an ambient shadow: `0px 2px 8px -2px rgba(27, 67, 50, 0.03), 0px 8px 24px -4px rgba(27, 67, 50, 0.05)`.
- **Level 2 (Interactive Floating Elements & Sheets)**: Persistent action rails and bottom sheets feature subtle background blurs (`backdrop-filter: blur(20px); background: rgba(255, 255, 255, 0.88);`) with deep diffused shadows: `0px 12px 36px -6px rgba(17, 25, 21, 0.08), 0px 4px 12px -2px rgba(17, 25, 21, 0.03)`.
- **Level 3 (Modals & Overlays)**: Centered security alerts and PIN validation overlays utilize a tinted back-scrim (`rgba(17, 25, 21, 0.40)`) with an elevation shadow of `0px 24px 48px -12px rgba(0, 0, 0, 0.16)`.

## Shapes
The structural geometry is defined by generous modern roundedness, balancing structured financial spreadsheets with organic, thumb-friendly mobile gestures:

- **Cards & Primary Modules**: Standardized to `16px` to `24px` radius (token equivalent `rounded-lg` to `rounded-xl`). High-surface cards (such as the main balance portfolio card) utilize the full `24px` radius to create a soft, inviting container.
- **Pills & Status Badges**: Configured with a fully rounded radius (`9999px`) to create distinctive pill capsules for transaction tags, asset class chips, and currency selectors.
- **Interactive Inputs & Buttons**: Unified at `14px` to `16px` curvature for effortless tap targeting.

## Components

### Buttons
- **Primary Action**: Deep Forest Green (`#1B4332`) filled button with pure white text, 52px height for mobile ergonomics, 16px corner radius, semi-bold typography (`body-md`), active state scaling subtly to `scale(0.98)` with a background shift to `#143326`.
- **Secondary Action**: Warm Ivory (`#F3F4F1`) filled button with Primary Green text and subtle `1px` border (`#E5E8E3`).
- **Ghost/Tertiary**: Borderless, 44px minimum touch-target, secondary slate-sage text transitioning to deep green on press.

### Cards & Account Tiles
- **Standard Card**: White (`#FFFFFF`) background, 20px padding, 20px radius, enclosed by a 1px border (`rgba(27, 67, 50, 0.06)`).
- **Featured Card**: Deep Forest Green (`#1B4332`) backdrop with Mint accents (`#40916C`), carrying white and ivory textual tiers, designed specifically for active debit cards and total portfolio valuation summaries.

### Badges & Pill Chips
- **Status Badges**: Pill-shaped (`rounded-full`), 6px vertical padding by 12px horizontal padding. Positive trend: soft mint background (`rgba(64, 145, 108, 0.12)`) with `#2D6A4F` text. Negative trend/Outflow: soft terracotta background (`rgba(217, 83, 79, 0.12)`) with `#D9534F` text.
- **Filter Chips**: 36px height, pill form, `#F3F4F1` surface with `#5A6860` text when inactive; primary `#1B4332` surface with `#FFFFFF` text when selected.

### Input Fields & Controls
- **Amount & Transfer Inputs**: Minimalist borderless styling with large-format numeric text (`display-hero-mobile`), right-aligned inline pill for currency selection (`USD`, `EUR`, `GBP`), and dynamic exchange rate label micro-text directly beneath.
- **Form Text Fields**: 52px height, 14px radius, `#FFFFFF` surface with a resting `#E5E8E3` border. Focus state switches to a 1.5px solid `#2D6A4F` outline with an ultra-soft focus ring (`rgba(45, 106, 79, 0.10)`).

### Transaction Lists
- **Rows**: 64px row height, divided by 1px subtle hairline dividers (`#F1F3EE`). Left: 44px rounded-full avatar container for vendor logo or category icon in Ivory (`#F3F4F1`). Center: Counterparty name (`headline-sm`, 15px) stacked above transaction timestamp (`body-sm`). Right: Tabular amount with dynamic color allocation (Terracotta for `-`, Forest Green for `+`).

### Specialized Domain Components
- **Asset Allocation Segment**: Segmented progress tracks with 8px height, 9999px radius, visually broken into proportional widths representing cash, equities, and commodities using the primary, mint, and muted amber palettes.
- **Quick Action Dock**: A horizontally scrolling or 4-column icon matrix featuring 48px circular tactile buttons (Send, Add, Convert, Freeze) with centered label micro-text below.