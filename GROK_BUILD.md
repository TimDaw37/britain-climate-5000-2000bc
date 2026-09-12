# Protocol: hand this to Grok Build

You cannot be handed a Build session from this chat. Open **Grok Build** as a new project and paste everything below the line as the first prompt. Keep the GitHub repo as the source of truth. Build should produce a *front page*, not a second reconstruction.

Live data explorer (keep as `index.html` on Pages):
https://timdaw37.github.io/britain-climate-5000-2000bc/
Repo:
https://github.com/TimDaw37/britain-climate-5000-2000bc

A first-cut story page already exists at `story.html` on the same repo. Treat it as the brief made visible, not the final art direction.

---

## Build this

A single, designed page titled something like **“The climate at Stonehenge, 5000–2000 BC”**.

One job: kill three popular shortcuts without being a lecture.

1. **Frozen Avon as the sarsen road.** Gold’s ice-road formula wants about a metre of good ice for a 40-tonne stone. The winters in the reconstruction are the same maritime world as now. That ice does not grow on the Avon.
2. **Climate crash, then the stones, then the Beakers.** Wrong order. Sarsens ~2500 BC. Beaker replacement ~2450–2400 BC. The 4.2 ka label ~2200 BC.
3. **Pleistocene glaciers dumped the stones.** Different debate, different millennium. This page is Holocene climate, not ice-sheet geology.

The page must link, clearly and more than once, to the GitHub explorer for every proxy, citation, and uncertainty band.

## Audience

People who have already heard a theory (ice, catastrophe, replacement) and will spend two minutes. Not palaeoclimatologists first. Archaeologists and the Stonehenge-curious second.

## Tone

Dry, specific, slightly sharp. No “unlock the secrets.” No hero video of swirling ice. No fake precision (do not write 9.607 °C). British English.

## Exact numbers you may put on screen

Boscombe Down baseline, 1971–2000 (the pollen-era normal used in the reconstruction):

- Annual mean 9.85 °C
- January 4.0 °C
- July 16.75 °C
- Annual rain 736 mm

Today’s comparison (1991–2020 Boscombe): annual 10.4 °C, January 4.6 °C, July 17.1 °C, rain 783 mm.

Mauri et al. 2015 EPOCH-2, 1° cell near 51°N, 2°W, anomalies added to the 1971–2000 baseline. Four slices only:

| Slice | Annual °C | July °C | January °C | Annual rain mm (central) |
| --- | --- | --- | --- | --- |
| 5050 BC | 9.6 | 17.4 | 2.7 | 731 |
| 4050 BC | 10.1 | 16.7 | 4.2 | 816 |
| 3050 BC | 9.6 | 16.7 | 3.8 | 873 |
| 2050 BC | 9.6 | 16.5 | 4.0 | 838 |

Headline *ranges including published ±1σ* (annual T band borrows the JJA SE; annual rain assumes spring/autumn track the mean of DJF+JJA):

- Annual mean **8.6–11.1 °C**
- July **15.6–18.5 °C**
- January **1.8–5.3 °C**
- Annual rain roughly **580–1,020 mm** (wide because rainfall SE is large)

Do not invent other years. Do not interpolate a weather diary.

## Gold / Avon — use these figures

Gold (1971), Canadian ice roads:

P = A h^2

P in kg, h in cm of good clear floating ice, A ≈ 3.5 (conservative / river ice) to 4 (typical lake).

- 20 t sarsen, A=3.5: **76 cm**
- 40 t sarsen, A=3.5: **107 cm**
- 40 t, A=4: **100 cm**
- 50 t, A=3.5: **120 cm**

A metre of ice needs on the order of **4,000–5,000 freezing-degree-days**. A Wessex January whose millennial mean is ~3 °C does not supply that. Hill (1961) — sledging on *snow on land* — is a different, smaller claim. Say so.

## Timeline strip (required)

- ~3000 BC — Stonehenge I (ditch, first bluestones). Neolithic builders.
- ~2500 BC — Sarsen circle / trilithons.
- ~2450–2400 BC — Beaker arrivals; ancestry replacement starts.
- ~2200 BC — 4.2 ka interval (global drought *label*). Fenland yew woodland ends in wet / inundation terms, not a freeze. Roland et al. 2014: no coherent British–Irish peat event.

Do not draw a red crash arrow at 2400 BC. The Charman 2006 peat-stack cliff at that date is a plotting artefact (low replication at the start of the stack).

## Page structure (suggested)

1. Hero. One sentence. Four KPI chips. Link: “See the proxies.”
2. The Avon / Gold block. Formula, 40 t → ~1 m, January ~3 °C.
3. Timeline strip.
4. “What the graphs are not.” Three cards: Avon ice road; crash-then-Beakers; Pleistocene glacial delivery.
5. “What they are.” Moisture more than temperature; millennial slices; uncertainty is the point.
6. Footer: citations in one line each + “Full explorer, sources, series notes.”

## Visual direction

- Dark stone, lichen green, one brass highlight. Not teal-on-navy SaaS.
- Large type. Almost no decoration. If you use a picture of Stonehenge, use it once, still, no mist filter.
- Mobile first. The explorer is not.
- No Plotly unless you have a reason. Four numbers beat a chart on this page. If you chart, four millennial dots with error bars, not a smooth spline that looks like weather.

## Do not

- Do not scrape new climate numbers.
- Do not add SCOT2K, PAGES 2k, or “global temperature.”
- Do not show an ice sheet over Wiltshire.
- Do not write that Beakers were caused by climate, or that they were not. Write that replacement is genetic fact and the British climate series do not show a catastrophe that explains it.
- Do not vendor a second copy of the proxy database. Link.

## Definition of done

- One URL a journalist can be sent.
- Every factual climate number traceable to Mauri 2015 + Boscombe, or to Gold 1971.
- Two obvious links to `https://timdaw37.github.io/britain-climate-5000-2000bc/` (the explorer `index.html`).
- Works offline except webfonts, if any.
- English, not internationalised.

## After Build

If the output is static HTML/CSS/JS, drop it in the same repo as `story.html` (replace the first cut) and leave `index.html` as the explorer.
