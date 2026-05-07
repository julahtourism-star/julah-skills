---
name: awesome-design-md
description: Brand-inspired DESIGN.md design-system references for 70 well-known products. Use when the user asks to build, design, style, or theme a UI "like" / "inspired by" / "in the style of" a specific brand (e.g. "make it look like Linear", "Stripe-style landing page", "Notion-inspired dashboard"). Contains DESIGN.md files with colors, typography, spacing, radii, motion, and component conventions for: airbnb, airtable, apple, binance, bmw, bmw-m, bugatti, cal, claude, clay, clickhouse, cohere, coinbase, composio, cursor, elevenlabs, expo, ferrari, figma, framer, hashicorp, ibm, intercom, kraken, lamborghini, linear.app, lovable, mastercard, meta, minimax, mintlify, miro, mistral.ai, mongodb, nike, notion, nvidia, ollama, opencode.ai, pinterest, playstation, posthog, raycast, renault, replicate, resend, revolut, runwayml, sanity, sentry, shopify, spacex, spotify, starbucks, stripe, supabase, superhuman, tesla, theverge, together.ai, uber, vercel, vodafone, voltagent, warp, webflow, wired, wise, x.ai, zapier.
---

# Awesome DESIGN.md

A curated library of `DESIGN.md` files (the format introduced by Google Stitch) that capture the visual design system of 70 well-known products. Each file is plain markdown with structured tokens (colors, typography, spacing, radii, motion, components) ready for an AI agent to consume.

## When to use this skill

Trigger this skill when the user wants UI generated, restyled, or themed in the visual language of one of the brands listed above. Typical phrasings:

- "Build a landing page like Stripe"
- "Make this dashboard look like Linear"
- "Apply a Notion-inspired theme"
- "Use the Claude.ai color palette"

## How to use it

1. Identify the brand the user is referencing. Match it to a folder name under `design-md/` (case-insensitive; the folder name is the canonical key).
2. Read `design-md/<brand>/DESIGN.md` and use its tokens as the source of truth for colors, typography, spacing, radii, shadows, and motion when generating or modifying UI code.
3. If the user references a brand that is not in the list, say so and offer the closest stylistic match from the available set, or proceed without this skill.
4. Do not copy logos, trademarks, or proprietary illustrations from the source brand into the user's project. Use the design tokens (colors, type, spacing) only.

## Layout

```
design-md/
  <brand>/
    DESIGN.md   # design tokens & system
    README.md   # human-readable summary
```

## Source

Curated by VoltAgent: https://github.com/VoltAgent/awesome-design-md (MIT)
