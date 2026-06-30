---
name: Lumina Editorial
colors:
  surface: '#FFFFFF'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#4a4455'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#7b7486'
  outline-variant: '#ccc3d7'
  surface-tint: '#7331df'
  primary: '#5300b7'
  on-primary: '#ffffff'
  primary-container: '#6d28d9'
  on-primary-container: '#dac5ff'
  inverse-primary: '#d3bbff'
  secondary: '#5e5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e2e2e2'
  on-secondary-container: '#646464'
  tertiary: '#6b3000'
  on-tertiary: '#ffffff'
  tertiary-container: '#8f4200'
  on-tertiary-container: '#ffc19e'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ebddff'
  primary-fixed-dim: '#d3bbff'
  on-primary-fixed: '#250059'
  on-primary-fixed-variant: '#5b00c5'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c6'
  on-secondary-fixed: '#1b1b1b'
  on-secondary-fixed-variant: '#474747'
  tertiary-fixed: '#ffdbc8'
  tertiary-fixed-dim: '#ffb68b'
  on-tertiary-fixed: '#321300'
  on-tertiary-fixed-variant: '#743400'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
  border-subtle: '#E5E7EB'
  text-muted: '#6B7280'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 72px
    fontWeight: '700'
    lineHeight: 80px
    letterSpacing: -0.04em
  display-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.02em
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
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  section-gap-desktop: 120px
  section-gap-mobile: 64px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 20px
---

## Brand & Style

This design system is built for high-end tech storytelling and startup showcases. It leverages a **Modern Minimalist** aesthetic influenced by the "Software-as-a-Service" editorial style—characterized by expansive white space, precise grid alignment, and a focus on high-quality typography. 

The brand personality is professional, tech-forward, and sophisticated. It avoids visual clutter, favoring thin "hairline" borders and subtle depth over heavy gradients or complex patterns. The goal is to evoke a sense of clarity and "premium airiness," where the content (the startups and their innovations) is the hero. The interface should feel like a digital gallery: quiet, organized, and intentional.

## Colors

The palette is intentionally restrained to maintain an editorial feel. The primary background is a crisp White (`#FFFFFF`), with a very light Off-White (`#FAFAFA`) used for section alternating or secondary containers to create subtle contrast without breaking the "light" vibe.

The deep purple (`#6D28D9`) is the sole chromatic accent, reserved for high-priority calls to action, active states, and small icon accents. Black (`#000000`) is used for primary headers to ensure maximum impact and readability. Grays are used strictly for borders and secondary text to maintain a soft visual hierarchy.

## Typography

The typography system relies on a clean, geometric sans-serif for headlines to convey modernity. **Hanken Grotesk** provides a sharp, professional look for large-scale impact. For body text, **Inter** is utilized for its exceptional legibility and neutral tone, ensuring that long-form descriptions remain easy to read.

A monospaced font (**JetBrains Mono**) is introduced for small labels, dates, or technical metadata (like "STARTUP SHOWCASE 2026") to lean into the tech-forward, systematic nature of the event. Headlines should use tight letter spacing for a more "designed" editorial appearance, while body text remains at default tracking for clarity.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy for desktop to maintain editorial control over line lengths and whitespace. Content is centered within a 1200px container. On mobile, the layout shifts to a fluid model with 20px margins.

Section spacing is the defining characteristic of this system; use a generous 120px vertical gap between major content blocks to create the "airy" feel. Smaller components within sections should follow an 8px base grid, using multiples of 8 for padding and internal margins. Use a 12-column grid for desktop layouts to allow for flexible asymmetrical compositions—common in high-end startup showcases.

## Elevation & Depth

Depth is achieved through **Tonal Layers** and **Ambient Shadows** rather than heavy occlusion. Surfaces should predominantly feel flat or slightly lifted. 

- **Level 0:** The main white background.
- **Level 1:** Cards and secondary containers use a 1px border (`#E5E7EB`) and a very soft, diffused shadow (e.g., `0 4px 20px rgba(0,0,0,0.03)`).
- **Level 2:** Active modals or dropdowns use a slightly more pronounced shadow to indicate focus, but with low opacity to prevent a "dirty" look.

Interactive elements should not use shadows to indicate "pressed" states; instead, use subtle color shifts or scale transforms to maintain the clean aesthetic.

## Shapes

The design system uses a consistent **Rounded** language. Standard UI elements like buttons, input fields, and small cards utilize a 0.5rem (8px) radius. Larger layout containers, such as startup feature cards or image hero sections, should use the `rounded-xl` (1.5rem / 24px) setting to create a softer, more modern framing effect. 

Icons should follow this logic, using rounded caps and joins rather than sharp corners. Borders must remain thin (1px) to keep the interface looking precise and lightweight.

## Components

### Buttons
- **Primary:** Deep purple background, white text, 8px rounded corners. Use a subtle hover state that slightly darkens the purple.
- **Secondary:** Transparent background with a 1px light gray border. Text in black.
- **Ghost:** No background or border; used for low-priority navigation items.

### Cards
Feature cards for startups should use a white background, a 1px border (`#E5E7EB`), and 24px padding. Titles should be bold and concise. Use "pill" tags for categories (e.g., AI, Fintech) with light gray backgrounds and small monospaced labels.

### Input Fields
Inputs should be minimalist: a 1px light gray border that turns purple on focus. Labels should be small and placed above the field in the `label-caps` typography style.

### Navigation
The header should be sticky with a `backdrop-filter: blur(10px)` effect on a semi-transparent white background, creating a subtle glassmorphic transition as the user scrolls through the high-contrast content sections.

### Badges & Chips
Use for status or categories. These should be small, high-contrast text on very light pastel or neutral backgrounds, utilizing the same 8px corner radius as buttons.