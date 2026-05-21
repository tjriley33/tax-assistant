# Federal Tax Assistant

Lives at [builtbyriley.com](https://builtbyriley.com).

Static front-end (Cloudflare Workers Assets) for:

- **Tax Q&A** (`/tax-assistant`) — Cognito-authenticated chat over IRS docs
- **Forms Tracker** (`/tax-forms`) — searchable/filterable IRS forms catalog

The Q&A backend is a separate API (AWS API Gateway + Cognito); this repo is the UI only.

## Deploy

```sh
npx wrangler deploy
```

Custom domain `builtbyriley.com` is configured on the Worker via the Cloudflare dashboard.
