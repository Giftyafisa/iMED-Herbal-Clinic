---
name: Clinical Diagnostic System
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#464653'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#767684'
  outline-variant: '#c6c5d5'
  surface-tint: '#4b53bc'
  primary: '#00003c'
  on-primary: '#ffffff'
  primary-container: '#000080'
  on-primary-container: '#777eea'
  inverse-primary: '#bfc2ff'
  secondary: '#b4007d'
  on-secondary: '#ffffff'
  secondary-container: '#fe48b8'
  on-secondary-container: '#5a003d'
  tertiary: '#000e04'
  on-tertiary: '#ffffff'
  tertiary-container: '#002810'
  on-tertiary-container: '#009e52'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e0e0ff'
  primary-fixed-dim: '#bfc2ff'
  on-primary-fixed: '#00006e'
  on-primary-fixed-variant: '#3239a3'
  secondary-fixed: '#ffd8e8'
  secondary-fixed-dim: '#ffafd5'
  on-secondary-fixed: '#3d0027'
  on-secondary-fixed-variant: '#8a005f'
  tertiary-fixed: '#6bfe9c'
  tertiary-fixed-dim: '#4ae183'
  on-tertiary-fixed: '#00210c'
  on-tertiary-fixed-variant: '#005228'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display-lg:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  title-md:
    fontFamily: Manrope
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
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
    fontWeight: '700'
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
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  container-max: 1280px
---

## Brand & Style

This design system embodies a **Modern Clinical** aesthetic, balancing the high-energy vibrancy of magenta with the steady, authoritative weight of deep navy blue. The brand personality is diagnostic, precise, and high-end, aimed at patients seeking expert medical intervention in a technologically advanced setting.

The visual style utilizes a "Diagnostic-First" hierarchy, where data and clinical results are framed with intentional whitespace and sharp, professional accents. It leans into a **Modern Corporate** approach with a high-contrast palette, ensuring that critical medical information is never lost. The interface uses organic "pathway" curves (inspired by the flyer's swooping shapes) to soften the clinical precision, making the sophisticated technology feel human-centric and approachable.

## Colors

The palette is anchored by **Deep Navy Blue**, providing a foundation of trust and stability. **Vibrant Magenta** acts as the primary action and diagnostic highlight color, used to draw attention to critical health indicators and primary call-to-actions.

A **Clinical White** background is strictly maintained to preserve a sterile, professional atmosphere. **Tertiary Green** is reserved exclusively for health-positive indicators and the herbal/natural aspects of the clinic's identity. Neutrals are kept cool-toned to complement the navy foundation.

## Typography

The typography strategy focuses on clarity and institutional authority. **Manrope** is used for headlines to provide a modern, geometric, yet friendly appearance that suggests innovation. **Inter** handles all body copy for maximum legibility in dense medical reports.

For technical data, laboratory results, and "Diagnostic-First" labels, **JetBrains Mono** is introduced. This monospaced font reinforces the feeling of laboratory precision and computerized accuracy. Headlines should utilize "Sentence case" for an approachable feel, while technical labels use "UPPERCASE" to denote status.

## Layout & Spacing

The layout follows a **Fixed Grid** system for desktop (12 columns) and a fluid 4-column system for mobile. A generous 24px gutter ensures that complex medical data has "room to breathe," preventing the interface from feeling cluttered or overwhelming.

We employ a "Diagnostic Density" model: patient records and data tables use a tighter 4px baseline grid for efficiency, while educational content and marketing landing pages use a 12px baseline to increase whitespace and luxury feel. Content should be centered within a 1280px max-width container on larger screens to maintain clinical focus.

## Elevation & Depth

To maintain the clinical white aesthetic, depth is primarily conveyed through **Tonal Layers** and **Low-Contrast Outlines** rather than heavy shadows. 

1.  **Base Layer:** Pure White (#FFFFFF) for the primary canvas.
2.  **Surface Layer:** Soft Cool Gray (#F1F3F5) for sidebars and secondary containers.
3.  **Interactive Layer:** Deep Navy (#000080) for primary interactive zones.

When elevation is required (e.g., for diagnostic modals), use extremely diffused, low-opacity shadows with a 2% Navy tint. This prevents the "dirty" look of standard gray shadows on white backgrounds, keeping the UI looking crisp and high-end.

## Shapes

The shape language is defined by "Precision Softness." A standard **0.5rem (8px)** corner radius is applied to most UI components to feel modern and accessible. 

However, a distinctive **Circular Motif** is used for diagnostic imagery and specialized laboratory icons, echoing the flyer's circular photo frames. These circles represent the "lens" of the microscope or the focus of a diagnostic scan. Large-scale layout sections may use sweeping, asymmetrical curves to transition between navy and white sections, creating a sense of organic flow.

## Components

### Buttons
Primary buttons are solid Deep Navy with white text for maximum authority. Secondary actions use the Vibrant Magenta as a border or text color to signal medical urgency or diagnostic "next steps."

### Diagnostic Icons
Specialized laboratory icons must be enclosed in a circular magenta or navy stroke. Icons should be simplified line art with a 2px weight, matching the precision of the typography.

### Treatment Chips
Status indicators (e.g., "Confirmed," "Pending") use high-contrast caps from the label typography. Positive results use the Tertiary Green, while critical warnings use Magenta.

### Data Cards
Cards used for "Laboratory Investigations" feature a thick 4px left-border in Magenta to signify the Diagnostic-First hierarchy. These cards should have zero shadow but a subtle 1px gray border.

### Input Fields
Inputs use a "Clinical Focus" state: when active, the border shifts from light gray to Deep Navy with a 2px Magenta glow, highlighting the user's current data entry point.