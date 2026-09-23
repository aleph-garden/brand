# Source files

The designer's originals for the mark and its lockups. The files the package
ships are derived from these and live in `lockups/`; nothing here is
published to npm.

Each variant is one design in several formats:

| Directory | Format |
| --- | --- |
| `master/` | The combined artboard, as `.ai`, `.eps` and `.pdf` |
| `ai/`, `eps/` | Each variant as an editable vector file |
| `svg/` | Each variant as SVG, as exported |
| `jpg/` | Each variant at 4167 × 4167 px |
| `png/` | Each variant on a transparent ground at 1x, `@2x` and `@4x` |

The names say the arrangement, whether the secondary word GARDEN is present
(`full`) or absent (`primary`), and which ground the ink is for:

| Name | Arrangement | Ground | Delivered as |
| --- | --- | --- | --- |
| `horizontal-full-light` | Mark left, both words | light | `Logo-01`, `Asset 9` |
| `horizontal-full-dark` | Mark left, both words | dark | `Logo-02`, `Asset 10` |
| `horizontal-primary-light` | Mark left, ALEPH only | light | `Logo-03`, `Asset 2` |
| `horizontal-primary-dark` | Mark left, ALEPH only | dark | `Logo-04`, `Asset 1` |
| `stacked-full-light` | Mark above, both words | light | `Logo-05`, `Asset 8` |
| `stacked-full-dark` | Mark above, both words | dark | `Logo-06`, `Asset 3` |
| `stacked-primary-light` | Mark above, ALEPH only | light | `Logo-07`, `Asset 7` |
| `stacked-primary-dark` | Mark above, ALEPH only | dark | `Logo-08`, `Asset 4` |
| `mark-light` | Mark alone | light | `Logo-09`, `Asset 5` |
| `mark-dark` | Mark alone | dark | `Logo-10`, `Asset 6` |

The last column names the files as the designer delivered them, since the
research in the planning repository refers to them that way.
