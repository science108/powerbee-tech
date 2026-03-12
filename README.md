# PowerBee.tech

Investor landing page for **PowerBee P.S.A.** — the first company commercializing RCPM technology under license from inventor Zbigniew Sadlak.

## Stack

Static HTML/CSS/JS — no build step. Self-contained `index.html` with embedded styles and scripts.

## Deployment

Hosted on Cyberfolks at `powerbee.tech`. Auto-deployed via GitHub Actions on push to `main` (FTP).

### Required GitHub Secrets

| Secret | Value |
|--------|-------|
| `FTP_SERVER` | `s46.cyber-folks.pl` |
| `FTP_USERNAME` | `claude@powerbee.tech` |
| `FTP_PASSWORD` | *(set in Cyberfolks panel)* |
