# Google SERP & Search-Intent Analysis

Analysis of Google first-page results for five target keywords, each chosen to represent a different search intent, to understand how SERPs are built and where content opportunities exist.

**Tools:** Google Search, Google Sheets

## Keywords & intent

| Keyword | Primary intent | Dominant SERP feature |
|---|---|---|
| how to learn python | Informational | Step-list featured snippet, People Also Ask, videos |
| best laptop for programming | Commercial | Shopping carousel, product listicles |
| react vs angular | Commercial investigation | Comparison snippet, PAA |
| best biryani in hyderabad | Local / Transactional | Local map pack |
| github login | Navigational | Single brand result with sitelinks |

## Key findings

- **Format follows intent:** "how to" → numbered guides, "best X" → listicles with spec tables, "X vs Y" → side-by-side comparisons, local → map pack, brand → one domain.
- **Year in the title** is near-universal for informational and commercial queries.
- **FAQ sections** mirror People Also Ask questions on almost every informational page.
- **Stale pages still rank** (outdated Angular versions, a 2024 biryani list), so a genuinely fresh page has a real chance.
- **Navigational SERPs are closed** to third parties.

## Top content opportunities

1. **react vs angular** – 2026 comparison with the same app built in both, real bundle/performance numbers, decision flowchart.
2. **how to learn python** – project-first 30-day roadmap with a GitHub starter repo.
3. **best laptop for programming** – brand-neutral guide by budget and tech stack with real build benchmarks.

## Repository structure

```
├── README.md
├── report/SERP_Analysis_Report.pdf      # full report (5 pages)
├── data/
│   ├── SERP_Keyword_Analysis.xlsx       # import into Google Sheets
│   ├── keyword_analysis.csv
│   ├── serp_observations.csv
│   └── intent_classification.csv
└── screenshots/                          # SERP screenshots for each keyword
```

## Method

1. Selected five keywords covering every major intent type.
2. Searched each on Google (India) and recorded the first-page results in Google Sheets.
3. Logged content type, title, format and SERP features for each ranking page.
4. Classified intent from the SERP layout and identified gaps across ranking pages.

> Google results vary by location, device and personalisation; positions are approximate.

**Author:** Sadhanala Nischay Prasad
