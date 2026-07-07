# Available .VOTE One-Word Domains (12,180)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C180%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .vote one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,180 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,180 domains · **Median ask:** $53.22 · **High-demand under $2,500:** 0

**Last updated:** 2026-07-07
**Canonical page:** `https://unique.domains/domains/tld/vote`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/vote?utm_source=github&utm_medium=referral&utm_campaign=repo_vote_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./vote.csv">CSV</a> / <a href="./vote.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_vote_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_vote_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .VOTE search](https://unique.domains/domains/tld/vote?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_vote_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .VOTE search](https://unique.domains/domains/tld/vote?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_vote_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_vote_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .VOTE one-word domain catalog.

### Files

- `vote.csv`, public CSV extract (1,000 rows)
- `vote.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/vote-oneword-domains/main/vote.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                          |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------------------------------------------------------ |
| apt.vote       | available | $49.99    | —             | high           | low    | 3      | name.com                                                           |
| easy.vote      | resell    | —         | —             | high           | medium | 4      | Virtualia LLC                                                      |
| gold.vote      | premium   | $195      | $195          | high           | medium | 4      | namecheap                                                          |
| awe.vote       | available | $49.99    | —             | high           | low    | 3      | name.com                                                           |
| alert.vote     | resell    | —         | —             | medium         | low    | 5      | Domain Science Kutatási Szolgáltató Korlátolt Felelősségű Társaság |
| country.vote   | premium   | $53.92    | $53.92        | high           | low    | 7      | namesilo                                                           |
| bce.vote       | available | $49.99    | —             | medium         | low    | 3      | name.com                                                           |
| right.vote     | resell    | —         | —             | high           | low    | 5      | NameCheap, Inc.                                                    |
| england.vote   | premium   | $854      | $854          | high           | low    | 7      | namesilo                                                           |
| cap.vote       | available | $49.99    | —             | high           | low    | 3      | name.com                                                           |
| america.vote   | resell    | —         | —             | high           | low    | 7      | NameSilo, LLC                                                      |
| bullying.vote  | premium   | $187.50   | —             | medium         | low    | 8      | name.com                                                           |
| cut.vote       | available | $49.99    | $127.99       | high           | low    | 3      | name.com                                                           |
| prolife.vote   | premium   | $187.50   | —             | medium         | low    | 8      | name.com                                                           |
| DJI.vote       | available | $49.99    | —             | high           | low    | 3      | name.com                                                           |
| prochoice.vote | premium   | $187.50   | —             | medium         | low    | 10     | name.com                                                           |
| dye.vote       | available | $49.99    | —             | medium         | low    | 3      | name.com                                                           |
| fly.vote       | available | $49.99    | —             | high           | low    | 3      | name.com                                                           |
| gas.vote       | available | $49.99    | —             | high           | low    | 3      | name.com                                                           |
| ivy.vote       | available | $49.99    | —             | high           | low    | 3      | name.com                                                           |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,180 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/vote?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_vote_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/vote?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_vote_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_vote_oneword_domains&utm_content=related_pricing)

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

This selection covers .vote domain names built for election campaigns, civic-tech products, and advocacy brands. It spans single-word names like WiFi.vote alongside compound names such as TakeABreak.vote and WonderWoman.vote, giving both investors and founders a range of pricing tiers to evaluate. Median ask across the set is near $53, keeping most names within reach for direct registration rather than resale premiums. Updated daily, the list reflects current availability across roughly 12,180 .vote names.

- 12,180 .vote domain names in this selection
- Median ask near $53 across the set
- Names span elections, civic tech, and advocacy themes
- Mix of short, brandable, and compound-word options

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .VOTE One-Word Domains*. Version 2026-07-07. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .VOTE page](https://unique.domains/domains/tld/vote?utm_source=github&utm_medium=referral&utm_campaign=repo_vote_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_vote_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_vote_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_vote_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
