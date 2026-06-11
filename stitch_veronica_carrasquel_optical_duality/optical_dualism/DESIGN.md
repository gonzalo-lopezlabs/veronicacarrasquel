---
name: Optical Dualism
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f4'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#4c4546'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#7e7576'
  outline-variant: '#cfc4c5'
  surface-tint: '#5e5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1b1b1b'
  on-primary-container: '#848484'
  inverse-primary: '#c6c6c6'
  secondary: '#5e5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e3e2e2'
  on-secondary-container: '#646464'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1b1b1b'
  on-tertiary-container: '#848484'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c6'
  on-primary-fixed: '#1b1b1b'
  on-primary-fixed-variant: '#474747'
  secondary-fixed: '#e3e2e2'
  secondary-fixed-dim: '#c7c6c6'
  on-secondary-fixed: '#1b1c1c'
  on-secondary-fixed-variant: '#464747'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c6'
  on-tertiary-fixed: '#1b1b1b'
  on-tertiary-fixed-variant: '#474747'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
  void-black: '#000000'
  paper-white: '#FFFFFF'
  gallery-grey: '#F1F1F1'
  graphite: '#333333'
typography:
  headline-xl:
    fontFamily: Hanken Grotesk
    fontSize: 80px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: 0.1em
  caption:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: '1.4'
spacing:
  unit: 8px
  margin-desktop: 64px
  margin-mobile: 24px
  gutter: 32px
  grid-cols: '12'
---

## Brand & Style

This design system is built upon the tension between light and shadow, movement and stillness. It is designed for an optical artist where the interface serves as a silent, architectural gallery space rather than a decorative wrapper. 

The aesthetic is **Minimalist and Architectural**, drawing heavily from the precision of print design and the kinetic elegance of mid-century optical art. The core narrative is "The Void and the Form"—using generous white space to give breathing room to complex artworks while maintaining a rigid, sophisticated structural integrity. The emotional response should be one of quiet authority, intellectual depth, and rhythmic precision.

## Colors

The palette is strictly monochromatic to emphasize the dualistic nature of the artist's work. 

- **Primary (Void Black):** Used for typography, structural borders, and high-impact UI elements. It represents the "ink" on the digital page.
- **Neutral (Paper White):** The primary canvas. It is not just a background, but a structural element that defines the boundaries of content.
- **Secondary (Gallery Grey):** Utilized for metadata, secondary labels, and subtle UI divisions that do not require the harshness of black.
- **Backgrounds:** Use pure white (#FFFFFF) for primary containers and a very subtle grey (#F1F1F1) for hover states or secondary depth tiers to maintain a clean, clinical feel.

## Typography

The typography is inspired by modern exhibition catalogs and architectural blueprints. 

- **Display & Headlines:** Use **Hanken Grotesk** for its sharp, contemporary terminals. Large scale and tight tracking create a bold "print-like" impact.
- **Body Text:** **Inter** provides a neutral, utilitarian foundation for readability across descriptions and artist statements.
- **Utility & Metadata:** **JetBrains Mono** is introduced for captions, dates, and technical specifications, evoking the precision of scientific classification or engineering documents.

Typography should always be high contrast (Black on White) unless indicating a disabled or secondary state.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy rooted in a 12-column system. The interface behaves like a printed page, where margins are intentional and vast.

- **Grid:** Use a 12-column grid for desktop with 32px gutters. Elements should span increments of 2 or 3 columns to maintain a rhythmic vertical rhythm.
- **Safe Margins:** A generous 64px outer margin on desktop ensures that the artwork is never "crowded" by the edges of the browser.
- **Rhythm:** Spacing should be strictly mathematical, based on an 8px base unit. Vertical spacing between sections should be aggressive (e.g., 128px or 160px) to force focus on one piece of content at a time.
- **Mobile:** Reflow to a 4-column grid with 24px margins, maintaining the same typographic hierarchy but scaling down font sizes for accessibility.

## Elevation & Depth

This design system rejects traditional shadows and blurs in favor of **Tonal Layers and Bold Borders**. 

- **Flat Depth:** Hierarchy is established through layering of pure black and white surfaces. A black surface "floats" above a white surface simply by its visual weight.
- **Outlines:** Use 1px or 2px solid black borders to define containers. Do not use soft shadows; if depth is required, use a solid 4px black offset (hard shadow) to mimic brutalist print aesthetics.
- **Negative Space:** Use the absence of elements to create focus. The primary "elevation" tool is the white margin surrounding an object.

## Shapes

The shape language is **Sharp (0)**. 

Every element—buttons, input fields, images, and cards—must have 90-degree corners. This reinforces the architectural and mathematical precision of optical art. There are no rounded corners in this system. Interactive states should be conveyed through color inversion (White to Black) rather than shape changes.

## Components

### Buttons
- **Primary:** Solid black background, white JetBrains Mono text. No border. On hover, invert to solid white background with a 1px black border and black text.
- **Secondary:** 1px black border, white background, black text. On hover, invert to solid black.

### Input Fields
- Underline style only: 1px black bottom border, no side or top borders. Text is Inter 16px. Label is JetBrains Mono 12px positioned above.

### Cards
- No shadows. Use a 1px black border or simply use whitespace to define the card boundaries. Titles should be Hanken Grotesk; metadata should be JetBrains Mono.

### Lists
- Items separated by 1px light grey (#F1F1F1) horizontal rules. Hover state involves the entire row shifting to a gallery-grey background or the text color changing to pure black from a graphite grey.

### Navigation
- Minimalist top-bar or side-bar. Use uppercase JetBrains Mono for links. The "Active" state is indicated by a solid black block behind the text or a simple strikethrough.

### Dualism Toggle
- A prominent toggle for the user to switch the entire site from "Light" (White base) to "Dark" (Black base), reflecting the dualistic nature of the brand.