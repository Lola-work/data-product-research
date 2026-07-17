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
| 2026-07 | [The Literature Data Product in 2026](https://lola-work.github.io/data-product-research/2026-07-literature-ai/) | Elsevier runs a 38.4% margin; Clarivate just sold its Life Sciences arm for $600m. Both own proprietary content. So ownership was never the moat. |

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
