# Astromia — "Dawn Ink" mobile re-skin (contest entry)

A re-skin of astromia.eu: same sections, same order, same Bulgarian copy and CTAs, same 4-step form → free preview → order flow.
Only the look changes: warm paper, plum ink, rosé and one clay colour for every call to action, instead of the navy-and-gold template.

## Open it
- `index.html` — live mobile homepage prototype (open on a phone; sticky CTA appears after the hero). On desktop it shows a phone-width column with links.
- `site/home.html` — homepage, 390 px design width (full length).
- `site/flow-date.html` · `site/flow-preview.html` · `site/flow-order.html` — purchase flow screens (390 × 797 content + status bar).
- `site/desktop.html` — desktop hero (1440 × 900) in the same system.
- `entries/entry-1.html`, `entries/entry-1-detail.html` — the two presentation boards.

## Fonts (free, Google Fonts, OFL)
- **Playfair** (v2, variable `opsz` 5–1200, `wght` 300–900, italics) — headings, quotes, book pages. Use `lang="bg"` for Bulgarian letterforms.
- **Sofia Sans** (Lettersoup) — UI, forms, prices, labels. Native Bulgarian letterforms with `lang="bg"`.

## Colours
| Token | Hex | Use |
|---|---|---|
| Paper | `#F7F1EA` | page background |
| Paper 2 | `#F2E7DE` | alternate bands |
| Blush | `#EFDCD2` | soft bands, chips |
| Rosé | `#EBC0AE` | accents on night bands |
| Plum ink | `#2A1730` | text, selected states |
| Ink 2 | `#5B4560` | secondary text (7:1 on paper) |
| Night | `#23122A` | dark bands, ticker, preview reader |
| Clay (CTA) | `#B5503A` | every call to action (white text 5.0:1, WCAG AA) |
| Book navy / gold foil | `#121B42` / `#C9A35E` | the product only |

## Components
Buttons (58 px, pill, clay), fields (58 px, 16 px radius, clay focus ring), selects with floating labels, progress bar,
step card, review card with zodiac monogram, edition cards / radio rows, sticky CTA bar, ticker, night bands, CSS 3D book.

## Assets
`assets/svg/` — chart wheels (site, hero, night, gold foil), book cover (vector), logo mark, moon phases, sparkle,
24 line icons, 12 zodiac + 12 planet glyphs. `assets/photos/` — the client's own product photos (from astromia.eu), resized.

## Source
`src/` — page templates and the design-system CSS (`astromia.css`). The SVG wheel, cover, glyphs and icons are generated
(tools in the project root: `svgkit.py`, `build_site.py`). Chart data in the wheel is illustrative (Sun Cancer, Moon Leo, Asc Virgo).
