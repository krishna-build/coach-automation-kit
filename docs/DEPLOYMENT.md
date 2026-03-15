# Deployment Guide

## Option 1: Netlify (Recommended — Free)
```bash
npm run build
# Deploy dist/ to Netlify
```

## Option 2: Vercel
```bash
npx vercel --prod
```

## Option 3: Cloudflare Pages
```bash
npm run build
npx wrangler pages deploy dist
```

## Option 4: Docker (Coming Soon)
```bash
docker-compose up -d
```

## Supabase Edge Functions
```bash
npx supabase functions deploy razorpay-webhook
npx supabase functions deploy track-visitor
npx supabase functions deploy email-engine
```
