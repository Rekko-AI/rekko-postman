# Rekko AI — Postman Collection

Postman collection for the [Rekko AI](https://rekko.ai) Prediction Market Intelligence API.

## Quick Start

### Import into Postman

1. Open Postman and click **Import**
2. Drag `rekko-api.postman_collection.json` or paste this URL:

```
https://raw.githubusercontent.com/Rekko-AI/rekko-postman/main/rekko-api.postman_collection.json
```

3. Import `rekko-api.postman_environment.json` as an environment
4. Set your `api_key` in the environment variables

### Get an API Key

Sign up for free at [rekko.ai/dashboard](https://rekko.ai/dashboard) — 100 market listings and 10 AI insights per month, no credit card required.

## What's Included

| Folder | Endpoints | Tier |
|--------|-----------|------|
| **Markets** | List markets, get market details, price history, execution guidance, resolution intelligence | Listing ($0.01) |
| **Insights** | AI analyses, trigger analysis, batch screening | Insight ($0.10) |
| **Strategy** | Trading signals, portfolio-aware signals, trade reporting, scenario analysis | Strategy ($2.00) |
| **Portfolio** | Correlation analysis | Deep ($5.00) |
| **Arbitrage** | Cross-platform arbitrage (cached + live scan) | Deep ($5.00) |
| **Analytics** | Health, pricing, calibration, sentiment, performance | Free / Varies |
| **Streaming** | SSE event stream, webhooks (register, list, delete) | Varies |
| **Consensus** | Agent trade consensus | Strategy ($2.00) |

## Authentication

All authenticated endpoints use Bearer token auth. The collection is pre-configured — just set `api_key` in your environment.

```
Authorization: Bearer rk_free_xxxxx
```

## Environment Variables

| Variable | Description |
|----------|-------------|
| `base_url` | API base URL (default: `https://api.rekko.ai`) |
| `api_key` | Your Rekko AI API key |

## Links

- [API Documentation](https://docs.rekko.ai)
- [OpenAPI Spec](https://raw.githubusercontent.com/Rekko-AI/rekko-postman/main/openapi.json)
- [Sign Up](https://rekko.ai/dashboard)
- [Status](https://api.rekko.ai/health)

## Auto-Updated

This collection is automatically regenerated from the [OpenAPI spec](openapi.json) whenever the API changes. Do not edit the collection JSON manually.
