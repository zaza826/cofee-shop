---
name: Caramelia Heritage
colors:
  surface: '#fbf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae8e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#53443b'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#857369'
  outline-variant: '#d8c2b7'
  surface-tint: '#8c4f23'
  primary: '#894c20'
  on-primary: '#ffffff'
  primary-container: '#a76436'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb688'
  secondary: '#546251'
  on-secondary: '#ffffff'
  secondary-container: '#d4e4ce'
  on-secondary-container: '#586755'
  tertiary: '#79542b'
  on-tertiary: '#ffffff'
  tertiary-container: '#956d40'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbc7'
  primary-fixed-dim: '#ffb688'
  on-primary-fixed: '#311300'
  on-primary-fixed-variant: '#6f380d'
  secondary-fixed: '#d7e7d1'
  secondary-fixed-dim: '#bbcbb5'
  on-secondary-fixed: '#121f11'
  on-secondary-fixed-variant: '#3c4a3a'
  tertiary-fixed: '#ffdcbc'
  tertiary-fixed-dim: '#efbd8a'
  on-tertiary-fixed: '#2c1700'
  on-tertiary-fixed-variant: '#614018'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
  cream-surface: '#F5F1E8'
  paper-white: '#F9F7F3'
  caramel-deep: '#B8683D'
typography:
  headline-xl:
    fontFamily: Noto Serif
    fontSize: 56px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -1px
  headline-xl-mobile:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.5px
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  headline-sm:
    fontFamily: Noto Serif
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 19px
    fontWeight: '300'
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
  label-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '600'
    lineHeight: '1'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1200px
  section-v-desktop: 4rem
  section-h-desktop: 3rem
  section-v-mobile: 2rem
  section-h-mobile: 1.5rem
  gutter: 2rem
  stack-lg: 1.5rem
  stack-md: 1rem
  stack-sm: 0.5rem
---

## Brand & Style

The design system is built on an **Artisan Modern** aesthetic, blending the warmth of a traditional pâtisserie with the clean precision of contemporary digital design. It targets a discerning audience that values craft, quality ingredients, and a refined sensory experience. 

The visual language is "Warm, Artisan, and Refined." It achieves this through a high-contrast typographic pairing and a palette inspired by natural culinary elements. The interface uses a "Modern Minimalist with Texture" approach—relying on generous white space, subtle tonal layers, and strategic accent borders rather than heavy decorative elements. The emotional response should be one of comfort, reliability, and understated luxury.

## Colors

The palette is anchored by **Caramel**, used for primary branding and high-intent actions. **Cream** and **Paper White** serve as the primary surface colors, providing a softer, more organic feel than pure white. 

**Sage** is employed as a functional accent, signaling secondary information and providing a fresh, botanical contrast to the warm earth tones. **Charcoal** is reserved for high-contrast typography to ensure legibility, while **Gold** provides decorative highlights for social and secondary interactive elements. 

Gradients should be used sparingly, primarily in large-scale "Hero" areas, transitioning from Caramel to Deep Caramel to create a sense of richness and depth.

## Typography

This design system uses a high-contrast typographic pairing: **Noto Serif** (substituting Lora for an even more refined editorial feel) for headings and **Inter** for all UI and body text. 

Headlines should utilize the Serif font to convey a sense of heritage and artisanal craft. Body text is set in Inter to maintain modern accessibility and clarity. For long-form descriptions, a light weight (300) is used in larger sizes to evoke a premium, airy feel. Labels and CTAs use medium to semi-bold weights with slight letter spacing to improve navigation scanning.

## Layout & Spacing

The layout philosophy follows a **Fixed-Fluid Hybrid** model. Main content containers are capped at 1200px to maintain readability and visual balance on wide displays, while the internal grid is fluid.

A 12-column grid is used for desktop layouts, transitioning to a single-column stack on mobile devices. Spacing is generous, prioritizing "breathable" layouts that emphasize the premium nature of the brand. Section transitions should use substantial vertical padding (4rem) to clearly demarcate different brand stories or product categories.

## Elevation & Depth

Depth is conveyed through **Tonal Layers** and **Ambient Shadows** rather than heavy borders or skeuomorphism. 

1.  **Surfaces:** The system uses a hierarchy of off-white and cream surfaces to define depth levels. 
2.  **Shadows:** Shadows are extremely subtle and diffused. The base elevation uses a `5%` black opacity with a small blur, while interactive "Hover" states increase this to a `10-20%` opacity with a larger vertical offset to simulate the element lifting off the page.
3.  **Translucency:** In the Hero section, use semi-transparent white overlays (10% opacity) for decorative shapes to create a sense of multi-dimensional light.

## Shapes

The shape language is primarily **Soft and Structured**. We use subtle rounding (4px - 8px) to soften the edges of the professional layout without becoming overly "bubbly." 

A notable exception is the use of **Pill-shaped** containers for tags and "Atmosphere" markers, which provides a friendly, organic contrast to the more rigid grid of cards and info blocks. 

**Accent Borders:** Use directional borders as a signature design element:
- **Top Border (4px):** Used on primary "Highlight" cards in Caramel.
- **Left Border (4px):** Used on "Offering" or list items in Sage.

## Components

### Buttons
Primary buttons are solid Caramel with white text and a 4px corner radius. On hover, they shift slightly upwards (-2px) and gain a deeper shadow. Secondary buttons use a ghost style with a Caramel or Sage border and matching text.

### Cards
Cards are the primary container for products and features. They feature a white background, the standard 8px radius, and a very soft 4px-blur shadow. "Highlight" cards must include the 4px top accent border in Caramel.

### Input Fields
Fields should have a Cream background and a subtle 1px border in Charcoal (at 20% opacity). Focus states should transition the border to Caramel.

### Chips & Tags
Tags used for categorizing or atmosphere should be fully rounded (Pill-shaped) with a light Sage or Cream background and semi-bold Inter text.

### Lists
Lists in information sections use Sage-colored icons or checkmarks. Items are separated by generous padding (stack-md) to maintain the airy, refined aesthetic.

### Navigation
The navigation bar is a sticky element with a white background and a very faint bottom shadow. Links use Inter (500 weight) and transition to Caramel on hover.