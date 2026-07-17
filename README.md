# Data Product Research

Market research on data products in life sciences R&D. Visual explainers, primary sources, opinionated.


---

## The running thesis

For thirty years the product was the interface. AI ate the interface. What's left worth
paying for is structured, rights-cleared, traceable data delivered into a workflow someone
can be audited on.

Each report takes a market and asks whether that survives contact with the evidence. It's a
claim, not a conclusion — if a report ever falsifies it, that's a better report than one
that confirms it.

---

## Reports

| Date | Report | Thesis |
|---|---|---|
| 2026-07 | [The Literature Data Product in 2026](2026-07-literature-ai/) | Elsevier runs a 38.4% margin; Clarivate just sold its Life Sciences arm for $600m. Both own proprietary content. So ownership was never the moat. |

---

## Repo layout

```
data-product-research/
├── index.html              # the hub — states the thesis, indexes the reports
├── TEMPLATE.html           # proven skeleton, extracted from a working report
├── README.md
└── YYYY-MM-topic/          # one folder per report, dated
    ├── index.html          # the explainer
    └── sources.md          # every claim, traced, with confidence ratings
```

Dated folders because the date is load-bearing metadata — "what did this market look like
in July 2026" is a question people will actually ask later. One repo rather than one per
report, because the series is the asset. Ten repos with one page each is ten dead links.

---

## Writing a new report

**1. Find the spine before writing any markup.**
Four to seven beats, one idea each. Usually chronological (this happened, then this) or
causal (this problem, this response, this consequence). A report without a spine turns into
a pile of well-styled boxes.

**2. Build `sources.md` first, not last.**
Every claim, its source, a confidence rating, the date verified. Doing this first is faster
— you find out what you can't support before you've built a screen around it. It's also the
thing these reports argue vendors should do, so not doing it would be embarrassing.

Confidence key:
- **A** — primary source: filing, results announcement, peer-reviewed paper, regulator doc
- **B** — vendor announcement: accurate as to what was announced, claims within are theirs
- **C** — third-party estimate or interested-party claim: directional only

**3. Copy `TEMPLATE.html` into `YYYY-MM-topic/index.html` and fill it in.**
Sections are marked KEEP (structure) or REPLACE (content). The CSS block is the visual
language — leave it alone.

**4. Add the report to the hub `index.html` and the table above.**

**5. Check the chart integrity rule before publishing.** See below.

---

## Standards

These exist because a visual explainer applies constant pressure to smooth things. Charts
want clean curves; evidence is lumpy. Every report will tempt you to round a number or
invent a midpoint. That temptation is the failure mode of the format, not bad luck.

- **Filings over commentary.** Company results and regulator documents first. Vendor press
  releases are claims, not facts. Analyst market-sizing gets treated with suspicion — the
  published estimates for STM publishing range from $12.6bn to $36bn depending on
  definition, which makes any single figure close to meaningless.
- **Estimated data is labelled on the chart, not in a footnote.** If you have two measured
  points, draw two bars and a dashed line for direction. Don't invent the middle. The first
  version of the July 2026 report showed four bars, two of which were interpolated — that
  was wrong, and the correction is in the git history.
- **Gaps get stated.** Every `sources.md` ends with what couldn't be verified.
- **Interpretation is flagged.** The financials belong to the companies. The argument
  doesn't. Where a report is reading into the numbers, `sources.md` says so.
- **Nothing gets quietly edited.** Corrections are commits with a message saying what was
  wrong. The history is public, including the mistakes. This is the whole point — a series
  arguing that provenance is the moat cannot have an unauditable edit history.

---

## Style

Reports are single-file HTML in a hand-drawn whiteboard style — sketchy SVG, index-card
blocks, one concept per screen. Zero dependencies: no CDN, no webfonts, no API calls. They
have to open offline, on a locked-down laptop, in 2031.

The aesthetic does a job. A polished dashboard says "this is finished, evaluate it." A
sketch says "this is being explained to you, follow along." That framing is why the
deliberate imperfection matters.

The full visual language and the assembly rules live in the `whiteboard-explainer` skill.
Key details that are easy to get wrong:
- Wobbly beziers, never straight lines (`C` not `L`, control points offset 1-2px)
- Uneven `border-radius`, varied between cards
- Offset shadow with zero blur — `2px 3px 0 #e8e8e4`. A soft blur reads as generic.

---

## Publishing

GitHub Pages: Settings → Pages → Deploy from a branch → `main` / root.

Reports are point-in-time. Markets move; the dates are load-bearing.

---

## Corrections

Found an error? [Open an issue](https://github.com/[YOUR-USERNAME]/data-product-research/issues).
Corrections get credited.

---

## Licence

Consider CC BY 4.0 for the written analysis if you want it reused with attribution. Not yet
applied — add a `LICENSE` file when you decide.
