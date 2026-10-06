# GlowAI

GlowAI — AI-powered beauty, skincare, hair, fitness and style guidance.

## Files
- `index.html` — main GlowAI site
- `reset-password.html` — Supabase password reset page
- `glow-favicon.png` — site favicon

## Security
This repository is intended to contain only frontend/public site code.

The Supabase key in the frontend is a **publishable key**, intended for browser use. Keep all Supabase secret/service-role keys, Shopify Admin API tokens, Resend API keys, Discord bot tokens, database passwords, and other server-side credentials out of this repository.

If secrets are ever accidentally committed, revoke/rotate them immediately rather than relying on deleting the commit.
