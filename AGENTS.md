> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- **ezpz.fi** — public product brand and web app (`frontend_v2`)
- **buukie-*** — internal service and Solana program names (rename to ezpz planned)
- **Gambler / bettor** → use **player** in public docs
- **Agent** (market creator) → use **maker** in public docs
- **Maker** — creates markets, seeds liquidity, earns maker fees
- **Player** — retail user who places predictions
- **Operator** — oracle-admin user who resolves markets and manages treasury
- **AMM** — automated market maker; M1 default execution venue
- **CLOB** — central limit order book; planned for v2
- **Custodial wallet** — server-managed Solana keypair per user account

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Document M1 scope accurately; mark v2/deferred features with Notes

## Content boundaries

- Document the public product (ezpz.fi) and operator workflows
- Do **not** publish API reference — the API is closed with no third-party integrators
- Do not document internal runbooks, deployment secrets, or cron endpoints in public docs
- Keep buukie internal names in technical references until the ezpz rename
- Structure mirrors [Polymarket docs](https://docs.polymarket.com) (101 intro, core concepts, trading flows, resources) — adapt for custodial Solana model, not copy
