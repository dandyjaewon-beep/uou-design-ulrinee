---
version: alpha
name: University of Ulsan — Ulrinee Edition (울산대학교 · 울리니 에디션)
description: A heritage-grounded academic design language anchored by **UOU Green** (DIC 643) — the deep forest green that has signaled the University of Ulsan since its CIS was formalized. **This document is a design grammar (colors, typography, spacing, and content-area component patterns) intended to be applied to NEW content pages and applications. It is NOT a recipe for cloning the official University of Ulsan website shell** — there is no global-nav, no signature-lockup, no language-toggle, no sitemap-link, and no footer component documented here. Builders should NOT auto-render any "ulsan.ac.kr-style" top bar, breadcrumb, or footer chrome unless the user explicitly asks for the official site shell. UOU Green dominates content surfaces; UOU Gray and UOU Yellow appear only as supporting accents (Yellow specifically reserved for emphasis moments such as event banners or "신규(NEW)" badges). **Ulrinee Edition:** the official UOU mascot **울리니 (Ulrinee)** is the friendly logo mark (`assets/ulrinee/`, always used unmodified), its official character palette is added as a secondary set reserved for mascot moments, and typography switches to the free, open-licensed **주아 (Jua)** typeface (SIL OFL 1.1, via Google Fonts) with Pretendard / Noto Sans KR / Malgun Gothic as fallbacks — round, friendly, and legible for Korean + English. The institutional 윤고딕 (YoonGothic) font files are intentionally NOT included in this public repository.

colors:
  primary: "#006B3C"
  primary-deep: "#004D2B"
  primary-light: "#2E8B57"
  secondary-gray: "#58595B"
  secondary-gray-light: "#9EA0A2"
  accent-yellow: "#F2A900"
  accent-yellow-soft: "#FFD966"
  ink: "#1A1A1A"
  ink-muted-80: "#333333"
  ink-muted-60: "#666666"
  ink-muted-40: "#999999"
  body: "#222222"
  body-on-dark: "#FFFFFF"
  body-muted-on-dark: "#D0D0D0"
  hairline: "#E5E5E5"
  divider-soft: "#F0F0F0"
  canvas: "#FFFFFF"
  canvas-warm: "#F7F7F5"
  surface-pearl: "#FAFAFA"
  surface-section-dark: "#004D2B"
  surface-footer: "#1A1A1A"
  surface-footer-deep: "#0D0D0D"
  status-new: "#E63946"
  status-info: "#0066B2"
  on-primary: "#FFFFFF"
  on-dark: "#FFFFFF"
  link-on-light: "#006B3C"
  link-hover: "#004D2B"
  focus-ring: "#F2A900"
  ulrinee-leaf: "#B9D887"
  ulrinee-sprout: "#99C45C"
  ulrinee-cream: "#F9E79B"
  ulrinee-moss: "#76A854"
  ulrinee-line: "#2C3D28"
  ulrinee-blush: "#EDBE7F"
  ulrinee-mouth: "#F08C8C"

typography:
  hero-display:
    fontFamily: "Jua, Pretendard, 'Noto Sans KR', 'Malgun Gothic', -apple-system, sans-serif"
    fontSize: 52px
    fontWeight: 400
    lineHeight: 1.2
    letterSpacing: -1.04px
  display-lg:
    fontFamily: "Jua, Pretendard, 'Noto Sans KR', 'Malgun Gothic', sans-serif"
    fontSize: 40px
    fontWeight: 400
    lineHeight: 1.25
    letterSpacing: -0.8px
  display-md:
    fontFamily: "Jua, Pretendard, 'Noto Sans KR', 'Malgun Gothic', sans-serif"
    fontSize: 32px
    fontWeight: 400
    lineHeight: 1.3
    letterSpacing: -0.64px
  section-title:
    fontFamily: "Jua, Pretendard, 'Noto Sans KR', 'Malgun Gothic', sans-serif"
    fontSize: 28px
    fontWeight: 400
    lineHeight: 1.35
    letterSpacing: -0.56px
  heading-lg:
    fontFamily: "Jua, Pretendard, 'Noto Sans KR', 'Malgun Gothic', sans-serif"
    fontSize: 22px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: -0.44px
  heading-md:
    fontFamily: "Jua, Pretendard, 'Noto Sans KR', 'Malgun Gothic', sans-serif"
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: -0.36px
  lead:
    fontFamily: "Jua, Pretendard, 'Noto Sans KR', 'Malgun Gothic', sans-serif"
    fontSize: 20px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: -0.4px
  body-lg:
    fontFamily: "Jua, Pretendard, 'Noto Sans KR', 'Malgun Gothic', sans-serif"
    fontSize: 17px
    fontWeight: 400
    lineHeight: 1.65
    letterSpacing: -0.34px
  body:
    fontFamily: "Jua, Pretendard, 'Noto Sans KR', 'Malgun Gothic', sans-serif"
    fontSize: 15px
    fontWeight: 400
    lineHeight: 1.7
    letterSpacing: -0.3px
  body-strong:
    fontFamily: "Jua, Pretendard, 'Noto Sans KR', 'Malgun Gothic', sans-serif"
    fontSize: 15px
    fontWeight: 400
    lineHeight: 1.7
    letterSpacing: -0.3px
  caption:
    fontFamily: "Jua, Pretendard, 'Noto Sans KR', 'Malgun Gothic', sans-serif"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: -0.26px
  caption-strong:
    fontFamily: "Jua, Pretendard, 'Noto Sans KR', 'Malgun Gothic', sans-serif"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: -0.26px
  fine-print:
    fontFamily: "Jua, Pretendard, 'Noto Sans KR', 'Malgun Gothic', sans-serif"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: -0.24px
  micro-legal:
    fontFamily: "Jua, Pretendard, 'Noto Sans KR', 'Malgun Gothic', sans-serif"
    fontSize: 11px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: -0.22px
  nav-primary:
    fontFamily: "Jua, Pretendard, 'Noto Sans KR', 'Malgun Gothic', sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.0
    letterSpacing: -0.32px
  nav-utility:
    fontFamily: "Jua, Pretendard, 'Noto Sans KR', 'Malgun Gothic', sans-serif"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.0
    letterSpacing: -0.13px
  button-label:
    fontFamily: "Jua, Pretendard, 'Noto Sans KR', 'Malgun Gothic', sans-serif"
    fontSize: 15px
    fontWeight: 400
    lineHeight: 1.0
    letterSpacing: -0.3px
  badge-label:
    fontFamily: "Jua, Pretendard, 'Noto Sans KR', 'Malgun Gothic', sans-serif"
    fontSize: 11px
    fontWeight: 400
    lineHeight: 1.0
    letterSpacing: 0px

rounded:
  none: 0px
  xs: 2px
  sm: 4px
  md: 8px
  lg: 12px
  xl: 20px
  pill: 9999px
  full: 9999px

spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  xxxl: 64px
  section: 96px
  hero: 120px

shadows:
  none: "none"
  card-soft: "0 2px 8px rgba(0, 0, 0, 0.06)"
  card-hover: "0 6px 20px rgba(0, 0, 0, 0.10)"
  nav-fixed: "0 1px 4px rgba(0, 0, 0, 0.08)"
  modal: "0 12px 40px rgba(0, 0, 0, 0.18)"

components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button-label}"
    rounded: "{rounded.sm}"
    padding: 12px 24px
  button-primary-active:
    backgroundColor: "{colors.primary-deep}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.sm}"
  button-outline:
    backgroundColor: "transparent"
    textColor: "{colors.primary}"
    typography: "{typography.button-label}"
    rounded: "{rounded.sm}"
    padding: 12px 24px
    border: "1px solid {colors.primary}"
  button-outline-on-dark:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    typography: "{typography.button-label}"
    rounded: "{rounded.sm}"
    padding: 12px 24px
    border: "1px solid {colors.on-dark}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.ink-muted-80}"
    typography: "{typography.button-label}"
    rounded: "{rounded.sm}"
    padding: 10px 16px
  button-icon-square:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    rounded: "{rounded.sm}"
    size: 44px
    border: "1px solid {colors.hairline}"
  text-link:
    backgroundColor: "transparent"
    textColor: "{colors.link-on-light}"
    typography: "{typography.body}"
  text-link-on-dark:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    typography: "{typography.body}"
  hero-band:
    backgroundColor: "{colors.surface-section-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.hero-display}"
    rounded: "{rounded.none}"
    padding: 120px 64px
  hero-photographic:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.on-dark}"
    typography: "{typography.hero-display}"
    rounded: "{rounded.none}"
    padding: 120px 64px
  section-band-light:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.section-title}"
    rounded: "{rounded.none}"
    padding: 96px 64px
  section-band-warm:
    backgroundColor: "{colors.canvas-warm}"
    textColor: "{colors.ink}"
    typography: "{typography.section-title}"
    rounded: "{rounded.none}"
    padding: 96px 64px
  section-band-dark:
    backgroundColor: "{colors.surface-section-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.section-title}"
    rounded: "{rounded.none}"
    padding: 96px 64px
  notice-card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.heading-md}"
    rounded: "{rounded.md}"
    padding: 24px
    border: "1px solid {colors.hairline}"
    shadow: "{shadows.none}"
  notice-card-hover:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
    shadow: "{shadows.card-hover}"
  notice-card-featured:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-dark}"
    typography: "{typography.heading-md}"
    rounded: "{rounded.md}"
    padding: 24px
  news-tile:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.heading-md}"
    rounded: "{rounded.md}"
    padding: 0
    border: "1px solid {colors.hairline}"
  quick-link-card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-strong}"
    rounded: "{rounded.md}"
    padding: 24px
    border: "1px solid {colors.hairline}"
  quick-link-card-active:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.md}"
  badge-new:
    backgroundColor: "{colors.status-new}"
    textColor: "{colors.on-dark}"
    typography: "{typography.badge-label}"
    rounded: "{rounded.xs}"
    padding: 3px 6px
  badge-yellow:
    backgroundColor: "{colors.accent-yellow}"
    textColor: "{colors.ink}"
    typography: "{typography.badge-label}"
    rounded: "{rounded.xs}"
    padding: 3px 6px
  badge-category:
    backgroundColor: "transparent"
    textColor: "{colors.primary}"
    typography: "{typography.caption-strong}"
    rounded: "{rounded.xs}"
    padding: 2px 6px
    border: "1px solid {colors.primary}"
  search-input:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.sm}"
    padding: 12px 16px
    height: 44px
    border: "1px solid {colors.hairline}"
  tab-active:
    backgroundColor: "transparent"
    textColor: "{colors.primary}"
    typography: "{typography.heading-md}"
    border-bottom: "2px solid {colors.primary}"
    padding: 12px 16px
  tab-inactive:
    backgroundColor: "transparent"
    textColor: "{colors.ink-muted-60}"
    typography: "{typography.heading-md}"
    padding: 12px 16px
  ulrinee-logo:
    image: "assets/ulrinee/ulrinee-main.png"
    height: 56px
    minHeight: 40px
    clearSpace: "25% of logo height"
    backgroundColor: "{colors.canvas}"
  ulrinee-callout:
    backgroundColor: "{colors.ulrinee-cream}"
    textColor: "{colors.ulrinee-line}"
    typography: "{typography.body-lg}"
    rounded: "{rounded.lg}"
    padding: 24px
  badge-ulrinee:
    backgroundColor: "{colors.ulrinee-leaf}"
    textColor: "{colors.ulrinee-line}"
    typography: "{typography.badge-label}"
    rounded: "{rounded.xs}"
    padding: 3px 6px
---

## Overview

> ### ⚠️ Scope of this design system
>
> **This is a design grammar, not a website clone.** Apply the colors, typography, spacing, and content-area components below to your own content pages, internal tools, research pages, presentations, or applications.
>
> **Do NOT auto-render any of the following unless the user explicitly asks for the official ulsan.ac.kr site shell:**
> - Global top navigation bar (the row with 대학소개 / 대학·대학원 / 입학 / 학사 / 산학협력 / 연구 / 캠퍼스 라이프)
> - Utility row (로그인 / ENG / 中文 / Sitemap / Family Sites)
> - Institutional signature lockup (Girin symbol + "울산대학교 / UNIVERSITY OF ULSAN" wordmark)
> - Breadcrumb trail (홈 > 대학소개 > …)
> - Site footer with address/contact/copyright
>
> Those elements belong to the operational ulsan.ac.kr website and are intentionally NOT documented as components in this file. If a builder needs them for an official sub-site, they should be sourced from the university's CIS/web team — not generated from this design grammar.
>
> **What this system IS for:** a content page, a research-group landing page, a slide deck, an internal dashboard, a course-material site, or any artifact that should *feel* like UOU but live on its own.

> ### 🐲 Ulrinee Edition — what changed from the base UOU grammar
>
> 1. **Logo:** the official mascot **울리니 (Ulrinee)** (`assets/ulrinee/ulrinee-main.png`) is the friendly mark for this edition. It is used exactly as published by the university — never tilted, recolored, re-lined, reshaped, or cropped.
> 2. **Font:** **주아 (Jua)** replaces 윤고딕 (YoonGothic). Jua is free under SIL OFL 1.1 and ships in a single weight, so hierarchy comes from size and color instead of weight.
> 3. **Color:** UOU Green stays the single brand fill. The official Ulrinee character palette (`{colors.ulrinee-*}`) is added for mascot moments only.
> 4. **Fixes:** corrected bundled-asset paths (`UOU_CI/`, `UOU_CI_font/`) and the token namespace (`{components.*}`), which were wrong in the base document.

The University of Ulsan's design language is a **dense, institutionally-confident Korean academic presence**. When applied to a content page, it organizes information as a stack of horizontal bands: a brand-statement hero, content sections (notice/news tile grids, program intros), a deep-green feature band as a mid-page anchor, and quick-access utility zones. The dominant moment is **UOU Green** (`{colors.primary}` — DIC 643, the institutional spot color since the CIS was formalized) appearing in primary CTAs, link colors, the dark feature band that anchors mid-page rhythm, category tags, and active states.

The information density is significantly higher than Western product sites — this is the rule across Korean academic surfaces, where pages must function simultaneously as marketing surface, news desk, and resource hub. The design grammar handles that load by leaning on three structural moves: (1) a generous photographic or color-block hero, (2) tightly-organized tile grids with subtle 1px hairline borders rather than heavy elevation, and (3) a deep-green feature band (`{colors.surface-section-dark}`) that visually centers the page rhythm.

Typography in this edition is set in **주아 (Jua)** — a round, friendly Korean display face (SIL OFL 1.1, Google Fonts), with Pretendard / Noto Sans KR as web fallbacks — carrying characteristic tight negative tracking (`-0.02em` to `-0.04em` on display sizes) that gives Korean Hangul its modern, confident cadence. Body copy runs at 15px (smaller than Western standards but normal for Korean web) at 1.7 line-height, which is the leading required to make Hangul + interspersed English read comfortably in dense layouts.

The official UOU **Girin (기린)** symbol mark is a heritage asset governed by the university's CIS — this design grammar does NOT redraw or restyle the mark. The official CI/symbol-mark assets are **bundled with this repository** at `UOU_CI/` (`uou_sm_01.gif` symbol mark, `uou_sm_02.gif` UOU wordmark, `uou_sm_03.gif` Korean/English signatures); reference those files directly rather than recreating the mark. For print or scalable production, source the original EPS/AI from the UOU UI page. This document only describes how UOU-flavored content surfaces should look, not how the institutional logo is constructed.

The **울리니 (Ulrinee)** mascot — born from 기린 (Kirin), the same auspicious creature as the symbol mark, and named from 울(UOU) + 리니(Kirin) — is this edition's friendly logo. The two official PNGs live at `assets/ulrinee/` (`ulrinee-main.png` standing pose, `ulrinee-sub.png` waving pose), sourced unmodified from the university's mascot page (ulsan.ac.kr › 대학상징 › 마스코트 캐릭터). The mascot complements, but never replaces, the Girin symbol mark on official documents.

## Visual Theme & Atmosphere

A *Korean institutional academic system* with traceable design-conservative roots. The system reads as: **established, trustworthy, regionally rooted (Ulsan / industrial heritage), academically serious**. There is no playful chrome, no decorative gradients, no novelty animations — with one deliberate exception in this edition: the official 울리니 mascot, which adds a single warm, friendly moment per page. The brand moments are:

1. **UOU Green dominant** (`{colors.primary}` #006B3C — a rendering of DIC 643 in sRGB, since the official spec is a spot color). It anchors primary CTA fills, link color on light surfaces, the dark feature band, category tags, tab-active states, and the rare "featured" emphasis tile.
2. **Photographic hero** — full-bleed campus photography (Mugeo campus aerials, lab/research imagery, student life), typically darkened with an overlay so the white headline reads. This is where the brand's emotional moment lives.
3. **Tile grids over cards** — news and notices are organized as a 3-or-4-column tile grid with a single 1px hairline border (`{colors.hairline}` #E5E5E5) and no shadow at rest. Hover lifts elevation gently (`{shadows.card-hover}`).
4. **Yellow as exception** (`{colors.accent-yellow}` #F2A900 — DIC 207 rendered to sRGB). Used only on "신규(NEW)" badges, event announcements, focus rings, and rare emphasis moments. Never used as a general accent.
5. **Gray as structure** (`{colors.secondary-gray}` #58595B — DIC 654 rendered to sRGB). Used for body-secondary text, hairlines, and supporting metadata. Never used decoratively.
6. **Ulrinee as the friendly mark** (`{components.ulrinee-logo}`). The mascot appears in the page header as the logo and, at most once more, in a `{components.ulrinee-callout}` that softens a guide, FAQ, or welcome message.

**Color-block page rhythm:** White hero (or photographic dark hero) → White content tile section → Dark green feature band (CTA / vision statement / featured highlight) → Warm-cream supporting zone → White content section → (page ends, OR a closing dark band if context demands). The dark-green band in the middle is the page's spine — without it, the layout would read as flat utility. Pages should have **one** deep-green feature band, not several.

## Color Palette & Roles

### Source colors (institutional)

The University of Ulsan publishes its color spec as **DIC numbers** (the Dainippon Ink standard widely used in Korea/Japan for spot-color printing), not as web hex. The values below are the recommended **sRGB renderings** for screen use — close approximations of the print spec, calibrated to match the symbol-mark lockup as it appears on the official UI page.

- **UOU Green** (`#006B3C`) — DIC 643 spot color. The primary brand surface. Used for the symbol mark, primary CTA fills, link color on light surfaces, navigation active states, and category tags.
- **UOU Gray** (`#58595B`) — DIC 654 spot color. Secondary brand color. Used for body-secondary text, supporting metadata, hairlines, and quiet utility surfaces.
- **UOU Yellow** (`#F2A900`) — DIC 207 spot color. Tertiary accent. **Reserved** for emphasis-only — "NEW" badges, event highlights, focus rings. Never a general-purpose accent.

### Extended UI palette

- **Primary Deep** (`#004D2B`) — Active/pressed state for primary CTA; also the dark feature-band surface (`{colors.surface-section-dark}`).
- **Primary Light** (`#2E8B57`) — Used sparingly for hover tints and decorative accents on light surfaces.
- **Yellow Soft** (`#FFD966`) — Background washes for legacy event sections; gentler than full UOU Yellow.

### Neutrals & text

- **Ink** (`#1A1A1A`) — Primary heading color on light surfaces. Not pure black.
- **Body** (`#222222`) — Body copy on light surfaces.
- **Ink Muted 80 / 60 / 40** (`#333333` / `#666666` / `#999999`) — Three-step muted ladder for secondary text, captions, and disabled states.
- **Hairline** (`#E5E5E5`) — The 1px tile borders, table dividers, form input borders. The most-used neutral after white.
- **Divider Soft** (`#F0F0F0`) — Section dividers and form-row separators.

### Surfaces

- **Canvas** (`#FFFFFF`) — Primary page surface.
- **Canvas Warm** (`#F7F7F5`) — Section bands that need to break two consecutive white zones (supporting zones, stats bands, alternate content sections).
- **Surface Pearl** (`#FAFAFA`) — Dropdown menus, search-suggestion containers, table-row alternates.
- **Surface Section Dark** (`#004D2B`) — The deep-green feature band. Always paired with `{colors.on-dark}` text.
- **Surface Footer** (`#1A1A1A`) — Reserved for the official site shell only. Do NOT apply this surface to content-page bottoms; let the page end on a content section instead.
- **Surface Footer Deep** (`#0D0D0D`) — Reserved for the official site shell only.

### Semantic & status

- **Status New** (`#E63946`) — The red "NEW" badge color. Reserved for this badge only — not used as a general error color.
- **Status Info** (`#0066B2`) — External-link or download-link indicator.
- **Focus Ring** (`#F2A900`) — Re-uses UOU Yellow for keyboard focus outlines (2px solid, 2px offset).

### Ulrinee character palette (official 색상규정)

Taken directly from the university's Ulrinee color specification. These colors belong to the mascot — use them only around mascot moments (callout backgrounds, mascot badges, friendly illustrations), never for CTAs, links, or the deep-green band.

| Token | Hex | RGB | Role on the character | UI use |
|---|---|---|---|---|
| `ulrinee-leaf` | `#B9D887` | 185:216:135 | Body (main) | `{components.badge-ulrinee}` fill |
| `ulrinee-sprout` | `#99C45C` | 153:196:92 | Body shading (main) | Decorative accents |
| `ulrinee-cream` | `#F9E79B` | 249:231:155 | Horns, belly, feet (main) | `{components.ulrinee-callout}` surface |
| `ulrinee-moss` | `#76A854` | 118:168:84 | Forehead marks (sub) | Decorative accents |
| `ulrinee-line` | `#2C3D28` | 44:61:40 | Outline, eyes (sub) | Text on Ulrinee surfaces |
| `ulrinee-blush` | `#EDBE7F` | 237:190:127 | Cheeks (sub) | Decorative accents |
| `ulrinee-mouth` | `#F08C8C` | 240:140:140 | Inside of mouth (sub) | Decorative accents |

Pair light Ulrinee surfaces (`leaf`, `cream`) with `{colors.ulrinee-line}` text — never white text on them.

### Color usage discipline

- One brand green only (`{colors.primary}`). Don't introduce blue, teal, or alternative green tints. The Ulrinee palette is a character palette for mascot moments, not a second brand fill.
- Yellow appears in three contexts only: NEW badges, focus rings, and rare event highlights.
- Gray is structural, never decorative — it builds hierarchy in text and dividers, but doesn't appear as a fill.
- Pure black is rare; everywhere else uses `{colors.ink}` (#1A1A1A) for warmer rendering.

## Typography Rules

### Font Family

- **Primary stack:** `Jua, Pretendard, "Noto Sans KR", "Malgun Gothic", -apple-system, sans-serif`

**주아 (Jua)** is this edition's typeface — a round, friendly Korean face by Woowahan Brothers, released under the **SIL Open Font License 1.1** and served free from Google Fonts, so it can be used, embedded, and redistributed in a public repository. It covers Hangul and Latin, which keeps bilingual text in one face.

Load it from Google Fonts:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Jua&display=swap" rel="stylesheet">
```

```css
body { font-family: Jua, Pretendard, "Noto Sans KR", "Malgun Gothic", -apple-system, sans-serif; font-synthesis: none; }
```

**Jua ships in a single weight (400).** Every typography token in this edition is therefore `fontWeight: 400`, and `font-synthesis: none` stops browsers from faking bold. Hierarchy is carried by size, color, and spacing.

#### Institutional typeface (not bundled here)

윤고딕 (YoonGothic / YDYGO) remains the official UOU typeface for official university surfaces. It is a commercial Yoon Design font licensed for UOU use, and publishing its files in a public repository would be redistribution outside that license — so **no YDYGO files are included in this repository.** For internal projects that do hold the font, the base document's paths were wrong (`UOU_CI_폰트/윤고딕 폰트/…`, a folder that does not exist); the bundled files actually sit directly in `UOU_CI_font/`:

```css
@font-face { font-family: "YoonGothic"; font-weight: 400; src: url("UOU_CI_font/YDYGO135.ttf"); }
@font-face { font-family: "YoonGothic"; font-weight: 600; src: url("UOU_CI_font/YDYGO155.ttf"); }
@font-face { font-family: "YoonGothic"; font-weight: 700; src: url("UOU_CI_font/YDYGO165.ttf"); }
```

### Hierarchy

| Role | Size | Weight | Line Height | Letter Spacing | Notes |
|------|------|--------|-------------|----------------|-------|
| Hero Display | 52px | 400 | 1.2 | -1.04px (-0.02em) | Photographic hero h1 |
| Display Large | 40px | 400 | 1.25 | -0.8px | Section opening h2 |
| Display Medium | 32px | 400 | 1.3 | -0.64px | Sub-section h2 |
| Section Title | 28px | 400 | 1.35 | -0.56px | Tile-grid section heading |
| Heading Large | 22px | 400 | 1.4 | -0.44px | Card titles, sidebar heads |
| Heading Medium | 18px | 400 | 1.45 | -0.36px | Notice/news titles, tabs |
| Lead | 20px | 400 | 1.55 | -0.4px | Hero sub-copy, intro paragraphs |
| Body Large | 17px | 400 | 1.65 | -0.34px | Long-form content body |
| Body | 15px | 400 | 1.7 | -0.3px | Default UI body, list items |
| Caption | 13px | 400 | 1.5 | -0.26px | Metadata, dates, source labels |
| Fine Print | 12px | 400 | 1.5 | -0.24px | Footer links, legal text |

All roles use Jua's single weight (400); the size ladder above is the hierarchy.

### Principles

- **Tight negative tracking** (`-0.02em` to `-0.04em` on display sizes) is universal — this is what makes Korean Hangul read with modern confidence rather than typewriter-flat.
- **1.7 body line-height** is the Korean web standard, not 1.5 — Hangul characters are visually denser per line than Latin characters and need the extra leading. **Don't tighten body line-height below 1.65.**
- **One weight only:** Jua has a single 400 weight. Build hierarchy from the size ladder (52 → 11px) and from color (`{colors.ink}` vs `{colors.ink-muted-60}`, UOU Green for links). Never apply `bold` to Jua.
- **No italics in Korean.** Hangul has no italic form — emphasis comes through size or color (UOU Green link).
- **Bilingual surfaces** — when Korean and English appear together (program names, faculty bios), Jua (and the Pretendard fallback) handles both. Don't mix typefaces.

### Notes on font availability

주아 (Jua) is free for any use under SIL OFL 1.1 and loads from Google Fonts. The fallback chain — **Pretendard** (open-source, SIL OFL; distributed via its GitHub releases and CDNs such as jsDelivr — it is *not* on Google Fonts, contrary to the base document) and **Noto Sans KR** (Google Fonts), with **Malgun Gothic** as the Windows system fallback — keeps text legible if the Jua request is slow or blocked.

## Component Stylings

### Buttons

**`button-primary`** — The dominant CTA. Background `{colors.primary}` (UOU Green #006B3C), text `{colors.on-primary}` in `{typography.button-label}` (15px / 400 / -0.3px), rounded `{rounded.sm}` (4px — note: Korean institutional buttons typically use a small radius rather than full-pill, signaling formality), padding 12px × 24px. Active state shifts background to `{colors.primary-deep}` (#004D2B). Used for "지원하기 (Apply)", "입학 안내 (Admissions)", "자세히 보기 (View More)" primary actions.

**`button-outline`** — Secondary action. Transparent background, text `{colors.primary}`, 1px solid `{colors.primary}` border. Same radius/padding/typography as primary. Used for "더보기 (More)" links into the news/notice archives, alternative actions paired with a primary.

**`button-outline-on-dark`** — On the deep-green feature band (`{colors.surface-section-dark}`). Transparent background, white text, white border. Same proportions as `{components.button-outline}`.

**`button-ghost`** — Tertiary, inline action. No background, no border, text `{colors.ink-muted-80}` in `{typography.button-label}`. Used in tables, list rows, dense utility surfaces.

**`button-icon-square`** — 44 × 44px square button for utility actions (search toggle, language toggle, accessibility menu). Background `{colors.canvas}`, 1px solid `{colors.hairline}`, rounded `{rounded.sm}`.

**`text-link`** — Inline body links in `{colors.link-on-light}` (UOU Green). Underlined on hover, not at rest. On dark surfaces, switch to `{components.text-link-on-dark}` which uses `{colors.on-dark}` (white) — UOU Green disappears against `{colors.surface-section-dark}`.

### Site Shell — INTENTIONALLY EXCLUDED

> The official ulsan.ac.kr global navigation, language toggle, sitemap link, signature lockup, breadcrumb, and footer are **deliberately not documented as components** in this design grammar. They belong to the operational university website and should not be auto-generated when applying this system to a content page, research-group landing page, slide deck, or internal tool.
>
> If you are building a UOU-branded artifact and need a header, build a **minimal page header that fits the artifact's actual purpose** — for example: a small wordmark + page-title + back-link, or a simple page-title bar in `{typography.section-title}`. Do not reproduce the full corporate top bar from the official homepage unless you are working on the official site itself.

### Hero & Section Bands

**`hero-photographic`** — Full-bleed campus photography hero. Background image (campus aerial, research lab, students) with a 40% black overlay layer for text legibility. Text `{colors.on-dark}` in `{typography.hero-display}` (52px / 400). Optional sub-line in `{typography.lead}` (20px / 400). Optional `{components.button-primary}` CTA. Padding 120px × 64px (vertical × horizontal). The hero may include a subtle photo carousel with dot indicators bottom-center.

**`hero-band`** — Non-photographic hero used on interior pages. Background `{colors.surface-section-dark}` (deep green), white text. Same proportions as photographic hero but no image overlay. Used on policy/about pages where photography isn't appropriate. **Note:** this is a CONTENT hero (a band that holds the page's title and intro). It does NOT include a global navigation row above it; if you need a header, build a minimal one specific to your page.

**`section-band-light`** — Standard content section. Background `{colors.canvas}`, padding 96px × 64px. Centered content max-width 1200px. Used for content body, tile grids, program intros.

**`section-band-warm`** — Contrast section. Background `{colors.canvas-warm}` (#F7F7F5). Used to break two consecutive white sections — typically a supporting zone or a stats band.

**`section-band-dark`** — The deep-green feature band. Background `{colors.surface-section-dark}` (#004D2B), white text, padding 96px × 64px. Used **once per page**, mid-rhythm, to host a CTA, vision statement, or featured highlight.

### Cards & Containers

**`notice-card`** — The primary content tile (notices, news, announcements, items in a list). Background `{colors.canvas}`, 1px solid `{colors.hairline}` border, rounded `{rounded.md}` (8px), padding 24px. Vertical stack: optional `{components.badge-category}` → title in `{typography.heading-md}` (clamped to 2 lines with ellipsis) → date + author in `{typography.caption}` with `{colors.ink-muted-60}`. No shadow at rest; on hover, transitions to `{components.notice-card-hover}` with `{shadows.card-hover}` and a 1px upward translate.

**`notice-card-featured`** — The "main notice" tile, typically the first card in a notice grid. Background `{colors.primary}` (UOU Green), text `{colors.on-dark}`. Same dimensions as `{components.notice-card}`. Used to elevate the most important item in a list.

**`news-tile`** — Image-led tile. 1px hairline border, rounded `{rounded.md}`. Top: 16:9 image crop. Below: padding 20px, category badge, title in `{typography.heading-md}`, date in `{typography.caption}`. Hover behavior identical to `{components.notice-card}`.

**`quick-link-card`** — Dense link tile for navigating between related resources. Square or near-square card, 1px hairline border, rounded `{rounded.md}`, padding 24px. Centered icon (24px–32px) above a label in `{typography.body-strong}`. On hover, fills with `{colors.primary}` and text inverts to white (`{components.quick-link-card-active}`).

### Badges

**`badge-new`** — Red "NEW" pill on recent items. Background `{colors.status-new}` (#E63946), white text in `{typography.badge-label}` (11px / 400), rounded `{rounded.xs}` (2px), padding 3px × 6px. Inline-positioned to the right of a title.

**`badge-yellow`** — Yellow event/highlight badge. Background `{colors.accent-yellow}`, dark text. Same dimensions as `{components.badge-new}`. Used for "EVENT", "공지(Notice)" emphasis.

**`badge-category`** — Outline category tag (학사, 입학, 채용, 행사, or any custom category). Transparent background, `{colors.primary}` text and 1px border. Used to categorize items in a grid.

### Inputs & Forms

**`search-input`** — A search field for content within a page. Background `{colors.canvas}`, text `{colors.ink}` in `{typography.body}`, 1px solid `{colors.hairline}` border, rounded `{rounded.sm}`, padding 12px × 16px, height 44px. Leading icon: search glyph in `{colors.ink-muted-60}`. Focus state: border swaps to `{colors.primary}`, 2px outer focus ring in `{colors.focus-ring}` (UOU Yellow) at 2px offset.

Validation, error, and form-state styling follow the same `{colors.status-new}` for invalid and `{colors.primary}` for valid — specific input-error states are not formalized in this grammar.

### Tabs

**`tab-active`** — Selected tab in a tab group. Text `{colors.primary}`, 2px solid `{colors.primary}` bottom border, padding 12px × 16px.

**`tab-inactive`** — Unselected tab. Text `{colors.ink-muted-60}`, no border, same padding.

### Mascot (Ulrinee)

**`ulrinee-logo`** — The edition's logo mark: `assets/ulrinee/ulrinee-main.png` at 56px height in the page header (minimum 40px), with clear space of at least 25% of its height on every side. Place it on light surfaces (`{colors.canvas}`, `{colors.canvas-warm}`, `{colors.ulrinee-cream}`); its dark outline disappears on the deep-green band. Pair it with the page or project title in `{typography.heading-lg}` — not with the Girin signature lockup.

**`ulrinee-callout`** — A friendly message box for guides, FAQs, onboarding, or welcome notes. Background `{colors.ulrinee-cream}`, text `{colors.ulrinee-line}` in `{typography.body-lg}`, rounded `{rounded.lg}`, padding 24px, with `ulrinee-sub.png` (waving pose) at 72–96px beside the text. Use at most once per page.

**`badge-ulrinee`** — Light-green tag for mascot-related or student-friendly items. Background `{colors.ulrinee-leaf}`, text `{colors.ulrinee-line}`, same dimensions as `{components.badge-new}`.

**Ulrinee usage rules (official 금지규정).** The university prohibits five modifications. Never:

1. tilt or rotate the character,
2. change its line weight,
3. change its colors,
4. change its shape or proportions (no squashing or stretching),
5. alter or crop part of the character.

Scale it only proportionally and always use the official PNG files as published.

## Do's and Don'ts

### Do
- Use `{colors.primary}` (UOU Green #006B3C) as the dominant brand surface — symbol mark, primary CTA, link color, navigation active states, category tags, the deep-green feature band's lighter sibling.
- Set hero headlines in `{typography.hero-display}` or `{typography.display-lg}` with negative letter-spacing (`-0.02em` to `-0.04em`) for the modern Hangul cadence.
- Run body copy at 1.7 line-height — Korean text needs the leading; tightening makes Hangul stacks hard to scan.
- Use `{components.section-band-dark}` once per page to anchor the rhythm — the page should have one deep-green moment, not several.
- Reserve `{colors.accent-yellow}` for "NEW" badges, focus rings, and rare event highlights only.
- Use `{rounded.sm}` (4px) on buttons — the institutional formality requires a small, controlled radius.
- Apply `{shadows.card-hover}` only on hover, not at rest — at-rest tiles use a 1px hairline border.
- Use 주아 (Jua) as the primary face, with Pretendard / Noto Sans KR as fallback — all handle Hangul + Latin.
- Use the 울리니 mascot exactly as published, on light surfaces, as the header logo and at most one `{components.ulrinee-callout}` per page.

### Don't
- **Don't auto-render the official ulsan.ac.kr site shell.** Specifically: do NOT add a top utility row (로그인 / ENG / 中文 / Sitemap / Family Sites), do NOT add the 7-item primary nav (대학소개 / 대학·대학원 / 입학 / 학사 / 산학협력 / 연구 / 캠퍼스 라이프), do NOT include the institutional Girin signature lockup, do NOT add a breadcrumb trail, and do NOT append the corporate footer with university address and copyright. Those belong to the operational university website, not to artifacts that merely *use* this design grammar.
- Don't redraw the Girin symbol mark from this document. If the official mark is genuinely required for a piece of work, source the EPS/AI files from the UOU UI page.
- Don't introduce a second brand color (no blues, teals, or alternative greens). UOU Green is the single brand fill; the Ulrinee palette stays around the mascot.
- Don't tilt, re-line, recolor, reshape, or crop 울리니 — the university's guideline prohibits all five.
- Don't use yellow as a general accent — it's reserved for badge/focus/event use.
- Don't use full-pill (`{rounded.pill}`) buttons on institutional surfaces; the small-radius `{rounded.sm}` is the system grammar.
- Don't tighten body line-height below 1.65 — it breaks Hangul readability.
- Don't apply bold or semibold to Jua — it has one weight, and synthesized bold smears the rounded strokes.
- Don't add decorative gradients or shadow chrome to cards — the system is flat-with-hover, not elevated-by-default.
- Don't italicize Hangul — italics don't exist in Korean type. Use size or color for emphasis.
- Don't run lines longer than ~80 characters on body copy — Korean web typography norms favor shorter measure than Latin.

## Responsive Behavior

### Breakpoints

> Nav, hamburger, and footer behavior below applies only when building the official site shell, which this grammar excludes. Content pages can ignore those entries.

| Name | Width | Key Changes |
|---|---|---|
| Small phone | ≤ 375px | Single-column tile stack; nav collapses to hamburger only; hero h1 drops to 32px |
| Phone | 376–640px | Single-column; news tiles maintain image-on-top layout; quick-link grid 2-col |
| Tablet portrait | 641–834px | Notice grid becomes 2-col; quick-link grid 3-col; nav primary stays as hamburger |
| Tablet landscape | 835–1024px | Global nav re-expands; notice grid 3-col; quick-link grid 4-col |
| Small desktop | 1025–1280px | Full layout; notice/news grids 3-col; content max-width 1200px |
| Desktop | 1281–1600px | Standard desktop; quick-link grid 5–6 col |
| Wide desktop | ≥ 1601px | Content locks at 1400–1440px max; outer margins absorb extra width |

### Touch Targets
- Minimum 44 × 44px for all interactive elements (button, icon button, search input, tab).
- `{components.button-primary}` lands at ~44 × 100px+ depending on label.
- Mobile hamburger and primary nav items: 48 × 48px on small phone for safety.

### Collapsing Strategy
- **Global nav utility row**: hidden below 834px; its functions (login, language, search) move into the hamburger drawer.
- **Global nav primary row**: full menu on ≥ 1025px → hamburger + signature lockup on ≤ 1024px. The mega-menu becomes a vertical accordion in the drawer.
- **Hero**: full-bleed photo at all breakpoints; text overlay reflows; hero h1 ramps 52 → 40 → 32px.
- **Notice/news grids**: 3-col → 2-col (834px) → 1-col (640px); image-led tiles maintain 16:9 crop across breakpoints.
- **Quick-link grid**: 6-col → 4-col (1024px) → 3-col (834px) → 2-col (640px).
- **Footer**: 4-column link layout → 2-column (834px) → accordion-collapsed (640px) with each section heading expandable.

### Image Behavior
- Hero photography uses responsive `srcset` with breakpoint-matched crops; mobile may use a tighter portrait crop.
- News/event thumbnails stay 16:9 across breakpoints; only scale changes.
- Lazy-loading default for below-fold imagery; hero loads eagerly.
- Decorative graphics (icons in quick-link cards) use SVG so they scale crisply at all densities.

## Iteration Guide

1. Focus on ONE component at a time. Reference its YAML key directly (`{components.notice-card}`, `{components.section-band-dark}`, `{components.button-primary}`).
2. Variants of an existing component (`-active`, `-on-dark`, `-featured`, `-on-scroll`) live as separate entries in `components:`.
3. Use `{token.refs}` everywhere — never inline hex.
4. Document default and active/pressed/hover states only; transient micro-states (focus-visible, disabled with reduced opacity) follow standard a11y patterns.
5. Hero/section type stays 주아 (Jua) at display sizes with negative letter-spacing. Body stays Jua 400 at 15px / 1.7. Hierarchy comes from size, never from synthesized bold.
6. The single brand fill is UOU Green. UOU Yellow is reserved for badges/focus/events. UOU Gray is structural neutral. The Ulrinee palette is for mascot moments only. Don't introduce additional brand colors.
7. The page rhythm is **one deep-green band per page**. Two deep-green bands signal the spec is wrong.
8. When in doubt about emphasis, alternate **surface** (white → warm-cream → deep-green) before adding chrome. The color block IS the divider.

## Known Gaps

- **Spot-color → sRGB conversion.** UOU Green (DIC 643), UOU Gray (DIC 654), and UOU Yellow (DIC 207) are spot-color specifications, not web hex values. The hex values in this document (`#006B3C`, `#58595B`, `#F2A900`) are **screen-calibrated approximations** matched to how the symbol-mark lockup renders on the official UI page. For print-accurate work, always reference the DIC swatches directly; for web/screen work, the hex values here will read consistently.
- **Site shell is intentionally not part of this grammar.** The official ulsan.ac.kr global navigation, signature lockup, language toggle, breadcrumb, and footer are operational website features governed by the university's CIS PDF manual and web team. If you need them for an official sub-site, source them from the UOU UI page; do not generate them from this document.
- **Symbol-mark construction** (Girin proportions, clear-space rules, minimum size, color variants in 1-color reverse) is governed by the official UOU CIS PDF manual. Bundled raster assets live at `UOU_CI/` for screen reference; always pull the official EPS/AI files for production/print use.
- **윤고딕 (YoonGothic / YDYGO) is not bundled here.** Its license covers UOU use, not public redistribution, so this public repository ships no YDYGO files and sets type in 주아 (Jua). Internal projects that hold the font should load it from `UOU_CI_font/` (the base document's `UOU_CI_폰트/윤고딕 폰트/` path does not exist).
- **Ulrinee variants.** Only the two basic 2D poses are bundled. The 3D, applied, and emoticon variants, the AI source files, and the full guideline manual are on the university's mascot page (ulsan.ac.kr › 대학상징 › 마스코트 캐릭터).
- **Form validation states** (error tints, success ticks, disabled inputs) are not surfaced on the public homepage; only the neutral search input is documented here. Sub-sites (admissions application, course registration via UWINS portal) likely have their own validated form library.
- **Sub-site systems** (의과대학, 산학협력단, 도서관, 입학처) inherit the colors and typography but each has its own information architecture and may layer additional components — those sub-systems are out of scope for this document.
- **Mega-menu behavior** in the global nav (column structure, hover-to-expand timing, mobile-drawer animation) is documented structurally only; the exact transition timings (`200ms ease`, `cubic-bezier`) are platform-conventional and not formalized as tokens.
- **Bilingual page variants** (English / Chinese / Vietnamese mirror sites) reuse the same color and typography tokens but may adjust line-height tokens for Latin-only text — not separately documented here.
- **Photographic hero art direction** — the rotation of campus photography (aerials, lab shots, student portraits, athletics) is a content asset stream managed editorially, not a design token. The component spec describes the surface; the imagery is editorial.
- **Animation/motion tokens** — page-load fades, scroll-reveal timings, and the hero-carousel auto-advance are platform-conventional Korean university web behaviors but aren't formalized as named motion tokens in this doc.
