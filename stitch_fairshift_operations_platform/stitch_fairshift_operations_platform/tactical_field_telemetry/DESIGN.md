---
name: Tactical Field Telemetry
colors:
  surface: '#051424'
  surface-dim: '#051424'
  surface-bright: '#2c3a4c'
  surface-container-lowest: '#010f1f'
  surface-container-low: '#0d1c2d'
  surface-container: '#122131'
  surface-container-high: '#1c2b3c'
  surface-container-highest: '#273647'
  on-surface: '#d4e4fa'
  on-surface-variant: '#bbcabf'
  inverse-surface: '#d4e4fa'
  inverse-on-surface: '#233143'
  outline: '#86948a'
  outline-variant: '#3c4a42'
  surface-tint: '#4edea3'
  primary: '#4edea3'
  on-primary: '#003824'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#006c49'
  secondary: '#ffb95f'
  on-secondary: '#472a00'
  secondary-container: '#ee9800'
  on-secondary-container: '#5b3800'
  tertiary: '#ffb3ad'
  on-tertiary: '#68000a'
  tertiary-container: '#ff7a73'
  on-tertiary-container: '#79000e'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#ffddb8'
  secondary-fixed-dim: '#ffb95f'
  on-secondary-fixed: '#2a1700'
  on-secondary-fixed-variant: '#653e00'
  tertiary-fixed: '#ffdad7'
  tertiary-fixed-dim: '#ffb3ad'
  on-tertiary-fixed: '#410004'
  on-tertiary-fixed-variant: '#930013'
  background: '#051424'
  on-background: '#d4e4fa'
  surface-variant: '#273647'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-data-lg:
    fontFamily: JetBrains Mono
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0.02em
  label-data-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-data-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.03em
  label-caps:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.08em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-desktop: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system delivers an industrial, tactical, and uncompromisingly utility-first aesthetic for enterprise shift-tracking, labor compliance, and field telemetry. Built under the mission of SDG 8 (Decent Work & Economic Growth), the interface treats field management as a mission-critical operation where clarity equals safety, fair compensation, and life-line transparency.

### Brand Narrative & Ethos
- **Mission Criticality:** Every pixel serves operational truth. There are zero non-functional embellishments, floating ambient neon blurs, or faux-futuristic glowing orbs.
- **Instrument-Grade Utility:** Drawing direct influence from aerospace telemetry consoles and sovereign data platforms, workflows prioritize data density, high-speed scannability, and immediate alert triage under harsh field environments (e.g., bright glare, heavy vibration, dust-resistant rugged tablets).
- **Ethical Precision:** Wage hours, overtime ratios, hazard exposure, and rest breaks are exposed with forensic clarity to prevent labor exploitation and fatigue accidents.

### Aesthetic Movement
- **High-Density Tactical Brutalism:** Structural modularity defined by mechanical paneling, crisp 1px borders, rigid grid alignments, and flat tactile affordances.
- **Monochrome Foundation with Semantic Signal Lighting:** Surfaces remain anchored in subterranean slates and charcoals so that critical alerts (amber warnings, emerald confirmations, red hazards) cut through with immediate, unambiguous optical priority.

## Colors

The system uses a strict functional dark-mode architecture built to exceed WCAG AAA contrast ratios across all critical interactive states and indicators.

### Surface Architecture
- **Base Canvas (`#0B0F17`):** Deep Slate substrate providing maximum dynamic range.
- **Structural Underlay (`#0F172A`):** Charcoal container wells and secondary toolbars.
- **Card & Cell Layer (`#1E293B`):** Workstation modules, table cards, telemetry panels.
- **Border Definers (`#334155`):** Razor-sharp, 1px solid structural dividing lines.
- **Micro-Grid Overlay (`#1E293B` at 15% opacity):** Fixed 16px isometric grid line-mesh on root canvas layers for spatial alignment.

### Operational Signal Palette
- **Industrial Emerald (`#10B981` / `#059669`):** Safe operational status, verified shift sign-off, certified compliant rest intervals, active legal wage confirmation.
- **Safety Amber / Construction Yellow (`#F59E0B` / `#D97706`):** Fatigue accumulation warnings, impending maximum legal shift violations, thermal/environmental hazard cautions.
- **Critical Alert Red (`#EF4444` / `#DC2626`):** Immediate shift lockout, safety protocol breach, unauthorized overtime overrun, emergency halt.

### Monochrome Typography & Icons
- **Metric Text / Primary:** `#F8FAFC` (Slate 50) - 15.8:1 contrast on base.
- **Secondary / Captions:** `#94A3B8` (Slate 400) - 7.3:1 contrast on base.
- **Muted Structural / Inactive:** `#64748B` (Slate 500).
- **Disabled Backgrounds:** `#1E293B` with `#475569` text.

## Typography

The typographic engine marries the utilitarian clarity of **Inter** for narrative framing, task instructions, and UI scaffolding with the exactitude of **JetBrains Mono** for numerical values, financial balances, ISO timestamps, and shift coordinate hashes.

### Rules of Engagement
- **Tabular Figures & Monospace Alignment:** All quantitative telemetry—including duration counters (`07:42:19`), wage calculation currencies (`$1,482.50`), and biometric/fatigue percentages—must strictly use `JetBrains Mono` with full tabular alignment enabled (`font-variant-numeric: tabular-nums`).
- **Section Headers & Uppercase Badging:** Top-level console markers and operational modes utilize `label-caps` rendered in solid capital letters with expanded letter tracking (`0.08em`) to guarantee quick recognition on low-grade field displays.
- **Hierarchy & Scale Restraint:** Type scale avoids theatrical jumps. Screen real estate is reserved for dense relational data tables and time-series operational graphs rather than oversized headlines.

## Layout & Spacing

Layouts adhere to an inflexible, dense structural cadence adapted for tactical situational displays and high-throughput data entry.

### Grid Infrastructure
- **Micro-Grid Foundation:** Built entirely upon a baseline 4px atomic scale and a recurring 16px modular canvas matrix. Root container backgrounds render a subtle 16px grid lines system (`#1E293B` at 15% opacity) to provide visible tactile anchoring for engineering instrumentation.
- **Desktop (12 Columns):** Fluid structural grid anchored inside fixed max-width containers or full-viewport control rooms. 24px gutters, 32px canvas margins. Modularity emphasizes split vertical panes (3-column telemetry sidebar, 9-column shift-dispatch core).
- **Tablet / Rugged Terminal (8 Columns):** Optimized for landscape rugged tablets (Panasonic Toughbook, Zebra terminals) with 16px gutters and 16px margins.
- **Mobile Handheld (4 Columns):** Single-column stacked telemetry cards with compact 12px outer padding, maximizing touch-target clearance for gloved field personnel (minimum touch targets: 48x48px).

## Elevation & Depth

This system eliminates decorative drop shadows, blurred light glows, and translucent glassmorphic surfaces. Depth is purely architectural and functional, achieved through **mechanical tonal steps** and **high-contrast physical borders**.

### Structural Layering
1. **Bedrock Canvas (Level 0 - `#0B0F17`):** Primary viewport backdrop housing the 16px coordinate grid.
2. **Structural Channels & Trays (Level 1 - `#0F172A`):** Recessed toolbars, filter ribbons, and footer diagnostic strips. Inset 1px borders in `#334155`.
3. **Operational Panels & Cells (Level 2 - `#1E293B`):** Individual dispatch modules, personnel telemetry cards, and data logs. Bound by a crisp, continuous 1px outline in `#334155`.
4. **Actionable Overlays & Modal Heads (Level 3 - `#1E293B` with `#475569` border):** Active contextual dialogs, manual override inputs, and critical emergency alerts. Accompanied solely by a hard, non-blurred 2px structural offset (`box-shadow: 0 4px 0 0 #000000`), emphasizing hardware-level presence.

### Interactive State Elevation
- **Hover / Focus:** Rather than diffusing outward, elements react with optical surface brightness increases (e.g., surface shifts from `#1E293B` to `#243347`) and border transitions to `#64748B` or the active semantic channel color (`#10B981` / `#F59E0B`).

## Shapes

The design system employs a disciplined, industrial corner-radius discipline (`roundedness: 1`), keeping edges compact, technical, and structural.

### Geometry Specifications
- **Standard UI Elements (Buttons, Inputs, Metric Tiles):** `4px` (`rounded-sm` / `0.25rem`). Maintains a robust, machined aesthetic that eliminates organic softness.
- **Modules & Master Panels:** `6px` to `8px` (`rounded-md` / `rounded-lg`). Provides containment boundary without diluting the brutalist engineering lineage.
- **Tactical Cut-Outs / Counters:** Corner radiuses never exceed `8px`. Pill shapes (`rounded-full`) are strictly reserved for operational state pills (e.g., live telemetry indicators) that mimic physical illuminated LED fixtures.

## Components

Every component functions as an industrial control instrument: responsive, unambiguous, and tactile.

### Buttons & Operational Switches
- **Primary Operational Button:** Solid Emerald `#10B981` background, `#0B0F17` ultra-dark bold text (`font-weight: 700`). 4px border radius. No ambient glow. On hover, shifts to `#059669`. On press, 1px downward translation.
- **Secondary / Utility Button:** Deep charcoal `#1E293B` background, `#334155` 1px border, `#F8FAFC` text. Hover shifts border to `#64748B`.
- **Emergency Halt / Lockout Action:** Solid Crimson `#DC2626` background with white text (`#FFFFFF`) and instantaneous tactile response.
- **Touch Clearance:** Height is strictly calibrated: 40px on desktop systems, 48px on field and tablet configurations to maintain gloved-hand compliance.

### Telemetry Cards & Containers
- Built on `#1E293B` with a continuous 1px solid border in `#334155`.
- **Header Plate:** Distinct inner sub-header band in `#0F172A` separating parameter titles from metric content.
- Top or left 3px indicator strip in emerald (`#10B981`), amber (`#F59E0B`), or red (`#DC2626`) denoting health status of the module.

### Input Fields & Controls
- **Background:** `#0B0F17` recessed wells with `#334155` border.
- **Typography:** `JetBrains Mono` for all parameter and time inputs; `Inter` for standard descriptions.
- **Focus State:** 1px sharp solid highlight in `#10B981`, zero outer glow or bloom. 
- **Checkboxes & Radios:** Sharp 2px rounded corners, flat slate background `#0F172A`, 1px `#475569` border. Checked states feature solid `#10B981` fill with black geometric tick marks.

### Data Chips & Telemetry Badges
- Compact rectangular forms with 2px corner radius.
- Backgrounds use deep 15% opacity fills matched with 1px solid borders in the parent semantic color (e.g., Active Compliant Shift: Background `rgba(16, 185, 129, 0.15)`, Border `#10B981`, Text `#10B981` in `JetBrains Mono` uppercase).

### Shift & Labor Telemetry Timers (Specialized)
- High-prominence digital clock displays using `label-data-lg` in JetBrains Mono.
- Dual-color bar indicators showing current shift elapsed vs. legal maximum hours under SDG 8 standards, transitioning dynamically from Emerald to Amber at 85% capacity, and Red at 100% lockout threshold.