
# POWFOLIO White Paper

Official standalone white-paper viewer for POWFOLIO.

## Files

- `index.html` — Responsive document page.
- `Powfolio_White_Paper.pdf` — Official white paper displayed in the embedded viewer.
- `vercel.json` — Vercel configuration.

## Local preview

Open `index.html` in a browser after adding the PDF.

For a more representative local test, serve the directory using any static HTTP server.

## Deployment

1. Import this repository into Vercel.
2. Select the repository root as the project root.
3. Use the Other framework preset or static deployment configuration.
4. Deploy.
5. Configure `whitepaper.powfolio.xyz` in Vercel's project domain settings.
6. Add the DNS record requested by Vercel at your DNS provider.

No build command or framework dependency is required.

## Document requirements

The PDF must be committed to the repository root and named exactly:

`Powfolio_White_Paper.pdf`

The viewer provides embedded viewing, direct opening, and downloading.
