# Sources — The Literature Data Product in 2026

Report: `2026-07-literature-ai/index.html`
Published: July 2026
Last verified: July 2026

Every factual claim in the explainer is listed below with its source and a confidence
rating. If you find an error, open an issue.

**Confidence key**
- **A** — Primary source: SEC filing, company results announcement, peer-reviewed paper, regulator document.
- **B** — Vendor announcement or press release. Accurate as to what was announced; claims within are the vendor's own.
- **C** — Third-party estimate or interested-party claim. Directional only.

---

## Screen 3 — The scoreboard

| Claim | Source | Confidence |
|---|---|---|
| Elsevier (RELX STM) 2024 revenue £3.05bn | RELX FY2024 results, 13 Feb 2025 | A |
| STM adjusted operating profit £1.17bn | RELX FY2024 results | A |
| STM adjusted operating margin 38.4% | RELX FY2024 results | A |
| STM underlying revenue growth +5% | RELX FY2024 results | A |
| RELX group revenue £9.43bn, adj. operating profit just under £3.2bn | RELX FY2024 results | A |
| Buybacks £1bn (2024), £1.5bn planned (2025) | RELX FY2024 results | A |
| Elsevier ~17% of global research output, ~29% of academic citations | RELX 2024 Annual Report | B — company's own measure, methodology not independently audited |
| Clarivate revenue $2.63bn (2023) → $2.56bn (2024) | Clarivate FY2024 8-K earnings release | A |
| Clarivate FY2024 net loss $636.7m | Clarivate FY2024 8-K | A |
| Clarivate share price ~$1.77 early 2026; 52-week high $4.91 | Market data, early 2026 | A — but time-sensitive, will be stale |
| Clarivate sold Life Sciences & Healthcare to Altaris for $600m | Clarivate Form 8-K, 6 July 2026 | A |
| Deal structure: $500m cash at closing, $25m deferred, $75m seller note | Clarivate 8-K, 6 July 2026 | A |
| ~97% of Clarivate revenue is proprietary | Clarivate investor materials / "Intelligence Amplified" positioning | B — company's own framing |
| Clarivate 88% recurring revenue mix; 2026 guidance 2–3% organic ACV growth | Clarivate Q4 2025 materials | A — guidance is forward-looking, not fact |

**Note on the framing.** The "same market, opposite outcomes" comparison and the conclusion
that ownership alone wasn't the moat is my interpretation, not a claim either company makes.
The financials are theirs; the argument is mine.

---

## Screen 4 — The phase shift

| Claim | Source | Confidence |
|---|---|---|
| Web of Science Research Assistant launched Sept 2024 | Clarivate announcement | B |
| Scopus AI, Dimensions Research GPT as 2023–24 chat-era products | Vendor product pages | B |
| Reaxys AI Search, July 2025, NLQ over 121m documents incl. 46m patents | Elsevier product page | B |
| CAS SciFinder "SearchSense", 7 Aug 2025 | CAS press release | B |
| CAS: "During beta testing, 93% of users reported improved efficiency" | CAS press release | C — vendor-reported, no published methodology |
| ScienceDirect AI launched March 2025 | Elsevier announcement | B |
| Elsevier LeapSpace live Jan 2026, incl. Trust Cards, Claim Radar | Elsevier / RELX materials | B |
| Causaly Discover agentic AI (Mar 2025), Agentic Research (Sept 2025), Scientific Workflows (May 2026) | Causaly press releases | B |
| CAS "Newton" agentic assistant, 2025 | CAS press release | B |
| Norstella Atlas CI — agentic, sourced PPTX deliverables | Norstella / Evaluate product page | B |
| Wiley AI Gateway, 13 Oct 2025, MCP endpoint, 8M+ articles from 2,000+ journals | Wiley announcement | B |
| Clarivate Nexus Connect MCP gateway, early access July 2026 | Clarivate announcement | B |
| Web of Science Research Intelligence global launch 6 May 2026 | Clarivate announcement | B |
| Norstella: 74bn+ linked data points, 1.5m records tagged to 55 ontologies | Norstella materials | C — vendor-reported |
| Causaly knowledge graph: 500m+ facts, 70m+ directional relationships | Causaly materials | C — vendor-reported |

**Weak point.** The three-phase framing (chat → AI-aided search → agentic) is my synthesis
of the shipping record, not something the industry formally declares. The "chat is not the
product" consensus is drawn from practitioner commentary rather than a citable position
paper. Directionally well-supported by what vendors actually shipped; not a hard citation.

---

## Screen 5 — The threat and the flaw

| Claim | Source | Confidence |
|---|---|---|
| Fabricated citations: 4 per 10,000 papers (2023) → 51.3 per 10,000 (Q4 2025) | Topaz et al., "Fabricated citations: an audit across 2·5 million biomedical papers," *The Lancet*, 7 May 2026 | A |
| Audit scope: PubMed Central OA subset, Jan 2023–Feb 2026, ~2.47m papers / ~125.6m references | Topaz et al., *The Lancet*, 2026 | A |
| Rise begins mid-2024, coinciding with mainstream AI writing tools | Topaz et al., *The Lancet*, 2026 | A — the paper notes the coincidence; causation is inferred, not established |
| Review articles show 57% higher fabrication rate | Topaz et al., *The Lancet*, 2026 | A |
| GPT-4o fabricated 19.9% of citations across six simulated literature reviews | *JMIR Mental Health*, 17 Nov 2025 | A |
| GPT-3.5 fabrication 55%, GPT-4 18% | Walters & Wilder, 2023 | A — dated; models have changed |
| Retrieval-augmented settings still fabricate 3–13% of URLs | Cited in the above literature | B — secondary citation, not verified at source |
| GPT-4 literature retrieval recall 0.073 vs 0.782 for structured tool | TrialMind study | B — single study, narrow task |
| Deep research modes: Perplexity Deep Research launched Feb 2025 | Perplexity announcement | B |

**Chart integrity note.** The Lancet audit gives two hard endpoints: 4 per 10,000 (2023)
and 51.3 per 10,000 (Q4 2025), and states the inflection begins mid-2024. An earlier draft
of this explainer showed four bars, two of which were interpolated — that was wrong and has
been corrected. The published chart shows only the two measured values, with the mid-2024
inflection marked as an annotation rather than a fabricated data point.

---

## Screen 6 — The licensing paradox

| Claim | Source | Confidence |
|---|---|---|
| Wiley AI licensing revenue $40m FY2025, up from $23m FY2024 | Wiley earnings release, 17 June 2025 | A |
| Includes an $18m agreement with a "third tech company" | Wiley earnings release, June 2025 | A |
| Wiley FY2025 customers include large tech, pharma and chemical companies | Wiley FY2025 proxy | A |
| Informa 2024 AI partnerships generated $75m+ non-recurring data access revenue | Informa 2024 Annual Report | A |
| Microsoft deal (May 2024): "$10m+" initial fee, 2024–2027, ~3,000 academic journals | Informa 2024 Annual Report | A |

**Note.** "Selling rope to the hangman" is editorial. The publishers would say — with some
justification — that the licensing revenue funds the AI products that constitute their
defence, and that non-exclusive licensing doesn't transfer the structured layer. That
counterargument is real and the explainer doesn't give it much room.

---

## Screen 7 — The imperatives

| Claim | Source | Confidence |
|---|---|---|
| FDA draft guidance on AI in regulatory decision-making issued 6 Jan 2025; comments closed 7 Apr 2025 | FDA | A |
| Risk-based credibility framework tied to context of use | FDA draft guidance, Jan 2025 | A |
| CDER received 500+ submissions with AI components since 2016; CBER 560+ | FDA (Tala Fakhouri, to MedCentral, 17 Jan 2025) | B — reported statement, not a filing |
| Wolters Kluwer UpToDate Expert AI launched Oct 2025 | Wolters Kluwer announcement | B |
| Adopted across ~70% of largest enterprise health systems, 1,600 US hospitals | Wolters Kluwer materials | C — vendor-reported |
| Wolters Kluwer FY2025 revenue €6.1bn; cloud revenue +15% | Wolters Kluwer FY2025 results | A |
| AI-assisted PV screening reduces workload (~58% average reduction cited) | Secondary literature | C — varies enormously by study design and use case |
| Causaly "93% accuracy on biomedical claims" | Causaly materials | C — vendor-reported, no published methodology |

---

## Market sizing — deliberately excluded

The explainer mentions the range but doesn't build on it, and that's on purpose.

| Estimate | Source |
|---|---|
| $12.65bn global scientific & technical publishing (2022) | Simba Information |
| $34–36bn "STM publishing" (2024–2026), 3–4.8% CAGR | Various market research firms |

These differ by ~3x because they're measuring different things — journals only vs. journals
plus data, analytics and workflow tools. Any single number here is close to meaningless
without its definition attached. The company filings above are the reliable ground.

---

## Known gaps

- **First-party MCP servers** were confirmed for Wiley and Clarivate only. Whether CAS,
  Dimensions or Causaly have shipped them is unverified — the "context-for-agents" thesis
  is directionally strong but its scale is unproven.
- **No independent benchmarks exist** for any vendor's accuracy claims. Every accuracy
  figure in this report is self-reported by an interested party. This is itself one of the
  report's findings.
- **Springer Nature and IQVIA** are named in the market map but not analysed. Springer
  Nature FY2024: revenue €1,847m (+5% underlying), adj. operating profit €512m — solid but
  didn't advance the argument.
- **Forward-looking guidance is not fact.** Clarivate's 2026 ACV guidance and the LS&H
  deal close are projections and agreements, not realised results.
