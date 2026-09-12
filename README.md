# Climate of Britain, 5000–2000 BC

Interactive, referenced graphs of published palaeoclimate proxies for the British Isles between **5000 and 2000 BC** (about 6950–3950 cal yr BP).

Open the working page:

- [`index.html`](index.html) — single-page viewer. Series data are embedded; **Plotly is loaded from `cdn.plot.ly` at runtime**, so the page needs a network connection.
- Live: https://timdaw37.github.io/britain-climate-5000-2000bc/

This is a **viewer**, not a new climate reconstruction. Each series carries the citation, archive, what the proxy measures, and an uncertainty note.

Current build: **v0.5** (12 September 2026).

## What is plotted

| Series | What it is | Window coverage |
| --- | --- | --- |
| Mauri et al. 2015 EPOCH-2 | Pollen-grid anomalies at 51°N, 2°W + Boscombe Down 1971–2000 normals | Four millennial slices (headline) |
| Charman et al. 2006 | Stacked peat water tables, northern Britain | From ~2493 BC; overlay starts 2200 BC (low replication before that) |
| Charman & Hendon 2000 | N England water-table depth | From ~3000 BC |
| Langdon et al. 2004 | Talkin Tarn chironomid July T | From ~3808 BC |
| Barber et al. 2013 | Bigland Tarn chironomid July T | From ~2856 BC |
| Taylor et al. 2018 | Lough Meenachrinna chironomid July T | Full window |
| McDermott CC3 (SISAL) | Crag Cave, SW Ireland, δ18O | Full window |
| Alley 2000 GISP2 | Greenland temperature (context) | Full window |
| Bond et al. 2001 | N Atlantic drift-ice stack (context) | Full window |
| Steinhilber et al. 2009 | Total solar irradiance ±1σ (forcing) | Full window |
| Leuschner et al. 2002 | Irish/continental bog-oak generation changes | Events ~4000 and ~2500 BC (no annual curve file) |
| Boswijk / ITRDB BRIT036 | Thorne Moors subfossil oak ring-width | 3772–3016 BC (site hydrology, not °C) |
| Bebchuk et al. 2025/2026 | Fenland yew span + wet-end interpretation | Bars 2668–2213 BC and decline/end; annual isotope file not public |

## What this is not

- Not evidence of ice sheets or a frozen Britain in the Neolithic or Early Bronze Age.
- Not a single “temperature of Britain” curve.
- Not a verdict on the global 4.2 ka event.
- Not a climate crash at ~2400 BC timed to Beaker arrival. The peat-stack cliff at the start of Charman 2006 is low replication plus one outlier; Charman et al. do not list a major wet shift then.

## Data policy

Original series remain copyright / licence of their authors and of NOAA WDS Paleoclimatology. Processed points used in the graphs are redistributed with full citation so the figures can be rebuilt. If an author objects to a processed copy, open an issue and it will be replaced with a link-only catalogue entry.

## Still missing (no public time series, or wrong geography)

- Fenland yew/oak annual δ18O–δ13C file (Bebchuk; span marked only)
- Swansea / UK Oak Project 7000-year oak δ18O master (not released)
- Irish bog-oak annual head-count / mean-age curve
- A southern England / Somerset Levels peat stack
- SCOT2K Scottish pine temperature (last ~800 years only — wrong window)
- Lochnagar (held back: 788 m, almost no points in-window)

See `CITATIONS.md`.
