# LeadMiner guide
## Goal
- Build a CLI that:
  1. Takes keywords, location, and gender hints
  2. Opens Google with X-ray query (e.g. "site:linkedin.com/in 2025 'AI' 'Miami' 'She/her'")
  3. Parses first 20 result links
  4. Writes names + titles + URLs to prospects.csv

## How to validate
- `pytest tests.py` should pass
- Script must run: `python linkedin_miner.py --query "AI Miami" --out prospects.csv`
