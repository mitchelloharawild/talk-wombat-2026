# WOMBAT 2026 workshop day slides

The slide deck for the workshop day (Tuesday 1 December 2026): opening, talk introductions and breaks, and closing. Edit [`index.qmd`](index.qmd), then:

```sh
quarto preview index.qmd
```

This renders to one self-contained `index.html`. Opening and closing slides marked `TODO` are stubs. The style is the `wombat` Quarto extension in `_extensions`; [`template.qmd`](template.qmd) shows every style.

Slides are 1600 x 900 and the fonts are bundled, so the deck works offline. For PDF, open the deck with `?print-pdf` in Chrome and print with background graphics on (the footer is left out).

| Style | Markdown |
|---|---|
| Title | navy by default, `title-style: light` for white; optional `kicker` and `photo` |
| Section divider | `# Title`, or `# Title {.light}` |
| Regular slide | `## Title`; add `.night` for navy |
| Label above a heading | `## Title {kicker="Text"}` |
| Talk introduction | `## Title {.talk .night kicker="Talk · 10:30 am"}`, see below |
| Break | `## Lunch {.break until="13:00"}` or `{.break minutes=10}` |
| Hexagon list | `::: {.hexes}` around a list |
| Images | `![](x.jpg){.image-right .nostretch}`, `.image-left`, or `## Title {.image-full background-image="x.jpg"}` |
| Hide the footer / hexagons | `{.no-footer}` / `{.plain}` |

`until` counts down to that time on the presenting computer's clock, so check its time zone. `minutes` starts when the slide is first shown.

Talk introductions take one or more presenters:

```markdown
## Talk title {.talk .night kicker="Talk · 10:30 am"}

Abstract, around 40 words.

:::: {.presenters}
::: {.presenter}
![](img/speakers/name.jpg){.nostretch alt="Name"}

### Name

Bio, around 15 words.
:::
::::
```
