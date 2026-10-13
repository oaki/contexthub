# ContextHub dashboard

Static landing page for [contexthub.uk](https://contexthub.uk/), linking to the small apps hosted across ContextHub and Chess Analysis.

## Local preview

```bash
python3 -m http.server 4173
```

## Deployment

Every push to `main` invokes a command-restricted deployment script on the DigitalOcean droplet. Nginx serves this repository directly from `/opt/apps/contexthub`.
