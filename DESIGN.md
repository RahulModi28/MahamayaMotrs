---
name: Commercial Heavy-Duty System
colors:
  surface: '#f9f9ff'
  surface-dim: '#d8dae2'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3fb'
  surface-container: '#ecedf6'
  surface-container-high: '#e7e8f0'
  surface-container-highest: '#e1e2ea'
  on-surface: '#191c21'
  on-surface-variant: '#424752'
  inverse-surface: '#2e3037'
  inverse-on-surface: '#eff0f9'
  outline: '#727783'
  outline-variant: '#c2c6d4'
  surface-tint: '#005db7'
  primary: '#004d99'
  on-primary: '#ffffff'
  primary-container: '#1565c0'
  on-primary-container: '#dae5ff'
  inverse-primary: '#a9c7ff'
  secondary: '#525f71'
  on-secondary: '#ffffff'
  secondary-container: '#d3e1f6'
  on-secondary-container: '#566475'
  tertiary: '#813900'
  on-tertiary: '#ffffff'
  tertiary-container: '#a64c00'
  on-tertiary-container: '#ffdece'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#a9c7ff'
  on-primary-fixed: '#001b3d'
  on-primary-fixed-variant: '#00468c'
  secondary-fixed: '#d6e4f9'
  secondary-fixed-dim: '#bac8dc'
  on-secondary-fixed: '#0f1c2c'
  on-secondary-fixed-variant: '#3a4859'
  tertiary-fixed: '#ffdbc9'
  tertiary-fixed-dim: '#ffb68c'
  on-tertiary-fixed: '#321200'
  on-tertiary-fixed-variant: '#753400'
  background: '#f9f9ff'
  on-background: '#191c21'
  surface-variant: '#e1e2ea'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-bold:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
  button-text:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '700'
    lineHeight: 24px
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
  gutter: 16px
  margin-mobile: 16px
  margin-desktop: 64px
  container-max: 1280px
---

## Brand & Style

The design system is engineered for **M/S Mahamaya Motors**, a Tata Motors Authorised Service Station. It prioritizes authority, reliability, and precision, catering to fleet owners and commercial vehicle drivers who require rapid, trustworthy information in high-stakes environments.

The visual style is **Rugged-Modern**. It blends the mechanical robustness of heavy-duty trucks with a "computerized" diagnostic aesthetic. The interface utilizes high-contrast ratios to ensure legibility in high-glare outdoor conditions typical of highway environments. It avoids decorative fluff in favor of structural clarity, using technical accents like micro-grids and monospaced data readouts to evoke a sense of professional vehicle diagnostics.

## Colors

The palette is anchored in high-visibility professional tones:

- **Royal Blue (#1565C0):** The primary brand color, representing Tata Motors' heritage and engineering trust.
- **Dark Navy (#0D1B2A):** Used for deep text, headers, and structural elements to provide a "heavy-duty" foundation.
- **Accent Orange (#FF6F00):** Reserved exclusively for high-priority Call-to-Actions (CTAs) and "Book Now" triggers.
- **Emergency Red (#C62828):** Utilized for 24/7 Breakdown Assistance and critical safety warnings.
- **White (#FFFFFF):** The base background for maximum readability against dark text.

## Typography

This design system utilizes a tiered typographic approach to balance rugged impact with technical clarity:

- **Headlines (Inter):** Bold and condensed-feeling to project strength. Headlines should always use high-weight (700+) to command attention.
- **Body (Work Sans):** Chosen for its excellent legibility at distance and its neutral, grounded character.
- **Technical Labels (JetBrains Mono):** Used for diagnostic codes, vehicle specs, or badge text to reinforce the "computerized" service station aesthetic.

On mobile devices, scale `display-lg` down to `32px` to prevent text wrapping on smaller handheld units used by technicians on the floor.

## Layout & Spacing

The layout follows a **Rigid 12-Column Grid** for desktop and a **Single Column Stack** for mobile. 

- **The 8px Rhythm:** All padding and margins must be multiples of 8px to maintain a precise, engineered feel.
- **Gutter Strategy:** 16px gutters are used to keep cards and information dense but distinct, mirroring the compact efficiency of a workshop dashboard.
- **High-Contrast Margins:** Use generous outer margins on desktop (64px) to center focus on the diagnostic cards and service lists, preventing visual "leak" on wide monitors.

## Elevation & Depth

To maintain the "rugged but computerized" style, this design system avoids soft, ambient shadows. Instead, it uses:

- **Hard Strokes:** Surface elements (cards, containers) use a 1px solid border in Dark Navy or Light Gray (#E0E4E8).
- **Tonal Stepping:** Rather than shadows, depth is created by shifting background colors. The main canvas is White, while "Sunken" or secondary areas use the Surface Color (#F8F9FA).
- **Active Elevation:** When a card is hovered or tapped, it does not lift; instead, its border thickness increases to 2px and the Accent Orange is applied to the border, mimicking a digital selector in a diagnostic tool.

## Shapes

The design system uses **Soft (0.25rem)** roundedness. This "near-sharp" geometry reflects the industrial nature of commercial vehicles—functional, sturdy, and machined. 

- **Buttons & Cards:** Use the standard 4px (0.25rem) radius.
- **Badges:** Use 2px radius for a more utilitarian, "stamped metal" look.
- **Icons:** Should be stroke-based (2px thickness) with squared ends rather than rounded caps to match the technical theme.

## Components

### Buttons
- **Primary CTA:** Solid Accent Orange (#FF6F00) with White text. Bold, uppercase typography.
- **Secondary:** Transparent with a 2px Royal Blue border. 
- **Emergency Button:** High-visibility Red (#C62828) with a pulsing outer ring for 24/7 Breakdown calls.

### Cards
- Service cards feature a 32px icon in the top left, a Bold Inter headline, and a short Work Sans description.
- Use a "Technical Header" on cards: a thin 4px top-border in Royal Blue to signify "Authorised Status."

### Badges & Features
- Badges use JetBrains Mono for text. 
- "Genuine Tata Parts" or "Express Service" badges should be high-contrast: Dark Navy background with White or Orange text.

### Input Fields
- Input fields should have a distinct "active" state using the Royal Blue color for the border and label to ensure the user knows exactly where they are entering data in bright outdoor light.