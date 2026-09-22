# BN Earning Hub — Telegram Mini App v1

## What is included
- Telegram Mini App SDK integration
- Mobile-first UI
- Home / Earn / Referral / Profile tabs
- Telegram user name, username, ID and language display
- Local demo balance
- Referral-link UI
- Monetag SmartLink button
- Community/channel button
- No bot token exposed in the frontend

## Important
This is a FRONT-END first version.

For real production earnings you still need:
1. HTTPS hosting
2. A Telegram bot backend
3. Server-side validation of Telegram WebApp initData
4. Database for users, tasks, referrals and balances
5. Anti-fraud/rate-limit rules
6. Verified reward/offer tracking
7. Withdrawal system

Do NOT put your BotFather bot token in index.html.

## Replace before launch
Inside index.html:
- MONETAG_LINK: currently set to the user's existing SmartLink
- COMMUNITY_LINK: replace with the real channel/group URL

## Deploy
Upload index.html to an HTTPS host. Then configure the URL in @BotFather as the Main Mini App or Menu Button.

