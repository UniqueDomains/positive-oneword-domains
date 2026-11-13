# Positive One-Word Domains (~5,410,000)

1,000 real positive one-word domain names, refreshed every night, each with its status, the price to register or buy it and what it renews at. One line of pandas, no scraping, no key.

Each word exists once on each ending. [The list behind this file](https://unique.domains/domains/positive) holds ~5,410,000 names today; the file is a sample of it, in the list's own neutral order, not a ranking.

Live page: [unique.domains/domains/positive](https://unique.domains/domains/positive?utm_source=github&utm_medium=referral&utm_campaign=repo_positive_oneword_domains&utm_content=top_page)

<img alt="updated: daily" src="https://img.shields.io/badge/updated-daily-0969da"> <img alt="extract: 1,000 rows" src="https://img.shields.io/badge/extract-1%2C000%20rows-8250df"> <img alt="formats: CSV | JSON" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b"> <img alt="licence: CC BY 4.0" src="https://img.shields.io/badge/licence-CC%20BY%204.0-2ea44f">

## Download

- [positive.csv](https://github.com/UniqueDomains/positive-oneword-domains/raw/main/positive.csv), 1,000 rows
- [positive.json](https://github.com/UniqueDomains/positive-oneword-domains/raw/main/positive.json), 1,000 rows

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/positive-oneword-domains/main/positive.csv")
print(df.head())
```

## Sample rows

The first 20 rows of the file, in the file's order.

| domain               | status    | purchase_price | renewal_price | attractiveness | demand | length |
| -------------------- | --------- | -------------- | ------------- | -------------- | ------ | ------ |
| boldness.farm        | available | $30.20         | $30.20        | high           | low    | 8      |
| headmaster.clothing  | available | $32.99         | $32.99        | high           | low    | 10     |
| ripen.click          | premium   | $72.65         | $103.70       | high           | low    | 5      |
| fandango.im          | available | $4.18          | $6.73         | high           | low    | 8      |
| manhood.nexus        | available | $14            | —             | high           | low    | 7      |
| impactful.care       | available | $20            | —             | high           | low    | 9      |
| souffle.win          | available | $4.48          | $5.55         | high           | low    | 7      |
| befit.win            | premium   | $448           | $53.92        | high           | low    | 5      |
| cookware.organic     | available | $66.20         | $66.20        | high           | low    | 8      |
| impresario.tax       | available | $7.96          | $54.02        | high           | low    | 10     |
| potatoes.my          | premium   | $91.96         | $91.96        | medium         | low    | 8      |
| carers.hamburg       | available | $69.98         | $73.98        | medium         | low    | 6      |
| refresher.press      | available | $62.20         | $62.20        | high           | low    | 9      |
| yingyang.delivery    | available | $5.03          | $58           | high           | low    | 8      |
| laserwire.online     | available | $1.96          | $28.84        | high           | low    | 9      |
| recommender.help     | available | $2.99          | $26.97        | high           | low    | 11     |
| categorise.directory | available | $8.99          | $32.99        | high           | low    | 10     |
| unparalleled.forsale | available | $16.99         | $36.99        | high           | low    | 12     |
| alleviate.organic    | available | $17            | —             | high           | low    | 9      |
| cresting.boats       | available | $1.54          | $14.21        | high           | low    | 8      |

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

- The files hold 1,000 rows of the ~5,410,000 names in the live list today.
- Every row is a one-word domain name.
- Status and prices are the latest on record for each name, not a reading taken on the day of the rebuild.
- The live count marked with a tilde is estimated from a 2 percent page sample of the catalog and rounded to three significant digits; it moves between nights. The rows in the files are real rows.

More in [METHODOLOGY.md](./METHODOLOGY.md).

## Update policy

- The files are rebuilt every night from the same export.
- The snapshot is the day of the rebuild; each row's status is the latest on record for the name, not a reading of that day.
- The files hold the public extract, not the whole live list.

## How to cite

> Unique.domains, Positive One-Word Domains, https://unique.domains/domains/positive, CC BY 4.0

Citation metadata: [CITATION.cff](./CITATION.cff). A DOI follows once Zenodo mints one.

## Related datasets

- [Every one-word domain](https://github.com/UniqueDomains/oneword-domains) (the hub)

One-word domains by ending:

- [.com](https://github.com/UniqueDomains/com-oneword-domains), [page](https://unique.domains/tld/com?utm_source=github&utm_medium=referral&utm_campaign=repo_positive_oneword_domains&utm_content=related_tld_page)
- [.ai](https://github.com/UniqueDomains/ai-oneword-domains), [page](https://unique.domains/tld/ai?utm_source=github&utm_medium=referral&utm_campaign=repo_positive_oneword_domains&utm_content=related_tld_page)
- [.io](https://github.com/UniqueDomains/io-oneword-domains), [page](https://unique.domains/tld/io?utm_source=github&utm_medium=referral&utm_campaign=repo_positive_oneword_domains&utm_content=related_tld_page)
- [.app](https://github.com/UniqueDomains/app-oneword-domains), [page](https://unique.domains/tld/app?utm_source=github&utm_medium=referral&utm_campaign=repo_positive_oneword_domains&utm_content=related_tld_page)
- [.co](https://github.com/UniqueDomains/co-oneword-domains), [page](https://unique.domains/tld/co?utm_source=github&utm_medium=referral&utm_campaign=repo_positive_oneword_domains&utm_content=related_tld_page)
- [.xyz](https://github.com/UniqueDomains/xyz-oneword-domains), [page](https://unique.domains/tld/xyz?utm_source=github&utm_medium=referral&utm_campaign=repo_positive_oneword_domains&utm_content=related_tld_page)

Lists:

- [Expired](https://github.com/UniqueDomains/expired-oneword-domains)
- [Expiring](https://github.com/UniqueDomains/expiring-oneword-domains)
- [Brandable](https://github.com/UniqueDomains/brandable-oneword-domains)
- [Short](https://github.com/UniqueDomains/short-oneword-domains)

Every ending Unique.domains tracks: [unique.domains/tld](https://unique.domains/tld?utm_source=github&utm_medium=referral&utm_campaign=repo_positive_oneword_domains&utm_content=related_hub).

## About Unique.domains

[Unique.domains](https://unique.domains/?utm_source=github&utm_medium=referral&utm_campaign=repo_positive_oneword_domains&utm_content=about) tracks one-word domain names across the endings people build on: which are free to register, what they cost to hold and what names of each ending sell for. The datasets in this organization are its public extracts, refreshed every night.

From code: the [Node.js SDK and CLI](https://github.com/UniqueDomains/nodejs) (`npm install @uniquedomains/sdk`), the [Python client](https://github.com/UniqueDomains/python) (`pip install uniquedomains`) and the [MCP server](https://github.com/UniqueDomains/mcp-server) for AI assistants, hosted at `https://mcp.unique.domains/mcp`.

Questions and corrections: `kai@unique.domains`
