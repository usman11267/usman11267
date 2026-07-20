# Muhammad Usman — GitHub Profile Repository

This is the source repository for the GitHub profile of **[@usman11267](https://github.com/usman11267)**.

## Repository Structure

```
usman11267/
├── README.md                          # Profile README (rendered on GitHub profile)
├── assets/
│   ├── svg/
│   │   ├── banner.svg                 # Custom animated cyberpunk hero banner
│   │   └── divider.svg               # Section dividers
│   └── metrics/
│       ├── languages.svg              # Auto-generated language stats (GitHub Actions)
│       ├── activity.svg               # Auto-generated activity (GitHub Actions)
│       └── achievements.svg           # Auto-generated achievements (GitHub Actions)
└── .github/
    └── workflows/
        ├── snake.yml                  # Contribution snake animation (daily)
        ├── metrics.yml                # GitHub metrics update (daily)
        └── quote.yml                  # Quote refresh (every 6 hours)
```

## GitHub Actions Setup

### 1. Snake Animation
No setup required — uses `GITHUB_TOKEN` automatically.
Ensure **Settings > Actions > General > Workflow permissions** is set to **Read and write**.

### 2. Metrics
Requires a Personal Access Token (PAT):
1. Go to **Settings > Developer settings > Personal access tokens > Tokens (classic)**
2. Create token with scopes: `read:user`, `public_repo`, `read:org` (optional)
3. Add as repository secret: `METRICS_TOKEN`

### 3. Quote Refresh
No setup required — runs automatically.

## Theme

- **Colors:** `#0d1117` background · `#00d4ff` cyan accent · `#ffffff` text · `#8892b0` muted
- **Font:** JetBrains Mono (code blocks) · Inter (prose)
- **Style:** Cyberpunk dark · Minimal · Professional
