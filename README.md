# Borozdov Marble

A theme from the Borozdov collection. Two faces — light **Travertine**, an architectural
editorial on white marble, and dark **Slab**, the same structure cut from near-black stone.
A humanist serif sets the title and the three largest headings, the platform's own sans
carries the body, and one cobalt blue is the only saturated colour in the system.

![Borozdov Marble in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/marble/main/screenshots/light.png)

![Borozdov Marble in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/marble/main/screenshots/dark.png)

## Principles

- **A facade, not a poster.** Marble Serif — upright, precise — sets the title and the three
  largest headings; the two smallest headings and all body text stay in the platform's own
  sans, the way a building's floor directory stays plainer than its facade lettering.
- **One cobalt accent.** Cobalt blue appears only in small, functional doses: links, the
  caret, tag outlines, the blockquote rule and the plain note callout's tinted wash. It
  never fills a button.
- **A filled dark action, not a coloured one.** The main button fills solid ink and turns
  cobalt only on hover; plain buttons are 8px-cornered outlines that defer to it, the same
  way a ghost button defers to a primary one in the source's own interface.
- **A drawing's frame.** Tables and callouts draw a single hairline rim at 8–12px corners
  with the faintest blue-tinted lift — never a hard shadow, never a double edge.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- Callouts as flat hairline-bordered cards with a soft blue-tinted lift; the plain note
  tinted with the cobalt wash
- Blockquotes in the humanist serif, a size up, behind a cobalt rule
- Tables ruled with a single frame and an inner grid, no doubled borders
- Tags as thin cobalt outlines, never filled
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory, as a variant:** this theme ships inside **Borozdov
Utility**. Install Borozdov Utility under Settings → Appearance → Themes → Manage, then
the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin, and
choose **Marble** under Style Settings → Borozdov Utility → Variant. The variant brings
this theme's palette, type and corners; its own layout, and its embedded font if it has
one, come with the full theme below.

**The full theme, by hand:** download `manifest.json` and `theme.css` from the
[latest release](https://github.com/borozdov-obsidian-themes/marble/releases/latest)
into `<vault>/.obsidian/themes/Borozdov Marble/`, then choose Borozdov Marble under
Settings → Appearance → Themes.

## Font

Marble Serif is embedded in `theme.css` as base64 WOFF2 under the SIL Open Font License
1.1 — see [`fonts/OFL.txt`](fonts/OFL.txt). It is a Latin and Cyrillic subset of Cochineal
(© 2016–2021 Michael Sharpe, itself based on Sebastian Kosch's Crimson), renamed because a
modified copy may not use the original's Reserved Font Name. One weight, for the title and
the three largest headings only.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Travertine» — архитектурная
редакция на белом мраморе, и тёмный «Slab» — та же структура, вытесанная из тёмного камня.
Гуманистическая антиква несёт заголовок и крупные подзаголовки, рубленый шрифт платформы —
основной текст, а один кобальтовый акцент — единственный насыщенный цвет в системе.
В каталоге тема живёт вариантом Borozdov Utility: установите Borozdov Utility и плагин Style Settings, затем выберите Marble в Style Settings → Borozdov Utility → Variant. Целиком, со своей вёрсткой, тема ставится вручную из последнего релиза репозитория.
