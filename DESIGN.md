# Splash Social — Design Reference

> ** source of truth:** the **Splash Design System**

## Fonts (approved social set)
- **Brand (canonical):** **Gotham** (Book 400 / Medium 500 / Bold 700) +
  **SplashSerif** (Medium 500 / Italic 400). Now loaded into the **Canva Brand Kit**.
  - SplashSerif *Italic* → human-story headlines & pull quotes
  - SplashSerif Medium → section titles
  - Gotham Bold → impact stats, CTAs, strong headings · Gotham Medium → eyebrows/nav · Gotham Book → body
- **Also approved for social** (used consistently, OK to keep): **Poppins ·
  Montserrat · Avenir**. These pair with the brand and are Canva-native.
- **Retired / off-set:** Outfit, Work Sans, Lora (the one-off SBCC Canva kit). Don't use for new work.

### Per-template fonts
| Template | Font | Status |
|---|---|---|
| The Reality (PPTX) | Poppins | ✅ approved (keep) |
| Proof in Practice (HTML) | Gotham + SplashSerif | ✅ canonical |
| Built to Last / others | → migrate to Gotham/SplashSerif or an approved social sans | |

## Colors (canonical hexes)
sky `#20bcff` · deep blue `#0092d2` · ink `#2a3135` · orange `#f16322` ·
gold `#fbad18` · purple `#88206a` · green `#005332` ·
neutrals `#e5e4e3` (dividers) / `#c2c1c0` (borders) / `#929190` (captions).

## Hard rules (from the Design System)
- **No emoji** anywhere on social. Warmth comes from photography, not icons/emoji.
- **No gradients** on backgrounds; flat color only.
- **No pill/capsule buttons** — buttons nearly square (radius 4–6px). Minimal shadows.
- **Full-bleed photography** for heroes; overlaid text = white or drop-shadow only (no overlay blocks).
- **Casing:** eyebrows/labels & CTAs = ALL CAPS tracked · hero headlines = sentence case · section headers & names = Title Case.
- Location labels = Gotham Bold, white, ALL CAPS (e.g. "KITWE, ZAMBIA").

## Voice
Human-first, mission-driven. Hyper-specific stats ("1,191,876 kids"). "We" =
Splash, "you" = donor. Short, declarative, no jargon. Urgency without guilt.

## Type scale / spacing (tokens)
Text 11 / 13 / 15 / 17 / 20 / 24 / 32 / 42 / 56px · spacing 4→128px ·
radius sm 4 / md 6 / lg 12 · shadows minimal. See `colors_and_type.css` for the full token set.
