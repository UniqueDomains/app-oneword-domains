# Available .APP One-Word Domains (67,357)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-67%2C357%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .app one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **67,357 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 67,357 domains · **Median ask:** $41.84 · **High-demand under $2,500:** 95

**Last updated:** 2026-09-25
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

- `app.csv`, public CSV extract (1,000 rows)
- `app.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/app-oneword-domains/main/app.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain       | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                 |
| ------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------------- |
| cxxv.app     | available | $10.98    | $22.98        | high           | low    | 4      | namecheap                                                 |
| advise.app   | resell    | $5,173.85 | $123.75       | high           | high   | 6      | Global Domains International, Inc. DBA DomainCostClub.com |
| beaded.app   | premium   | $57.82    | $57.82        | high           | low    | 6      | namesilo                                                  |
| lxvi.app     | available | $10.98    | $22.98        | high           | low    | 4      | namecheap                                                 |
| aja.app      | resell    | —         | —             | high           | high   | 3      | Dynadot LLC.                                              |
| painful.app  | premium   | $57.82    | $57.82        | high           | low    | 7      | namesilo                                                  |
| aargh.app    | available | $9.99     | $22.99        | high           | high   | 5      | name.com                                                  |
| arr.app      | resell    | —         | —             | high           | high   | 3      | BF Internet Limited                                       |
| warfare.app  | premium   | $248.75   | —             | high           | low    | 7      | name.com                                                  |
| aback.app    | available | $6.98     | $22.98        | high           | low    | 5      | namecheap                                                 |
| ate.app      | resell    | —         | —             | high           | low    | 3      | GrepApps Technology Inc.                                  |
| barbeque.app | premium   | $61.25    | —             | high           | low    | 8      | name.com                                                  |
| ended.app    | available | $10.98    | $22.98        | high           | low    | 5      | namecheap                                                 |
| bho.app      | resell    | —         | —             | high           | high   | 3      | West263 International Limited                             |
| buddhist.app | premium   | $118.80   | $118.80       | high           | low    | 8      | namesilo                                                  |
| ropey.app    | available | $6.98     | $22.98        | high           | medium | 5      | namecheap                                                 |
| brs.app      | resell    | —         | —             | high           | low    | 3      | West263 International Limited                             |
| cocktail.app | premium   | $1,998.75 | —             | high           | low    | 8      | name.com                                                  |
| scads.app    | available | $6.98     | $22.98        | high           | low    | 5      | namecheap                                                 |
| deq.app      | resell    | —         | —             | high           | low    | 3      | West263 International Limited                             |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 67,357 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 95 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/app?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_app_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/app?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_app_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_app_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.
- `status_verified_at`, When status was last established against the registry. Null means never checked.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list of domains covers one-word names on the .app extension, spanning tech-forward, playful, and elegant styles. Most are available now, with a small share carrying premium or resale status. Pricing skews low, but a handful of high-demand names command five-figure reference value relative to their ask.

- 54,122 of 57,698 domains are available now
- Median ask price is about $105 per domain
- 37,745 names score in the high-demand range (70-84)
- 4,882 domains are priced under $500

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The snapshot date above is when this file was written, not when each row was checked. Read `status_verified_at` for that: a name whose status was last established months ago is exported with its real date rather than the snapshot's.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .APP One-Word Domains*. Version 2026-09-25. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .APP page](https://unique.domains/domains/tld/app?utm_source=github&utm_medium=referral&utm_campaign=repo_app_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_app_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_app_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_app_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `kai@unique.domains`
