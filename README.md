# Available .ART One-Word Domains (28,498)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-28%2C498%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .art one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **28,498 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 28,498 domains · **Median ask:** $364.49 · **High-demand under $2,500:** 115

**Last updated:** 2026-10-01
**Canonical page:** `https://unique.domains/domains/tld/art`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/art?utm_source=github&utm_medium=referral&utm_campaign=repo_art_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./art.csv">CSV</a> / <a href="./art.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_art_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_art_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .ART search](https://unique.domains/domains/tld/art?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_art_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .ART search](https://unique.domains/domains/tld/art?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_art_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_art_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .ART one-word domain catalog.

### Files

- `art.csv`, public CSV extract (1,000 rows)
- `art.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/art-oneword-domains/main/art.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain     | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                   |
| ---------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------- |
| aglet.art  | available | $3.98     | $32.98        | medium         | low    | 5      | namecheap                   |
| eagle.art  | resell    | —         | —             | high           | low    | 5      | Instra Corporation Pty Ltd. |
| acl.art    | premium   | $282.76   | $72.65        | high           | low    | 3      | spaceship                   |
| golgi.art  | available | $3.19     | $23.99        | high           | low    | 5      | namesilo                    |
| urban.art  | resell    | —         | —             | high           | low    | 5      | Porkbun LLC                 |
| amr.art    | premium   | $282.76   | $72.65        | high           | low    | 3      | spaceship                   |
| iraki.art  | available | $3.19     | $23.99        | medium         | low    | 5      | namesilo                    |
| ano.art    | premium   | $354.90   | $91           | high           | low    | 3      | namecheap                   |
| jural.art  | available | $3.19     | $23.99        | medium         | low    | 5      | namesilo                    |
| aus.art    | premium   | $282.76   | $72.65        | high           | low    | 3      | spaceship                   |
| nubby.art  | available | $3.19     | $23.99        | medium         | low    | 5      | namesilo                    |
| bcs.art    | premium   | $291.20   | $83.30        | high           | low    | 3      | namesilo                    |
| uveal.art  | available | $3.19     | $23.99        | medium         | low    | 5      | namesilo                    |
| bmw.art    | premium   | $282.76   | $72.65        | high           | high   | 3      | spaceship                   |
| alkene.art | available | $3.19     | $23.99        | medium         | low    | 6      | namesilo                    |
| bob.art    | premium   | $1,950    | $91           | high           | medium | 3      | namecheap                   |
| antido.art | available | $3.19     | $23.99        | medium         | low    | 6      | namesilo                    |
| cns.art    | premium   | $354.90   | $91           | medium         | low    | 3      | namecheap                   |
| bailor.art | available | $3.98     | $32.98        | medium         | low    | 6      | namecheap                   |
| dud.art    | premium   | $341.25   | $87.50        | high           | low    | 3      | name.com                    |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 28,498 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 115 high-demand names under $2,500         |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/art?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_art_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/art?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_art_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_art_oneword_domains&utm_content=related_pricing)

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

This list covers one-word domain names on the .art extension only. Status is split between available (4,657) and premium (6,857) names, with a small resell segment (64). Demand skews low across most of the set, but a top tier of 36 names scores in the highest demand bracket, and 34 names combine high demand with pricing under $2,500.

- 9,398 names priced under $500 — budget-friendly entry point
- 6,857 carry premium status, requiring closer price review
- 36 names sit in the top 15% demand tier
- 542 names are launch-ready for immediate use

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

> Unique Domains. *Available .ART One-Word Domains*. Version 2026-10-01. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .ART page](https://unique.domains/domains/tld/art?utm_source=github&utm_medium=referral&utm_campaign=repo_art_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_art_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_art_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_art_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `kai@unique.domains`
