---
name: Nocturne Editorial
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
  on-surface-variant: '#c4c7c8'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#8e9192'
  outline-variant: '#444748'
  surface-tint: '#c6c6c7'
  primary: '#ffffff'
  on-primary: '#2f3131'
  primary-container: '#e2e2e2'
  on-primary-container: '#636565'
  inverse-primary: '#5d5f5f'
  secondary: '#c7c6c6'
  on-secondary: '#2f3031'
  secondary-container: '#464747'
  on-secondary-container: '#b5b5b5'
  tertiary: '#ffffff'
  on-tertiary: '#303030'
  tertiary-container: '#e4e2e1'
  on-tertiary-container: '#656464'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c7'
  on-primary-fixed: '#1a1c1c'
  on-primary-fixed-variant: '#454747'
  secondary-fixed: '#e3e2e2'
  secondary-fixed-dim: '#c7c6c6'
  on-secondary-fixed: '#1b1c1c'
  on-secondary-fixed-variant: '#464747'
  tertiary-fixed: '#e4e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1b1c1c'
  on-tertiary-fixed-variant: '#474746'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-hero:
    fontFamily: Syne
    fontSize: 112px
    fontWeight: '700'
    lineHeight: 96px
    letterSpacing: -0.04em
  display-hero-mobile:
    fontFamily: Syne
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Syne
    fontSize: 64px
    fontWeight: '600'
    lineHeight: 68px
    letterSpacing: -0.03em
  headline-lg-mobile:
    fontFamily: Syne
    fontSize: 38px
    fontWeight: '600'
    lineHeight: 42px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Syne
    fontSize: 36px
    fontWeight: '500'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 22px
    fontWeight: '500'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-mono:
    fontFamily: Space Grotesk
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.08em
  editorial-accent:
    fontFamily: Syne
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: -0.01em
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 4rem
  margin-tablet: 2rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 2rem
  space-xl: 4rem
  space-2xl: 8rem
---

## Brand & Style

This design system embodies an avant-garde, stark editorial minimalism rooted in contemporary photography studios, high-fashion monographs, and independent creative directions. The aesthetic balances aggressive Swiss architectural typography against contemplative, generous negative space. 

It evokes mystery, razor-sharp technical discipline, and haute-couture restraint. Interfaces are treated as printed exhibition catalogues brought to digital life: confident scale shifts, unyielding jet-black tones, hairline grid dividers, and deliberate asymmetry replace conventional interface decorative clutter.

## Colors

The palette is strictly monochromatic and high-contrast, avoiding saturated hues to let visual artwork, photography, and type dynamics command attention.

- **Primary Canvas & Surfaces (`#0A0A0A`)**: A deep, absorbing obsidian black that eliminates screen glare and elevates media depth. Surface elevations transition subtly to `#141414` and `#1A1A1A`.
- **Primary Text & High Contrast Elements (`#F8F8F8`)**: Crisp, stark off-white delivering uncompromised legibility and editorial punch without clinical optical fatigue.
- **Secondary / Metadata (`#8E8E8E`)**: Mid-gray dedicated to technical annotations, index labels, captions, and secondary timestamps.
- **Hairline Dividers & Framing (`#262626` / `#333333`)**: Ultra-refined razor borders that delineate grid structures and asymmetrical modules without visual heaviness.
- **Inverted Canvas (`#F8F8F8` with `#0A0A0A` text)**: Utilized intentionally for high-impact callout sections (e.g., editorial inquiry blocks and booking forms) to generate dramatic visual tension.

## Typography

Typography acts as the dominant architectural spine. The system leverages **Syne** for sculptural, provocative display headlines; **Inter** for clean, crystalline utilitarian reading; and **Space Grotesk** for precise technical metadata, numerals, and navigation brackets.

- **Dramatic Scale Shifts**: Headlines are intentionally oversized, colliding with layout boundaries and overlapping photographic compositions to emphasize scale.
- **Lowercase & Editorial Punctuation**: Major navigation and display anchors frequently adopt disciplined lowercase styling (e.g., `services`, `studio`, `contact me`) paired with monospaced brackets (`[mtl]`) and parenthetical subtitles `(uniq conditions)`.
- **Text Ratios**: High tracking in metadata labels contrasts against tightly condensed negative tracking in large display heroes.

## Layout & Spacing

The layout is built upon an asymmetric 12-column fluid grid on desktop (reflowing to 6 columns on tablet and 2 columns on mobile). 

- **Asymmetry & Editorial Tension**: Avoid uniform center alignments. Stagger blocks across unexpected column anchors (e.g., left headline span 4, offset content span 6 at column 7) to mirror high-end editorial magazines.
- **Section Rhythm**: Generous vertical breathings (`space-2xl` / 8rem+) between thematic sections ensure imagery and oversized type resonate without competition.
- **Breakpoint Mechanics**:
  - **Desktop (1200px+)**: 12 columns, 64px canvas margins, flexible gutters, expansive horizontal image offsets.
  - **Tablet (768px – 1199px)**: 6 columns, 32px canvas margins, vertical stacking for complex price matrices.
  - **Mobile (<768px)**: 2 columns, 20px canvas margins. Editorial display type scales down aggressively to maintain one-to-two line integrity while maintaining oversized presence.

## Elevation & Depth

This design system rejects conventional drop shadows and skeuomorphic blur stacks. Depth is achieved purely through **luminance contrast, structural layering, and planar containment**:

- **Hairline Framing**: Structural separation is achieved via `1px solid #262626` borders. Surfaces do not lift off the page; they are segmented like architectural blueprints.
- **Tonal Inversion**: Dramatic emphasis is established by inverting planes—shifting from a pitch-black surface to an intense `#F8F8F8` white container block, turning content into a visual gravitational pull.
- **Photographic Bleeds & Text Overlays**: Text layers directly intersect and overlap grayscale imagery with subtle blend interactions, asserting depth through pure z-index choreography rather than blurred shadows.
- **Backdrop Frosting**: Sticky top navigation utilities utilize a minimal `rgba(10, 10, 10, 0.8)` veil with a razor-thin `backdrop-filter: blur(8px)` and bottom hairline border (`#1A1A1A`).

## Shapes

The geometric philosophy is strictly **sharp and architectural (0px radius)** across all core layout elements, input fields, and imagery frames. This enforces a modern, uncompromising Brutalist discipline.

- **Exceptions for Typographic Embellishments**: Pill-shaped or oval contours are reserved exclusively as delicate parenthetical containers (e.g., hand-drawn or fine-line oval badges containing italicized notes or pricing subtext like `(stylist, make-up artist and hairstyle are paid separately)`). All buttons, containers, cards, and modal sheets remain sharply unrounded (`0px`).

## Components

### Buttons & Interactive Links
- **Primary Action**: Crisp rectangles with a stark `#F8F8F8` background and `#0A0A0A` typography. On hover, background inverts to `#0A0A0A` with a crisp `1px solid #F8F8F8` border and white text.
- **Text & Editorial Links**: Underlined by a hairline border with 4px offset. Hover triggers a subtle forward translate transition (`transform: translateX(4px)`) or an arrow glyph reveal (`->`).
- **Pill Tags**: Enclosed in delicate 1px borders with generous horizontal padding, used for inline disclaimers or contextual categorization.

### Input Fields
- **Underline-Only Fields**: Minimalist bottom-border-only design (`1px solid #333333`). No background fill. Labels sit in uppercase `Space Grotesk` above or float directly on the hairline. Focus shifts border to `#F8F8F8` with a 200ms ease.

### Cards & Service Tiers
- **Structure**: Transparent backgrounds partitioned by top and bottom hairline borders. 
- **Layout**: Large headline typography juxtaposed with right-aligned bold numerals (e.g., `studio` at 36px aligned across from `5 700€`), followed by modular columns containing technical inclusions and monochromatic thumbnail visuals.

### Navigation Header
- **Layout**: Fixed or sticky top bar, edge-to-edge with 1.5rem vertical padding. Left bracket branding (`[mtl]`), right-aligned minimal links in lowercase `Space Grotesk`, separated by generous horizontal gaps (`space-lg`).

### Monochromatic Media Blocks
- **Image Displays**: Strict 100% grayscale images with crisp edges, set against `#0A0A0A`. Dynamic hover reveals a smooth brightness scale or slight cursor-following custom metadata tag.