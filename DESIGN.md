---
name: Academic Heritage Modernized
colors:
  surface: '#fdf9f4'
  surface-dim: '#ddd9d5'
  surface-bright: '#fdf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3ee'
  surface-container: '#f1ede8'
  surface-container-high: '#ebe8e3'
  surface-container-highest: '#e6e2dd'
  on-surface: '#1c1c19'
  on-surface-variant: '#40484a'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f4f0eb'
  outline: '#70787a'
  outline-variant: '#c0c8ca'
  surface-tint: '#36656e'
  primary: '#002c32'
  on-primary: '#ffffff'
  primary-container: '#0d434b'
  on-primary-container: '#80afb8'
  inverse-primary: '#9fcfd8'
  secondary: '#7f5616'
  on-secondary: '#ffffff'
  secondary-container: '#fdc57b'
  on-secondary-container: '#78500f'
  tertiary: '#540600'
  on-tertiary: '#ffffff'
  tertiary-container: '#741c0e'
  on-tertiary-container: '#ff836c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#baebf5'
  primary-fixed-dim: '#9fcfd8'
  on-primary-fixed: '#001f24'
  on-primary-fixed-variant: '#1b4d55'
  secondary-fixed: '#ffddb5'
  secondary-fixed-dim: '#f4bd73'
  on-secondary-fixed: '#2a1800'
  on-secondary-fixed-variant: '#633f00'
  tertiary-fixed: '#ffdad3'
  tertiary-fixed-dim: '#ffb4a6'
  on-tertiary-fixed: '#3f0300'
  on-tertiary-fixed-variant: '#822617'
  background: '#fdf9f4'
  on-background: '#1c1c19'
  surface-variant: '#e6e2dd'
typography:
  display-lg:
    fontFamily: Literata
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Literata
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Literata
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-sm:
    fontFamily: Literata
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
---

## Brand & Style

The design system for Cambrio English Center bridges the gap between traditional academic prestige and modern, accessible education. It targets parents seeking a high-quality, trustworthy environment for their children while remaining inviting and engaging for the students themselves.

The visual style is **Corporate / Modern** with subtle **Minimalist** influences. It prioritizes clarity, structure, and a premium "designful" feel. The atmosphere should feel established yet fresh, utilizing the deep teal to project authority and the warm gold to provide a welcoming, supportive glow. Photography should be high-resolution, featuring natural light and genuine interactions to reinforce the "high-quality learning environment."

## Colors

The palette is derived directly from the institution's heritage branding. 

- **Primary (Deep Teal):** Used for headlines, navigation bars, and primary buttons. It represents stability and professional education.
- **Secondary (Warm Gold):** Used for accents, highlights, and secondary UI elements. It evokes the "gold standard" of learning.
- **Tertiary (Coral/Clay):** Derived from the speech bubble in the logo, this is used sparingly for call-to-actions or "live" indicators to add warmth and energy.
- **Neutral (Parchment/Cream):** Instead of pure white, a soft cream base is used for surfaces to create a more sophisticated, "book-like" feel that is easier on the eyes.
- **Success/Warning/Error:** Maintain standard semantic colors but muted slightly to fit the sophisticated palette (e.g., a sage green for success).

## Typography

This system utilizes a pairing of a scholarly Serif and a contemporary Sans-Serif to balance "Academic" with "Friendly."

- **Literata** is the primary choice for headlines. It carries a literary, bookish quality that feels authoritative and premium.
- **Hanken Grotesk** is used for all functional text, body copy, and UI labels. It is exceptionally clean and professional, providing the "modern" edge to the design.
- **Hierarchy:** Use larger Serif headlines for storytelling and section headers. Use Sans-Serif for instructions, form fields, and interactive elements.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy for desktop to maintain a premium, editorial feel, while transitioning to a fluid model for mobile devices.

- **Desktop:** 12-column grid with a 1200px max-width. Use generous 48px margins to allow the content to breathe, emphasizing a "minimalist" and "clean" aesthetic.
- **Rhythm:** A strict 8px baseline grid should be used. Components should use 16px (2 units) or 24px (3 units) for internal padding.
- **Density:** Maintain low density. Whitespace is a first-class citizen in this design system, used to separate complex educational information into digestible sections.

## Elevation & Depth

To maintain a professional and "designful" look, this system avoids heavy shadows. Depth is created through **Tonal Layers** and **Low-contrast outlines**.

- **Surfaces:** Use subtle shifts in the neutral palette (e.g., a slightly darker cream background for a card) to denote hierarchy.
- **Outlines:** Use thin (1px) borders in a light gold or muted teal at 20% opacity. This creates structure without the "clutter" of traditional shadows.
- **Active States:** Only use soft, ambient shadows (blur 12px, 5% opacity Primary Color) when an element is hovered or "lifted" to indicate interactivity.

## Shapes

The shape language is **Soft**. It avoids the playfulness of hyper-rounded corners (which can feel too "childish" for a professional center) and the severity of sharp corners.

- **Standard Radius:** 4px (0.25rem) for input fields and small buttons.
- **Large Radius:** 8px (0.5rem) for cards and containers.
- **Decorative Elements:** Use the shield shape from the logo as a mask for imagery or as a subtle background watermark to reinforce brand identity.

## Components

- **Buttons:** 
    - *Primary:* Solid Teal background with white text. High contrast, slightly weighted font.
    - *Secondary:* Outlined Gold with Teal text.
- **Input Fields:** Soft cream background with a 1px border. Focus state should use a 2px Gold bottom border to feel like a "underline" in a notebook.
- **Cards:** Used for course listings or teacher bios. Use a white background on the cream page surface, with a thin 1px gold border.
- **Chips:** Used for "Level" or "Age Group" indicators. Use high-contrast teal text on a very light teal background.
- **Navigation:** Clear, top-aligned horizontal bar. Use the serif `headline-sm` for the logo wordmark and `label-caps` for navigation links to maintain the professional tone.
- **Progress Indicators:** Use the secondary Gold for progress bars in the student portal, reinforcing the reward-based nature of learning.