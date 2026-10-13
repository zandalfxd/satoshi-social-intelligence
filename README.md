# Satoshi Social Intelligence

Satoshi is a self-hosted cryptocurrency research and monitoring project that combines public market data with social discussion signals to identify emerging trends and potential risk indicators.

## Project Overview

Satoshi runs on a private Ubuntu Linux server using:

- **n8n** — Automated data collection and analysis workflows
- **PostgreSQL** — Historical market observations and research data
- **Open WebUI** — Interface for a locally hosted AI research assistant
- **DexScreener** — Public cryptocurrency market information

## Planned Reddit Integration

The proposed Reddit integration will use authorized, read-only API access to:

- Monitor permitted public discussions in cryptocurrency-related subreddits
- Identify cryptocurrency mentions, ticker symbols, and emerging narratives
- Analyze changes in discussion frequency and engagement
- Compare social activity with market liquidity and trading-volume observations
- Produce private research summaries with references to original discussions

Initial communities of interest include r/CryptoCurrency, r/CryptoMoonShots, r/solana, r/ethereum, r/Bitcoin, and r/defi.

## Privacy and API Compliance

The Reddit integration is not yet implemented and will not collect Reddit API data before authorization.

The project will not automatically post, comment, vote, send private messages, or manipulate engagement.

Any approved integration will respect API rate limits, applicable data-retention and deletion requirements, and restrictions on the use of Reddit content. Reddit content will not be used to train AI models.

## Development Status

The cryptocurrency market-monitoring components are operational. Social monitoring integrations, including Reddit, are planned and subject to platform authorization.

This is a personal, noncommercial research project. It does not currently provide a public-facing Reddit application or service.
