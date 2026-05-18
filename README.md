# cybersecurity

AI-powered application from Aurora Rayes ecosystem.

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

## Aurora Ecosystem Positioning
This project is positioned as part of the Aurora ecosystem and is ready for Aurora-aligned workflows and automation.

### No-Key-First Operation
This repository supports a no-key-first setup for local evaluation and onboarding, with optional credentials only for advanced integrations.
