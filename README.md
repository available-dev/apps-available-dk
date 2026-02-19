# Available Apps — Landing Page

Landing page for Available's Zendesk Marketplace apps at [apps.available.dk](https://apps.available.dk).

## Structure

```
├── index.html                          # Homepage — all apps listed
├── apps/
│   └── clickup-time-tracker/
│       ├── index.html                  # App detail page
│       ├── icon.png                    # App icon
│       └── screenshots/               # App screenshots
├── legal/
│   ├── privacy-policy.html            # Privacy Policy
│   └── terms-of-service.html          # Terms of Service
├── assets/
│   ├── style.css                      # Global styles
│   └── img/                           # Shared images
└── CNAME                              # GitHub Pages custom domain
```

## Adding a New App

1. Create `apps/{app-name}/` with `index.html`, `icon.png`, and `screenshots/`
2. Add an app card to `index.html`

## Deployment

Deployed via GitHub Pages. DNS: `apps.available.dk` → CNAME to GitHub Pages.

## Updating Screenshots

Drop screenshot images into `apps/{app-name}/screenshots/` and update the HTML.
