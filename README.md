# Kvarn X — Onboarding & Auth Redesign

Interactive, click-through HTML prototype rebuilding Kvarn X's registration, login, email
verification, 2FA and KYC flow, based on a UX/security audit of the live site
(kvarnx.com) plus patterns borrowed from Kraken, Binance, Revolut and eToro.

Every screen ties its changes back to a specific finding from the audit (shown in the
right-hand panel as you click through).

## View it

Open `index.html` directly in a browser — no build step, no dependencies.

## Flow

Landing → Log in / Sign up → Email verification → Verified (view-only or KYC) →
2FA setup → Identity verification → Dashboard.

Navigation is real: clicking the actual buttons inside the mocked browser window moves
you through the flow, the same way it would on the live site.
