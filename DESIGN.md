---
name: Kinetic Intellect
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
  on-surface-variant: '#d1c5b4'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#9a8f80'
  outline-variant: '#4e4639'
  surface-tint: '#eac077'
  primary: '#f6cb81'
  on-primary: '#412d00'
  primary-container: '#d8b068'
  on-primary-container: '#5e4202'
  inverse-primary: '#78591a'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#bcd2ff'
  on-tertiary: '#153059'
  tertiary-container: '#9eb6e7'
  on-tertiary-container: '#2e4771'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdea7'
  primary-fixed-dim: '#eac077'
  on-primary-fixed: '#271900'
  on-primary-fixed-variant: '#5e4201'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#d7e2ff'
  tertiary-fixed-dim: '#afc7f9'
  on-tertiary-fixed: '#001b3f'
  on-tertiary-fixed-variant: '#2e4771'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
  surface-elevated: '#121212'
  surface-border: '#262626'
  text-muted: '#A3A3A3'
typography:
  display-lg:
    fontFamily: Outfit
    fontSize: 72px
    fontWeight: '800'
    lineHeight: 80px
    letterSpacing: -0.04em
  display-lg-mobile:
    fontFamily: Outfit
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Outfit
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Outfit
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
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
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  mono-code:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style

This design system is built for a high-impact professional persona, blending the rigorous academic excellence of an IIT background with the forward-leaning energy of Machine Learning. The aesthetic is **High-Contrast Minimalist**, utilizing a deep dark-mode foundation to allow content to "pop" with cinematic intensity.

The visual narrative focuses on authority, precision, and clarity. It avoids unnecessary decoration, instead using massive, bold typography and a restricted color palette to convey confidence. The experience should feel like a premium terminal—technical yet polished—evoking a sense of high-performance intelligence and modern craftsmanship.

## Colors

The palette is anchored by a "True Dark" background (`#050505`) to maximize contrast and focus. The primary brand color is a sophisticated **Muted Gold** (`#D8B068`), used sparingly for high-value accents, calls to action, and highlighting key technical achievements. 

Pure white is reserved for primary headings and critical interface elements to maintain a sharp, professional edge. A series of deep greys are used for borders and elevated surfaces to create subtle depth without breaking the dark-mode immersion. This high-contrast approach ensures that data visualizations and code snippets—central to an ML profile—remain the focal point.

## Typography

The typography system relies on the interplay between the geometric precision of **Outfit** for headings and the systematic clarity of **Inter** for body text. 

Headlines should be set with tight letter-spacing and heavy weights to create a "block-like" visual impact. Large display sizes are encouraged for landing sections and project titles. Body text maintains a generous line height to ensure readability of technical descriptions. A specialized label style using uppercase Inter with increased tracking is used for categories (e.g., "RESEARCH", "PROJECTS", "SKILLS") to establish a clear information hierarchy.

## Layout & Spacing

This design system employs a **Fixed Grid** model for desktop to ensure a controlled, editorial reading experience. Content is centered within a 1200px max-width container using a 12-column structure. 

The rhythm is defined by significant vertical "white space" (negative space) between sections to allow the bold typography to breathe. On mobile, the layout transitions to a single-column fluid flow with 20px side margins. Elements should be aligned to a strict 8px baseline grid to reflect the mathematical precision inherent in Machine Learning and Engineering disciplines.

## Elevation & Depth

Depth is conveyed through **Tonal Layering** rather than traditional shadows. Surfaces sit on the `#050505` base and lift using the `#121212` elevated surface color. 

Instead of soft ambient shadows, use **Low-Contrast Outlines** (`#262626`) to define the boundaries of cards and containers. This creates a "blueprint" or "schematic" feel that aligns with a technical profile. Interaction states (like hovering over a project card) should be signaled by a subtle increase in border brightness or the appearance of a primary gold accent border, rather than a shadow cast.

## Shapes

The shape language is **Soft (0.25rem)**. While the overall vibe is sharp and professional, a minimal radius prevents the UI from feeling aggressive or dated. This slight rounding suggests a modern, "hardware-inspired" aesthetic (similar to premium tech product design). For specific interactive components like tags or chips, a pill-shaped radius may be used to provide visual variety against the predominantly rectangular grid.

## Components

### Buttons
Primary buttons use the gold accent (`#D8B068`) with black text for maximum visibility. Secondary buttons are "ghost" style with a white border and white text. Transitions should be instant or very fast (150ms) to feel responsive and high-performance.

### Cards
Project and experience cards use the elevated surface color (`#121212`) with a 1px border. They should lack shadows entirely. Titles within cards use the Headline-MD style.

### Input Fields
Inputs are dark-themed with `#262626` borders. Upon focus, the border transitions to white or gold. Use Inter for all placeholder and user input text.

### Technical Tags (Chips)
Small, rectangular tags with 2px rounded corners. Use them to list tech stacks (e.g., "PyTorch", "Transformer", "NLP"). These should have a subtle dark background and grey text to remain secondary to the main content.

### Code Blocks
Essential for an ML profile. Use a slightly lighter background than the page base, with syntax highlighting that utilizes the brand gold and secondary whites to maintain a unified aesthetic.