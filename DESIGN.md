---
name: Cody Butryn — The Estimate Packet
description: A contractor's carbonless estimate form, rendered as a website — printed rules and caps labels, typed fill-ins, one red stamp ink.
colors:
  desk: "#E9E4D8"
  paper: "#FBFAF5"
  paper-dim: "#F4F1E7"
  canary: "#F6E9C0"
  pink: "#F5DCD6"
  carbon: "#1E3A5F"
  carbon-deep: "#16304F"
  carbon-soft: "#42597A"
  rule: "#C9D0DC"
  rule-strong: "#8FA0B8"
  ink: "#23201B"
  stamp: "#A63325"
  overlay: "rgba(30,40,55,0.93)"
  print-page: "#FFFFFF"
typography:
  display:
    fontFamily: "Libre Franklin, Arial, sans-serif"
    fontSize: "clamp(1.6rem, 4.4vw, 2.6rem)"
    fontWeight: 900
    lineHeight: 1
    letterSpacing: "0.015em"
  headline:
    fontFamily: "Courier Prime, Courier New, monospace"
    fontSize: "clamp(1.5rem, 4vw, 2.35rem)"
    fontWeight: 700
    lineHeight: 1.22
    letterSpacing: "-0.01em"
  title:
    fontFamily: "Libre Franklin, Arial, sans-serif"
    fontSize: "clamp(1.05rem, 2.6vw, 1.45rem)"
    fontWeight: 800
    lineHeight: 1.2
    letterSpacing: "0.09em"
  subtitle:
    fontFamily: "Libre Franklin, Arial, sans-serif"
    fontSize: "1.12rem"
    fontWeight: 800
    lineHeight: 1.3
    letterSpacing: "0.02em"
  body:
    fontFamily: "Libre Franklin, Arial, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.65
    letterSpacing: "normal"
  typed:
    fontFamily: "Courier Prime, Courier New, monospace"
    fontSize: "0.88rem"
    fontWeight: 400
    lineHeight: 1.7
    letterSpacing: "normal"
  label:
    fontFamily: "Libre Franklin, Arial, sans-serif"
    fontSize: "0.72rem"
    fontWeight: 700
    lineHeight: 1.5
    letterSpacing: "0.15em"
  stamp:
    fontFamily: "Libre Franklin, Arial, sans-serif"
    fontSize: "0.78rem"
    fontWeight: 800
    lineHeight: 1.2
    letterSpacing: "0.12em"
rounded:
  none: "0"
  tab: "6px"
  stamp: "5px"
  badge: "3px"
  scroll: "7px"
spacing:
  tab-gap: "6px"
  grid-gap: "20px"
  card-gap: "22px"
  block: "1.6rem"
  section-y: "2.6rem"
  gutter: "clamp(1.1rem, 4vw, 3rem)"
components:
  button-fill:
    backgroundColor: "{colors.carbon}"
    textColor: "{colors.paper}"
    typography: "{typography.stamp}"
    rounded: "{rounded.none}"
    padding: "0.95rem 1.5rem"
  button-fill-hover:
    backgroundColor: "{colors.carbon-deep}"
    textColor: "{colors.paper}"
  button-line:
    backgroundColor: "transparent"
    textColor: "{colors.carbon}"
    typography: "{typography.stamp}"
    rounded: "{rounded.none}"
    padding: "0.95rem 1.5rem"
  button-line-hover:
    backgroundColor: "{colors.paper-dim}"
    textColor: "{colors.carbon}"
  button-fill-on-carbon:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.carbon}"
    typography: "{typography.stamp}"
    rounded: "{rounded.none}"
    padding: "0.9rem 1.4rem"
  button-fill-on-carbon-hover:
    backgroundColor: "{colors.canary}"
    textColor: "{colors.carbon}"
  tab:
    backgroundColor: "{colors.paper-dim}"
    textColor: "{colors.carbon}"
    typography: "{typography.label}"
    rounded: "{rounded.tab}"
    padding: "0.62rem 1.15rem 0.7rem"
  tab-current:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.carbon}"
    padding: "0.62rem 1.15rem 0.85rem"
  tab-action:
    backgroundColor: "{colors.carbon}"
    textColor: "{colors.paper}"
  filter-chip:
    backgroundColor: "{colors.paper-dim}"
    textColor: "{colors.carbon}"
    typography: "{typography.label}"
    rounded: "{rounded.tab}"
    padding: "0.55rem 1rem 0.62rem"
  filter-chip-on:
    backgroundColor: "{colors.carbon}"
    textColor: "{colors.paper}"
  stamp:
    backgroundColor: "transparent"
    textColor: "{colors.stamp}"
    typography: "{typography.stamp}"
    rounded: "{rounded.stamp}"
    padding: "0.32em 0.6em"
  sheet:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    padding: "0 {spacing.gutter}"
    width: "1060px"
  field-box:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    padding: "0.5rem 0.55rem"
    width: "172px"
  field-box-label:
    backgroundColor: "{colors.carbon}"
    textColor: "{colors.paper}"
    typography: "{typography.label}"
    padding: "0.3rem 0.55rem"
  kpi-tag:
    backgroundColor: "{colors.paper-dim}"
    textColor: "{colors.carbon}"
    typography: "{typography.stamp}"
    rounded: "{rounded.none}"
    padding: "0.32rem 0.55rem"
---

# Design System: Cody Butryn — The Estimate Packet

## Overview

**Creative North Star: "The Carbonless Estimate Packet"**

This is a website that behaves like paperwork a trade owner already signs weekly. A single warm sheet of paper sits on a slightly darker counter; on that sheet, everything the visitor needs is set as a *form*: a letterhead with numbered boxes, a scope-of-work table with line items and reference numbers, work orders with results and a PAID stamp, a triplicate copy set, and an acceptance block with a signature line. The persuasion is structural, not rhetorical — proof reads as line items and stamped totals rather than as hero copy and case-study scroll.

The system runs on a strict two-voice split that is the whole personality: **the form is printed, the answers are typed.** Anything pre-printed on the blank (labels, section bars, the letterhead name, buttons, box headers) is Libre Franklin in heavy weights, uppercase, wide-tracked, in carbon blue. Anything filled in for this particular customer (headline, results, contact, prose in the copies, résumé bullets) is Courier Prime in near-black ink. A reader can tell blank-form from fill-in at a glance without reading a word, and that legibility is the system's core asset.

Density is high and deliberately un-airy: hairline rules, double-rule section bars, small caps labels at 0.72rem, tables that stay tables. Depth is paper-thin — the sheet and the cards float on soft, warm, double-layer ambient shadows, never hard-offset ones. One color, the red stamp ink, carries every piece of state in the system (availability, PAID, job numbers, dates, sample badges) and is used nowhere else. The build refuses the designer-portfolio hero: no full-bleed image lede, no oversized centered statement type, no case-study scroll.

**Key Characteristics:**
- Warm paper-on-desk ground, never white-on-white
- Two faces, one job each: printed Franklin caps vs. typed Courier fill-ins
- Square corners everywhere except the folder tabs that name the metaphor
- One red ink for every state, used sparingly enough to stay loud
- Rules and boxes, not cards-with-radius; borders do the structural work
- Ambient warm shadows only; the sheet lifts, nothing else pops
- One authored motion moment (stamps pressing on), then stillness

## Colors

A carbonless form set: two warm papers, one desk, one carbon blue for everything printed, one near-black for everything typed, and a single red stamp ink reserved entirely for state.

### Primary
- **Carbon Blue** (`{colors.carbon}`): The printed-form ink. Every pre-printed element — section bars, letterhead name, field-box headers, tab labels, table captions, borders around results and totals, primary button fill, the inverted acceptance block — is this blue. It is the structural voice of the system.
- **Carbon Deep** (`{colors.carbon-deep}`): Hover state for filled carbon buttons and tabs only. It exists for one purpose and should never appear at rest.
- **Carbon Soft** (`{colors.carbon-soft}`): Secondary printed text — table column heads, sub-labels, role lines, the `h2` marginal note. Passes AA on paper; it is the quiet register of the printed voice, not a decorative tint.

### Secondary
- **Stamp Red** (`{colors.stamp}`): The one stamp ink. It appears on the TAKING NEW PROJECTS and PAID stamps, JOB № and ESTIMATE № references, résumé date ranges, the SAMPLE badge, and link-hover on site URLs. Nothing else in the system is red. Its rarity is what makes a stamp read as a stamp.

### Tertiary
- **Canary** (`{colors.canary}`): The customer's duplicate copy. Used as the second sheet in the triplicate set, as the highlighter swipe behind the headline's marked word, as text selection, as hover fill on the totals strip and filter tabs, and as the accent for bold text and button hover inside the carbon-blue block. It is the system's only "highlight" material.
- **Pink** (`{colors.pink}`): The file copy — the third sheet in the triplicate set. Reserved for that one structural role; it is a material of the form set, not a general accent.

### Neutral
- **Desk** (`{colors.desk}`): The counter the paperwork sits on. Page background, sticky nav background, and scrollbar track. Carries a very low-contrast fractal-noise SVG overlay so the ground reads as surface rather than as flat fill.
- **Paper** (`{colors.paper}`): The form sheet. The main container, cards, work orders, and the current folder tab.
- **Paper Dim** (`{colors.paper-dim}`): Shaded form regions — result boxes, the totals strip, résumé chips and KPI tags, inactive folder tabs, empty tray slots, gallery image wells. It signals "this region is pre-shaded on the blank."
- **Rule** (`{colors.rule}`): Hairline form rules — table row dividers, dotted résumé rows, image-well underlines.
- **Rule Strong** (`{colors.rule-strong}`): Heavier rules — sheet border, card borders, the bottom rule under section bars, underline color for links, scrollbar thumb.
- **Ink** (`{colors.ink}`): Typed-entry black-brown. All Courier Prime fill-ins, `h1`, results, and bolded body emphasis.

### Surface-only
- **Overlay** (`{colors.overlay}`): The lightbox scrim. The one cool, non-paper surface in the system, and the only place a neutral shadow is permitted.
- **Print Page** (`{colors.print-page}`): The résumé's printed page under `@media print`. The system's only pure white, and it exists because paper stock is the printer's job, not the stylesheet's.

### Named Rules

**The One Stamp Ink Rule.** Red is state, and state only: availability, PAID, and reference numbers. If a new element needs red for emphasis rather than for status, it does not get red — it gets a canary highlight or carbon weight.

**The Printed-vs-Typed Rule.** Carbon blue means the form printed it; ink black-brown means someone typed it in. Never set a filled-in value in carbon blue, and never set a pre-printed label in ink.

**The Warm Ground Rule.** No pure white and no pure black anywhere on screen. Paper is `{colors.paper}`, the ground is `{colors.desk}`, text is `{colors.ink}`. Pure `#fff` appears only in the résumé's print stylesheet, where the physical page supplies the paper.

## Typography

**Display / Print Font:** Libre Franklin (400–900, with Arial fallback)
**Typed / Fill-in Font:** Courier Prime (400/700 + italic, with Courier New fallback)

**Character:** Franklin in 700–900 uppercase with wide tracking is the pre-printed form: authoritative, compressed, bureaucratic in the good sense. Courier Prime is the typewriter that filled the form out: slightly irregular, human, and unmistakably "entered by hand." The pairing carries the entire metaphor; neither face may do the other's job.

### Hierarchy
- **Display** (Franklin 900, `clamp(1.6rem, 4.4vw, 2.6rem)`, line-height 1, tracking 0.015em, uppercase, carbon): The letterhead name. One per page, top-left. Gallery reuses the same treatment for its page title at `clamp(1.7rem, 4.6vw, 2.7rem)`.
- **Headline** (Courier Prime 700, `clamp(1.5rem, 4vw, 2.35rem)`, line-height 1.22, tracking -0.01em, ink, max 24ch): The typed job line on the estimate — the only place a fill-in is set at display scale. Capped at 24ch so it breaks like a typed entry, not a marketing hero.
- **Title** (Franklin 800, `clamp(1.05rem, 2.6vw, 1.45rem)`, tracking 0.09em, uppercase, carbon): Section bars. Always carries a 3px double top rule and a 1px bottom rule; the type and the rules are one component, never separated.
- **Subtitle** (Franklin 800, 0.92–1.12rem, tracking 0.02–0.04em, uppercase): Work-order names, copy-set headings, gallery card titles, résumé job titles.
- **Body** (Franklin 400, 1rem, line-height 1.65, carbon-soft, max 62ch): Printed explanatory prose — the sub-line under the headline, table descriptions, process copy.
- **Typed** (Courier Prime 400, 0.78–0.92rem, line-height 1.65–1.9): Every fill-in — contact lines, scope values, results, résumé bullets and profile, gallery tags, fine print. The default register for content the visitor is meant to read as *this customer's answer*.
- **Label** (Franklin 700, 0.72rem, tracking 0.14–0.16em, uppercase, carbon-soft or carbon): Field names, table column heads, box headers, tab text, signature captions. The workhorse of the printed voice.
- **Stamp** (Franklin 800, 0.72–0.95rem, tracking 0.12em, uppercase, stamp red): Stamps, badges, and buttons share this register — buttons are set in the same stamped voice as the rubber stamps, which is what makes the CTA feel like part of the form.

### Named Rules

**The Two-Face Rule.** There are two fonts and no third. New type needs are solved by moving between Franklin's weights (400/600/700/800/900) and Courier's two, not by adding a face.

**The Tabular Numbers Rule.** Every figure that reads as a total, a reference, a phone number, or a date carries `font-variant-numeric: tabular-nums` (the `.num` class). Numbers are the product here; they must line up.

**The Caps-Get-Tracking Rule.** Uppercase text is never set at default tracking. Labels take 0.14–0.16em, tabs and stamps 0.10–0.12em, section bars 0.09em, the display name 0.015em. Tracking falls as size rises.

## Layout

One centered sheet on a desk. The container is a max-width sheet (1060px on index and gallery, 1020px on the résumé) with a fluid gutter of `{spacing.gutter}` — the sheet is the page, and nothing but the sticky tab nav and the fine-print footer lives outside it.

Vertical rhythm is set by the section: `2.6rem` top / `2.2rem` bottom padding, opened by a double-rule section bar with `1.6rem` beneath it. Grids are simple and few — work orders at two columns (`22px` gap) with a single flagship spanning full width and splitting `1.25fr / 1fr`; the triplicate copy set at three equal columns; the gallery at three columns (`20px` gap); the résumé at `1.55fr / 1fr`. Folder tabs sit flush at `6px` gaps and align to the bottom edge so they read as file tabs entering the sheet.

Breakpoints are content-driven rather than device-driven: **920px** (gallery 3→2 columns), **820px** (work orders and résumé columns collapse to one), **720px** (letterhead stacks, totals strip 4→2 cells), **680px** (résumé letterhead stacks), **640px** (nav becomes an edge-to-edge horizontal scroller, the scope table drops its header row and becomes stacked rows, the availability stamp leaves its absolute corner and takes its own line), **560px** (gallery to one column). The mobile block on index is declared last in the stylesheet so it wins without `!important`.

Full-bleed inside the sheet is done by negative margin (`margin: 0 calc(gutter * -1)`), used only by the carbon-blue acceptance block. That inversion is the page's one full-width color event.

**The Print Is A Layout Rule.** On the résumé, print is a first-class breakpoint: navigation, the acceptance strip, the print button, and the fine print are hidden; the sheet drops its border, shadow, margin, max-width, and padding so the paper becomes the sheet; links lose underlines; jobs and skill groups get `break-inside: avoid`. The two-column grid collapses to one column in print via the existing **820px** breakpoint (a US Letter page measures under 820 CSS px), not via a print-specific override — so any change to that breakpoint changes the printed résumé. `print-color-adjust: exact` is set on `body` so carbon rules and stamp-red dates survive to paper.

## Elevation & Depth

The system is paper-flat with warm ambient lift. There are no hard-offset shadows, no glows, and no colored shadows: every shadow is a two-layer stack in warm near-black (`rgba(35,32,27, …)`) at low opacity, tuned to read as a sheet resting slightly above a counter. Depth ranking is: desk (no shadow) → sheet (highest lift) → filed cards (light lift) → inline boxes and stamps (no shadow at all, they are printed *on* the paper).

### Shadow Vocabulary
- **Sheet lift** (`box-shadow: 0 2px 5px rgba(35,32,27,0.12), 0 10px 22px rgba(35,32,27,0.14)`): The main sheet and the clipped screenshots. The strongest elevation in the system.
- **Filed card rest** (`box-shadow: 0 1px 3px rgba(35,32,27,0.09), 0 8px 18px rgba(35,32,27,0.07)`): Work orders, copy sheets, gallery cards.
- **Filed card lift** (`box-shadow: 0 3px 6px rgba(35,32,27,0.10), 0 16px 32px rgba(35,32,27,0.12)`, with `translateY(-3px)`): Fine-pointer hover only.
- **Nav hairline** (`box-shadow: 0 1px 0 rgba(35,32,27,0.08)`): The sticky tab bar's separation from the desk. A rule, not a shadow.
- **Lightbox plate** (`box-shadow: 0 20px 60px rgba(0,0,0,0.4)`): The enlarged image over the dimmed overlay; the only place a cool/neutral shadow is permitted, because the backdrop is not paper.

### Named Rules

**The Paper-Only Elevation Rule.** Only things that are sheets of paper cast shadows. Boxes, stamps, tags, chips, table rows, and buttons are printed on the paper and are flat forever.

**The Hover-Is-A-Fine-Pointer Rule.** Every lift, background shift, and color hover is wrapped in `@media (hover:hover) and (pointer:fine)`. Touch devices get the `:active` press (`scale(0.97)` on controls, `scale(0.99)` on cards) instead — no sticky hover states on phones, which is the primary device here.

## Shapes

Square by default. Borders — not radius, not fill — do the structural work: 1px `{colors.rule}` hairlines between table rows, 1px–1.5px `{colors.rule-strong}` around sheets and cards, 1.5px `{colors.carbon}` around anything that is a field or a result, and a 3px **double** rule beneath the letterhead and above every section bar. The double rule is the system's signature stroke and marks a division of the form.

Radius is used in exactly four places, each earning it: folder tabs (`{rounded.tab}`, applied to the top two corners only, which is what makes them tabs), stamps (`{rounded.stamp}`), gallery badges (`{rounded.badge}`), and the scrollbar thumb (`{rounded.scroll}`). Nothing else is rounded.

Two textures make the paper physical, both inline SVG filters with no raster cost: a fractal-noise tint over the desk, and a turbulence mask on stamps that eats ink coverage so the impression reads as rubber on paper. Slight rotations are the third physical device: the triplicate copies sit at −0.4°/+0.35°/−0.3°, screenshots at +0.7°, stamps at −6°/−8°. Rotation stays under 1° for sheets; only stamps rotate visibly.

### The Set

Every page is a **carbonless set**, not a single sheet. `.sheet` carries two pseudo-element underlays offset down-and-right — `::before` in `{colors.canary}` at 5px, `::after` in `{colors.pink}` at 10px — each with a 1px `{colors.rule-strong}` edge, sitting at `z-index:-1` so only the offset margin shows. The result is a visible stack: white on top, the customer's canary beneath it, the pink file copy deepest. This is what makes the site read as *paperwork* rather than as one styled page, and it is the single highest-leverage physical device in the system.

Below 640px the underlays collapse to a downward-only peek (`inset:0 0 -4px 0` and `0 0 -8px 0`), because a horizontal offset at that width pushes past the viewport edge. In `@media print` they are hidden outright — a printed page is one sheet.

**The Set Is Not Decoration Rule.** The canary and pink underlays are the same two stocks named in the triplicate process section. If a new surface is added, it inherits the set; a page rendered as a lone white sheet has left the world.

### Physical Devices

Four devices beyond texture and rotation, each earning its place by being something that happens to real forms:

- **Staple** (`.staple`): a 26px inline SVG at the sheet's top-left corner, in `{colors.rule-strong}`, with two faint legs implying the back of the set. Purely decorative, `pointer-events:none`, hidden in print.
- **Carbon misregistration**: `text-shadow: 1.5px 1.4px 0 rgba(30,58,95,0.17)` on the letterhead name — the second impression landing a hair off the first. Kept in carbon, never in stamp red, because red is state.
- **Perforation** (`.perf`): a 15px band of `{colors.desk}` circles punched through the paper on a 22px repeat, over a dashed `{colors.rule-strong}` top edge. It spans the full sheet width by negating the gutter padding.
- **Tear-off stub** (`.stub`): the detachable remittance slip below the perforation, repeating the estimate number, name, and both contact methods, with the primary action as its own button. It is the page's third and final call to action, and it exists because a real estimate ends with something you send back.

## Components

### Buttons
- **Shape:** Square (`{rounded.none}`), 1.5px border.
- **Primary (fill):** Carbon fill, paper text, `0.95rem 1.5rem`, set in the stamp register (Franklin 800, 0.78rem, 0.12em tracking, uppercase). This is the mailto CTA.
- **Secondary (line):** Transparent on a carbon 1.5px border, carbon text, same padding and type. Used for the tel: link beside the primary.
- **On carbon:** Inside the inverted acceptance block the pair inverts — fill becomes paper-on-carbon, line becomes paper border with transparent fill; fill hover goes canary, line hover goes `rgba(251,250,245,0.12)`.
- **Hover / Active:** Fill → `{colors.carbon-deep}`, line → `{colors.paper-dim}`, both at 150ms. `:active` presses to `scale(0.97)` at 120ms on all devices.

### Folder Tabs (navigation)
- **Style:** Bottom-aligned tabs with top-only radius, 1px `rule-strong` border with no bottom edge, offset `top: 1px` so they tuck under the sheet. Inactive tabs are `paper-dim`; the current page tab is `paper` with extra bottom padding so it visually merges with the sheet below.
- **Action tab:** Pushed right with `margin-left: auto`, carbon fill and paper text — a tab that is also the CTA.
- **Mobile:** Below 640px the bar goes edge-to-edge and becomes a horizontal scroller with hidden scrollbars, tighter padding and tracking; the owner's name is dropped from the first tab.

### Filter Chips (gallery)
- **Style:** The same tab silhouette used as a filter row, sitting on a 1.5px carbon rule — a drawer of tabs. Inactive `paper-dim`; hover fills canary.
- **State:** Active is carbon fill / paper text with a carbon border, mirrored in `aria-pressed`.

### Cards / Filed Sheets
- **Corner Style:** Square.
- **Background:** `{colors.paper}` (work orders, gallery cards); the copy set overrides to paper / canary / pink to show the triplicate.
- **Shadow Strategy:** Filed card rest, lifting to filed card lift on fine-pointer hover only.
- **Border:** 1px `{colors.rule-strong}`; empty tray slots use a 1.5px **dashed** border on `paper-dim` with no shadow, which is how the system says "this slot is honestly empty."
- **Internal Padding:** `1.15–1.25rem` on work orders, `0.8rem 0.95rem` on gallery meta.

### Field Boxes and Result Rows
- **Style:** A 1.5px carbon rectangle whose `dt` is a reversed carbon bar with paper caps label, and whose `dd` is the typed value at Courier 700. Used for ESTIMATE №/DATE in the letterhead (min-width 172px) and for the RESULT row inside each work order (on `paper-dim`, with the PAID stamp pushed to the right edge).

### Stamps (signature component)
Red 3px outline, 5px radius, uppercase Franklin 800, rotated −6° (availability) or −8° (PAID), with a turbulence SVG mask that erodes the ink. Stamps are visible by default; the `js` class on `<html>` (set inline in `<head>`) opts into the animation, so a JS failure leaves the stamps printed rather than invisible. An IntersectionObserver at `threshold: 0.6` adds `.in` on first sight and immediately unobserves — each stamp presses on exactly once, from `scale(1.25)` to `scale(1)` with opacity over 220ms on `cubic-bezier(0.23, 1, 0.32, 1)`. Under `prefers-reduced-motion: reduce` the scale is dropped and only a 180ms fade remains. Without IntersectionObserver support, all stamps are marked `in` immediately.

### The Scope Table
A real `<table>` with a caps caption on a 1.5px carbon rule, carbon-soft column heads, and typed cells on hairline row rules. Line-item names are carbon Courier 700; reference numbers are stamp-red links. Below 640px the header row is hidden and rows restack as blocks, keeping the row rule as the separator.

### The Totals Strip
Four equal cells inside a single 1.5px carbon frame, divided by `rule-strong` verticals, on `paper-dim`. Each cell is a link: a Courier 700 figure at `{typography.headline}` scale — `clamp(1.5rem, 3.1vw, 2.35rem)`, tracking `-0.03em` — over a caps caption with a stamp-red job reference. Hover fills the cell canary. At 720px it becomes 2×2 and the internal borders re-map.

**These figures are the page's display type.** The letterhead is set larger in weight but the totals are what the eye lands on, and that is correct for the world: on a real estimate the biggest number is the total. The system deliberately has no oversized statement headline — the `h1` sits in the fill-in face at `{typography.headline}` because it is a typed entry on a form, not a marketing lede. Anything that needs to shout in this system shouts as a number.

### The Terms Panel
The hero's right column, and the reason the first viewport is not half empty. A 1.5px carbon frame on `paper-dim` with a reversed carbon header bar (`{typography.label}`, paper text), three dotted-rule rows each led by a 14px authored checkmark SVG in carbon, and a footer row divided by a 1.5px carbon rule carrying a `PREPARED BY` label and the initials box. Collapses below the lede at 860px.

### The Initials Box
A 1.5px carbon square on `paper` holding `CB` in Franklin 800, rotated `-1.5°`. It is the system's only hand-annotation device, and the rotation is what sells it as applied rather than printed. Use it where a form would carry an approval mark; never as a logo.

### Signature Line (the CTA affordance)
A 1.5px ink bottom rule at `2.1rem` height with an inline SVG signature scrawl in carbon sitting on it, captioned by a caps label. On the acceptance block the rule and caption invert to paper and `#B7C4D6`. It is decorative-but-meaningful: it frames the mailto button as "signing."

### Inputs
There are no form inputs in the build. Everything that looks like a field is a printed value. If a real input is ever added, it should take the field-box treatment: 1.5px carbon rectangle, square corners, Courier value text, and the standard focus ring.

### Focus
A single global rule: `2px solid {colors.carbon}` outline at `2px` offset on `:focus-visible`, never removed and never restyled per component.

## Do's and Don'ts

### Do:
- **Do** set every new element in the printed-vs-typed split: Franklin caps for what the form printed, Courier for what was filled in.
- **Do** reserve `{colors.stamp}` for state and reference numbers, and keep it under a handful of appearances per screen.
- **Do** build structure from borders — 1px hairlines, 1.5px field rectangles, 3px double rules at divisions — rather than from radius or fill.
- **Do** put `.num` (tabular figures) on every total, phone number, date, and job reference.
- **Do** gate every hover behind `@media (hover:hover) and (pointer:fine)` and give touch a `scale(0.97)`/`scale(0.99)` press instead.
- **Do** keep motion to the one stamp impression: enter once, unobserve, and honor `prefers-reduced-motion` by dropping the scale.
- **Do** make new content degrade without JavaScript — the `js` class opt-in pattern means the default state must already be correct.
- **Do** treat the résumé's print output as a shipping surface: check any layout change at page width, since print inherits the 820px breakpoint.
- **Do** letterbox artwork inside the fixed 4:3 image well (`object-fit: contain` on a `paper-dim` ground) when its own lettering must survive, rather than varying card heights.

### Don't:
- **Don't** add a third typeface, or use a system display face. Franklin's five weights and Courier's two cover every need in this system.
- **Don't** use pure white or pure black on screen; the only `#fff` in the system is the print stylesheet's page.
- **Don't** apply hard offset shadows, glows, or colored shadows. Shadows are two-layer warm ambient stacks, and only paper sheets get them.
- **Don't** round corners on anything other than folder tabs, stamps, badges, and the scrollbar. Cards, boxes, and buttons stay square.
- **Don't** introduce decorative eyebrows or kickers above headings. Small caps text above a heading is permitted only when it is a real form field with a real value (`PREPARED FOR: …`, `SCOPE`, `RESULT`) — a label with nothing filled in is not a field, it is decoration.
- **Don't** use glyph or icon-font icons. The four icons in the build (external link, paperclip, signature, favicon wordmark) are inline SVG stroked in `currentColor`; new icons follow that.
- **Don't** hard-code hex values that a token already covers, and don't add new untokenized ink tints. Several body greys (`#3E3A32`, `#33302A`, `#5C564B`, `#5C6B80`) and the carbon hover (`#16304F`) drifted in as literals; new work uses `{colors.ink}`, `{colors.carbon-soft}`, or `{colors.carbon-deep}`.
- **Don't** let the token block drift between pages. There is no shared stylesheet (static site, no build step), so `:root` is duplicated verbatim in all three `<style>` heads — any token change must be applied to `index.html`, `gallery.html`, and `resume.html` in the same edit.
- **Don't** style with inline `style` attributes. A handful survive in the build; they are debt, not a pattern.
- **Don't** rotate sheets more than 1°. Only stamps rotate visibly (−6° / −8°).
- **Don't** reintroduce the designer-portfolio hero: no full-bleed image lede, no centered oversized statement type, no case-study scroll. Proof arrives as line items, totals, and stamps.
