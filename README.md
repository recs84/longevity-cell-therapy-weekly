# Longevity Cell Therapy Weekly

A weekly, curated research feed for AI agents and the people who build with them. Scope: mesenchymal stromal cells (including manufacturing and bioreactors), MSC secretome, conditioned media and extracellular vesicles, NK cell therapy (autologous products, expansion, activation, aging), and senolytics and immune clearance of senescent cells.

Edited by Ramon Coronado (CubicBio, BioLabs Dallas). Published by his agent, hustlerc.

## What is here (free tier)

| File | What it is |
|------|------------|
| `headlines.json` | Latest issue, free headline fields: id, title, source, posted_date, one-line finding, url, DOI, topic_tags, preprint flag |
| `headlines.md` | Same, human readable |
| `issues/NNN-headlines.json` / `.md` | Archive by issue |
| `feed.json` and `.well-known/feed.json` | Feed manifest: issues, tiers, endpoints, schemas |
| `llms.txt` | Short guide for language-model agents |
| `schema/headlines.schema.json` | JSON Schema for the free headlines |
| `schema/issue.schema.json` | JSON Schema describing the paid full issue (shape only, no paid content) |

## Paid tier (coming soon)

The full structured issue adds study type, authors, key readouts or biomarkers (only if stated), manufacturing relevance, limitations, an evidence rating with a reason, why it matters for builders, and cross-item notes. It will be sold per request over [x402](https://www.x402.org/) in USDC on Base: `GET /v1/issues/{n}` at $0.25 and `GET /v1/search?q=` at $0.02. The endpoint URL will be added to `feed.json` when live.

## How items are chosen

Each week we query the bioRxiv and medRxiv APIs, PubMed E-utilities and Europe PMC (which covers Research Square and Preprints.org), score for relevance, and review abstracts by hand. Every item links to a real source and its DOI was checked. Nothing is summarized beyond what the source states.

## License

Summaries, tags and one-line findings are licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). Please attribute "Longevity Cell Therapy Weekly (Ramon Coronado)". Titles, author names, DOIs and links are factual metadata. Abstracts are not reproduced; follow each link for the source and its own license.

## Disclaimer

Not medical advice. Research summaries for information only, based on public abstracts. Preprints are not peer reviewed. Nothing here is an endorsement of any product or treatment. Verify against the original source before relying on any detail.
