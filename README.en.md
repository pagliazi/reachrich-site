# ReachRich

A multi-market quantitative **data platform**. It turns the most tedious part of quant — finding, cleaning, and reconciling data — into one stable service: **unified schema, consistent price adjustment, multi-source cross-validation, real-time and historical from the same source**, with built-in freshness and quality monitoring.

> Capability showcase only. For data-research purposes only; nothing herein is investment advice, reference, recommendation, or a promise of return. Past performance does not indicate future results.

**[reachrich.ai](https://reachrich.ai)** · Docs: [Overview](docs/reachrich.md) · [Coverage](docs/data-coverage.md) · [Reliability](docs/reliability.md) · [Access](docs/access.md)

## Coverage

- **Markets**: China A-shares (Main / ChiNext / STAR / BSE), Hong Kong, US majors
- **Quotes**: real-time snapshots, intraday, daily/minute/weekly/monthly bars, second-level call auction, tick
- **Adjustment**: forward / backward / corporate-action factors
- **News**: feeds, filings, sentiment, AI summaries
- **Fundamentals**: F10, statements, valuation, dividends
- **Flows**: money flow, top-list, northbound, block trades
- **Sectors**: concepts, industries, index constituents, rotation & sentiment

## Why it matters

| Pain | How ReachRich handles it |
|---|---|
| Inconsistent multi-source schema | One unified data contract |
| Adjustment chaos / fake overnight gaps | Consistent corporate-action handling |
| Separate real-time vs history | Same source, same schema |
| Single-source unreliability | Cross-validation + auto failover |
| Unknown data freshness | Per-stream freshness monitoring |

## Relationship to RR-Agent

ReachRich is the **data layer (callee)**. The upper-layer quant research agent **RR-Agent** (separate project) calls it via API / MCP to fetch data. Responsibilities are separated; the two evolve independently.

## Disclaimer

Showcase repository. No backend code, credentials, keys, or deployment details. For data-research only; not investment advice or a promise of return.
