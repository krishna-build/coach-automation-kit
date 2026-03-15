# Webhook Setup Guide

## Razorpay Webhook
1. Go to Razorpay Dashboard → Settings → Webhooks
2. Add webhook URL: `https://YOUR_PROJECT.supabase.co/functions/v1/razorpay-webhook`
3. Select events: `payment.captured`, `payment.failed`, `refund.created`
4. Copy the webhook secret to your `.env`

## Google Sheets Webhook
1. Open your Google Sheet
2. Extensions → Apps Script
3. Add the trigger script from `scripts/gsheet-webhook.gs`
4. Set trigger to run on form submission
