---
name: Industrial Precision
colors:
  surface: '#f9f9fa'
  surface-dim: '#dadadb'
  surface-bright: '#f9f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f4'
  surface-container: '#eeeeef'
  surface-container-high: '#e8e8e9'
  surface-container-highest: '#e2e2e3'
  on-surface: '#1a1c1d'
  on-surface-variant: '#46474a'
  inverse-surface: '#2f3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#76777b'
  outline-variant: '#c7c6ca'
  surface-tint: '#5f5e5f'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1b1b1c'
  on-primary-container: '#858384'
  inverse-primary: '#c8c6c7'
  secondary: '#9d4300'
  on-secondary: '#ffffff'
  secondary-container: '#fd761a'
  on-secondary-container: '#5c2400'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#002109'
  on-tertiary-container: '#009844'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e3'
  primary-fixed-dim: '#c8c6c7'
  on-primary-fixed: '#1b1b1c'
  on-primary-fixed-variant: '#474647'
  secondary-fixed: '#ffdbca'
  secondary-fixed-dim: '#ffb690'
  on-secondary-fixed: '#341100'
  on-secondary-fixed-variant: '#783200'
  tertiary-fixed: '#6bff8f'
  tertiary-fixed-dim: '#4ae176'
  on-tertiary-fixed: '#002109'
  on-tertiary-fixed-variant: '#005321'
  background: '#f9f9fa'
  on-background: '#1a1c1d'
  surface-variant: '#e2e2e3'
  slate-900: '#0F172A'
  industrial-gray: '#71717A'
  warning-orange: '#EA580C'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
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
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
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
  base: 4px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  max-width: 1280px
---

## Brand & Style

The brand identity is rooted in the concept of "Technology born in operations." It bridges the gap between the gritty reality of industrial environments and the precision of modern digital tools. The target audience includes operations managers, plant directors, and logistics leads who value utility over aesthetics but appreciate professional reliability.

The design style is **Corporate Modern with a Technical Edge**. It utilizes high-contrast interfaces, clean lines, and subtle structural patterns (like dot grids or thin technical rules) to evoke a sense of engineering and architectural blueprints. Visuals should prioritize authenticity, using photography that captures real-world operations—manufacturing floors, warehouses, and logistics hubs—rather than sanitized corporate stock. The interface feels robust, efficient, and intentional, mirroring the tools it aims to replace.

## Colors

This design system moves away from generic "Tech Blue" in favor of a palette inspired by industrial hardware and safety signaling.

- **Primary:** Deep Charcoal (#1A1A1B) is used for typography, heavy borders, and structural elements. It provides a grounded, authoritative foundation.
- **Secondary:** Safety Orange (#F97316) serves as the "operational" accent. It is used sparingly for high-priority actions, status indicators, and critical call-to-outs, mimicking the visibility of industrial safety gear.
- **Tertiary:** Precise Green (#22C55E) is used for success states, data upticks, and "Go" signals, providing a professional balance to the orange.
- **Neutral:** Industrial Steel Gray (#F4F4F5) acts as the primary background color to maintain a clean, high-contrast workspace that reduces eye strain.

The default mode is **Light**, ensuring maximum readability in varied lighting conditions typical of operational environments (from bright offices to dimly lit warehouses).

## Typography

The typography system balances approachable professionalism with technical precision. 

**Inter** is the primary typeface, chosen for its exceptional legibility and neutral, geometric structure. It is used for all narrative content, headlines, and general UI elements. 

**JetBrains Mono** is introduced for small labels, data points, and technical metadata. This monospaced choice reinforces the "built by experts" feel and ensures that numerical data is easy to scan and compare in dashboards and reports.

To maintain high contrast and clarity, headline weights are kept bold, while body text uses generous line heights to facilitate reading on the move.

## Layout & Spacing

The layout utilizes a **Fixed Grid** system for desktop to ensure data-heavy interfaces remain organized and scannable, while transitioning to a fluid, single-column model for mobile.

- **Desktop (1024px+):** A 12-column grid with a 1280px max-width. Gutters are fixed at 24px to provide clear separation between cards and data modules.
- **Mobile (<768px):** A fluid layout with 16px side margins. Elements stack vertically, prioritizing the hierarchy defined in the "How it works" and "Experience" sections.

The spacing rhythm is based on a **4px baseline grid**. All padding and margins should be multiples of 4 (4, 8, 12, 16, 24, 32, 48, 64), creating a rigid, "engineered" sense of order. Large sections are separated by 64px or 80px blocks to allow the "real operation" photography to breathe.

## Elevation & Depth

This design system avoids heavy shadows and skeuomorphism. Instead, it uses **Tonal Layers** and **Low-Contrast Outlines** to define hierarchy.

- **Level 0 (Background):** The Steel Gray (#F4F4F5) base.
- **Level 1 (Cards/Modules):** Pure white surfaces (#FFFFFF) with a 1px solid border in a slightly darker gray (#E4E4E7). No shadow is used here to maintain a "flat" industrial feel.
- **Level 2 (Interactive/Floating):** Subtle, tight shadows (0px 2px 4px rgba(0,0,0,0.05)) are reserved only for elements that require immediate attention or float over content, such as dropdown menus or mobile navigation drawers.

Depth is also communicated through "Technical Grids"—subtle 24px dot patterns in a light gray—used in the background of hero sections or section transitions to imply a workspace environment.

## Shapes

The shape language is **Soft (0.25rem)**. This slight rounding takes the edge off the industrial aesthetic, making the technology feel modern and user-friendly without appearing "bubbly" or consumer-grade.

- **Standard Buttons & Inputs:** 0.25rem (4px) corner radius.
- **Cards & Larger Containers:** 0.5rem (8px) corner radius.
- **Status Tags (Chips):** 0.25rem (4px) to maintain a rigid, label-like appearance.

Interactive elements should feel like solid blocks of color or outlined containers, emphasizing their functional nature.

## Components

**Buttons**
Primary buttons use the Charcoal (#1A1A1B) background with White text for maximum authority. Secondary buttons use the Safety Orange (#F97316) for specific "Operational" CTAs like "Start Diagnosis." Ghost buttons use a 1px border of the Primary color.

**Input Fields**
Inputs feature a 1px border in Industrial Gray, moving to a 2px Charcoal border when focused. Labels always use the monospaced font (**JetBrains Mono**) to give a technical, data-entry feel.

**Cards**
Used to encapsulate modules like "Dashboards" or "Mantenimiento." They should have a white background, a thin gray border, and use the monospaced label at the top-right to categorize the content type.

**Status Chips**
Small, rectangular tags with low-saturation backgrounds (e.g., light green for "Active", light orange for "Pending"). They use the monospaced font in all-caps for a "tagging" effect.

**Interactive Diagnostic (Lead Gen)**
The diagnostic tool should use a stepped progress bar. Each question is housed in a clean white container. Use large, high-contrast radio cards for options to ensure ease of use on mobile devices in industrial settings.

**Technical Grid/Rule**
Use thin horizontal and vertical lines (0.5px or 1px) to separate sections, reminiscent of technical drawings or CAD software.