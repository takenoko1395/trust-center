# trust-center

Public pages for legal and help documents across multiple apps.

## Purpose

This repository is intended for public hosting (e.g. GitHub Pages).
Store only non-sensitive content such as:

- Privacy Policy
- Terms of Service
- FAQ
- Contact guidance

## Repository Structure

- apps/
  - <app-slug>/
    - privacy-policy.md
    - terms-of-service.md
    - faq.md
- templates/
  - privacy-policy-template.md
  - terms-of-service-template.md
  - faq-template.md

## Public Safety Rules

- Never commit secrets, tokens, private keys, or credentials.
- Never include personal addresses, phone numbers, or private emails unless intentionally public.
- Keep contact email to a dedicated support mailbox.
- Validate links before publishing to app stores.

## Suggested Per-App Slug

Use lowercase kebab-case, for example:

- go-shichi-go
- my-second-app

## Next Steps

1. Copy templates into a new app folder under apps/.
2. Replace placeholders.
3. Enable GitHub Pages.
4. Register final URLs in Play Console.
