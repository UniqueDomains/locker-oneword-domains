# Available .LOCKER One-Word Domains (12,382)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C382%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .locker one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,382 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,382 domains · **Median ask:** $398.12 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-11  
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

- `locker.csv` — public CSV extract (1,000 rows)
- `locker.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/locker-oneword-domains/main/locker.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| Uber.locker      | available | $56.98    | —             | 88             | 85     | 4      | namecheap |
| Trex.locker      | available | $56.98    | —             | 80             | 24     | 5      | namecheap |
| jewels.locker    | available | $19.99    | —             | 80             | 15     | 6      | name.com  |
| geton.locker     | available | $19.99    | —             | 82             | 10     | 6      | name.com  |
| Adidas.locker    | available | $56.98    | —             | 88             | 23     | 6      | namecheap |
| playin.locker    | available | $19.99    | —             | 80             | 10     | 7      | name.com  |
| makeit.locker    | available | $19.99    | —             | 82             | 22     | 7      | name.com  |
| stirup.locker    | available | $19.99    | —             | 82             | 3      | 7      | name.com  |
| dogsick.locker   | available | $19.99    | —             | 90             | 1      | 7      | name.com  |
| getlife.locker   | available | $19.99    | —             | 80             | 5      | 8      | name.com  |
| Snickers.locker  | available | $56.98    | —             | 80             | 10     | 8      | namecheap |
| rumcake.locker   | available | $19.99    | —             | 81             | 3      | 8      | name.com  |
| FabFour.locker   | available | $13.25    | $37.99        | 82             | 3      | 8      | namesilo  |
| winners.locker   | premium   | $290.91   | $8.05         | 60             | 81     | 7      | namesilo  |
| Spotify.locker   | available | $56.98    | —             | 78             | 69     | 7      | namecheap |
| online.locker    | premium   | $6,250    | —             | 70             | 62     | 7      | name.com  |
| RedSox.locker    | available | $56.98    | —             | 72             | 60     | 7      | namecheap |
| travelers.locker | premium   | $290.91   | $8.05         | 58             | 61     | 9      | namesilo  |
| regions.locker   | available | $19.99    | —             | 64             | 59     | 7      | name.com  |
| farmers.locker   | premium   | $250      | —             | 54             | 59     | 7      | name.com  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,382 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/locker?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_locker_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/locker?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_locker_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_locker_oneword_domains&utm_content=related_pricing)

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

This set is entirely focused on one-word .locker domains. The strongest candidates are simple, readable words that feel natural with the .locker ending and remain easy to recall after a single view. Examples in this selection range from generic terms such as finals.locker and jewels.locker to names that raise clear trademark questions, such as Uber.locker and Adidas.locker. When comparing these domains, start with commercial clarity: does the word create a clean, ownable phrase with .locker, and is the ask justified? With a median ask of $398.12, disciplined buyers should favor names with broad meaning, low ambiguity, and no obvious brand conflict.

- Favor words that read naturally with the .locker extension
- Median ask is $398.12 across this .locker selection
- Avoid obvious trademark conflicts in branded terms
- Prefer memorable generics over forced or unclear wording

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .LOCKER One-Word Domains*. Version 2026-05-11. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .LOCKER page](https://unique.domains/domains/tld/locker?utm_source=github&utm_medium=referral&utm_campaign=repo_locker_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_locker_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_locker_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_locker_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
