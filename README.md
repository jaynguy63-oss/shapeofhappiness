# The Shape of Happiness

An interactive data visualisation exploring the relationship between national wealth and happiness across 146 countries from 2019 to 2025.

**Live site:** https://jaynguy63-oss.github.io/shapeofhappiness/

![Cover image of the interactive showing flower glyphs on a wealth-happiness scatter plot](preview.png)

---

## About this project

This is the A2 interactive submission for DECO2200/7220 (Information Visualisation) at the University of Queensland. It extends the static A1 poster ("The Happiness Paradox") into an animated, interactive piece that lets viewers explore how the wealth–happiness relationship has changed over seven years.

Each country is rendered as a flower glyph. Position on the chart shows wealth (x-axis) and happiness (y-axis). Petal length shows the magnitude of each underlying factor — wealth, social support, health, freedom, generosity, and low corruption — with each petal coloured by factor type. Eight countries are featured as a curated cast representing four quadrants of the chart; the remaining 138 countries appear as hover-identifiable grey dots in the background.

## How to view

**Online:** Just open the [live site](https://jaynguy63-oss.github.io/shapeofhappiness/).

**Locally:** Download `index.html` and open it in any modern browser (Chrome, Firefox, Safari, Edge). No installation required — the file is self-contained and loads D3.js from a CDN.

## How to use

- **Year slider (2019–2025):** drag to see how the wealth–happiness relationship has changed
- **Play button:** animate through the years automatically
- **Hover any flower or background dot:** see the country name, happiness score, and factor breakdown
- **Click any flower:** pin its seven-year trail at the bottom of the page, showing how its shape has evolved
- **Reset button:** return to the 2025 view

## Built with

- **HTML, CSS, vanilla JavaScript** — no framework
- **[D3.js v7](https://d3js.org/)** (Mike Bostock, ISC License) — for SVG rendering, scales, and transitions
- **[Inter typeface](https://rsms.me/inter/)** (Rasmus Andersson, SIL Open Font License)
- **GitHub Pages** — for hosting

All visual design, glyph paths, layout, captions, and colour decisions are original. The flower glyph form is inspired by [Moritz Stefaner's OECD Better Life Index](https://www.oecd.org/en/data/tools/well-being-data-monitor/better-life-index.html).

## Data source

[World Happiness Report 2026](https://worldhappiness.report/ed/2026/) (Helliwell et al., Wellbeing Research Centre, University of Oxford), plus historical panel data 2019–2025 for 146 countries.

## Acknowledgements

Built with step-by-step coding assistance from Claude (Anthropic), as permitted by the course tutor. All design decisions, country selection, narrative, and written content are my own. See `Statement_of_Original_Work.docx` for full declaration.

## Author

Le Thao Trang Nguyen (Jay Nguyen) · s49026812 · DECO2200/7220 · 2026
