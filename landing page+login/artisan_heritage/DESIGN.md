---
name: Artisan Heritage
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1b1c1c'
  surface-container: '#1f2020'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e4e2e1'
  on-surface-variant: '#d4c4b7'
  inverse-surface: '#e4e2e1'
  inverse-on-surface: '#303030'
  outline: '#9c8e82'
  outline-variant: '#50453b'
  surface-tint: '#f0bd8b'
  primary: '#f2be8c'
  on-primary: '#482904'
  primary-container: '#d4a373'
  on-primary-container: '#5b3912'
  inverse-primary: '#7d562d'
  secondary: '#c8c6c5'
  on-secondary: '#313030'
  secondary-container: '#4a4949'
  on-secondary-container: '#bab8b7'
  tertiary: '#c8c7c6'
  on-tertiary: '#2f3130'
  tertiary-container: '#acacab'
  on-tertiary-container: '#3f403f'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdcbd'
  primary-fixed-dim: '#f0bd8b'
  on-primary-fixed: '#2c1600'
  on-primary-fixed-variant: '#623f18'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474646'
  tertiary-fixed: '#e3e2e0'
  tertiary-fixed-dim: '#c7c6c5'
  on-tertiary-fixed: '#1a1c1b'
  on-tertiary-fixed-variant: '#464746'
  background: '#131313'
  on-background: '#e4e2e1'
  surface-variant: '#353535'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 80px
    fontWeight: '700'
    lineHeight: 90px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 54px
    letterSpacing: -0.01em
  headline-xl:
    fontFamily: Libre Caslon Text
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
  headline-lg:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style

This design system is built on a foundation of **Editorial Minimalism** and **Craftsmanship**. It is designed to evoke a sense of timeless quality, targeting an audience that values provenance, attention to detail, and a premium aesthetic experience. 

The visual narrative is driven by high-contrast typography and a structured, museum-like use of space. It mimics the layout of a luxury publication, where the products are treated as artifacts. The emotional response is one of quiet confidence, authority, and cultural pride. By utilizing a "Dark Mode First" approach for key immersive sections, the design creates a focused environment that highlights imagery and storytelling.

## Colors

The palette is rooted in an "Obsidian and Sand" theme. 
- **Surface & Background:** The primary surface is `#131313`, providing a deep, ink-like canvas. For lighter editorial sections, a warm off-white (`#F9F8F6`) is used to maintain a soft, parchment-like feel rather than a harsh digital white.
- **Accents:** The primary accent is a muted gold/sand (`#D4A373`), used sparingly for key calls to action and micro-details to signify "artisanal" quality.
- **Neutrals:** Grayscale tones are suppressed; instead, we use warm-tinted darks (`#262626`) for containers and borders to maintain the organic, premium atmosphere.

## Typography

The typography system relies on the contrast between the authoritative, high-contrast serifs of **Libre Caslon Text** and the functional, modern clarity of **Hanken Grotesk**.

- **Headlines:** Use Libre Caslon Text for all editorial headers. Tighten letter-spacing for large display sizes to create a "locked-in" magazine look.
- **Body:** Use Hanken Grotesk for readability. Maintain generous line heights to ensure a relaxed reading pace.
- **Labels:** Small utility text and eyebrow headers should always be in uppercase Hanken Grotesk with expanded letter spacing to signify structural hierarchy.

## Layout & Spacing

The layout philosophy follows a **Rigid Editorial Grid**. It uses a 12-column system for desktop with significant negative space used as a functional element rather than just a filler.

- **Asymmetry:** Content should often be offset (e.g., text occupying columns 1-5 while columns 7-12 host an image) to create a sophisticated, non-template appearance.
- **Rhythm:** Vertical rhythm is strictly enforced in multiples of 8px. Large sections are separated by expansive padding (120px+) to allow the design to breathe.
- **Mobile:** Transition to a 4-column grid, reducing horizontal margins but maintaining large vertical gaps between distinct content blocks to preserve the premium feel.

## Elevation & Depth

This system avoids traditional drop shadows in favor of **Tonal Layering** and **Strict Outlines**.

- **Depth through Color:** Depth is achieved by stacking `#262626` surfaces on top of the `#131313` background. 
- **Borders:** Use thin (1px), low-opacity borders (`rgba(255,255,255,0.1)`) to define containers. This creates a "technical drawing" aesthetic that feels precise and architectural.
- **Imagery:** Depth is often provided by the photography itself. Images should feature shallow depth-of-field and organic textures to contrast with the sharp, flat UI.

## Shapes

The shape language is **Strictly Geometric and Sharp**. 

To reinforce the feeling of tradition and structural integrity, all buttons, input fields, and image containers use 0px border radius. Sharp corners imply precision and a "cut from stone" quality. Occasionally, a circular element (like a play button or a scroll indicator) may be used as a focal point, but structural elements must remain rectangular and sharp.

## Components

### Buttons
- **Primary:** Solid `#D4A373` background with dark text, sharp corners. High-contrast hover state (slight shift in saturation).
- **Secondary:** Transparent with a 1px border of the current text color. Text in uppercase with tracking.

### Cards
- **Product Cards:** Minimalist. Image occupies 100% of the top area. Text is placed below with a clear grid-aligned price and title. No shadows; use a subtle background fill on hover to define the hit area.

### Input Fields
- Underlined style or fully boxed with 1px borders. Labels always use the `label-caps` typography style and sit above the field.

### Lists & Navigation
- Use generous vertical padding. Dividers should be 1px and semi-transparent. Navigation items should use a subtle strike-through or underline on hover rather than a color change.

### Imagery
- All photos should follow a consistent art direction: muted saturation, warm white balance, and high-quality textures (leather, textile, wood).