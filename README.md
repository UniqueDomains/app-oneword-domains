# Available .APP One-Word Domains

42,767 one-word .app names are free to register today, from $7.99 the first year at GoDaddy. Renewal there $19.99, three times the first year. 92 .app sales in the last 12 months, median $1,267.

Live page: [unique.domains/tld/app](https://unique.domains/tld/app?utm_source=github&utm_medium=referral&utm_campaign=repo_app_oneword_domains&utm_content=top_tld_page)

<img alt="updated: daily" src="https://img.shields.io/badge/updated-daily-0969da"> <img alt="extract: 1,000 rows" src="https://img.shields.io/badge/extract-1%2C000%20rows-8250df"> <img alt="formats: CSV | JSON" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b"> <img alt="licence: CC BY 4.0" src="https://img.shields.io/badge/licence-CC%20BY%204.0-2ea44f">

## Download

- [app.csv](https://github.com/UniqueDomains/app-oneword-domains/raw/main/app.csv), 1,000 rows
- [app.json](https://github.com/UniqueDomains/app-oneword-domains/raw/main/app.json), 1,000 rows

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/app-oneword-domains/main/app.csv")
print(df.head())
```

## Sample rows

The first 20 rows of the file, in the file's order.

| domain            | status    | purchase_price | renewal_price | attractiveness | demand | length |
| ----------------- | --------- | -------------- | ------------- | -------------- | ------ | ------ |
| chear.app         | available | $10.98         | $22.98        | high           | low    | 5      |
| plodded.app       | available | —              | —             | high           | high   | 7      |
| grampa.app        | available | $10.98         | $22.98        | high           | low    | 6      |
| undermine.app     | available | $10.99         | $16.99        | high           | low    | 9      |
| symbolise.app     | available | $7.99          | $19.99        | high           | low    | 9      |
| agnomen.app       | available | $10.99         | $16.99        | high           | low    | 7      |
| trumpeting.app    | available | $8.48          | $14.69        | high           | low    | 10     |
| rhomboid.app      | available | $6.98          | $22.98        | high           | low    | 8      |
| disembark.app     | available | $8.20          | $14.20        | high           | low    | 9      |
| egregious.app     | available | $8.48          | $14.69        | high           | low    | 9      |
| briny.app         | available | $8.48          | $14.69        | high           | low    | 5      |
| vhdl.app          | available | $8.20          | $14.20        | high           | low    | 4      |
| multinational.app | available | $8.75          | $14.93        | high           | low    | 13     |
| drinamyl.app      | available | —              | —             | high           | low    | 8      |
| rosebudding.app   | available | —              | —             | high           | low    | 11     |
| dualski.app       | available | $19.50         | —             | high           | low    | 7      |
| kimonolike.app    | available | —              | —             | high           | high   | 10     |
| antiparticle.app  | available | $10.99         | $16.99        | high           | low    | 12     |
| centroids.app     | available | —              | —             | medium         | low    | 9      |
| groundsheets.app  | available | —              | —             | medium         | low    | 12     |

## What is in the data

- `domain`: Fully qualified domain name.
- `status`: Current acquisition state for the domain in the public extract.
- `purchase_price`: Visible purchase price when available.
- `renewal_price`: Visible renewal price when available.
- `attractiveness`: Public composite naming band used as a decision-support signal.
- `demand`: Public buyer-pressure band when available.
- `length`: Character count without the TLD.
- `registrar`: Registrar name when known.
- `created_at`: Creation timestamp when known.
- `expires_at`: Expiry timestamp when known.

Types and formats: [DATA_DICTIONARY.md](./DATA_DICTIONARY.md).

## Methodology

- The files hold 1,000 rows of the 23,193 names in the live list today.
- Every row is a one-word domain name.
- Status and prices are the last ones Unique Domains stored for each name, not a reading taken on the day of the rebuild.

More in [METHODOLOGY.md](./METHODOLOGY.md).

## Update policy

- The files are rebuilt every night from the same export.
- The snapshot is the day of the rebuild; each row's status is the last one stored, not a reading of that day.
- The files hold the public extract, not the whole live list.

## How to cite

> Unique Domains, One-word .app domains, https://unique.domains/tld/app, CC BY 4.0

Citation metadata: [CITATION.cff](./CITATION.cff). A DOI follows once Zenodo mints one.

## Related datasets

- [Every one-word domain](https://github.com/UniqueDomains/oneword-domains) (the hub)

One-word domains by ending:

- [.com](https://github.com/UniqueDomains/com-oneword-domains), [page](https://unique.domains/tld/com?utm_source=github&utm_medium=referral&utm_campaign=repo_app_oneword_domains&utm_content=related_tld_page)
- [.ai](https://github.com/UniqueDomains/ai-oneword-domains), [page](https://unique.domains/tld/ai?utm_source=github&utm_medium=referral&utm_campaign=repo_app_oneword_domains&utm_content=related_tld_page)
- [.io](https://github.com/UniqueDomains/io-oneword-domains), [page](https://unique.domains/tld/io?utm_source=github&utm_medium=referral&utm_campaign=repo_app_oneword_domains&utm_content=related_tld_page)
- [.co](https://github.com/UniqueDomains/co-oneword-domains), [page](https://unique.domains/tld/co?utm_source=github&utm_medium=referral&utm_campaign=repo_app_oneword_domains&utm_content=related_tld_page)
- [.xyz](https://github.com/UniqueDomains/xyz-oneword-domains), [page](https://unique.domains/tld/xyz?utm_source=github&utm_medium=referral&utm_campaign=repo_app_oneword_domains&utm_content=related_tld_page)

Lists:

- [Expired](https://github.com/UniqueDomains/expired-oneword-domains)
- [Expiring](https://github.com/UniqueDomains/expiring-oneword-domains)
- [Brandable](https://github.com/UniqueDomains/brandable-oneword-domains)
- [Short](https://github.com/UniqueDomains/short-oneword-domains)

Every ending Unique Domains tracks: [unique.domains/tld](https://unique.domains/tld?utm_source=github&utm_medium=referral&utm_campaign=repo_app_oneword_domains&utm_content=related_hub).

## About Unique Domains

[Unique Domains](https://unique.domains/?utm_source=github&utm_medium=referral&utm_campaign=repo_app_oneword_domains&utm_content=about) tracks one-word domain names across the endings people build on: which are free to register, what they cost to hold and what names of each ending sell for. The datasets in this organization are its public extracts, refreshed every night.

Questions and corrections: `kai@unique.domains`

[Start a Radar for .app names](https://unique.domains/tld/app?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_app_oneword_domains&utm_content=about)
