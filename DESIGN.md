---
name: Obsidian Terminal
colors:
  surface: '#121316'
  surface-dim: '#121316'
  surface-bright: '#38393c'
  surface-container-lowest: '#0d0e11'
  surface-container-low: '#1b1b1f'
  surface-container: '#1f1f23'
  surface-container-high: '#292a2d'
  surface-container-highest: '#343538'
  on-surface: '#e3e2e6'
  on-surface-variant: '#d8c3ad'
  inverse-surface: '#e3e2e6'
  inverse-on-surface: '#303034'
  outline: '#a08e7a'
  outline-variant: '#534434'
  surface-tint: '#ffb95f'
  primary: '#ffc174'
  on-primary: '#472a00'
  primary-container: '#f59e0b'
  on-primary-container: '#613b00'
  inverse-primary: '#855300'
  secondary: '#94de2d'
  on-secondary: '#1f3700'
  secondary-container: '#7ac100'
  on-secondary-container: '#2c4900'
  tertiary: '#56e5a9'
  on-tertiary: '#003824'
  tertiary-container: '#30c88f'
  on-tertiary-container: '#004e34'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffddb8'
  primary-fixed-dim: '#ffb95f'
  on-primary-fixed: '#2a1700'
  on-primary-fixed-variant: '#653e00'
  secondary-fixed: '#acf847'
  secondary-fixed-dim: '#91db2a'
  on-secondary-fixed: '#102000'
  on-secondary-fixed-variant: '#304f00'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#121316'
  on-background: '#e3e2e6'
  surface-variant: '#343538'
typography:
  display:
    fontFamily: Syne
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-mobile:
    fontFamily: Syne
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Syne
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.025em
  headline-lg-mobile:
    fontFamily: Syne
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Syne
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 17px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  code-inline:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: -0.01em
  hud-label-lg:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
  hud-label-sm:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.12em
  caption:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 3rem
  margin-sm: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies the calculated precision of an advanced systems architect merged with the discerning eye of an avant-garde creative technologist. The aesthetic synthesizes high-end computational HUD environments, aerospace telemetry, and refined architectural editorial layout. It speaks directly to enterprise founders, machine learning researchers, and design-led engineering leaders seeking uncompromising technical pedigree.

The core visual style bridges high-contrast dark-mode minimalism, surgical utilitarian brutalism, and restrained optical glassmorphism:
- **Atmosphere:** Deep void foundations, quiet density, and deliberate optical clarity. Visual interest arises from hairline spatial divisions, strict monospaced alignment, and targeted phosphor accents rather than visual clutter.
- **Tone:** Authoritative, cerebral, highly disciplined, and cinematic. Interfaces feel like a low-latency instrument running on an experimental hardware architecture.
- **Accents:** Restrained luminous embers (warm amber) for status and statefulness, tempered by muted technical emerald/lime for execution vectors and telemetry markers.

## Colors

The palette establishes an absolute visual hierarchy anchored in a near-black, zero-light canvas to preserve contrast fidelity and eliminate visual fatigue:

- **Canvas & Surface Tier:**
  - `bg-base`: `#0A0B0E` — Deep cosmic void canvas.
  - `bg-surface-1`: `#111318` — Primary card, HUD panel, and terminal drawer fill.
  - `bg-surface-2`: `#181B22` — Raised interactive containers, hovered rows, and input surfaces.
  - `bg-surface-glass`: `rgba(17, 19, 24, 0.72)` — Frosted backdrop layers with `backdrop-filter: blur(12px)`.

- **Linework & Structural Boundaries:**
  - `border-hairline`: `rgba(255, 255, 255, 0.08)` — Standard 1px mechanical partition for all cards and dividers.
  - `border-active`: `rgba(245, 158, 11, 0.40)` — Focused or active status ring.
  - `border-subtle`: `rgba(255, 255, 255, 0.04)` — Internal grid lines and passive separators.

- **Chromatics & Telemetry Accents:**
  - `accent-amber-primary`: `#F59E0B` — Main execution hooks, primary actions, running model checkpoints.
  - `accent-amber-subdued`: `#D97706` — Inactive flags, resting focus rings, telemetry hover states.
  - `accent-lime-telemetry`: `#84CC16` — Live state indicators, low-latency metrics, compiler success markers.
  - `accent-emerald-aux`: `#10B981` — Network pulse, verified proofs, deterministic outputs.

- **Typography & Foreground:**
  - `text-primary`: `#E2E8F0` — High-clarity editorial text, headlines, terminal outputs.
  - `text-secondary`: `#94A3B8` — Metadata, inline descriptions, parameter names.
  - `text-tertiary`: `#475569` — Column indicators, line numbers, non-actionable timestamps.

## Typography

The typographic hierarchy implements a dual-register layout approach:
1. **Expressive Structural Display (`Syne`):** Used strictly for high-impact headlines and narrative anchors. Its geometric, broad anatomy delivers architectural weight without retro stylization.
2. **Neutral Reading Texture (`Plus Jakarta Sans`):** Delivers clean optical rhythm across technical case studies, essays, architecture overviews, and narrative logs.
3. **Telemetry & Instrumentation (`JetBrains Mono`):** Applied to badges, table metrics, execution logs, parameters, breadcrumbs, status tags, and coordinates. All `hud-label` variants must enforce `text-transform: uppercase`.

Never allow `Syne` to be used for dense body copy. Ensure monospace numbers use tabular figures (`font-variant-numeric: tabular-nums`) across all analytical tables and data visualizations.

## Layout & Spacing

The structural layout relies on an asymmetric 12-column fluid modular grid capped at a maximum width of `1440px`. Grid alignment is deliberately strict: interface cards, code inspectors, and system metrics align precisely along column bounds.

- **Breakpoints:**
  - **Desktop (≥ 1280px):** 12 columns, `margin: 3rem`, `gutter: 1.5rem`. Enables side-by-side terminal viewers, real-time node graphs, and narrative documentation.
  - **Tablet (768px – 1279px):** 8 columns, `margin: 2rem`, `gutter: 1rem`. Secondary inspectors collapse into tabbed HUD panels.
  - **Mobile (< 768px):** 4 columns, `margin: 1.25rem`, `gutter: 1rem`. Multi-pane telemetry stacks vertically. Fixed-position HUD overlays dock to screen top/bottom rails.

- **Spacing Cadence:** Vertical spacing flows in multiples of `8px` (`0.5rem`). Group logically coupled parameters with `space-xs` and `space-sm`. Structural cards and layout partitions leverage `space-lg` to `space-xl` to preserve breathing room against dark backdrops.

## Elevation & Depth

Spatial layering avoids heavy drop shadows and instead establishes depth through surface reflectance, progressive translucency, and hairline vector borders:

1. **Layer 0 (Canvas Base):** Solid `#0A0B0E`. Host to passive vector grid coordinates and ambient, ultra-low opacity particle canvases (opacity `<= 0.15`).
2. **Layer 1 (Recessed Panels / Wells):** `#08090C` inset containers with an inner stroke of `1px solid rgba(0, 0, 0, 0.4)`. Used for terminal output boxes, execution runs, and hardware status shells.
3. **Layer 2 (Primary Glass HUD):** `rgba(17, 19, 24, 0.72)` with `backdrop-filter: blur(16px)` and border `1px solid rgba(255, 255, 255, 0.08)`. Subtle ambient perimeter shadow: `0 8px 32px -8px rgba(0, 0, 0, 0.60)`.
4. **Layer 3 (Floating Overlays / Modals / Command Bars):** `rgba(24, 27, 34, 0.90)` backed by `backdrop-filter: blur(24px)`, framed with `1px solid rgba(255, 255, 255, 0.14)`, and elevated by `0 20px 48px -12px rgba(0, 0, 0, 0.85)`.
5. **Phosphor Glow Highlights:** Interactive elements feature razor-thin optical reflections. Primary focused elements gain an ambient glow: `0 0 20px -4px rgba(245, 158, 11, 0.25)`.

## Shapes

The design system adopts a restrained `Soft` corner profile (`roundedness: 1`). Curvature is kept intentionally small to evoke precision machining and physical rackmount electronics:

- **Default UI Containers & Cards:** `0.25rem` (4px). Replicating precise chassis edge cuts.
- **Buttons, Badges, and Text Inputs:** `0.25rem` (4px). Retains geometric consistency across form controls.
- **Floating Command Palettes & Modals:** `0.5rem` (8px, `rounded-lg`). Softened slightly to denote detached spatial hovering.
- **Pill / Circular Exceptions:** Used exclusively for circular telemetry status dots (`border-radius: 9999px`) and micro avatar nodes. Interactive buttons and tags must remain squared to their standard 4px profile.

## Components

### Buttons
- **Primary Technical CTA:** Solid background in `bg-surface-2`, border `1px solid rgba(245, 158, 11, 0.6)`, text in `#F59E0B` (`JetBrains Mono`, `hud-label-lg`). Hover shifts border to `1px solid #F59E0B` and adds a subtle phosphor aura (`box-shadow: 0 0 16px -2px rgba(245, 158, 11, 0.3)`). Active triggers a `1px` translation down.
- **Secondary Ghost Action:** Transparent background, hairline border `1px solid rgba(255, 255, 255, 0.08)`, text in `#E2E8F0`. Hover swaps surface to `rgba(255, 255, 255, 0.04)` and border to `rgba(255, 255, 255, 0.18)`.
- **Destructive / Abort:** Border `1px solid rgba(239, 68, 68, 0.4)`, text in `#EF4444`.

### Chips & Telemetry Badges
- Built using `JetBrains Mono` (`hud-label-sm`).
- Height: `22px`, internal padding `0 8px`, border-radius `4px`.
- Composed of an optional 6px pulsing indicator dot, a capitalized category, and a value (e.g., `STATUS: READY`, `LATENCY: 12ms`).
- Standard state: `bg-surface-2`, border `1px solid rgba(255, 255, 255, 0.08)`, text `#94A3B8`.
- Live state: Border `1px solid rgba(132, 204, 22, 0.3)`, text `#84CC16`, with dot pulsing at `0.8Hz`.

### Cards & Project Inspectors
- Background: `rgba(17, 19, 24, 0.72)` with `backdrop-filter: blur(16px)`.
- Outlines: `1px solid rgba(255, 255, 255, 0.08)`.
- Header rail: Features an inset horizontal bar containing section coordinates (e.g., `// 001.SYS_ARCH`) in `text-tertiary` alongside real-time state flags.
- Interactive cards exhibit zero vertical movement on hover; elevation is signaled by a quiet transition of the border to `rgba(255, 255, 255, 0.20)` and an ambient amber trace along the top border.

### Input Fields & Terminal Consoles
- Height: `40px`, background: `#0D0E12`, border: `1px solid rgba(255, 255, 255, 0.08)`.
- Monospace input text in `#E2E8F0`, placeholder in `#475569`.
- Fixed command-line prompt symbol (`>` or `λ`) anchored on the left edge in `#F59E0B`.
- Focus state: Border shifts to `rgba(245, 158, 11, 0.50)` with no thick outer outlines. Blinking vertical line cursor at `1Hz`.

### Checkboxes & Toggle Switches
- Checkbox: 16x16px square container, `roundedness: 2px`, border `1px solid rgba(255, 255, 255, 0.20)`. Checked state displays a high-contrast amber check mark against a `rgba(245, 158, 11, 0.15)` fill with an amber border.
- Toggle Switch: Architectural track (28x16px) with an interior 10x10px square slug (not circular). Toggled-on state shifts slug to the right, glowing in `#84CC16`.

### Lists & Data Logs
- Structured as dense rows with hairline bottom borders `1px solid rgba(255, 255, 255, 0.04)`.
- Alternating hover states introduce subtle row illumination (`rgba(255, 255, 255, 0.02)`).
- Strict column allocations using `JetBrains Mono` for timestamp, event namespace, and payload status.

### System-Specific Component: Interactive HUD Telemetry Drawer
- Collapsible bottom or side rail displaying live model runtime metrics, token generation rates, and active GPU cluster stats.
- Encased in Layer 3 glass with 1px hairline accents, running SVG sparkline charts plotted in `#84CC16` with zero fill gradient beneath the line.