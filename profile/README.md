# HoldingsIntel

**Get in early. Make your move before the crowd.**

HoldingsIntel combines SEC EDGAR filings (13F, Form 4, 13D/13G) with House and Senate STOCK Act disclosures into smart-money intelligence for retail stock traders.

[www.holdingsintel.com](https://www.holdingsintel.com) · [MCP server](https://www.holdingsintel.com/mcp) · [Developers](https://www.holdingsintel.com/developers) · [X](https://x.com/holdingsintel)

## Build on our data

- **[holdingsintel-mcp](https://github.com/holdingsintel/holdingsintel-mcp)**: ask Claude, ChatGPT or Cursor what hedge funds, insiders, activists and Congress are trading. One URL, 24 tools, no key needed to start.
- **[holdingsintel-open-data](https://github.com/holdingsintel/holdingsintel-open-data)**: open SEC datasets of 13F holdings, Form 4 insider trades and 13D/13G activist stakes. CC BY 4.0, with a DOI for every release.

## What we track

- The funds that hold 89% of US 13F-disclosed capital ($70.7T, Q2 2026), with filings back to 2014
- Company insider buys and sells (Form 4) and activist stakes above 5% (13D/13G), checked every 10 to 15 minutes
- Every stock trade members of Congress disclose under the STOCK Act, each benchmarked against SPY over the same dates

## Free public API

No key, no sign-up, 10 requests a minute, open to browsers:

```bash
curl https://www.holdingsintel.com/api/public/signals/convergence
```

Signal types: `convergence`, `conviction`, `double-downs`, `smart-money`, `congressional`, `backtesting`. Examples in [holdingsintel-mcp/api](https://github.com/holdingsintel/holdingsintel-mcp/tree/main/api).

---

Data from SEC EDGAR and the official House and Senate disclosure portals. Not investment advice.
