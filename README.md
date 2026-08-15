# Available .LOCKER One-Word Domains (15,918)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-15%2C918%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .locker one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **15,918 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 15,918 domains · **Median ask:** $171.59 · **High-demand under $2,500:** 47

**Last updated:** 2026-08-15
**Canonical page:** `https://unique.domains/domains/tld/locker`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/locker?utm_source=github&utm_medium=referral&utm_campaign=repo_locker_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./locker.csv">CSV</a> / <a href="./locker.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_locker_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_locker_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .LOCKER search](https://unique.domains/domains/tld/locker?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_locker_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .LOCKER search](https://unique.domains/domains/tld/locker?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_locker_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_locker_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .LOCKER one-word domain catalog.

### Files

- `locker.csv`, public CSV extract (1,000 rows)
- `locker.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/locker-oneword-domains/main/locker.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain      | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ----------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| vii.locker  | available | $6.88     | $37.99        | low            | low    | 3      | namesilo  |
| give.locker | resell    | —         | —             | high           | low    | 4      | GoDaddy   |
| ace.locker  | premium   | $6,500    | $58.50        | high           | medium | 3      | namecheap |
| adam.locker | available | $13.25    | $37.99        | medium         | high   | 4      | namesilo  |
| ass.locker  | premium   | $159.23   | $8.80         | low            | low    | 3      | namesilo  |
| atop.locker | available | $13.25    | $37.99        | medium         | low    | 4      | namesilo  |
| bad.locker  | premium   | $145.46   | $8.05         | high           | medium | 3      | namesilo  |
| axle.locker | available | $13.25    | $37.99        | high           | high   | 4      | namesilo  |
| bob.locker  | premium   | $145.46   | $8.05         | high           | medium | 3      | namesilo  |
| calf.locker | available | $13.25    | $37.99        | high           | low    | 4      | namesilo  |
| btw.locker  | premium   | $145.46   | $8.05         | high           | low    | 3      | namesilo  |
| camo.locker | available | $13.25    | $37.99        | high           | low    | 4      | namesilo  |
| dad.locker  | premium   | $290.91   | $8.05         | high           | low    | 3      | namesilo  |
| cent.locker | available | $13.25    | $37.99        | high           | low    | 4      | namesilo  |
| egg.locker  | premium   | $145.46   | $8.05         | high           | low    | 3      | namesilo  |
| cows.locker | available | $19.99    | —             | medium         | low    | 4      | name.com  |
| Eid.locker  | premium   | $145.46   | $8.05         | high           | low    | 3      | namesilo  |
| cyan.locker | available | $13.25    | $37.99        | high           | low    | 4      | namesilo  |
| fly.locker  | premium   | $3,136.33 | $8.05         | high           | low    | 3      | namesilo  |
| flop.locker | available | $13.25    | $37.99        | medium         | low    | 4      | namesilo  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 15,918 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 47 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/locker?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_locker_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/locker?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_locker_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_locker_oneword_domains&utm_content=related_pricing)

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

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection covers one-word and short compound .locker domain names spanning wellness, home, business, and lifestyle themes — from dogwalking.locker to makehistory.locker. With 12,382 names and a median asking price near $261, .locker offers a lower-cost path to a clean, memorable domain outside the mainstream extensions. When comparing these domains, weigh word clarity, renewal cost, and category fit before choosing a name to buy.

- 12,382 one-word .locker domains across many themes
- Median asking price near $261 in this set
- Names span wellness, home, tech, and lifestyle
- Compare renewal cost before locking in a name

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .LOCKER One-Word Domains*. Version 2026-08-15. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .LOCKER page](https://unique.domains/domains/tld/locker?utm_source=github&utm_medium=referral&utm_campaign=repo_locker_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_locker_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_locker_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_locker_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
