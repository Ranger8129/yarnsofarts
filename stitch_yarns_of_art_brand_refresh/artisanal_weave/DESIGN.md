---
name: Artisanal Weave
colors:
  surface: '#fefae0'
  surface-dim: '#dedbc2'
  surface-bright: '#fefae0'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f8f4db'
  surface-container: '#f2efd5'
  surface-container-high: '#ede9cf'
  surface-container-highest: '#e7e3ca'
  on-surface: '#1d1c0d'
  on-surface-variant: '#50453b'
  inverse-surface: '#323120'
  inverse-on-surface: '#f5f1d8'
  outline: '#82756a'
  outline-variant: '#d4c4b7'
  surface-tint: '#7d562d'
  primary: '#7d562d'
  on-primary: '#ffffff'
  primary-container: '#d4a373'
  on-primary-container: '#5b3912'
  inverse-primary: '#f0bd8b'
  secondary: '#5a6242'
  on-secondary: '#ffffff'
  secondary-container: '#dee7bf'
  on-secondary-container: '#606848'
  tertiary: '#745662'
  on-tertiary: '#ffffff'
  tertiary-container: '#c8a3b1'
  on-tertiary-container: '#543944'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdcbd'
  primary-fixed-dim: '#f0bd8b'
  on-primary-fixed: '#2c1600'
  on-primary-fixed-variant: '#623f18'
  secondary-fixed: '#dee7bf'
  secondary-fixed-dim: '#c2cba4'
  on-secondary-fixed: '#171e06'
  on-secondary-fixed-variant: '#424a2d'
  tertiary-fixed: '#ffd8e7'
  tertiary-fixed-dim: '#e3bccb'
  on-tertiary-fixed: '#2b141f'
  on-tertiary-fixed-variant: '#5b3f4b'
  background: '#fefae0'
  on-background: '#1d1c0d'
  surface-variant: '#e7e3ca'
typography:
  headline-xl:
    fontFamily: Libre Caslon Text
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 36px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: Plus Jakarta Sans
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
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
---

## Brand & Style
The design system embodies the "Handmade with Love" ethos, targeting fiber artists and craft enthusiasts who value quality and heritage. The aesthetic is **Tactile & Elegant**, blending high-end editorial sophistication with the warmth of a sun-drenched knitting studio.

The style leverages **Minimalism** with **Skeuomorphic touches**, utilizing expansive whitespace to let product photography shine, while grounding the digital interface with organic textures and soft, layered shadows. The emotional response is one of calm, comfort, and creative inspiration—evoking the rhythmic, meditative nature of knitting and crochet.

## Colors
The palette is rooted in natural, undyed fibers and botanical dyes. 

- **Primary (Soft Brown):** Used for primary actions and brand-defining elements, representing the earthiness of raw wool.
- **Secondary (Sage Green):** Applied to success states and growth-related UI elements, mirroring natural dyes.
- **Tertiary (Blush Pink):** Reserved for accents, highlights, and "Favorite" interactions to add a touch of softness.
- **Neutral (Cream & Beige):** These form the structural base of the UI, replacing harsh whites with a warmer, paper-like surface.
- **Text (Espresso):** A deep, warm brown is used instead of pure black to maintain a soft contrast that is gentle on the eyes during long reading sessions.

## Typography
The typographic pairing balances tradition with modern usability. 

**Libre Caslon Text** provides an authoritative yet graceful serif voice for headings, reminiscent of vintage pattern books and luxury editorial. **Plus Jakarta Sans** is used for body copy and UI labels; its soft, rounded terminals echo the curves of yarn loops while ensuring high legibility for technical pattern instructions. Use increased line height for body text to maintain a relaxed, airy feel.

## Elevation & Depth
Depth is achieved through **Tonal Layers** and **Soft Shadows**. Avoid harsh black shadows; instead, use shadows tinted with the primary soft brown (#4A3F35 at 5-10% opacity) to suggest objects resting on a soft surface.

Backgrounds should occasionally feature a subtle "grain" or "linen" texture overlay at 3% opacity to provide a tactile sensation. Cards should use a very thin, low-contrast border (1px, Beige) rather than heavy shadows to maintain a flat, modern elegance.

## Shapes
In this design system, sharp corners are avoided to maintain a "soft-to-the-touch" visual language. 

Standard components use **Rounded (0.5rem)** corners. For more prominent, inviting elements like "Add to Cart" buttons or Category tags, use **Pill-shaped (1rem+)** rounding. Container shapes for images may use organic, slightly irregular "blob" masks to evoke the shape of a yarn skein.

## Components
- **Buttons:** Primary buttons are pill-shaped, using the Primary color with white text. Hover states should involve a slight lift (elevation) rather than a color darken.
- **Cards:** Product cards use a Cream background with a subtle 1px border. The image should be the focus, often using a soft-focus photography style.
- **Input Fields:** Use a solid Beige background with a bottom-only border or a fully rounded frame. Labels should be in `label-caps` for clarity.
- **Chips/Tags:** Used for yarn weights (e.g., "DK", "Chunky") or material (e.g., "Alpaca"). Use the Secondary or Tertiary pastels with a slightly darker text of the same hue.
- **Progress Indicators:** For patterns or shipping, use a "stitched" line style (dashed lines) to reinforce the craft theme.
- **Illustrations:** Incorporate delicate, hand-drawn line art of floral motifs or knitting needles as decorative page breaks or empty-state anchors.