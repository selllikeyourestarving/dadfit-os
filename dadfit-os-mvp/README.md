# DadFit OS — MVP Prototype

This is a browser-based MVP prototype for DadFit OS.

## What works now
- Premium landing page
- $1,595 offer positioning
- Gated login experience
- Onboarding flow
- Personalized dashboard mockup
- Training, Nutrition, Restaurant, Travel, Progress and AI Coach screens
- Responsive browser UI
- Demo access switch for testing

## What still needs production integrations
1. Stripe Checkout for the $1,595 purchase
2. Real authentication/session management
3. Database (Supabase/Postgres recommended)
4. OpenAI API on the server side
5. Secure entitlement check: paid = access, refunded/chargeback = suspended
6. Exercise/video content
7. Production hosting

## Run locally
Open `public/index.html` in a browser.

For a production app, the static UI can be migrated into Next.js/React with the same information architecture.
