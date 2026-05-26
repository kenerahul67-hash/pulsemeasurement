# PulseMeasurement — Beta Deployment

Static website for PulseMeasurement, deployed via Azure Static Web Apps.

## Deployment

This site deploys automatically to Azure Static Web Apps on every push to `main`.

### First-time setup

1. Create an Azure Static Web App in the Azure Portal
2. Link it to this GitHub repository
3. Azure will provide a deployment token — add it as a GitHub secret named `AZURE_STATIC_WEB_APPS_API_TOKEN`
4. Push to `main` — the GitHub Action handles the rest

### Files

| File | Purpose |
|------|---------|
| `index.html` | Main website (PulseMeasurement beta) |
| `staticwebapp.config.json` | Azure SWA routing, headers, MIME types |
| `.github/workflows/azure-static-web-apps.yml` | CI/CD pipeline |

## Status

🟡 **Beta** — content and design are being actively refined.
