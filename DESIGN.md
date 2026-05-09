---
name: Logistics & Customs Enterprise
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#5b403b'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#90706a'
  outline-variant: '#e4beb7'
  surface-tint: '#b81f0d'
  primary: '#870800'
  on-primary: '#ffffff'
  primary-container: '#b01807'
  on-primary-container: '#ffc1b6'
  inverse-primary: '#ffb4a7'
  secondary: '#515f74'
  on-secondary: '#ffffff'
  secondary-container: '#d5e3fd'
  on-secondary-container: '#57657b'
  tertiary: '#374255'
  on-tertiary: '#ffffff'
  tertiary-container: '#4e596d'
  on-tertiary-container: '#c5d0e8'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad4'
  primary-fixed-dim: '#ffb4a7'
  on-primary-fixed: '#400200'
  on-primary-fixed-variant: '#910a00'
  secondary-fixed: '#d5e3fd'
  secondary-fixed-dim: '#b9c7e0'
  on-secondary-fixed: '#0d1c2f'
  on-secondary-fixed-variant: '#3a485c'
  tertiary-fixed: '#d8e3fb'
  tertiary-fixed-dim: '#bcc7de'
  on-tertiary-fixed: '#111c2d'
  on-tertiary-fixed-variant: '#3c475a'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Manrope
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  body-sm:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-bold:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.05em
  label-md:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 24px
  margin-desktop: 48px
  margin-mobile: 16px
  stack-xs: 4px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 24px
  stack-xl: 48px
---

## Brand & Style
The design system is engineered for the high-stakes world of global logistics and customs brokerage. It communicates unwavering reliability, institutional authority, and high-performance precision. The target audience consists of supply chain directors and enterprise logistics managers who prioritize security and efficiency over decorative flair.

The visual style is **Corporate Modern with a Minimalist execution**. It leverages expansive whitespace to provide clarity in data-heavy environments, utilizing sharp, clean lines to denote structural integrity. By combining a heritage-inspired crimson with a tech-forward slate palette, the design system bridges the gap between established customs expertise and modern digital tracking.

## Colors
The color strategy uses the **Deep Crimson Red** as a high-impact signal for authority, action, and primary brand touchpoints. It is used sparingly to maintain its premium feel and to avoid visual fatigue in dense interfaces.

**Secondary Charcoal and Slate Grays** serve as the foundation for the interface structure, providing a sophisticated backdrop that feels more professional than pure black. **Neutral Off-Whites** are used for background surfaces to reduce eye strain, while **Pure White** is reserved for cards and interactive containers to create a clear "layered" hierarchy.

## Typography
This design system utilizes **Manrope** for its unique balance between geometric precision and humanist warmth. It feels more "established" than Inter while maintaining modern legibility.

**Heading weights are kept heavy (Bold/ExtraBold)** to emphasize authority and provide immediate scanning of document sections. For body text, a generous line-height of 1.6 ensures that complex shipping manifests and customs data remain readable. Small labels and metadata use an uppercase style with increased letter spacing to denote technical or "system-level" information.

## Layout & Spacing
The design system follows a **Fixed-Grid philosophy** for desktop to maintain a premium "dashboard" feel, while transitioning to a fluid model for mobile.

- **Desktop (1440px+):** 12-column grid with 24px gutters and 48px outer margins.
- **Tablet (768px - 1439px):** 8-column fluid grid with 20px gutters.
- **Mobile (< 767px):** 4-column fluid grid with 16px margins.

The spacing rhythm is strictly based on a **linear 8px scale**. All component heights, padding, and margins must be multiples of 8. This ensures a mathematical rigor that reflects the precision required in customs and logistics operations.

## Elevation & Depth
Hierarchy is established through **Tonal Layering and Ambient Shadows**. 

The background uses a subtle off-white (#F8FAFC). Primary content areas reside on "Level 1" cards (Pure White) with an extremely subtle, highly-diffused shadow (0px 4px 12px, 4% opacity of Slate-900). 

Active elements like modals or dropdowns reside on "Level 2," featuring a more pronounced shadow (0px 10px 32px, 8% opacity). This approach avoids heavy gradients or dramatic "floating" effects, opting instead for a grounded, architectural depth that feels secure and permanent.

## Shapes
To align with the "reliable and established" personality, the design system uses a **standard 8px (0.5rem) corner radius**. 

This specific radius is soft enough to feel modern and accessible but sharp enough to maintain a corporate, professional edge. Small components like checkboxes or tags may use 4px (Soft), while large containers and primary buttons must strictly adhere to the 8px standard. Circular radii are reserved exclusively for avatars and status indicators.

## Components
- **Buttons:** Primary buttons use the Deep Crimson background with White text. Hover states shift to the Brand-Dark shade. Secondary buttons use a Slate-700 outline with no fill.
- **Input Fields:** Use a 1px Slate-100 border with an 8px radius. On focus, the border transitions to Slate-700 (not Crimson) to keep the user's attention on the data entry task.
- **Cards:** White background, 8px radius, subtle Level 1 shadow. Used to group shipping details, invoice summaries, or tracking updates.
- **Status Chips:** Critical for logistics. Use a semi-transparent background of the status color (e.g., 10% Green for "Delivered") with bold centered text.
- **Data Tables:** High-density with Slate-900 headers and subtle Slate-100 dividers. No vertical borders; use horizontal lines only to emphasize flow.
- **Customs Indicators:** Specialized badges used for "Cleared," "Inspection Required," or "Duty Paid," utilizing the Crimson only for urgent "Action Required" items.