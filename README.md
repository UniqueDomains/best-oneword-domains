# Available .BEST One-Word Domains (8,351)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-8%2C352%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-8%2C351%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated dataset of available and resale .best one-word domains from Unique Domains.

> **Note:** this repository currently mirrors the full live catalog for this exact search.
> Unique Domains counts can still change as the search refreshes.

**Public extract:** 8,352 rows · **Live catalog:** 8,351 domains

**Last updated:** 2026-04-13  
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

- `best.csv` — public CSV extract (8,352 rows)
- `best.json` — public JSON extract (8,352 rows)
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

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| nationwide.best | available | $23.08    | —             | 76             | 66     | 10     | namecheap       |
| unity.best      | resell    | $5,748.85 | $29.99        | 70             | 40     | 5      | Dynadot LLC     |
| indeed.best     | premium   | $91       | $91           | 86             | 85     | 6      | namecheap       |
| april.best      | available | $23.08    | —             | 74             | 63     | 5      | namecheap       |
| leaf.best       | resell    | $5,921.32 | —             | 82             | 35     | 4      | Dynadot LLC     |
| power.best      | premium   | $518.96   | $518.96       | 98             | 62     | 5      | namecheap       |
| seventeen.best  | available | $23.08    | —             | 84             | 61     | 9      | namecheap       |
| lord.best       | resell    | $5,748.85 | $29.99        | 84             | 28     | 4      | Dynadot LLC     |
| data.best       | premium   | $1,038.96 | $1,038.96     | 70             | 56     | 4      | namecheap       |
| athletics.best  | available | $23.08    | —             | 69             | 52     | 9      | namecheap       |
| rise.best       | resell    | —         | —             | 62             | 98     | 4      | Spaceship, Inc. |
| true.best       | premium   | $91       | $91           | 86             | 52     | 4      | namecheap       |
| gather.best     | available | $23.08    | —             | 96             | 38     | 6      | namecheap       |
| orange.best     | resell    | —         | —             | 74             | 83     | 6      | Key-Systems LLC |
| one.best        | premium   | $1,038.96 | $1,038.96     | 132            | 50     | 3      | namecheap       |
| conscious.best  | available | $23.08    | —             | 89             | 38     | 9      | namecheap       |
| universal.best  | resell    | —         | —             | 96             | 81     | 9      | Dynadot LLC     |
| big.best        | premium   | $1,038.96 | $1,038.96     | 88             | 47     | 3      | namecheap       |
| forward.best    | available | $23.08    | —             | 68             | 38     | 7      | namecheap       |
| kick.best       | resell    | —         | —             | 98             | 80     | 4      | Sav.com, LLC    |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 8,352-row public sample | 8,351 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

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

> Unique Domains. *Available .BEST One-Word Domains*. Version 2026-04-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .BEST page](https://unique.domains/domains/tld/best?utm_source=github&utm_medium=referral&utm_campaign=repo_best_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_best_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_best_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_best_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
