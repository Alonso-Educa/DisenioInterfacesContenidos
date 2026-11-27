---
name: Apex Velocity
colors:
  surface: "#10131a"
  surface-dim: "#10131a"
  surface-bright: "#363940"
  surface-container-lowest: "#0b0e14"
  surface-container-low: "#191c22"
  surface-container: "#1d2026"
  surface-container-high: "#272a31"
  surface-container-highest: "#32353c"
  on-surface: "#e1e2eb"
  on-surface-variant: "#c4c9ac"
  inverse-surface: "#e1e2eb"
  inverse-on-surface: "#2e3037"
  outline: "#8e9379"
  outline-variant: "#444933"
  surface-tint: "#abd600"
  primary: "#ffffff"
  on-primary: "#283500"
  primary-container: "#c3f400"
  on-primary-container: "#556d00"
  inverse-primary: "#506600"
  secondary: "#bdf4ff"
  on-secondary: "#00363d"
  secondary-container: "#00e3fd"
  on-secondary-container: "#00616d"
  tertiary: "#ffffff"
  on-tertiary: "#680019"
  tertiary-container: "#ffdada"
  on-tertiary-container: "#ca003a"
  error: "#ffb4ab"
  on-error: "#690005"
  error-container: "#93000a"
  on-error-container: "#ffdad6"
  primary-fixed: "#c3f400"
  primary-fixed-dim: "#abd600"
  on-primary-fixed: "#161e00"
  on-primary-fixed-variant: "#3c4d00"
  secondary-fixed: "#9cf0ff"
  secondary-fixed-dim: "#00daf3"
  on-secondary-fixed: "#001f24"
  on-secondary-fixed-variant: "#004f58"
  tertiary-fixed: "#ffdada"
  tertiary-fixed-dim: "#ffb3b5"
  on-tertiary-fixed: "#40000c"
  on-tertiary-fixed-variant: "#920027"
  background: "#10131a"
  on-background: "#e1e2eb"
  surface-variant: "#32353c"
typography:
  display-hero:
    fontFamily: Space Grotesk
    fontSize: 56px
    fontWeight: "700"
    lineHeight: 60px
    letterSpacing: -0.04em
  display-hero-mobile:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: "700"
    lineHeight: 44px
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: "700"
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: "700"
    lineHeight: 32px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: "600"
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: "600"
    lineHeight: 24px
    letterSpacing: 0em
  telemetry-metric:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: "700"
    lineHeight: 32px
    letterSpacing: 0.02em
  body-lg:
    fontFamily: Chivo
    fontSize: 16px
    fontWeight: "400"
    lineHeight: 22px
    letterSpacing: 0em
  body-md:
    fontFamily: Chivo
    fontSize: 14px
    fontWeight: "400"
    lineHeight: 20px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: "600"
    lineHeight: 18px
    letterSpacing: 0.06em
  label-md:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: "600"
    lineHeight: 16px
    letterSpacing: 0.08em
  label-tech:
    fontFamily: Space Grotesk
    fontSize: 10px
    fontWeight: "700"
    lineHeight: 12px
    letterSpacing: 0.12em
spacing:
  gutter: 1rem
  gutter-sm: 0.75rem
  margin: 1.25rem
  margin-sm: 1rem
  margin-landscape: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1.25rem
  space-xl: 2rem
---

## Brand & Style

This design system channels the precision of GT sim-racing telemetry combined with the visceral, electric energy of street racing culture. It targets mobile racing enthusiasts, competitive esports drivers, and gearheads who demand immediate visual feedback, tactile mechanical interfaces, and high-octane immersion.

### Aesthetic Foundation

- **Modern Motorsport Sim meets Neon Street:** High-contrast, dark-mode-first aesthetic with deep asphalt/carbon fiber foundations contrasted against high-voltage kinetic accents.
- **Speed Cuts & Chamfers:** Precision 45-degree cuts, dynamic forward slashes, and italicized forward momentum. Static boxes are replaced with directional frames that look sculpted in a wind tunnel.
- **Telemetry Precision:** Fine technical grids, micro tick marks, bar-graph rev limiters, coordinate trackers, and digital readouts that ground the fantasy in mechanical authenticity.

## Colors

The palette simulates night racing: deep, non-reflective asphalt tarmac lit up by neon stadium lamps, redline rev limiters, and nitrous oxide purges.

### Roles & Harmonies

- **Electric Volt (`#CCFF00`):** The primary kinetic driver. Used for primary CTAs, high-priority state notifications, current gear readouts, and top tier Apex rewards. High daytime luminance against dark tones.
- **Nitrous Azure (`#00E5FF`):** Secondary boost indicator. Used for telemetry metrics, turbo spool gauges, drafting indicators, and technical stat radar plots.
- **Nitro Crimson (`#FF2A54`):** Tertiary critical accent. Used for redline tachometer spikes, hazardous race warnings, rival indicators, and critical lap-time delta losses.
- **Deep Asphalt (`#0B0E14`):** Base canvas background simulating textured asphalt and carbon weave.
- **Carbon Shell (`#121722`):** Elevated structural card surfaces and floating chassis frames.
- **Steel Trim (`#1F2637`):** Structural borders, divider ticks, inactive gauge segments, and bracket lines.
- **High-Velocity White (`#FFFFFF`):** Display headers, tachometer numbers, and primary data readouts.
- **Muted Steel (`#8A95A5`):** Sub-labels, vehicle specs, and secondary telemetry metadata.

## Typography

Typography balances technical telemetry with aggressive motorsport branding.

- **Display & Headlines (Space Grotesk):** Engineered, angular, and authoritative. Display copy, gear indicators, and lap readouts should lean into italicized forms (`font-style: italic`) to create kinetic forward tilt.
- **Body & Data Metrics (Chivo):** Highly legible grotesque with rapid scannability at small sizes for car part lists, setup tuning specs, and driver bios.
- **Technical Readouts (`label-tech`):** Always transformed to uppercase with expanded letter-spacing to emulate racing avionics, ECU parameters, and tire temperature readings.

## Layout & Spacing

Mobile racing setups require dual orientation support: vertical portrait for garage management/tuning and horizontal landscape for in-race HUDs and cinematic showroom views.

### Grid Architecture

- **Orientation Awareness:**
  - **Portrait Mode:** 4-column fluid layout with dynamic safe areas for touch navigation zones within the lower thumb-sweep arc.
  - **Landscape HUD Mode:** Flanked telemetry column layout (Left: Speedometer/Gear/RPM, Right: Mini-map/Lap Delta/Tire Temps) leaving the center 60% viewport clear for racing line visibility.
- **Safe Zones:** In landscape mode, apply `margin-landscape` padding to clear camera notches and curved screen glass boundaries.
- **Rhythm:** Spacing follows compact multiples of 4px to maintain dense, mechanical cockpit telemetry density without visual clutter.

## Elevation & Depth

This design system avoids traditional soft dropped shadows in favor of laser neon ambient back-glows, technical wireframe borders, and dark carbon surface layering.

- **Level 0 (Track Canvas):** Flat `#0B0E14` asphalt base with optional subtle 45-degree carbon weave micro-patterning at 4% opacity.
- **Level 1 (Chassis Panels):** Surface `#121722` bordered by 1px solid `#1F2637`. Chamfered corners on top-right and bottom-left to establish an aggressive silhouette.
- **Level 2 (Active Telemetry / Overlays):** Semi-translucent `#121722CC` with `backdrop-filter: blur(16px)` and an interior inset edge highlight of `rgba(255, 255, 255, 0.08)`.
- **Kinetic Glow (Boost / Redline Focus):** 0px offset ambient projections.
  - _Electric Volt Glow:_ `0 0 20px rgba(204, 255, 0, 0.35)`
  - _Nitro Crimson Glow:_ `0 0 20px rgba(255, 42, 84, 0.45)`
  - _Cyan Nitrous Glow:_ `0 0 20px rgba(0, 229, 255, 0.35)`
- **Structural Separation:** Panels use 1px ghost borders or sharp cutouts rather than diffusion shadows to retain simulated high-precision carbon-composite assembly seams.

## Shapes

To mirror high-speed aerodynamic bodywork and precision aerospace telemetry, standard organic fillets are rejected.

- **Sharp Geometry (`roundedness: 0`):** Default corners are strict 90-degree or 45-degree chamfered cuts (`clip-path: polygon(...)`).
- **Speed Cuts:** Primary cards and hero banners feature a characteristic 12px cut on the top-right corner, paired with a matching angled slash on the bottom-left edge.
- **Slanted Dividers:** Separator lines and telemetry columns use a 12-degree forward skew (`transform: skewX(-12deg)`) reinforcing the perception of rapid velocity across all interface cards.

## Components

### Buttons & Action Bars

- **Race Ignition (Primary CTA):** High-voltage Electric Volt background (`#CCFF00`), jet black bold italic typography, 45-degree chamfered right corner. Active state emits a 20px neon volt flare.
- **Nitrous Action (Secondary):** Deep asphalt background with a 1px solid Nitrous Azure border (`#00E5FF`) and cyan text. Fills with cyan on tap.
- **Bail / Abort Button:** Ghost style with 1px Nitro Crimson border (`#FF2A54`) and redline text.

### Telemetry Gauges & Speedometers

- **Segmented Tachometer Bar:** Stepped LED-style block bars (16 segments). Segments 1–11 light up in cold white, 12–14 in Volt Yellow, and 15–16 pulse violently in Nitro Crimson for the shift point.
- **Digital Speed Readout:** Massive Space Grotesk italic numbers accompanied by an absolute `KM/H` or `MPH` technical label pinned to the baseline.

### Car Stat Radar Charts

- Pentagonal or hexagonal SVG radars comparing Top Speed, Acceleration, Handling, Nitro Efficiency, and Braking.
- Outer perimeter rendered in 1px `#1F2637` wireframe; filled stat area rendered in 20% opacity `#00E5FF` with a glowing 1.5px `#00E5FF` stroke and electric volt vertices.

### Driver Class & Apex Badges

- **Apex Legend / S-Class Badges:** Parallelogram badges (`skewX(-15deg)`) featuring metallic gradient fills, framed by carbon trim and laser volt accents.
- Grade letters (D, C, B, A, S, APEX) rendered with extreme display weights and technical micro-subtext displaying worldwide percentile rank.

### Vehicle Selection & Tuning Cards

- Angled rectangular cards featuring car silhouettes breaking outward across the top-right border.
- Bottom panel contains tiered spec bars, PI (Performance Index) rating blocks (e.g., `S2 998`), and class color-coded tags.

### Sliders & Tuning Toggles

- Stepped linear track with segmented notches indicating suspension stiffness, gear ratios, and tire PSI.
- Slider thumb is a skewed neon trapezoid that leaves a glowing trail across the active region of the track.

Se ha ampliado el elemento.
