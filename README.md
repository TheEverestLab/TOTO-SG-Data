# TOTO Results SG - Data

This repository contains the lottery results data for the TOTO Results SG app.

## Structure

```
├── toto/
│   ├── latest.json       # Latest TOTO draw
│   ├── draws-all.json    # All TOTO historical draws
│   └── statistics.json   # TOTO statistics
├── 4d/
│   ├── latest.json       # Latest 4D draw
│   ├── draws-all.json    # All 4D historical draws
│   └── statistics.json   # 4D statistics
└── netlify.toml          # Netlify configuration
```

## API Endpoints

Base URL: `https://[your-netlify-site].netlify.app`

| Endpoint | Description |
|----------|-------------|
| `/toto/latest.json` | Latest TOTO draw result |
| `/toto/draws-all.json` | All TOTO historical draws |
| `/toto/statistics.json` | TOTO number statistics |
| `/4d/latest.json` | Latest 4D draw result |
| `/4d/draws-all.json` | All 4D historical draws |
| `/4d/statistics.json` | 4D number statistics |

## Updates

Data is automatically updated by the scraper in the main [Result_SG](https://github.com/user/Result_SG) repository.

- **TOTO**: Monday & Thursday after 9:30 PM SGT
- **4D**: Wednesday, Saturday & Sunday after 6:30 PM SGT

## Deployment

This repo auto-deploys to Netlify on every push to `main` branch.
