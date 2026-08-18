# Available .FM One-Word Domains (15,169)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-15%2C169%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .fm one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **15,169 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 15,169 domains · **Median ask:** $173.72 · **High-demand under $2,500:** 45

**Last updated:** 2026-08-18
**Canonical page:** `https://unique.domains/domains/tld/fm`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/fm?utm_source=github&utm_medium=referral&utm_campaign=repo_fm_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./fm.csv">CSV</a> / <a href="./fm.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_fm_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_fm_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .FM search](https://unique.domains/domains/tld/fm?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_fm_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .FM search](https://unique.domains/domains/tld/fm?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_fm_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_fm_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .FM one-word domain catalog.

### Files

- `fm.csv`, public CSV extract (1,000 rows)
- `fm.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/fm-oneword-domains/main/fm.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain    | status    | ask_price  | renewal_price | attractiveness | demand | length | registrar                  |
| --------- | --------- | ---------- | ------------- | -------------- | ------ | ------ | -------------------------- |
| ago.fm    | available | $99        | $160.99       | medium         | low    | 3      | name.com                   |
| new.fm    | resell    | —          | —             | high           | medium | 3      | BRS Media Inc.             |
| hit.fm    | premium   | $62,493.75 | —             | high           | low    | 3      | name.com                   |
| ain.fm    | available | $69.98     | $118.98       | low            | low    | 3      | namecheap                  |
| tax.fm    | resell    | —          | —             | high           | medium | 3      | 1API GmbH                  |
| lip.fm    | premium   | $1,243.75  | —             | high           | low    | 3      | name.com                   |
| bce.fm    | available | $88.99     | $88.99        | medium         | low    | 3      | namesilo                   |
| date.fm   | resell    | —          | —             | high           | low    | 4      | Dynadot LLC                |
| mix.fm    | premium   | $62,493.75 | $160.99       | medium         | low    | 3      | name.com                   |
| but.fm    | available | $88.99     | $88.99        | high           | low    | 3      | namesilo                   |
| boost.fm  | resell    | —          | —             | high           | low    | 5      | dotFM                      |
| pen.fm    | premium   | $368.75    | —             | medium         | low    | 3      | name.com                   |
| clv.fm    | available | $69.98     | $118.98       | low            | low    | 3      | namecheap                  |
| raise.fm  | resell    | —          | —             | high           | low    | 5      | Instra Corporation Pty Ltd |
| pre.fm    | premium   | $243.75    | —             | medium         | low    | 3      | name.com                   |
| coy.fm    | available | $99        | $160.99       | medium         | low    | 3      | name.com                   |
| shift.fm  | resell    | —          | —             | high           | medium | 5      | 1API GmbH                  |
| toy.fm    | premium   | $1,243.75  | —             | high           | low    | 3      | name.com                   |
| ixl.fm    | available | $69.98     | $118.98       | low            | low    | 3      | namecheap                  |
| campus.fm | resell    | —          | —             | high           | low    | 6      | 1API GmbH                  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 15,169 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 45 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/fm?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_fm_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/fm?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_fm_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_fm_oneword_domains&utm_content=related_pricing)

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

This set of 10,991 one-word .FM domain names carries a median ask near $234, spanning short, real-word names built for radio, media, and audio brands. Updated daily, it gives investors a clear read on pricing and renewal exposure, and gives founders a fast way to find a brandable, ownable name without wading through noise.

- Median ask near $234 across this .FM selection
- 10,991 one-word .FM domains, updated daily
- Short, brandable names ownable now
- Compare pricing and renewal before you buy

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .FM One-Word Domains*. Version 2026-08-18. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .FM page](https://unique.domains/domains/tld/fm?utm_source=github&utm_medium=referral&utm_campaign=repo_fm_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_fm_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_fm_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_fm_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
