---
name: Clinical Nature System
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
  on-surface-variant: '#454650'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#757681'
  outline-variant: '#c5c6d1'
  surface-tint: '#495b99'
  primary: '#000622'
  on-primary: '#ffffff'
  primary-container: '#001a57'
  on-primary-container: '#7285c6'
  inverse-primary: '#b5c4ff'
  secondary: '#1b6d24'
  on-secondary: '#ffffff'
  secondary-container: '#a0f399'
  on-secondary-container: '#217128'
  tertiary: '#190005'
  on-tertiary: '#ffffff'
  tertiary-container: '#470019'
  on-tertiary-container: '#f83976'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b5c4ff'
  on-primary-fixed: '#00164d'
  on-primary-fixed-variant: '#304380'
  secondary-fixed: '#a3f69c'
  secondary-fixed-dim: '#88d982'
  on-secondary-fixed: '#002204'
  on-secondary-fixed-variant: '#005312'
  tertiary-fixed: '#ffd9de'
  tertiary-fixed-dim: '#ffb2bf'
  on-tertiary-fixed: '#3f0016'
  on-tertiary-fixed-variant: '#90003b'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Montserrat
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
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  section-padding: 80px
---

## Brand & Style

The design system bridges the gap between traditional herbal wisdom and modern clinical excellence. It is engineered to evoke **trust, vitality, and precision**. By combining a rigorous medical foundation with organic elements, the UI establishes a "Modern Clinical" aesthetic that feels authoritative yet deeply rooted in nature.

The visual direction follows a **Corporate / Modern** style, characterized by structured layouts, intentional whitespace, and sophisticated photographic integration. We use clean lines to represent medical professionalism, while soft roundedness and organic imagery introduce the herbal, human-centric aspect of the clinic. High-fidelity photography of botanicals and professional medical environments should be treated as primary design assets, often framed within circular or organic masks to soften the clinical edge.

## Colors

The palette is anchored by **Deep Navy Blue**, representing the stability and authority of a medical institution. **Vibrant Forest Green** acts as the bridge to nature, used for success states and growth-oriented messaging. **Magenta Pink** serves as a high-contrast accent to draw the eye toward critical calls-to-action and key health metrics.

- **Primary (Navy):** Headers, primary buttons, and heavy structural elements.
- **Secondary (Green):** Iconography, secondary actions, and herbal-focused content areas.
- **Tertiary (Magenta):** Appointment buttons, urgent alerts, and decorative flourishes.
- **Neutral:** A range of soft grays and off-whites to ensure the photography and high-contrast accents remain the focus.

## Typography

This design system utilizes a dual-font strategy. **Montserrat** provides a bold, geometric presence for headlines, echoing the strength of the clinic's brand. **Inter** is used for body copy and UI labels to ensure maximum legibility and a neutral, functional feel during the patient’s digital experience.

For editorial sections, use generous line-heights to promote a "calm" reading experience. All caps should be reserved for `label-md` or `caption` styles to create hierarchy without feeling aggressive.

## Layout & Spacing

The design system employs a **12-column fluid grid** for desktop and a **4-column grid** for mobile. We prioritize "generous whitespace" to mimic the clean, sterile environment of a clinic, preventing the user from feeling overwhelmed by medical data.

- **Vertical Rhythm:** Use the `stack` variables to maintain consistent spacing between elements within a card or section.
- **Section Breaks:** Large `section-padding` (80px+) should be used to separate different service offerings (e.g., Kidney Disease vs. Laboratory Investigation).
- **Responsive Reflow:** On mobile devices, side-by-side elements (like service cards) should stack vertically to maintain readability.

## Elevation & Depth

To maintain a professional clinical feel, we avoid heavy drop shadows. Depth is communicated through **Tonal Layers** and **Low-Contrast Outlines**.

- **Surface Levels:** The background is typically white or the lightest neutral. Cards and containers use a very subtle 1px border (`#E9ECEF`) or a faint, diffused ambient shadow (0px 4px 20px, 5% opacity) to lift them from the page.
- **Micro-Depth:** On hover, primary interactive elements may increase their shadow slightly to provide tactile feedback.
- **Containment:** Use Navy or Green backgrounds for high-impact sections, which naturally creates depth through color blocking rather than shadows.

## Shapes

The shape language is defined by **Rounded** corners, which soften the clinical aesthetic and make the interface feel more approachable and modern. 

- **Standard Elements:** Buttons, input fields, and small cards use the base `0.5rem` radius.
- **Large Containers:** Hero sections and large content blocks use the `1.5rem` (rounded-xl) radius to create a distinct, modern frame.
- **Image Treatment:** Photography of herbs or doctors should often be placed in perfect circles or "pill" shapes, mirroring the clinic's promotional flyers.

## Components

### Buttons
- **Primary:** Deep Navy background, white text. High-contrast, used for "Book Appointment."
- **Secondary:** Forest Green background or border. Used for "Learn More" or "Herbal Products."
- **Accent:** Magenta Pink. Used sparingly for urgent health alerts or special offers.

### Input Fields
- Clean, 1px bordered boxes with `rounded-md` corners. Focus states should use a 2px Navy border. Labels are placed above the field in `label-md` weight.

### Cards
- White background with a subtle border. Cards for "Treatments" should feature a circular image at the top or left, followed by a Montserrat headline.

### Chips & Tags
- Used for categorizing health conditions (e.g., "Diabetes," "Arthritis"). These use a light green background with dark green text to signify health and vitality.

### Progress Indicators
- For laboratory results or health journeys, use Forest Green trackers to symbolize positive progress.

### Lists
- Bulleted lists (as seen in "Treatments Include") should use custom Magenta checkmarks or dots to maintain brand consistency with the printed flyers.