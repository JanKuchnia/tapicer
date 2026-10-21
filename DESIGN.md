---
name: Marcin Nowak Atelier Rymarskie
description: Concours d'Elegance & Preservation Atelier for classic automotive interiors and master saddlery
colors:
  forest: "#091c16"
  forest-light: "#122a21"
  forest-dark: "#040e0b"
  cognac: "#9e4a1a"
  cognac-dark: "#77340e"
  cognac-soft: "#ba5921"
  champagne: "#c5a059"
  champagne-light: "#f3e8d2"
  canvas: "#f5f6f2"
  canvas-pure: "#ffffff"
  canvas-subtle: "#ecefe8"
  ink: "#0f1714"
  ink-muted: "#44524c"
  border-fine: "#dadfd6"
  border-dark: "rgba(197, 160, 89, 0.22)"
typography:
  display:
    fontFamily: "'Cormorant Garamond', Georgia, serif"
    fontSize: "clamp(2.5rem, 5vw, 3.75rem)"
    fontWeight: "400"
    lineHeight: "1.12"
    letterSpacing: "-0.01em"
  headline:
    fontFamily: "'Cormorant Garamond', Georgia, serif"
    fontSize: "clamp(1.75rem, 3vw, 2.25rem)"
    fontWeight: "600"
    lineHeight: "1.2"
    letterSpacing: "-0.01em"
  title:
    fontFamily: "'Cormorant Garamond', Georgia, serif"
    fontSize: "1.25rem"
    fontWeight: "600"
    lineHeight: "1.3"
    letterSpacing: "normal"
  body:
    fontFamily: "'Manrope', -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: "0.9375rem"
    fontWeight: "300"
    lineHeight: "1.6"
    letterSpacing: "normal"
  label:
    fontFamily: "'Manrope', -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: "0.75rem"
    fontWeight: "600"
    lineHeight: "1.4"
    letterSpacing: "0.08em"
rounded:
  sm: "4px"
  md: "8px"
  lg: "12px"
  full: "9999px"
spacing:
  xs: "4px"
  sm: "8px"
  md: "16px"
  lg: "24px"
  xl: "32px"
  2xl: "48px"
  3xl: "64px"
components:
  button-primary:
    backgroundColor: "{colors.champagne}"
    textColor: "{colors.forest}"
    rounded: "{rounded.sm}"
    padding: "14px 28px"
  button-primary-hover:
    backgroundColor: "{colors.champagne-light}"
  button-consultation:
    backgroundColor: "{colors.cognac}"
    textColor: "{colors.canvas-pure}"
    rounded: "{rounded.sm}"
    padding: "10px 20px"
  button-consultation-hover:
    backgroundColor: "{colors.cognac-dark}"
  button-outline:
    backgroundColor: "transparent"
    textColor: "{colors.canvas}"
    rounded: "{rounded.sm}"
    padding: "14px 24px"
  card-portfolio:
    backgroundColor: "{colors.canvas-pure}"
    rounded: "{rounded.md}"
    padding: "32px"
  card-ledger:
    backgroundColor: "{colors.canvas}"
    rounded: "{rounded.sm}"
    padding: "20px"
---

# Design System: Marcin Nowak Atelier Rymarskie

## Overview

**Creative North Star: "The Concours Preservation Atelier"**

The visual world of Marcin Nowak Atelier Rymarskie reflects an uncompromising standard of aristocratic craft, heritage preservation, and master saddlery dating back to 1998. Rather than adopting the loud, neon-lit visual conventions of modern commercial auto-detailing shops or generic franchised trimmers, this design system evokes the refined atmosphere of an elite coachbuilder's private restoration salon and bookbinder's archival workshop.

The visual architecture is structured around deliberate, high-contrast atmospheric shifts: deep British Racing Forest greens (`#091c16`) provide dignified gravity for the atelier brand, hero stages, and technical protocol ledgers, while warm Linen Canvas (`#f5f6f2`) creates an inviting, highly legible editorial canvas for detailed service dossiers, case studies, and customer correspondence. Metallic champagne gold foil (`#c5a059`) functions as an artisanal watermark, establishing hairline boundary rules, registry stamps, and subtle status markers without devolving into excessive ornament.

Interactive touchpoints prioritize the tactile weight of hand-tailored leathercraft. Primary call actions are imbued with rich Saddle Cognac leather gradients (`#9e4a1a` to `#77340e`), immediately identifying the phone consultation with master craftsman Marcin Nowak as the central relationship conduit of the workshop.

**Key Characteristics:**
- Deep heritage grounding via British Racing Forest Green and archival linen canvas.
- Classical, stately typography pairing: Cormorant Garamond display alongside legible Manrope technical body copy.
- Hairline gold foil framing (`rgba(197, 160, 89, 0.28)`) and radial micro-pattern grain.
- Tactile, dignified CTAs reflecting natural vegetable-tanned leather and saddler's wax.
- High editorial density with structured data strips, definition lists, and formal registry dossier numbering.

## Colors

The palette balances the deep nocturnal dignity of heritage automotive interiors with the tactile warmth of vegetable-tanned saddle leather and archival bookbinding paper.

### Primary
- **British Racing Forest Green** (`#091c16`): The authoritative foundation color of the atelier. Used for major hero backdrops, dark editorial bands, sticky navigation, and primary brand framing.
- **Saddle Cognac Leather** (`#9e4a1a`): The warm, tactile soul of the workshop. Used exclusively for telephone consultation badges, call-to-action buttons, and featured restoration highlights.

### Secondary
- **Champagne Gold Foil** (`#c5a059`): The refined artisanal accent. Applied to hairline borders, vintage seals, icons, and primary high-priority buttons (`#c5a059` text or background).
- **Light Champagne** (`#f3e8d2`): Subtle highlight tone for hover states and secondary micro-labels over dark surfaces.

### Neutral
- **Warm Linen Canvas** (`#f5f6f2`): The primary light surface background. Imparts an archival paper feel that prevents clinical sterile white glare.
- **Pure Canvas** (`#ffffff`): Reserved for elevated portfolio cards, project showcases, and illuminated content blocks.
- **Subtle Canvas** (`#ecefe8`): Hover and alternating row tint for ledger items.
- **Deep Ink** (`#0f1714`): The primary high-contrast text color on light canvas surfaces.
- **Muted Slate Ink** (`#44524c`): Secondary body text, captions, and metadata on light canvas.
- **Fine Divider** (`#dadfd6`): Crisp 1px structural dividing lines on light surfaces.
- **Dark Border Hairline** (`rgba(197, 160, 89, 0.22)`): The signature vintage hairline border on dark surfaces.

### Named Rules
**The Heritage Rarity Rule.** Champagne Gold Foil (`#c5a059`) is reserved for fine hairline borders, heraldic stamps, and key CTA accents. It must never coat expansive solid backdrops, preserving its metallic preciousness.

**The Cognac Tactile Rule.** Saddle Cognac gradients (`#9e4a1a` to `#77340e`) are strictly reserved for telephone consultation actions (`tel:+48605304999`) and material badge signifiers. They signify a direct line to the master craftsman.

## Typography

**Display Font:** Cormorant Garamond (with Georgia, serif fallback)
**Body Font:** Manrope (with -apple-system, BlinkMacSystemFont, sans-serif fallback)
**Icons:** Material Symbols Outlined

**Character:** A deliberate synthesis of Old-World aristocrat refinement and contemporary European technical clarity. Cormorant Garamond infuses vehicle marques, headlines, and numbers with the dignity of a concours d'elegance program, while Manrope ensures crisp, immediate scannability for vehicle specifications, addresses, and telephone digits.

### Hierarchy
- **Display** (weight 400, `clamp(2.5rem, 5vw, 3.75rem)`, line-height 1.12, letter-spacing -0.01em): Main hero headlines and signature historical introductions.
- **Headline** (weight 600, `clamp(1.75rem, 3vw, 2.25rem)`, line-height 1.2, letter-spacing -0.01em): Section titles, featured restoration project names.
- **Title** (weight 600, `1.25rem`, line-height 1.3): Discipline titles, card headings, and testimonial marques.
- **Body** (weight 300, `0.9375rem`, line-height 1.6, max line length 70ch): Paragraphs, service descriptions, historical dossiers, and rationale notes.
- **Label** (weight 600, `0.75rem`, letter-spacing 0.08em, uppercase): Eyebrows, registry numbers, technical specifications, and metadata tags.

### Named Rules
**The Master Artisan Rule.** Cormorant Garamond is reserved exclusively for editorial headlines, section titles, and project marques; Manrope handles all body text, technical specs, phone CTAs, and navigation for sharp, fatigue-free legibility.

**The Classical Numeral Rule.** Discipline numbering (e.g., "01", "02") and historical dates (e.g., "1998") are styled in Cormorant Garamond italic or bold to maintain atelier tradition.

## Layout

The spatial model employs an architectural grid grounded in a maximum width of 1400px (`max-w-[1400px] mx-auto`) with responsive gutter padding ranging from 24px (`px-6`) on mobile to 48px (`px-12`) on large displays.

- **Dossier Columns:** Hero and flagship project sections employ asymmetric 12-column grids (7-column narrative / 5-column photographic archive), framed with 1px borders rather than nested boxes.
- **Atelier Ledger:** Service disciplines are arranged in a 2-column ledger separated by clean hairline dividers (`divide-y divide-border-fine`), evoking an artisan's workshop register.
- **Technical Specs Strips:** 3-column definition strips separated by 1px vertical rules, providing immediate technical clarity (method, provenance, turnaround).
- **Responsive Navigation:** A 96px (`h-24`) sticky header featuring a persistent telephone consultation CTA on desktop, supported by a 36px top concours announcement ribbon with live hours and workshop location.

## Elevation & Depth

The design system operates on a philosophy of **Layered Surface & Hairline Boundaries**. Depth is achieved through material contrast between rich dark surfaces and warm canvas grounds, punctuated by 1px hairline rules, rather than through heavy, diffused drop shadows.

### Shadow Vocabulary
- **Subtle Surface Lift** (`box-shadow: 0 1px 3px rgba(0, 0, 0, 0.05)`): Applied to white portfolio cards resting on warm canvas.
- **Interactive Button Elevation** (`box-shadow: 0 4px 12px rgba(158, 74, 26, 0.25)`): Applied to Saddle Cognac consultation buttons on hover.
- **Sticky Saloon Shadow** (`box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.3)`): Grounds the sticky navigation bar over scrolling canvas content.

### Named Rules
**The Hairline Depth Rule.** Depth is established through 1px gold and fine linen dividers rather than blurred drop shadows. Surfaces feel like physical leather skins and parchment boards laid upon a craftsman's cutting table.

**The Radial Grain Rule.** Deep Forest surfaces incorporate a subtle radial micro-dot racing pattern (`racing-pattern`, 24px grid at 8% opacity) to provide tactile tooth without visual noise.

## Shapes

The form language is restrained and architectural:
- **Corner Radii:** Strictly limited to `4px` (`rounded`) for buttons, badges, and input elements, and `8px` (`rounded-lg`) for major container cards. Pill shapes (`rounded-full`) are reserved strictly for status indicators and micro-avatars.
- **Borders:** Characteristic `vintage-border` (`border: 1px solid rgba(197, 160, 89, 0.28)`) encasing photographs and flagship dossier frames.
- **Separators:** 1px hairline borders (`border-b border-champagne/20` on dark; `border-b border-border-fine` on light).

## Components

### Buttons
- **Primary Champagne Action:** Solid champagne gold background (`#c5a059`), deep forest text (`#091c16`), 4px radius (`rounded`), padding `14px 28px`. Hover lifts brightness to champagne-light (`#f3e8d2`).
- **Consultation Master Button:** Gradient from Saddle Cognac (`#9e4a1a`) to Cognac Dark (`#77340e`), white text, champagne icon, padding `10px 20px`, 4px radius. Features two-line typographic hierarchy (micro-eyebrow + phone number).
- **Atelier Outline Button:** Transparent background, 1px border (`rgba(197, 160, 89, 0.4)`), linen text, padding `14px 24px`, 4px radius. Hover triggers `rgba(197, 160, 89, 0.1)` wash.

### Badges & Registry Seals
- **Historic Registry Seal:** Dark forest backdrop (`#040e0b` at 95% opacity), 1px champagne border, gold foil icon (`workspace_premium`), two-line stacked typography ("Tradycja 1998", "Krzyszkowice").
- **Dossier Number Badge:** Deep forest box, 1px champagne border, champagne monospace tracking (`Dossier Konkursowe № 01/CAD`).

### Cards & Containers
- **Flagship Concours Card:** Asymmetric 12-column card split between full-height photographic plate (left) and technical ledger (right). 8px radius, fine border (`#dadfd6`), pure white background.
- **Discipline Ledger Item:** Clean horizontal row with bold Cormorant numeral ("01"), discipline title, material description, and hover highlight (`#ecefe8` at 50%).
- **Project Grid Card:** 8px radius, pure white background, 1px fine border, 288px photograph with floating spec overlay badge.

### Navigation
- **Grand Atelier Header:** Sticky 96px header in British Racing Forest (`#091c16` at 95% with `backdrop-blur-md`), 1px champagne bottom border, heraldic logo mark, Manrope navigation links with champagne hover transitions, and dedicated phone consultation CTA.

## Do's and Don'ts

### Do:
- **Do** format all telephone links with `tel:+48605304999` and display operating hours (Pn–Pt 08:00–17:00).
- **Do** pair Cormorant Garamond for titles with Manrope for body text to maintain artisan-technical balance.
- **Do** use 1px hairline borders (`border-champagne/25` or `border-border-fine`) for structural divisions.
- **Do** use authentic Polish craftsmanship terminology (*rymarstwo, ścieg francuski, skóra juchtowa, Nappa, renowacja zabytków*).
- **Do** maintain the 4px / 8px restrained corner radius across all components.

### Don'ts:
- **Don't** use neon, electric greens, or commercial saturated blues; adhere strictly to Forest, Cognac, Champagne, and Linen.
- **Don't** use generic commercial claims like "najtaniej", "błyskawicznie", or "zawsze na czas".
- **Don't** apply large, heavy, blurred box shadows; maintain flat, layered architectural boundaries.
- **Don't** use Cormorant Garamond for long paragraphs or small UI labels.
- **Don't** add arbitrary border-radius values (e.g. 16px, 24px, or 32px pill cards); keep corners tailored and crisp.
