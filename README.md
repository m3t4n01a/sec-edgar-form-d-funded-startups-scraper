# SEC EDGAR Form D Funded Startups & CEO Email Scraper

[![Run on Apify Store](https://img.shields.io/badge/Apify_Store-Run_Actor-00C853?style=for-the-badge&logo=apify)](https://apify.com/willowy_catamaran_fco/sec-edgar-form-d-vc-leads-scraper)

Extract newly funded US startups from SEC Form D XML filings with exact USD raised, CEO/Founder names, direct phones, domains, and verified B2B emails.

## 1-Click Synchronous API Execution (n8n / Clay / Claude MCP)
```bash
curl -X POST "https://api.apify.com/v2/acts/willowy_catamaran_fco~sec-edgar-form-d-vc-leads-scraper/run-sync-get-dataset-items?token=YOUR_APIFY_TOKEN" \
  -H "Content-Type: application/json" -d '{}'
```