# troxy-internal

Internal handbook for Troxy founders, served at **internal.troxy.io**.

## What it contains

- Architecture overview (MVP and production)
- Infrastructure decisions and tradeoffs
- Runbooks and operational procedures
- Open questions and deferred decisions
- Onboarding notes

## Stack

- Single `index.html` — no build step
- Hosted on **Cloudflare Pages** (auto-deploys on push to `main`)

## Deployment

Push to `main` → Cloudflare Pages deploys automatically.

## Access

Public URL but not linked anywhere externally. For internal use only.
