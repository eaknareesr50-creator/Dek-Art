---
name: Creative Studio Workspace
colors:
  surface: '#111319'
  surface-dim: '#111319'
  surface-bright: '#373940'
  surface-container-lowest: '#0c0e14'
  surface-container-low: '#191b22'
  surface-container: '#1e1f26'
  surface-container-high: '#282a30'
  surface-container-highest: '#33343b'
  on-surface: '#e2e2eb'
  on-surface-variant: '#bfc7d3'
  inverse-surface: '#e2e2eb'
  inverse-on-surface: '#2e3037'
  outline: '#89919d'
  outline-variant: '#3f4852'
  surface-tint: '#99cbff'
  primary: '#99cbff'
  on-primary: '#003354'
  primary-container: '#31a8ff'
  on-primary-container: '#003b61'
  inverse-primary: '#00629d'
  secondary: '#ffc07f'
  on-secondary: '#492900'
  secondary-container: '#fd9900'
  on-secondary-container: '#643900'
  tertiary: '#c2c1ff'
  on-tertiary: '#231f83'
  tertiary-container: '#9797fd'
  on-tertiary-container: '#2b298b'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#cfe5ff'
  primary-fixed-dim: '#99cbff'
  on-primary-fixed: '#001d33'
  on-primary-fixed-variant: '#004a78'
  secondary-fixed: '#ffdcbd'
  secondary-fixed-dim: '#ffb86d'
  on-secondary-fixed: '#2c1600'
  on-secondary-fixed-variant: '#693c00'
  tertiary-fixed: '#e2dfff'
  tertiary-fixed-dim: '#c2c1ff'
  on-tertiary-fixed: '#0b006b'
  on-tertiary-fixed-variant: '#3b3a9a'
  background: '#111319'
  on-background: '#e2e2eb'
  surface-variant: '#33343b'
typography:
  display-lg:
    fontFamily: Inter, 'Noto Sans Thai', sans-serif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Inter, 'Noto Sans Thai', sans-serif
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Inter, 'Noto Sans Thai', sans-serif
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Inter, 'Noto Sans Thai', sans-serif
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter, 'Noto Sans Thai', sans-serif
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.005em
  headline-sm:
    fontFamily: Inter, 'Noto Sans Thai', sans-serif
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: '0'
  body-lg:
    fontFamily: Inter, 'Noto Sans Thai', sans-serif
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: '0'
  body-md:
    fontFamily: Inter, 'Noto Sans Thai', sans-serif
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: '0'
  body-sm:
    fontFamily: Inter, 'Noto Sans Thai', sans-serif
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter, 'Noto Sans Thai', sans-serif
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter, 'Noto Sans Thai', sans-serif
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.25rem
  gutter-mobile: 0.75rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

The design system establishes a high-performance, studio-grade creative workbench engineered for digital artists, mentors, and students. Taking inspiration from the functional rigor and ergonomic clarity of industry-standard creative software, the environment delivers an unobtrusive, focus-first dark canvas that foregrounds student artwork, high-resolution critique overlays, and mentor annotations without visual competition.

The aesthetic philosophy centers on **Refined Studio Utility**:
- **Workstation Discipline:** A quiet slate-zinc architecture reduces optical fatigue across long review sessions while letting user-generated artwork pop with authentic color fidelity.
- **Accented Software Pedigree:** Deliberate, high-recognition tool-specific accents anchor navigation, tagging, and contextual critique threads without compromising system cohesion.
- **Functional Clarity:** Interface boundaries rely on micro-borders and subtle tonal steps rather than heavy decorative drops, creating an environment that feels tactile, professional, and reliable.

## Colors

The palette operates on a calibrated dark-mode hierarchy engineered to preserve ocular stamina and highlight visual assets.

### Palette Architecture
- **Primary Studio Accent (`#31A8FF`):** The functional engine of the workspace. Used for active selection bounds, primary commit buttons, input focus states, interactive scrubbers, and primary workflow triggers.
- **Secondary Creative Accent (`#FF9A00`):** Vector, drafting, and warning-tier highlights. Dedicated to secondary milestones, vector workspace badges, and high-priority revision notes.
- **Tertiary Motion & Compositing Accent (`#9999FF`):** Time-based, dynamic, and community review tags, video timeline checkpoints, and specialized critique status markers.
- **Neutral Canvas Foundations (`#0F1117` base):**
  - `canvas-default`: `#0F1117` (Global viewport backdrop)
  - `surface-base`: `#161922` (Panels, side docks, and primary containers)
  - `surface-elevated`: `#1E2230` (Interactive cards, review popovers, and flyouts)
  - `surface-overlay`: `#262B3D` (Selected states, contextual tooltips, and active chip fills)
  - `border-subtle`: `rgba(255, 255, 255, 0.08)` (Defines structural separation)
  - `border-focus`: `rgba(49, 168, 255, 0.5)` (Signals interactive attention)

### Extended Tool Indicators
- **Procreate & Illustration Coral (`#FF4B72`):** Applied strictly to illustration badges, paint tool filters, and unresolved critique callouts.
- **Fresco Indigo (`#6366F1`):** Applied to sketching, layer-based exercises, and draft statuses.

## Typography

The typography scale relies on **Inter** with systemic fallback to **Noto Sans Thai** to guarantee uniform typographic metrics across international character sets. 

### Typographic Hierarchy & Behavior
- **Headlines:** Clean optical kerning with subtle negative letter spacing at larger scales ensures punchy studio headlines that remain technical rather than theatrical.
- **Dual-Language Alignment:** Line-height values are tuned generously (minimum 1.5x on body sizes) to prevent vertical collision of Thai vowel marks and tone ascenders/descenders when juxtaposed with Latin characters.
- **Labels & Metrics:** Small-scale labels leverage medium and semibold weights (`500` and `600`) with positive tracking (`0.01em` to `0.04em`) to maintain sharp legibility on dark panels and tool palettes.

## Layout & Spacing

The layout model balances an asymmetrical, split-pane workspace with a reliable 12-column responsive fluid grid.

### Layout Philosophy
- **Workspace Canvas & Docks:** The interface is divided into a fixed or collapsible tool/navigation rail (64px to 240px), a fluid center viewport for critique review and canvas inspection, and an inspectable context sidebar (340px) for mentor feedback threads.
- **Content Grids:** Course rosters, critique galleries, and project libraries render across a 12-column fluid grid on desktop (1280px+), stepping down to 8 columns on tablet (768px-1279px) and 4 columns on mobile (<768px).
- **Rhythm & Increments:** Built strictly on an 8pt base grid with a 4pt micro-increment (`space-xs: 0.25rem`). Padding inside dense critique inspection panels uses `space-sm` and `space-md`, while external boundaries between artwork modules rely on `space-lg` and `space-xl`.

## Elevation & Depth

Visual depth avoids excessive atmospheric blur and exaggerated skeuomorphism, prioritizing tight, layered surface stacking that mimics professional creative software panels.

### Surface Tiers & Stacking
1. **Level 0 (Canvas):** Pure `#0F1117`. Flat base for artwork display.
2. **Level 1 (Docked Surfaces & Sidebars):** `#161922` combined with a crisp, low-contrast inner border (`1px solid rgba(255, 255, 255, 0.06)`).
3. **Level 2 (Cards & Active Critique Containers):** `#1E2230` with `1px solid rgba(255, 255, 255, 0.09)`. Ambient shadow: `0 4px 16px -2px rgba(0, 0, 0, 0.45)`.
4. **Level 3 (Floating Toolbars, Modals & Menus):** `#262B3D` with `1px solid rgba(255, 255, 255, 0.14)`. Ambient shadow: `0 12px 32px -4px rgba(0, 0, 0, 0.65)`.

### Border Outlines Over Heavy Shadows
Boundaries between inspection tools and image upload grids are expressed through distinct contrast lines rather than heavy drop shadows, keeping rendering crisp on color-calibrated studio displays.

## Shapes

The design system adopts a balanced **Rounded (`2`)** shape vocabulary, applying disciplined corner radii that soften UI density while preserving the precision expected from creative desktop utilities.

### Corner Radius Mapping
- **Micro UI Elements (Pills, Status Badges, Badges):** Full pill (`9999px`) or `rounded` (`0.5rem`) for compact tags.
- **Interactive Controls (Buttons, Inputs, Segmented Tabs):** `0.5rem` (`roundedness: 2`), ensuring a balanced tactile appearance.
- **Structural Containers (Cards, Critique Dialogue Boxes, Image Upload Drops):** `1rem` (`rounded-lg`), providing clear macro separation.
- **Large Presentation Overlays & Modals:** `1.5rem` (`rounded-xl`), creating distinct focus layers over the workspace.

## Components

### 1. Buttons
- **Primary Action (Commit / Post Critique):** Filled `#31A8FF` background with `#0F1117` text (Font weight: `600`), 0.5rem radius, hover transition with slight brightness increase, active state scales down to `0.98`.
- **Secondary (Tool Action / Cancel):** Transparent background with `1px solid rgba(255, 255, 255, 0.12)`, text `#FFFFFF`, hover brings background to `rgba(255, 255, 255, 0.06)`.
- **Icon / Canvas Utility Buttons:** 36x36px or 40x40px square bounds with 0.5rem radius, center-aligned SVG icons with 1.5px stroke width.

### 2. Interactive Software Category Cards
- **Structure:** Surface `#1E2230` with a 1px border colored by software family on hover (e.g., `#31A8FF` for Photoshop, `#FF9A00` for Illustrator).
- **Header:** Displays an icon badge with a semi-opaque background (e.g., `rgba(49, 168, 255, 0.15)`) next to the course/critique module count.
- **Micro-Interaction:** Hover elevation lifts container by `-2px` with a subtle glow tinted to the software accent.

### 3. Q&A Critique Message Cards
- **Header:** Split mentor/student avatar, timestamp, and context badge denoting revision round (e.g., `Revision #2`).
- **Body & Media Area:** Enclosed image preview with pin-point coordinate markers. Image dropzone features a dashed border (`1.5px dashed rgba(255, 255, 255, 0.18)`), responsive zoom triggers, and a dual-view split mode (Before vs. After).
- **Footer:** Action bar with thread replies, pinned voice note scrubber, and status update trigger.

### 4. Status Pills (Thai & English Bilingual System)
- **รอการตอบกลับ (Pending Mentor Feedback):** Soft amber base (`rgba(255, 154, 0, 0.12)`), text `#FF9A00`, with a pulsing 6px dot indicator.
- **ได้รับคำแนะนำแล้ว (Feedback Delivered):** Teal-blue base (`rgba(49, 168, 255, 0.12)`), text `#31A8FF`, with a solid checkmark glyph.
- **กำลังแก้ไข (In Revision):** Violet base (`rgba(153, 153, 255, 0.12)`), text `#9999FF`.

### 5. Input Fields & Critique Annotations
- **Text Inputs & Textareas:** Dark surface `#161922`, border `1px solid rgba(255, 255, 255, 0.1)`, placeholder text `rgba(255, 255, 255, 0.35)`.
- **Focus State:** 1px solid `#31A8FF` with a subtle ring `0 0 0 2px rgba(49, 168, 255, 0.2)`. No abrupt layout shifts.

### 6. Interactive Pin & Canvas Feedback Overlays
- Floating numerical pins (`#31A8FF` background, `#0F1117` text, font weight `700`) anchored to specific canvas coordinates. Clicking opens an anchored review popover with markdown commentary and layer references.