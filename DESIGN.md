---
name: Redline Poster System
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#5b403c'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#906f6b'
  outline-variant: '#e4beb8'
  surface-tint: '#ba1b16'
  primary: '#b61713'
  on-primary: '#ffffff'
  primary-container: '#da3429'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb4a9'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e4e2e1'
  on-secondary-container: '#656464'
  tertiary: '#5a5c5c'
  on-tertiary: '#ffffff'
  tertiary-container: '#737575'
  on-tertiary-container: '#fcfcfc'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad5'
  primary-fixed-dim: '#ffb4a9'
  on-primary-fixed: '#410001'
  on-primary-fixed-variant: '#930005'
  secondary-fixed: '#e4e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1b1c1c'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 84px
    fontWeight: '800'
    lineHeight: 90%
    letterSpacing: -0.04em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 100%
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 42px
    fontWeight: '700'
    lineHeight: 110%
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 120%
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 160%
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 150%
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 100%
    letterSpacing: 0.05em
  quote:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 130%
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 32px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style

This design system is built on a "Chunky Poster" aesthetic, blending the raw energy of an indie zine with the polished execution of a high-end creative agency. The personality is unapologetic, playful, and tactile. It moves away from the sterile "SaaS-blue" world into a space that feels physical and printed.

The core visual hook relies on **structural asymmetry** and **bold layering**. Large, outlined numeral watermarks provide a sense of progression (01, 02, 03) while tilted text blocks break the rigid digital grid to evoke a hand-composed feel. Charcoal doodle icons soften the high-contrast color palette, adding a human, "in-progress" touch to a professional portfolio environment.

## Colors

The palette is strictly restricted to four tones to maintain a high-impact, editorial presence:

- **Surface (#ECECEC):** A warm, light gray that serves as the "paper" stock.
- **Primary Red (#E23A2E):** An aggressive, saturated red used for interactive elements, background shapes behind photography, and high-priority UI accents.
- **Charcoal (#2B2B2B):** Used for all primary text and hand-drawn charcoal doodles.
- **Pure White (#FFFFFF):** Reserved for card surfaces and text labels sitting atop Red or Charcoal backgrounds.

**Strict Rule:** No yellow or secondary accent colors. Gradients are prohibited; use flat fills only.

## Typography

The typography leverages **Plus Jakarta Sans** for headlines to achieve a thick, friendly, and rounded "Fredoka-style" look while maintaining professional legibility. **Inter** provides a neutral, highly readable counterpoint for long-form body copy.

**Styling Rules:**
- **The Tilt:** Major headlines (`display-lg`) should be rotated by -2 to -3 degrees to enhance the "poster" feel.
- **Background Numerals:** Large background numbers (e.g., "01") use the Display-LG weight but are rendered as 2px charcoal outlines with 10% opacity.
- **Quotes:** Use massive, oversized charcoal quotation marks that bleed off the edge of the container.

## Layout & Spacing

This design system uses a **12-column fixed grid** for desktop, but encourages elements to break the grid. 

**Composition Rules:**
- **Asymmetric Margins:** Content should often be offset to one side, leaving significant whitespace for background numerals or doodle elements.
- **Photography Layering:** Images are never "just" rectangles. Every duotone photo must have a `Primary Red` rounded-square shape offset behind it (typically 24px bottom-right).
- **Zine-Style Overlaps:** Allow text blocks to slightly overlap the edge of image containers or background shapes to create depth.

## Elevation & Depth

This system rejects shadows in favor of **Tonal Layering** and **Shape Stacking**.

- **Level 0 (Base):** The #ECECEC surface.
- **Level 1 (Shapes):** Solid Primary Red blocks or speech bubbles.
- **Level 2 (Cards):** Pure White (#FFFFFF) surfaces.
- **Level 3 (Interactive):** Charcoal elements.

Depth is created through "The Offset." Instead of a shadow, an element might have a secondary charcoal border or a secondary red block positioned 8px behind it to give a "cut-out" physical appearance.

## Shapes

The shape language is "Extra Rounded." 

- **Primary Radius:** 0.5rem (8px) for standard UI cards.
- **Large Radius:** 1.5rem (24px) for hero image containers and speech bubbles.
- **Pill Shape:** Fully rounded ends (999px) for badges, tags, and small buttons.
- **Speech Bubbles:** Rectangular blocks with a 24px radius and a small triangular "tail" at the bottom-left or bottom-right, strictly in Primary Red.

## Components

### Buttons & Interaction
- **Circular Arrow Buttons:** 64px diameter circles filled with Primary Red. Inside, a white charcoal-style hand-drawn arrow.
- **Badge/Pills:** Small Primary Red pills with white `label-caps` text. No borders.

### Cards
- **Project Cards:** 16:9 aspect ratio containers. Images must be duotone (Black & White). A red pill tag sits in the top-left corner.
- **Doodle Cards:** Pure white cards containing a centered, thick-stroke charcoal doodle icon. These are used for "Services" or "Features."

### Imagery
- **Duotone Effect:** All photography should be processed to high-contrast B&W.
- **Backing Shapes:** Every main image is "framed" by a larger Red square with 24px rounded corners positioned behind the image, offset by 16-32px.

### Input Fields
- **Fields:** 2px charcoal borders on white backgrounds with 8px rounded corners. Focus state changes the border to Primary Red with a 4px "block shadow" offset in charcoal.