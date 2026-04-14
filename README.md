# Available .APP One-Word Domains (57,265)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-10%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-57%2C265%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .app one-word domains from Unique Domains.

> **Important:** this repository is a **public 10,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **57,265 domains** on the canonical page below.

**Public extract:** 10,000 rows · **Live catalog:** 57,265 domains

**Last updated:** 2026-04-14  
**Canonical page:** `https://unique.domains/domains/tld/app`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/app?utm_source=github&utm_medium=referral&utm_campaign=repo_app_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./app.csv">CSV</a> / <a href="./app.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_app_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_app_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .APP search](https://unique.domains/domains/tld/app?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_app_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .APP search](https://unique.domains/domains/tld/app?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_app_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_app_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .APP one-word domain catalog.

### Files

- `app.csv` — public CSV extract (10,000 rows)
- `app.json` — public JSON extract (10,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/app-oneword-domains/main/app.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain              | status    | ask_price  | renewal_price | attractiveness | demand | length | registrar                                                 |
| ------------------- | --------- | ---------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------------- |
| aback.app           | available | $9.99      | $22.99        | 76             | 80     | 5      | name.com                                                  |
| adviser.app         | resell    | $16,042.50 | $61.25        | 80             | 16     | 7      | Sav.com, LLC                                              |
| visualart.app       | premium   | $4,370     | $26.99        | 64             | 92     | 10     | name.com                                                  |
| refining.app        | available | $9.99      | $26.99        | 58             | 80     | 8      | name.com                                                  |
| adlib.app           | resell    | $16,847.50 | $22.99        | 88             | 7      | 6      | Global Domains International, Inc. DBA DomainCostClub.com |
| mathematics.app     | premium   | $498.75    | $498.75       | 64             | 92     | 11     | name.com                                                  |
| tillage.app         | available | $9.99      | $26.99        | 62             | 76     | 7      | name.com                                                  |
| gps.app             | resell    | —          | —             | 104            | 96     | 3      | GoDaddy.com, LLC                                          |
| algebra.app         | premium   | $998.75    | $998.75       | 68             | 88     | 7      | name.com                                                  |
| plastering.app      | available | $9.99      | $26.99        | 58             | 76     | 10     | name.com                                                  |
| rando.app           | resell    | —          | —             | 70             | 96     | 5      | Namecheap Inc.                                            |
| admission.app       | premium   | $498.75    | $498.75       | 66             | 88     | 9      | name.com                                                  |
| aargh.app           | available | $9.99      | $22.99        | 56             | 76     | 5      | name.com                                                  |
| joker.app           | resell    | —          | —             | 62             | 96     | 5      | Porkbun LLC                                               |
| litigation.app      | premium   | $248.75    | $248.75       | 54             | 88     | 10     | name.com                                                  |
| ABCIslands.app      | available | $20.98     | —             | 57             | 72     | 11     | namecheap                                                 |
| coyote.app          | resell    | —          | —             | 56             | 96     | 6      | GoDaddy.com, LLC                                          |
| stamping.app        | premium   | $61.25     | $61.25        | 60             | 84     | 8      | name.com                                                  |
| batchproduction.app | available | $9.99      | $26.99        | 56             | 72     | 16     | name.com                                                  |
| prestige.app        | resell    | —          | —             | 96             | 92     | 8      | GoDaddy.com, LLC                                          |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract           | Unique Domains                                   |
| ------------------------ | ------------------------------------------------ |
| 10,000-row public sample | 57,265 live domains                              |
| Static CSV / JSON        | live search and daily refresh                    |
| Basic exported fields    | deeper price, demand, risk, and workflow context |
| No persistence           | Radar, saved search, and alerts                  |
| No founder workflow      | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/app?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_app_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/app?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_app_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_app_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .APP One-Word Domains*. Version 2026-04-14. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .APP page](https://unique.domains/domains/tld/app?utm_source=github&utm_medium=referral&utm_campaign=repo_app_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_app_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_app_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_app_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
