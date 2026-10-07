# Sigma P&L Statement Plugin

A **real P&L statement** tile for Sigma — spreadsheet/FP&A layout, not a
decomposition tree and not a blank waterfall.

## What it renders

| Line | Prior | Current | Δ | Δ % |
|------|-------|---------|---|-----|
| Net revenue | … | … | … | … |
| … | | | | |
| **Contribution** | … | … | … | … |

- Statement rows with section / subtotal / total styling
- SI compact currency (`$109M`) or full accounting format
- Brandable navy / primary / accent

## Editor panel

| Config | Role |
|--------|------|
| `source` | Table / element |
| `line` | Account / P&L line name |
| `prior` | Prior period amount |
| `current` | Current period amount |
| `order` | Optional sort key |
| `title` / `subtitle` | Header copy |
| `navy` / `primary` / `accent` | Brand hexes |
| `siCompact` | SI `$` vs full currency |

## Host

GitHub Pages:
`https://gabrieljonessigmacomputing.github.io/sigma-pnl-statement-plugin/`

## Register (papercrane)

```bash
# via sigmaapi.register_plugin("P&L Statement", url, "Statement-style P&L")
```
