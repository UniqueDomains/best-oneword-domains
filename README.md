# Available .BEST One-Word Domains (11,160)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C160%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .best one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,160 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,160 domains · **Median ask:** $62.83 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-08  
**Canonical page:** `https://unique.domains/domains/tld/best`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/best?utm_source=github&utm_medium=referral&utm_campaign=repo_best_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./best.csv">CSV</a> / <a href="./best.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_best_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_best_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .BEST search](https://unique.domains/domains/tld/best?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_best_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .BEST search](https://unique.domains/domains/tld/best?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_best_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_best_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .BEST one-word domain catalog.

### Files

- `best.csv` — public CSV extract (1,000 rows)
- `best.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/best-oneword-domains/main/best.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar   |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------- |
| won.best      | premium   | —         | —             | 90             | 19     | 3      | —           |
| finals.best   | available | $2.35     | $17.79        | 80             | 7      | 6      | namesilo    |
| barup.best    | available | $23.08    | —             | 82             | 2      | 6      | namecheap   |
| geton.best    | available | $23.08    | —             | 82             | 10     | 6      | namecheap   |
| getup.best    | available | $23.08    | —             | 82             | 14     | 6      | namecheap   |
| useit.best    | available | $23.08    | —             | 94             | 7      | 6      | namecheap   |
| alabama.best  | premium   | —         | —             | 80             | 19     | 7      | —           |
| gearup.best   | available | $23.08    | —             | 80             | 16     | 7      | namecheap   |
| playin.best   | available | $23.08    | —             | 80             | 10     | 7      | namecheap   |
| playon.best   | available | $23.08    | —             | 80             | 14     | 7      | namecheap   |
| hangon.best   | available | $23.08    | —             | 82             | 6      | 7      | namecheap   |
| getlife.best  | available | $23.08    | —             | 80             | 5      | 8      | namecheap   |
| Snickers.best | available | $23.08    | —             | 80             | 10     | 8      | namecheap   |
| rumcake.best  | available | $23.08    | —             | 81             | 3      | 8      | namecheap   |
| FabFour.best  | available | $2.35     | $17.79        | 82             | 3      | 8      | namesilo    |
| farmers.best  | available | $23.08    | —             | 54             | 59     | 7      | namecheap   |
| robots.best   | resell    | —         | —             | 62             | 47     | 6      | Dynadot LLC |
| donuts.best   | premium   | $98       | $98           | 54             | 62     | 6      | namecheap   |
| heroes.best   | available | $23.08    | —             | 68             | 29     | 6      | namecheap   |
| prompts.best  | resell    | —         | —             | 54             | 39     | 7      | Dynadot LLC |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,160 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/best?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_best_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/best?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_best_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_best_oneword_domains&utm_content=related_pricing)

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

This selection is defined by a single trait: every domain ends in .best. That creates a broad mix of dictionary words, surnames, short verbs, and brandable terms such as won.best, finals.best, getup.best, and detail.best. For founders, the main question is whether the phrase feels credible and memorable with .best attached. For investors, the key is price discipline, because the median ask is 62.74 and resale stats are not established here. When comparing these domains, favor words that read naturally, are easy to say, and do not create obvious trademark friction or awkward meaning with the extension.

- All names in this set use the .best extension
- Median ask across the selection is 62.74
- Check whether the word pairs naturally with .best
- Avoid names with clear trademark or ambiguity risk

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .BEST One-Word Domains*. Version 2026-05-08. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .BEST page](https://unique.domains/domains/tld/best?utm_source=github&utm_medium=referral&utm_campaign=repo_best_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_best_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_best_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_best_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
