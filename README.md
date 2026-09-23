# @aleph-garden/brand

> Before 1.0. Any interface here can change in any release, including the
> ones marked `-dev` patches. Build against it to experiment, depend on an
> exact version, and expect to follow breaking changes by hand.

The look every Aleph Garden surface shares: the design tokens, the three
typefaces and the lockups. Pages, documentation themes and hosts import them
from here instead of carrying copies.

```sh
npm install @aleph-garden/brand
```

```css
@import "@aleph-garden/brand/fonts.css";
@import "@aleph-garden/brand/tokens.css";
```

| Path | What it holds |
| --- | --- |
| `tokens.css` | Every `--ag-*` custom property, light and dark |
| `fonts.css` | `@font-face` rules for IBM Plex Sans, IBM Plex Mono and Sora, Latin subsets |
| `fonts/*` | The font files and their licences |
| `lockups/*` | The mark and the lockups as SVG, light and dark |

## Light and dark

The tokens follow the reader's preference unless an ancestor sets a mode.
Any of these sets it: `data-ag-theme="dark|light"`, `data-theme="dark|light"`
(what Starlight writes) or the classes `.theme-dark` and `.theme-light`.

## Versions

Versions go to the `dev` dist-tag. The token names are the contract, so
renaming one is a breaking change.

## Licences

The mark and the lockups are not licensed. They may be used only with
written permission from Christopher Mühl, and that includes the files in
`lockups/` and `source/`. The fonts are under the SIL Open Font Licence 1.1,
with the licence texts in `fonts/`. The CSS and the documentation are MIT.
`LICENSE` has the full terms.
