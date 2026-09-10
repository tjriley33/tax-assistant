# builtbyriley.com

Lives at [builtbyriley.com](https://builtbyriley.com).

Currently a single "Coming soon" page (`public/index.html`). Every path, including the old `/tax-assistant` and `/tax-forms` URLs, serves it.

The Tax Q&A and Forms Tracker front-end was taken down on 2026-09-10; it is in git history before that date. The AWS backend (API Gateway, Cognito, Lambdas, the `forms123456` bucket) was left running because the IRS-Forms pipeline still uses it.

## Deploy

```sh
npx wrangler deploy
```

Custom domain `builtbyriley.com` is configured on the Worker via the Cloudflare dashboard.
