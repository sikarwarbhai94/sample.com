---
name: Premium Scholastic System
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f4'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#454652'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#767683'
  outline-variant: '#c6c5d4'
  surface-tint: '#4c56af'
  primary: '#000666'
  on-primary: '#ffffff'
  primary-container: '#1a237e'
  on-primary-container: '#8690ee'
  inverse-primary: '#bdc2ff'
  secondary: '#7345b6'
  on-secondary: '#ffffff'
  secondary-container: '#b889ff'
  on-secondary-container: '#4a148c'
  tertiary: '#735c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#cba72f'
  on-tertiary-container: '#4e3d00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e0e0ff'
  primary-fixed-dim: '#bdc2ff'
  on-primary-fixed: '#000767'
  on-primary-fixed-variant: '#343d96'
  secondary-fixed: '#eddcff'
  secondary-fixed-dim: '#d7baff'
  on-secondary-fixed: '#280056'
  on-secondary-fixed-variant: '#5a2a9c'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Poppins
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  display-md:
    fontFamily: Poppins
    fontSize: 36px
    fontWeight: '600'
    lineHeight: '1.25'
  headline-lg:
    fontFamily: Poppins
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Poppins
    fontSize: 24px
    fontWeight: '600'
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
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1280px
  gutter: 24px
---

## Brand & Style

The brand personality of the design system is authoritative yet visionary, catering to a premium educational demographic that values both tradition and innovation. The UI evokes a sense of "digital ivory towers"—a modern, sophisticated space for learning that feels exclusive and high-end.

The design style merges **Modern Minimalism** with **Glassmorphism**. It utilizes deep, intellectual tones layered with translucent glass surfaces to create a sense of multi-dimensional depth. This approach ensures the interface feels breathable and light despite the presence of heavy, rich colors. The overall aesthetic is professional, clean, and meticulously organized, reflecting the precision of high-level education.

## Colors

The palette is rooted in academic excellence. **Deep Navy (#1A237E)** serves as the primary anchor, providing a foundation of trust and stability. **Royal Purple (#4A148C)** is used for secondary accents, adding a touch of luxury and creative depth. 

**Gold (#D4AF37)** is reserved for high-impact calls to action and prestige markers, ensuring that critical interactive elements are immediately visible. **Crisp White** acts as the canvas, providing the necessary contrast for the glassmorphic effects to succeed. Backgrounds should favor a very light grey or cool-tinted white to make the pure white glass containers pop.

## Typography

This design system uses a dual-font strategy to balance character with legibility. **Poppins** is utilized for all headlines and display text, offering a geometric, modern, and confident appearance. **Inter** is the workhorse for body copy and labels, ensuring maximum readability for dense educational content and data-heavy interfaces.

Letter spacing is slightly tightened for large display titles to maintain a premium "editorial" feel, while labels utilize increased tracking and uppercase styling to provide clear visual hierarchy and structural signposting.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy for desktop, centered within a 1280px container to ensure content remains readable and focused. We employ a 12-column grid with 24px gutters.

Spacing is generous to promote a "premium" feel; whitespace is treated as a functional element that reduces cognitive load during learning. Sections are typically separated by `xl` (80px) vertical margins. Navigation is fixed to the top of the viewport (Sticky), utilizing a glassmorphic background blur to maintain context while the user scrolls through educational modules.

## Elevation & Depth

Depth is achieved through **Glassmorphism** and subtle, multi-layered shadows. Surfaces do not rely on heavy drop shadows; instead, they use backdrop blurs (typically 12px to 20px) and semi-transparent white fills (70-80% opacity).

To define the edges of these "glass" panels, a 1px solid border is applied with a low-opacity white or a very faint tint of the secondary purple. This creates a "frosted edge" effect. Elevation is communicated by increasing the backdrop blur intensity and adding a very soft, large-radius ambient shadow when an element is hovered or active.

## Shapes

The design system utilizes **Rounded** corners to soften the professional aesthetic and make the platform feel approachable. Standard containers and cards use a 0.5rem (8px) radius. Larger display cards or hero sections may scale up to 1rem (16px) to emphasize the "glass panel" metaphor. Interactive elements like buttons and input fields maintain consistent 8px rounding to ensure a unified visual language across the interface.

## Components

### Buttons
- **Primary:** High-contrast Navy background with Gold accents (either a bottom border or an icon). Text is white.
- **Secondary:** Transparent with a Royal Purple 2px border.
- **CTA:** Solid Gold background with Deep Navy text, used sparingly for "Enroll" or "Subscribe" actions.

### Glassmorphic Cards
Cards feature a `rgba(255, 255, 255, 0.7)` background with a `20px` backdrop-filter blur. They include a 1px white border at 30% opacity. For featured content, a thin Gold top-border (2px) is added to signal premium status.

### Input Fields
Inputs are clean and minimalist. They utilize a soft white fill with a 1px light grey border that shifts to Royal Purple on focus. Labels are always placed above the field using the `label-lg` typographic style.

### Sticky Navigation
The top navigation bar is persistent. It uses a high-blur glass effect to allow the colors of the content beneath to bleed through slightly without sacrificing text legibility. 

### Progress Indicators
Educational tracking is visualized through thin, elegant progress bars using the Gold primary accent against a muted Navy track, emphasizing achievement and value.