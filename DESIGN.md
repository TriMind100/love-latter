---
name: L'Amour Manuscrit
colors:
  surface: '#fff8f4'
  surface-dim: '#e4d8cc'
  surface-bright: '#fff8f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fef2e5'
  surface-container: '#f8ece0'
  surface-container-high: '#f3e6da'
  surface-container-highest: '#ede0d5'
  on-surface: '#201b13'
  on-surface-variant: '#584141'
  inverse-surface: '#362f27'
  inverse-on-surface: '#fbefe3'
  outline: '#8c7070'
  outline-variant: '#e0bfbe'
  surface-tint: '#ae2e39'
  primary: '#51000d'
  on-primary: '#ffffff'
  primary-container: '#7a0019'
  on-primary-container: '#ff7b7f'
  inverse-primary: '#ffb3b2'
  secondary: '#625e55'
  on-secondary: '#ffffff'
  secondary-container: '#e8e2d6'
  on-secondary-container: '#68645b'
  tertiary: '#735c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#cca72f'
  on-tertiary-container: '#4e3d00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad9'
  primary-fixed-dim: '#ffb3b2'
  on-primary-fixed: '#410009'
  on-primary-fixed-variant: '#8d1324'
  secondary-fixed: '#e8e2d6'
  secondary-fixed-dim: '#ccc6bb'
  on-secondary-fixed: '#1e1b14'
  on-secondary-fixed-variant: '#4a463e'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#fff8f4'
  on-background: '#201b13'
  surface-variant: '#ede0d5'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  letter-body:
    fontFamily: Literata
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 32px
  ui-main:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
  ui-label:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
---

## Brand & Style

This design system is built on the philosophy of "Digital Permanence"—treating every digital interaction with the weight and tactile intentionality of physical stationery. The target audience seeks a premium, intimate alternative to ephemeral instant messaging, valuing the ritual of slow communication.

The aesthetic direction merges **High-End Editorial Minimalism** with **Tactile Glassmorphism**. We utilize expansive white space (rendered in cream tones) to allow emotional content to breathe. UI overlays leverage frosted glass effects to simulate vellum paper transparency, creating a sense of layered depth without breaking the clean, sophisticated atmosphere. The emotional response is one of nostalgia, reverence, and romantic warmth.

## Colors

The palette is anchored in high-contrast elegance. **Deep Burgundy (#7A0019)** serves as the primary brand mark and the color for "ink" on critical calls to action. **Cream Paper (#F8F1E5)** replaces pure white to reduce eye strain and provide a vintage, organic feel. 

**Soft Gold (#D4AF37)** is used sparingly for decorative elements, icon flourishes, and premium states. **Warm Beige** acts as a structural neutral for borders and subtle backgrounds. For text outside of the "letter" experience, a refined **Warm Grey/Charcoal (#5C544B)** is used to ensure legibility without the harshness of pure black.

## Typography

The typographic hierarchy distinguishes between the **System UI** and the **Emotional Content**. 

1.  **Display & Headings:** Use *Playfair Display*. It provides the editorial authority and luxury feel required for titles and section headers.
2.  **The Letter Experience:** While a true script is often used for signatures, *Literata* (Italic) is selected for the main letter body to ensure long-form readability while maintaining a "bookish," intimate quality. 
3.  **Interface Elements:** *Plus Jakarta Sans* handles the functional aspects of the app. It is soft and modern, ensuring the "digital" part of the experience feels effortless and contemporary.

## Elevation & Depth

This system avoids traditional material shadows. Instead, depth is communicated through:

1.  **Vellum Overlays (Glassmorphism):** Modals and drawers use a background blur (20px) with a 70% opaque Cream Paper tint. This simulates the look of translucent envelopes or overlays.
2.  **Letterpress Indents:** Input fields and secondary buttons use subtle internal shadows to appear "pressed" into the paper surface.
3.  **Tonal Stacking:** Higher-level elements use slightly lighter shades of Cream or Soft Gold outlines rather than heavy drop shadows. If a shadow is necessary for a floating action button, it must be a very large, soft, and low-opacity (10%) Burgundy-tinted shadow.

## Shapes

The shape language is **Refined and Soft**. We use "Soft" roundedness (4px to 12px) to mimic the natural corners of high-quality cardstock. 

- **Cards:** Use `rounded-lg` (8px) to feel substantial.
- **Buttons:** Use a hybrid approach; primary buttons have a very slight `rounded-sm` (4px) to look like traditional wax seals or stamps, while decorative tags can be pill-shaped.
- **Envelopes:** Any container representing a letter should have a sharp top but slightly rounded bottom corners to imply a physical object.

## Components

**Buttons:**
- **Primary:** Deep Burgundy background with Soft Gold text. High-contrast, sharp, and authoritative.
- **Secondary:** Transparent with a 1px Soft Gold border ("Ghost Button").
- **Tertiary:** Text-only in Burgundy with a subtle underline that appears on hover.

**Cards & Envelopes:**
Cards are the primary container. They feature a subtle 1px border in Warm Beige. For "Love Letters," the card should include a decorative 4px Burgundy border on the left edge only, simulating the spine of a ledger or the edge of a formal invitation.

**Input Fields:**
Minimalist. A single bottom border in Warm Beige that turns Burgundy on focus. Labels use the `ui-label` style (Uppercase Plus Jakarta Sans) positioned above the field.

**Chips & Tags:**
Small, pill-shaped elements using a Soft Gold tint (10% opacity) with Gold text. Used for status (e.g., "Sent," "Draft," "Unopened").

**Specialty Component: The Wax Seal:**
A floating action button (FAB) or confirmation icon that uses a circular Burgundy shape with a Soft Gold icon in the center, featuring a subtle "melted" irregular outer stroke to mimic real wax.