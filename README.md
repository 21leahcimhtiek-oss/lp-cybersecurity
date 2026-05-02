# cybersecurity

AI-powered application from Aurora Market.

## Domain
https://auroramarket.org

## Features
- Premium-only AI tools
- No free tier
- Subscription required

## Deployment
### Vercel
1. Import this repository in Vercel.
2. Select **Other** framework preset.
3. Deploy from `main`.

### CI
`.github/workflows/ci.yml` runs static checks:
- required file presence
- JSON validation for `product.json`, `stripe.json`, `bundles.json`, `vercel.json`

## Environment Variables
From `.env.example`:
- `NEXT_PUBLIC_APP_URL`
- `NODE_ENV`
- `STRIPE_SECRET_KEY`
- `STRIPE_WEBHOOK_SECRET`
- `NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY`
- `DATABASE_URL`
- `OPENAI_API_KEY`

## License
See LICENSE file for details.
