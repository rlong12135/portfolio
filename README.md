# portfolio

Static site scaffold for deployment to Azure Static Web Apps.

## Local preview

Open `index.html` directly, or run:

```bash
npx serve .
```

## GitHub and Azure setup

1. Create a GitHub repository from this directory.
2. Create an Azure Static Web App.
3. Add the Azure deployment token as the GitHub secret `AZURE_STATIC_WEB_APPS_API_TOKEN`.
4. Push to `main`.

The GitHub Actions workflow is already included in `.github/workflows/azure-static-web-apps.yml`.
