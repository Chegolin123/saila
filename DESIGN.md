---
name: Azure Horizon
colors:
  surface: '#f8fafb'
  surface-dim: '#d8dadb'
  surface-bright: '#f8fafb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f5'
  surface-container: '#eceeef'
  surface-container-high: '#e6e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#43474f'
  inverse-surface: '#2d3132'
  inverse-on-surface: '#eff1f2'
  outline: '#737780'
  outline-variant: '#c3c6d1'
  surface-tint: '#3a5f94'
  primary: '#001e40'
  on-primary: '#ffffff'
  primary-container: '#003366'
  on-primary-container: '#799dd6'
  inverse-primary: '#a7c8ff'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#1e1e1a'
  on-tertiary: '#ffffff'
  tertiary-container: '#33332f'
  on-tertiary-container: '#9d9b95'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d5e3ff'
  primary-fixed-dim: '#a7c8ff'
  on-primary-fixed: '#001b3c'
  on-primary-fixed-variant: '#1f477b'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#e5e2db'
  tertiary-fixed-dim: '#c9c6c0'
  on-tertiary-fixed: '#1c1c18'
  on-tertiary-fixed-variant: '#474742'
  background: '#f8fafb'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display-lg:
    fontFamily: EB Garamond
    fontSize: 48px
    fontWeight: '500'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 36px
    fontWeight: '500'
    lineHeight: 44px
  headline-md:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  headline-sm:
    fontFamily: EB Garamond
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  title-lg:
    fontFamily: Manrope
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '700'
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
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style
The design system embodies the serene and exclusive atmosphere of high-end maritime travel. It targets affluent travelers seeking luxury yacht charters, prioritizing an emotional response of tranquility, freedom, and impeccable service. 

The style is a blend of **Minimalism** and **Modern Corporate**, utilizing expansive whitespace to simulate the open sea and sky. The aesthetic is "Airy Premium"—avoiding heavy ornamentation in favor of precise typography, generous margins, and a light-drenched interface that feels breathable and sophisticated.

## Colors
The palette is inspired by the coastal horizon at midday. 

- **Primary (Deep Ocean):** A commanding navy used for core branding, primary buttons, and critical navigation elements.
- **Secondary (Sunlight Gold):** Reserved for high-value accents, active states, and premium "call-to-action" highlights to evoke a sense of sunset and luxury.
- **Tertiary (Warm Sand):** A soft, desaturated beige used for subtle section backgrounds and container fills to break up pure white spaces.
- **Neutral (Sea Mist):** The foundation of the "airy" feel, utilizing off-whites and very light blues for the main background to reduce eye strain and enhance clarity.

## Typography
The typography strategy creates a tension between traditional elegance and modern efficiency. 

- **Headlines:** Use EB Garamond (as a high-quality alternative to Cormorant) for all large titles. It should feel editorial and prestigious. Use "Display" sizes for hero sections with slight negative letter spacing.
- **Body & UI:** Manrope provides a clean, functional contrast. Its high x-height ensures readability even in dense specifications (like yacht dimensions or deck plans).
- **Labels:** Use uppercase styling with increased letter spacing for Manrope labels to denote category headers or small metadata.

## Layout & Spacing
This design system uses a **Fluid Grid** with intentional "overflow" whitespace. 

- **Desktop:** A 12-column grid with wide 64px outer margins to center the content and provide the "airy" feel.
- **Mobile:** A 4-column grid with 20px margins.
- **Rhythm:** Use a strict 8px base unit. Vertical spacing between major sections should be significantly larger than standard web apps (up to 120px) to maintain the sense of luxury and prevent the interface from feeling "crowded."

## Elevation & Depth
Depth is achieved through **Tonal Layers** and **Ambient Shadows** rather than harsh lines.

- **Shadows:** Use extremely soft, long-range shadows (Blur: 30px+, Opacity: 4-6%) with a slight blue tint (#003366 at 5% opacity) to suggest objects floating over water.
- **Surfaces:** Secondary containers should use the Tertiary (Sand) or Neutral (Sea Mist) colors to create subtle separation without needing borders.
- **Glassmorphism:** Use light backdrop blurs (20px) on navigation bars to maintain the "airy" transparency while ensuring text legibility over high-resolution yacht photography.

## Shapes
The shape language is "Rounded," reflecting the aerodynamic and hydrodynamic curves of a luxury vessel.

- **Standard Elements:** 8px (0.5rem) radius for buttons and input fields.
- **Cards & Large Containers:** 16px (1rem) radius to soften the visual impact of high-resolution imagery.
- **Interactive States:** Soften corners further on hover for a tactile, inviting response.

## Components
- **Buttons:** Primary buttons are Solid Ocean Blue with white Manrope text. Secondary buttons use a Gold outline with 1.5px thickness. All buttons have a subtle hover lift effect.
- **Input Fields:** Use a "Float" style with no bottom border, instead using a very light gray-blue fill and rounded corners. Labels should be small and uppercase.
- **Cards:** Image-heavy cards with "floating" price tags in the top right. Content inside the card should have generous internal padding (24px+).
- **Chips:** Used for yacht features (e.g., "Crewed," "Wifi"). Use a light Sand background with Deep Ocean text.
- **Selection Controls:** Checkboxes and Radio buttons use the Gold accent for active states to denote a "premium" selection.
- **Navigation:** A minimal top-bar with a transparent background that transitions to a solid Sea Mist white on scroll.