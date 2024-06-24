This repository contains the Core Blocklists, maintained by the AGB team. These are entirely opinionated.

- Base – Core advertisement blocklist
- Community – Advertisements for world-specific communities
- Supporters – Patreon or supporter boards / images
- Upsell – World creator upsell


In order to install them into your AGB installation, add them to `BlocklistURLs` like this:

```json
"BlocklistURLs": [
"https://raw.githubusercontent.com/AdGoBye/AdGoBye-Blocklists/main/AGBBase.toml",
"https://raw.githubusercontent.com/AdGoBye/AdGoBye-Blocklists/main/AGBCommunity.toml",
"https://raw.githubusercontent.com/AdGoBye/AdGoBye-Blocklists/main/AGBUpsell.toml",
"https://raw.githubusercontent.com/AdGoBye/AdGoBye-Blocklists/main/AGBSupporters.toml"
]
```