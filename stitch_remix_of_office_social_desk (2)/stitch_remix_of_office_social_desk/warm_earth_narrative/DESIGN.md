---
name: Warm Earth Narrative
colors:
  surface: '#fff8f6'
  surface-dim: '#ecd5cf'
  surface-bright: '#fff8f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff1ed'
  surface-container: '#ffe9e4'
  surface-container-high: '#fbe3dd'
  surface-container-highest: '#f5ded7'
  on-surface: '#251915'
  on-surface-variant: '#58423b'
  inverse-surface: '#3b2d29'
  inverse-on-surface: '#ffede8'
  outline: '#8c716a'
  outline-variant: '#e0c0b7'
  surface-tint: '#a93812'
  primary: '#a73610'
  on-primary: '#ffffff'
  primary-container: '#c84e27'
  on-primary-container: '#fffdff'
  inverse-primary: '#ffb59f'
  secondary: '#605e5b'
  on-secondary: '#ffffff'
  secondary-container: '#e6e2dd'
  on-secondary-container: '#666460'
  tertiary: '#70584f'
  on-tertiary: '#ffffff'
  tertiary-container: '#8a7066'
  on-tertiary-container: '#fffeff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbd1'
  primary-fixed-dim: '#ffb59f'
  on-primary-fixed: '#3a0a00'
  on-primary-fixed-variant: '#862300'
  secondary-fixed: '#e6e2dd'
  secondary-fixed-dim: '#c9c6c1'
  on-secondary-fixed: '#1c1c19'
  on-secondary-fixed-variant: '#484743'
  tertiary-fixed: '#fddbd0'
  tertiary-fixed-dim: '#e0c0b4'
  on-tertiary-fixed: '#291710'
  on-tertiary-fixed-variant: '#584239'
  background: '#fff8f6'
  on-background: '#251915'
  surface-variant: '#f5ded7'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  title-md:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  container-margin: 20px
  gutter: 12px
---

## Brand & Style

This design system is built on the philosophy of "Professional Warmth." It aims to transform the sterile nature of workplace productivity into a cozy, communal experience. The brand personality is grounded, empathetic, and inviting, seeking to reduce workplace anxiety through soft aesthetics and tactile metaphors.

The visual style is a sophisticated blend of **Minimalism** and **Tactile Modernism**. It utilizes organic shapes, soft background blurs, and a color palette inspired by nature to create a sense of belonging. The UI should feel like a physical desk—composed of layers that have weight and soft edges—rather than a flat digital screen.

Key emotional drivers:
- **Connectedness:** Emphasizing social engagement through high-readability feed cards.
- **Serenity:** Using "My Desk" illustrative elements to provide a calm, personal sanctuary within the app.
- **Focus:** Leveraging generous whitespace and clear typography to manage cognitive load.

## Colors

The palette is rooted in an earthy, autumnal spectrum. 

- **Primary (Rust):** Used for primary actions, branding, and active states. It provides energy without the clinical feel of standard blue or red.
- **Secondary/Surface (Cream):** This is the foundation of the UI. It replaces pure white to reduce eye strain and provide a "paper-like" warmth.
- **Tertiary (Deep Brown):** Used for primary text and high-contrast surfaces. It offers better legibility and a softer feel than pure black.
- **Gradients:** Use soft radial and linear gradients for "My Desk" backgrounds, transitioning from Deep Brown to a warm Clay or muted Rust to simulate natural lighting and depth.

## Typography

The typography system balances the friendly curves of **Plus Jakarta Sans** with the technical precision of **Manrope**.

- **Headlines:** Use Plus Jakarta Sans for titles and "My Desk" headers. It should feel approachable and slightly playful.
- **Body & Metadata:** Manrope is used for all functional text, feed card descriptions, and data points. Its high legibility ensures engagement remains effortless.
- **Stylistic Note:** In special editorial moments (like the "Mumbai 2026" event title), use a mix of weights and italics to create visual hierarchy and a "magazine" feel.

## Layout & Spacing

The layout uses a **fluid grid** model optimized for high-density social interactions and immersive illustrative views.

- **Mobile:** 4-column grid with 20px side margins. Feed cards should span the full width minus margins.
- **Tablet/Desktop:** 12-column grid. Content is centered with a maximum width of 1200px.
- **Spacing Rhythm:** Use a 4px base unit. Component internal padding should favor `md` (16px) for a breathable feel.
- **Safe Areas:** Ensure the "Floating Action Button" (the central '+' button) has a clear 80px exclusion zone at the bottom of the screen to prevent overlap with navigation labels.

## Elevation & Depth

This design system uses **Tonal Layers** and **Ambient Shadows** to create a sense of physical space.

- **The Base:** The lowest layer is the Cream surface or the illustrative "My Desk" background.
- **Level 1 (Cards):** Feed cards and "My Desk" widgets use a subtle `0 4px 20px rgba(45, 27, 20, 0.08)` shadow.
- **Level 2 (Active/Floating):** Primary action buttons and navigation bars use a more pronounced, tinted shadow: `0 8px 24px rgba(200, 78, 39, 0.15)`.
- **Glassmorphism:** Use backdrop blurs (20px) on navigation bars and overlays to maintain the warmth of the background colors while ensuring text remains legible.

## Shapes

The shape language is dominated by **Rounded** corners to evoke friendliness.

- **Main Cards:** Use `rounded-xl` (24px) for high-engagement feed cards and illustrative containers.
- **Buttons/Chips:** Use `rounded-lg` (16px) or pill shapes for interactive elements to make them feel "squishy" and touch-friendly.
- **Icons:** Use icons with rounded terminals and a consistent 2px stroke weight to match the Manrope font weight.

## Components

### Social Feed Cards
Cards should be the hero of the social experience. 
- **Backgrounds:** Can be solid Deep Brown (for high-impact events) or White (for standard updates).
- **Metadata:** Top-left placement for event tags, top-right for more options.
- **Interactions:** Bottom row should feature distinct circular buttons for "Like," "Save," and "Share."

### Buttons
- **Primary:** Rust background, White text, pill-shaped.
- **Secondary:** Cream background, Rust border (1px), Rust text.
- **Floating Action Button (FAB):** The central circular Rust button with a white '+' icon, utilizing a soft glow effect.

### Chips & Tags
Used for categorization (e.g., "Event", "Nominate").
- **Style:** Semi-transparent white or tinted rust backgrounds with small, bold uppercase text.

### My Desk Widgets
Small, square-ish tiles that display quick stats (e.g., "Growth", "Meetings").
- **Style:** High roundedness (24px), White background, and colorful icons to provide a "sticker" aesthetic.

### Progress Charts
Within cards, use organic, curved lines rather than sharp angles. Data points should be represented by small, filled circles.