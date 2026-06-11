---
name: grafiflex-brand
description: "Grafiflex and FlexoLab brand identity guidelines. Use this skill whenever doing ANY design, styling, UI, branding, or visual work for Grafiflex or FlexoLab — including creating documents, presentations, social media posts, emails, UI components, mockups, or any visual asset. Also trigger when the user asks about brand colors, fonts, logo usage, tone of voice, or visual identity. If the user mentions 'brand', 'colores', 'logo', 'tipografía', 'diseño', 'estilo visual', 'guidelines', or is creating any visual deliverable for Grafiflex, use this skill."
---

# Grafiflex & FlexoLab Brand Guidelines

## Brand Overview

**Grafiflex** is Colombia's #1 flexographic prepress company (30 years). The brand identity reflects precision, technological innovation, and color mastery.

**FlexoLab** is Grafiflex's internal operations platform (React-admin v5, MUI v7). It inherits from Grafiflex but has its own character: more technical, more functional, more data-driven.

**Taglines:**
- Grafiflex: "Pasión por tu Mejor Impresión"
- FlexoLab: "Where we measure, test, and perfect."

## Brand Ecosystem

| Brand | Purpose | Audience |
|-------|---------|----------|
| Grafiflex | Corporate brand. Flexographic prepress. | Clients, industry, general public |
| FlexoLab | Internal operations platform | Internal team, clients (approval portal) |
| Grafiflex 30 Años | Commemorative mark (2025–2026) | All audiences |

---

## Color System

The brand aesthetic is **predominantly monochromatic** — grays and blacks that convey precision — with **subtle CMYK and CMYKOGV color accents** that reveal the brand's essence.

### The 90/10 Rule
90% of any interface/design should be neutrals (grays, black, white). Only 10% should be CMYK color accents.

### Neutral Palette (Primary)

| Name | HEX | Use |
|------|-----|-----|
| Black | `#1A1A1A` | Primary text, backgrounds, sidebar |
| Dark Gray | `#2D2D2D` | Secondary backgrounds, cards on dark |
| Medium Gray | `#666666` | Secondary text, icons default |
| Gray | `#999999` | Placeholder text, subtle labels |
| Light Gray | `#CCCCCC` | Borders, dividers |
| Lighter Gray | `#E8E8E8` | Subtle borders, table lines |
| Off White | `#F5F5F5` | Page background |
| White | `#FFFFFF` | Cards, content areas |

### CMYK Accents

| Name | HEX | Role |
|------|-----|------|
| **Cyan** | `#00AEEF` | **Primary accent.** Links, buttons, active states, selections, the "i" dot in logo |
| Magenta | `#EC008C` | Errors, critical alerts (use instead of red) |
| Yellow | `#FFF200` | Caution — low contrast, use only on dark backgrounds or as tiny accent |
| Key (Black) | `#1A1A1A` | Part of CMYK identity |

### Extended Gamut — OGV (Functional States)

| Name | HEX | Role |
|------|-----|------|
| Orange | `#F47920` | Warnings, "in progress" states |
| Green | `#00A651` | Success, approved |
| Violet | `#662D91` | Special, premium, highlighted |

### Color Rules
- **Cyan is the primary action color** — use for links, primary buttons, active states, selections
- **Magenta for errors** (not red) — it's part of the CMYK identity
- **Yellow with caution** — low contrast, only on dark backgrounds
- **OGV for functional states** — Green=success, Orange=warning, Violet=special
- **CMYKOGV line** — a thin gradient line (C→M→Y→K→O→G→V) used as decorative separator in headers/footers

### CSS Variables
```css
:root {
  --cyan: #00AEEF;
  --magenta: #EC008C;
  --yellow: #FFF200;
  --orange: #F47920;
  --green: #00A651;
  --violet: #662D91;
  --black: #1A1A1A;
  --dark-gray: #2D2D2D;
  --medium-gray: #666666;
  --gray: #999999;
  --light-gray: #CCCCCC;
  --lighter-gray: #E8E8E8;
  --off-white: #F5F5F5;
  --white: #FFFFFF;
  --success: #00A651;
  --warning: #F47920;
  --error: #EC008C;
  --info: #00AEEF;
}
```

---

## Typography

| Role | Font | Notes |
|------|------|-------|
| Logo only | **Rustica Bold Italic** | Proprietary to logo. Never use elsewhere. |
| UI & Body | **Inter** | All weights 300–800. Primary typeface for everything. |
| Data & Code | **JetBrains Mono** | Order codes, measurements, ΔE values, colorimetric data, technical specs |

### Type Scale (Inter)

| Level | Size | Weight | Use |
|-------|------|--------|-----|
| Display | 48px | 800 (ExtraBold) | Hero headlines, landing pages |
| H1 | 36px | 700 (Bold) | Page titles |
| H2 | 24px | 600 (Semibold) | Section headers |
| H3 | 18px | 600 (Semibold) | Subsections |
| Body | 14px | 400 (Regular) | Default text |
| Caption | 12px | 500 (Medium) | Labels, metadata |

### Monospace Usage (JetBrains Mono)
Use for: order numbers (`GF-2026-0418`), ΔE values, L*a*b* coordinates, LPI, dot gain percentages, any measurement or technical data.

---

## Logo

### Structure
- **Symbol:** Three interlocking geometric pieces forming an abstract "G" and triangle. Each piece = one process color: Yellow (top), Magenta (left), Cyan (right). Includes metallic reflections for 3D depth.
- **Wordmark:** "Grafiflex" in Rustica Bold Italic. The dot over the "i" is a **Cyan circle** — a distinctive, non-negotiable brand element.
- **® mark:** Positioned after the "x" at baseline level.

### Variants
- Horizontal (dark background): white text, CMY symbol
- Horizontal (light background): dark text (#1A1A1A), CMY symbol
- Vertical: symbol above wordmark
- Symbol only: for favicons, avatars, small applications

### Logo Rules
- Never alter colors, stretch, rotate, or distort
- Never use on busy/competing-color backgrounds
- Never reduce below minimum size (120px / 30mm horizontal, 24px / 8mm symbol only)
- Maintain clear space around logo

### FlexoLab Logo

**Symbol:** Geometric diamond/rhombus shape with interlocking angular **F** (left, structural) and **L** (right, dynamic) shapes. The cyan (L) portion features **halftone dots** — a direct reference to flexographic screening technology.

**Wordmark:** "FlexoLab" in **Rustica Bold Italic** (same font family as Grafiflex). "Lab" is mixed case (not "LAB"). The italic gives it the same dynamic energy as the Grafiflex wordmark, reinforcing sub-brand unity.

**Color:**
- F shape: Black `#1A1A1A` (positive) or White `#FFFFFF` (negative)
- L shape: Always Cyan `#00AEEF`
- Halftone dots on cyan portion: same color as the F shape

**Variants:**
- `flexolab-symbol-light.svg` — Black F + Cyan L (for light/white backgrounds)
- `flexolab-symbol-dark.svg` — White F + Cyan L (for dark backgrounds)
- `flexolab-lockup-horizontal-light.svg` / `-dark.svg` — Symbol + wordmark, horizontal
- `flexolab-lockup-vertical-light.svg` / `-dark.svg` — Symbol above wordmark, vertical

**Lockup geometry:** Gap between symbol and wordmark is **15% of the symbol's visual width** (both orientations).

**Rules:**
- The halftone dot pattern must never be removed or simplified
- The F and L interlock must remain intact — never separate the shapes
- Cyan on the L shape is non-negotiable (matches the Grafiflex "i" dot accent)
- Minimum size: 120px / 30mm (horizontal lockup), 24px / 8mm (symbol only)

### FlexoLab Name Format
| Context | Format |
|---------|--------|
| Logo/Display | **FlexoLab** (camelCase, F and L capitalized) |
| URL | `flexolab.grafiflex.com` |
| Running text | FlexoLab (always both capitals) |
| With parent brand | "Grafiflex FlexoLab" or "Powered by Grafiflex FlexoLab" |

---

## Spacing & Grid

Based on **4px multiples**:

| Token | Size |
|-------|------|
| xs | 4px |
| sm | 8px |
| md | 12px |
| base | 16px |
| lg | 24px |
| xl | 32px |
| 2xl | 48px |
| 3xl | 64px |
| 4xl | 80px |

### Border Radius
| Size | Use |
|------|-----|
| 4px | Small buttons |
| 8px | Buttons, inputs |
| 12px | Cards |
| 16px | Modals |
| 50% | Avatars, dots |

---

## Voice & Tone

### We are:
- Technical with clarity
- Direct and concise
- Passionate about quality
- Innovative but practical
- Collaborative with clients

### We are NOT:
- Excessively corporate
- Vague or ambiguous
- Unnecessarily complicated
- Distant or cold
- Aggressive salespeople

### Language
- UI is in **Spanish** (Colombian)
- Technical terms from flexography can remain in English when standard (ΔE, LPI, dot gain, gamut)
- FlexoLab tagline is in English ("Where we measure, test, and perfect.")

---

## Iconography

| Property | Value |
|----------|-------|
| Style | Line icons (stroke), rounded corners |
| Stroke width | 1.5px |
| Sizes | 16px, 20px, 24px |
| Default color | `#666666` (Medium Gray) |
| Active color | `#00AEEF` (Cyan) |
| Library | Lucide Icons (preferred) or Phosphor Icons |

---

## Patterns & Textures

- **Halftone dots:** Reference to flexographic screening. Use at low opacity as background texture.
- **CMYKOGV line:** Thin gradient stripe as decorative separator in headers, footers, section divisions.
- **Registration marks:** Stylized as subtle decorative elements.

---

## Photography

- **Treatment:** High contrast, slightly desaturated. Color should come from the printed product, not the environment.
- **Subjects:** Close-ups of plates, color proofs, densitometer measurements, machinery in action.
- **Avoid:** Generic office stock photos. Over-saturated images. Low-resolution or noisy photos.

---

## FlexoLab UI (MUI v7 Theme Tokens)

| Token | Value | Use |
|-------|-------|-----|
| `palette.primary` | `#00AEEF` Cyan | Buttons, links, selections, active indicators |
| `palette.secondary` | `#1A1A1A` Black | Secondary buttons, sidebar |
| `palette.error` | `#EC008C` Magenta | Error states |
| `palette.warning` | `#F47920` Orange | Warning states |
| `palette.success` | `#00A651` Green | Success states |
| `palette.info` | `#00AEEF` Cyan | Info states |
| `palette.background.default` | `#F5F5F5` | Page background |
| `palette.background.paper` | `#FFFFFF` | Cards, surfaces |
| Sidebar background | `#1A1A1A` | Dark sidebar |
| Active nav indicator | 2px left border in Cyan | Current page |

### FlexoLab UI Patterns
- Sidebar: dark (#1A1A1A) with gray text, active item has cyan left border
- Tables: white background, lighter-gray borders, mono font for codes/data
- Status tags: colored pills using OGV palette (Green=approved, Orange=in process, Magenta=review needed)
- Order codes: displayed in JetBrains Mono, colored cyan

---

## Documents & Presentations

- Use dark backgrounds (preferred) or clean white
- CMYKOGV accent line as header/footer decoration
- Inter for all text
- JetBrains Mono for data/specs
- Logo with appropriate variant for background
- Minimal use of color — let neutrals dominate

---

## Social Media

- Profile picture: Symbol only (CMY triangle)
- Cover/banner: Dark background with CMYKOGV line accent
- Posts: High-contrast imagery, minimal text, brand colors as accents only
- Hashtags: #Grafiflex #FlexoLab #Flexografía #PreprensaDigital

---

## Brand Assets Location

Logo files and brand assets are stored in: `grafiflex-brand/` (sibling to `grafiflex-interactivo/`)

Key files:
- `logo-horizontal-dark-r7.svg` — Horizontal, white text (for dark backgrounds)
- `logo-horizontal-light-r7.svg` — Horizontal, dark text (for light backgrounds)
- `logo-vertical-dark-v4.svg` — Vertical, white text
- `logo-vertical-light-r2.svg` — Vertical, dark text
- `logo-symbol.svg` — Grafiflex symbol only (CMY triangle)
- `flexolab-symbol-light.svg` — FlexoLab symbol (black F + cyan L, for light backgrounds)
- `flexolab-symbol-dark.svg` — FlexoLab symbol (white F + cyan L, for dark backgrounds)
- `flexolab-lockup-horizontal-{light,dark}.svg` — FlexoLab full lockup, horizontal
- `flexolab-lockup-vertical-{light,dark}.svg` — FlexoLab full lockup, vertical
- `logo-30-*.png` — 30th anniversary variants
- `grafiflex-brand-guidelines.html` — Full interactive guidelines reference
