---
name: Academic Pulse
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#e0c0b2'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#a78b7e'
  outline-variant: '#584237'
  surface-tint: '#ffb693'
  primary: '#ffb693'
  on-primary: '#562000'
  primary-container: '#f37021'
  on-primary-container: '#541f00'
  inverse-primary: '#a04100'
  secondary: '#ffb95f'
  on-secondary: '#472a00'
  secondary-container: '#ee9800'
  on-secondary-container: '#5b3800'
  tertiary: '#4edea3'
  on-tertiary: '#003824'
  tertiary-container: '#00ac77'
  on-tertiary-container: '#003723'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdbcb'
  primary-fixed-dim: '#ffb693'
  on-primary-fixed: '#341000'
  on-primary-fixed-variant: '#7a3000'
  secondary-fixed: '#ffddb8'
  secondary-fixed-dim: '#ffb95f'
  on-secondary-fixed: '#2a1700'
  on-secondary-fixed-variant: '#653e00'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-lg:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  title-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 22px
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
  label-lg:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-sm: 0.75rem
  margin: 1rem
  margin-tablet: 1.5rem
  margin-desktop: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system drives a high-precision, interactive academic cockpit tailored for undergraduate students navigating rigorous, credit-heavy curricula. The personality blends technological capability, institutional prestige, and motivational energy. It shifts the perception of degree progression from a bureaucratic chore into an actionable journey of mastery.

The visual style pairs **Corporate Modern** structure with **tactile dark slate depths and luminous status signaling**. Surfaces use deep, navy-tinted slates to minimize eye fatigue during night study sessions, illuminated by the high-visibility corporate orange and semantic status tiers (Emerald for completed credits, Amber for ongoing tasks, and Muted Slate for locked prerequisites). 

The emotional response must be:
- **Empowered & Confident:** Clear visualization of credit accumulation and OJT (On-the-Job Training) milestones gives students total ownership over their graduation trajectory.
- **Calm & Disambiguated:** Prerequisite chains and academic probation guards are parsed through unambiguous visual status cues rather than dense tabular data.
- **Agile & Focused:** Mobile-first micro-surfaces allow for rapid scenario planning, quick advisor consultations, and grade forecasting on the move.

## Colors

The palette operates in a default dark mode configured specifically for mobile OLED screens and high-contrast environments.

### Brand & Status Tiers
- **Primary Accent (`#F37021`):** Corporate University Orange. Used exclusively for primary interactive calls-to-action, active pathway nodes, and milestone highlights.
- **Secondary Accent (`#F59E0B`):** Vibrant Amber/Gold. Deployed for pending actions, current semester in-progress indicators, and high-impact advisor alerts.
- **Tertiary Accent (`#10B981`):** Emerald Green. Reserved for completed courses, satisfied prerequisites, passing grade badges, and achieved OJT readiness marks.
- **Warning & In-Progress (`#FBBF24`):** Soft Amber for ongoing enrollments and mid-term exam checkpoints.
- **Locked / Inactive (`#64748B`):** Muted Slate for future semesters, locked courses, and pending requirements, framed against `#475569` stroke lines.

### Surface Hierarchy (Dark Mode Foundation)
- **Canvas Base:** `#0F172A` (Dark Slate/Navy Canvas)
- **Surface Level 1 (Cards, Bottom Sheets):** `#1E293B` (Deep Navy Slate)
- **Surface Level 2 (Nested Panels, Active Chips):** `#334155` (Mid Slate)
- **Dividers & Subtle Borders:** `#334155` (1px clean contrast)
- **Text High-Emphasis:** `#F8FAFC`
- **Text Medium-Emphasis:** `#94A3B8`
- **Text Disabled/Muted:** `#64748B`

## Typography

The type stack is engineered for high-density academic telemetry. 

- **Inter** provides uncompromised legibility for UI labels, student names, degree titles, and natural text threads. Letter-spacing is tightened slightly (`-0.01em`) on headers for authority, while body text maintains standard geometric tracking for rapid scanning.
- **JetBrains Mono** acts as the dedicated tabular and metric face. It handles course codes (e.g., `PRJ301`, `SWP391`), GPA numerals (`3.64 / 4.00`), credit tallies, and prerequisite logic tags. Monospaced rendering ensures numerical figures stay perfectly aligned across vertical summary columns.

## Layout & Spacing

The layout uses a responsive fluid grid optimized for high-density mobile interfaces with progressive enhancement for larger viewports:
- **Mobile (<640px):** 4-column fluid grid, `1rem` outer canvas margins, `0.75rem` to `1rem` column gutters. Horizontal scroll tracks (swimlanes) overflow naturally to display consecutive terms (Semester 1 through Semester 9) with explicit edge-clipping indicators.
- **Tablet (640px–1024px):** 8-column layout, `1.5rem` margins. The roadmap converts from a single-axis horizontal scroll to a 2-column comparative term grid.
- **Desktop (>1024px):** 12-column layout, `2rem` outer margins. Accommodates simultaneous display of the full academic timeline alongside sticky consultation sidebars and credit analytics.

Vertical rhythm is strictly bound to an 8pt base unit (with 4pt sub-steps for compact badge paddings). Course nodes maintain tight vertical gaps (`space-xs` and `space-sm`) to maximize visible roadmap hierarchy above the fold.

## Elevation & Depth

Visual hierarchy does not use heavy drop-shadows; instead, it relies on **tonal stepping combined with low-contrast structural outlines**:

- **Ground Level (Canvas):** Pure `#0F172A` creates a non-reflective, deep background.
- **Card Tier 1 (Base Container):** `#1E293B` bordered with 1px solid `#334155`. Displays passive metrics, completed semesters, and consultation history.
- **Card Tier 2 (Interactive Elements & Floating Modals):** `#243247` or `#334155` elevated with subtle ambient dark glow: `0 4px 20px -2px rgba(0, 0, 0, 0.45)`.
- **Active Node Highlight (Focused Course/Active Term):** Highlighted with a 1px border colored in Primary Orange (`#F37021`) and an ambient directional glow: `0 0 12px rgba(243, 112, 33, 0.25)`.
- **Locked/Inactive State:** Flattened into the background with 0 elevation, 1px dashed or muted solid stroke `#475569`, and an opacity drop of `0.6` on internal labels.
- **Drawers & Bottom Nav:** Glass-tempered slate using `backdrop-filter: blur(16px)` over `#0F172A/90` with a crisp 1px top stroke in `#334155`.

## Shapes

The interface embraces a structured, modern curvature (`roundedness: 2`). This sets base shapes to `0.5rem` (8px), large cards to `1rem` (16px), and modal bottom drawers to `1.5rem` (24px) top-corner radii.

- **Micro-Elements (Status Badges, Grade Tags, Course Type Pills):** 4px to 6px border radius, keeping metadata compact and industrial.
- **Interactive Course Nodes:** 10px to 12px radius, balancing tactile tap ergonomics with information packaging.
- **Action Buttons & Progress Rails:** Full pill shapes for primary buttons (`9999px`) to separate navigational/operational actions from informational cards.
- **Bottom Navigation & Modal Drawers:** Rounded top edges (`1.5rem`) ensuring seamless sheet ergonomics on edge-to-edge mobile devices.

## Components

### 1. Buttons
- **Primary Action:** Background `#F37021`, text `#FFFFFF`, rounded full (`9999px`), bold typography. Active state scales to `0.98`. Focus ring: 2px offset with `#F59E0B`.
- **Secondary / Ghost:** Background `transparent`, border 1px solid `#334155`, text `#F8FAFC`. Hover/Active sets background to `#1E293B`.
- **Destructive / Drop Course:** Subtle red tint `#7F1D1D` background with `#F87171` text and border.

### 2. Interactive Course Pills & Nodes
- **Structure:** 2-line or 3-line composite cards displaying Course Code (`JetBrains Mono`, 12px bold), Course Name (`Inter`, 14px), Credit Weight (`3 Cr.`), and Prerequisite Indicator.
- **States:**
  - *Completed:* `#1E293B` background, `#10B981` leading strip or checkmark badge, grade stamp (e.g., `8.5` or `A`) in high-contrast pill.
  - *In-Progress:* `#1E293B` background, `#F59E0B` 1.5px border, pulsing micro-dot indicator.
  - *Locked:* Semi-transparent `#0F172A` background, `#475569` border, padlock icon, and tap-target revealing missing prerequisite code (e.g., "Requires CS102").

### 3. Semester Roadmap Swimlanes
- Mobile horizontal snapping carousel displaying terms (Fall 2024, Spring 2025). 
- Headers feature semester sequence, targeted credit load (e.g., `18 / 20 Credits`), and dynamic GPA projection.
- Connecting lines between course nodes illustrate upstream and downstream dependencies.

### 4. Progress Meters (Linear & Circular)
- **Linear Rails:** 6px track height, background `#334155`, filled with vibrant gradient (`#F37021` to `#F59E0B`) or solid `#10B981` for completed graduation requirements.
- **Circular Dashboard Gauges:** Concentric SVG rings displaying overall credit progression, major requirements completion, and General Education clearance.

### 5. OJT Readiness Checklist
- Status panel assessing prerequisite completion for On-the-Job Training eligibility (e.g., 72 required credits, English level, pre-OJT workshop).
- Unmet criteria show a muted warning pill with dynamic remaining credit countdown; met criteria trigger an Emerald badge.

### 6. Advisor Consultation Thread Cards
- Slate container (`#1E293B`) pairing advisor avatar, status flag (`Pending Response`, `Plan Approved`), timestamp, and actionable thread overview with one-tap schedule revisions.

### 7. Navigation & Drawers
- **Bottom Navigation:** Fixed frosted panel (`#0F172A/90` with 16px blur), 4 key destinations: *Roadmap*, *Curriculum*, *Analytics*, and *Advisor*.
- **Modal Sheets:** Swipeable bottom sheet for course details, prerequisite dependency tree inspection, and grade simulator.