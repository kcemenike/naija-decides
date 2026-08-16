# naija-decides

Nigerian election results, transcribed from INEC's own polling unit result
sheets and published so anyone can check them.

**<https://kcemenike.github.io/naija-decides/>**

| Election | Report |
|---|---|
| Osun State governorship, 2026 | [osun/2026](https://kcemenike.github.io/naija-decides/osun/2026/) |

## What these are

INEC publishes a scan of the Form EC8A for every polling unit on
[IReV](https://www.inecelectionresults.ng) — a handwritten sheet signed at the
unit, showing each party's votes and the ballot accounting. It publishes the
scans, not the numbers, so there is no way to add them up without reading
several thousand images.

Each report here is the result of doing that: every sheet transcribed, checked
against its own arithmetic, and aggregated by ward and local government area.
Every row links back to the scan it came from, so any figure can be checked
against the paper in one click.

Sheets that don't reconcile are not silently corrected. They are flagged,
reviewed by hand, and the verdict is shown next to the result along with who
recorded it.

## Caveats

- These are **transcriptions of provisional sheets**, not certified results.
  INEC's declaration is the official outcome.
- Not every polling unit has an uploaded sheet at any given moment. Each report
  states how many it read out of how many exist.
- Sheets can be re-uploaded for days after polling. Reports are regenerated as
  that happens; the generation timestamp is at the top of every page.

Each report is a single self-contained HTML file with its data embedded, next to
the `results.json` it was built from. Both are free to reuse.
