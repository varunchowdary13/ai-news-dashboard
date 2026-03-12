# AI News Dashboard

Aesthetic daily AI news from Hacker News, built with Astro.

## Features

- Clean, minimal design with dark mode support
- Auto-refreshes daily via Vercel cron
- Fetches top AI-related stories from Hacker News at build time
- Fast static output

## Development

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build
```

## Deployment

Deploy to Vercel — it auto-detects Astro:

```bash
npx vercel --prod
```

Daily rebuilds are configured in `vercel.json` (runs at 6 AM UTC daily).
