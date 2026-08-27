---
name: Cinematic Developer Core
colors:
  surface: '#111415'
  surface-dim: '#111415'
  surface-bright: '#37393b'
  surface-container-lowest: '#0c0e10'
  surface-container-low: '#1a1c1d'
  surface-container: '#1e2021'
  surface-container-high: '#282a2c'
  surface-container-highest: '#333537'
  on-surface: '#e2e2e4'
  on-surface-variant: '#c8c4d7'
  inverse-surface: '#e2e2e4'
  inverse-on-surface: '#2f3132'
  outline: '#928ea0'
  outline-variant: '#474554'
  surface-tint: '#c6bfff'
  primary: '#c6bfff'
  on-primary: '#2900a0'
  primary-container: '#6c5ce7'
  on-primary-container: '#faf6ff'
  inverse-primary: '#5847d2'
  secondary: '#41ddc2'
  on-secondary: '#00382f'
  secondary-container: '#00c1a7'
  on-secondary-container: '#00483e'
  tertiary: '#c8c6c5'
  on-tertiary: '#313030'
  tertiary-container: '#727171'
  on-tertiary-container: '#faf6f6'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e4dfff'
  primary-fixed-dim: '#c6bfff'
  on-primary-fixed: '#160066'
  on-primary-fixed-variant: '#4029ba'
  secondary-fixed: '#65fade'
  secondary-fixed-dim: '#41ddc2'
  on-secondary-fixed: '#00201b'
  on-secondary-fixed-variant: '#005045'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474646'
  background: '#111415'
  on-background: '#e2e2e4'
  surface-variant: '#333537'
typography:
  display-hero:
    fontFamily: Playfair Display
    fontSize: 84px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
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
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: 0.1em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 32px
  margin-mobile: 24px
  section-gap: 160px
---

## Brand & Style

This design system is built for a premium, high-impact professional presence. It merges **Cinematic Minimalism** with **Glassmorphism**, creating an environment that feels more like a curated digital gallery than a standard portfolio.

The aesthetic utilizes a deep "Pure Black" foundation to make AI-driven visualizations and code blocks pop with maximum vibrance. The emotional response is one of technical mastery, futuristic precision, and high-end craftsmanship. Key visual drivers include ultra-refined typography, generous negative space, and "light-as-material" effects where borders and surfaces appear to emit a soft, internal glow.

## Colors

The palette is rooted in an absolute black (`#000000`) environment to erase the boundaries of the screen. 

- **Primary (Electric Violet):** Used for primary calls to action and critical technical highlights.
- **Secondary (AI Teal):** Reserved for AI-specific features, status indicators, and success states.
- **Surface Strategy:** Layers are built using incremental luminance rather than color shifts, moving from `#000000` to `#141414` for cards and `#1C1C1C` for floating elements.
- **Interactive States:** Use the linear gradient exclusively for high-intent actions or as a "shimmer" effect on glass surfaces.

## Typography

This system uses a tri-font hierarchy to balance technicality with elegance:

1.  **Playfair Display:** Exclusive to the Hero section (Name/Role). It signals "Premium" and "Human-Centric Design."
2.  **Space Grotesk:** Used for all structural headings and labels. Its geometric quirks reinforce the "AI/Tech" focus.
3.  **Inter:** Used for all long-form body text and data-heavy inputs to ensure maximum legibility against the dark background.

Keep line lengths for body text between 60-75 characters to maintain a cinematic, editorial feel.

## Layout & Spacing

The layout philosophy follows a **Fixed-Fluid Hybrid**:
- **Desktop:** A 12-column grid with wide 32px gutters. Sections are separated by massive 160px gaps to allow the "Pure Black" background to create a sense of infinite space.
- **Alignment:** Content is primarily center-aligned for the Hero and left-aligned for project case studies.
- **Safe Areas:** Cards and glass containers should utilize a consistent 40px internal padding to maintain the "breathable" premium feel.

## Elevation & Depth

Depth is achieved through **Luminance and Translucency** rather than traditional drop shadows:

- **Level 1 (Base):** `#000000` — the infinite void.
- **Level 2 (Cards):** `#141414` with a 1px border of `#2E2E32`. 
- **Level 3 (Interactive):** Glassmorphism applied with a `backdrop-filter: blur(12px)` and a subtle `rgba(255, 255, 255, 0.05)` white tint.
- **Glows:** High-importance elements use a "Shadow-Glow" — a drop shadow with the primary color (`#6C5CE7`) at very low opacity (15-20%) and high blur (40px+).

## Shapes

The shape language is **Ultra-Rounded (24px)**. 
- Primary containers, buttons, and input fields all share the 24px radius to soften the technical "brutalist" potential of the black/white contrast.
- Media assets (images/videos) must also follow the 24px rounding to integrate seamlessly into the glass containers.
- Small labels or tags may use a full "Pill" shape (100px radius).

## Components

### Buttons
- **Primary:** Gradient background (`Electric Violet` to `AI Teal`), white text, 24px radius. 
- **Hover State:** A "Shine Sweep" effect—a diagonal white glint that moves across the button—accompanied by a 4px vertical lift.
- **Glass Button:** Transparent background, `backdrop-filter: blur(10px)`, 1px border of `#2E2E32`. On hover, the border color shifts to the primary gradient.

### Cards
- **Construction:** Background `#141414`, 24px radius, 1px border.
- **Interaction:** On hover, the border glows with a primary-to-secondary gradient stroke, and the card scales by 1.02x.

### Chips & Tags
- **Style:** Small, pill-shaped, using `label-caps` typography. 
- **AI-specific:** Tags related to AI/LLMs should use a subtle teal outer glow.

### Input Fields
- **Base:** Dark surface `#0A0A0A`, 24px radius, subtle `#2E2E32` border.
- **Focus:** Border transitions to `Electric Violet` with a soft 8px outer glow.

### Navigation Bar
- **Style:** Floating glass dock at the bottom or top of the screen. 
- **Blur:** Heavy `backdrop-filter: blur(20px)` to allow background content to melt behind the navigation.