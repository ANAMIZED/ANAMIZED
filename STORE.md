# ANAMIZED Store — Autonomous Agentic Revenue Streams

**Integrated catalog of Stripe (fiat) + x402 (USDC) revenue options for ANAMIZED agentic OS, MCP, and public-goods projects.**
Additive only — existing setups unchanged.

Live desk: [anamized.grok.me](https://anamized.grok.me) · floor + MCP market + desk-rate rack.

## Preferred for Agents: Non-custodial USDC (x402)

| Network | Address |
|---------|---------|
| **Base / Ethereum** | `0xD3d0E9eDAe3Ac7bb199a8EAA761BdA423b878438` |
| **Solana** | `ETQwWf19axArsY493UfC6bxe2BmEzmzvCb58PPnC38A` |

Desk x402: `GET https://anamized.grok.me/api/v1/x402` then `POST /api/v1/x402/compute|memory|reasoning`. Worker rail remains [x402-cloudflare-starter](https://github.com/ANAMIZED/x402-cloudflare-starter).

## Stripe Fiat Options (Live)

### Support & Kernels
- **Public Goods Support** ($25 one-time): [Donate](https://donate.stripe.com/00w5kE3wOg5L8Jn2F243S00)
- **Agentic OS Kernel Support** ($99): [Support](https://buy.stripe.com/bJecN63wObPv6Bf7Zm43S02)
- **RUI Kernel Support** ($99): [Support](https://buy.stripe.com/4gMaEY1oG6vbf7LfrO43S07)

### Pro Access (Subscriptions)
- **YodMCP Pro** ($49/mo): [Subscribe](https://buy.stripe.com/bJe3cw0kCaLrbVz1AY43S09)
- **YodMCP Enterprise** ($499/mo): [Subscribe](https://buy.stripe.com/9B68wQ1oGcTz9NrfrO43S0a)
- **OpenGOS Pro Access** ($49/mo): [Subscribe](https://buy.stripe.com/7sY8wQ5EWf1H3p3bby43S01)
- **RUI Pro Access** ($49/mo): [Subscribe](https://buy.stripe.com/aFacN65EW5r7e3HgvS43S08)

### Pay-per-use Cycles
- **Agentic OS Cycle** ($0.75) — LRSI / server-os / rui / openmesha: [Buy](https://buy.stripe.com/3cI14o8R8dXD3p3frO43S04)
- **Trading Cycle** ($4) — agenticarb / edge-os: [Buy](https://buy.stripe.com/bJedRaebsaLr2kZ2F243S05)
- **OpenGOS Advanced Search** ($0.40): [Buy](https://buy.stripe.com/7sY8wQ5EW3iZ5xb5Re43S06)
- **OpenGOS Proposal Draft** ($2.50): [Buy](https://buy.stripe.com/9B69AUd7o7zf2kZ2F243S03)

### Consulting
- **Consulting Hour** ($199, digital, no calendar): [Buy the hour](https://buy.stripe.com/dRmaEYgjA9Hnf7LdjG43S0b)

## How Agents Use This
1. Prefer desk MCP (`https://anamized.grok.me/mcp`) for catalog, floor, and rack. Do not invent SKUs.
2. Use Stripe Payment Links for human fiat. x402 on the desk origin spends claimed credits; the Worker is the on-chain USDC rail.
3. After Stripe, the human signs in at [anamized.grok.me/account](https://anamized.grok.me/account) and syncs.
4. There is no constellation or swarm auto-poster on the live desk.

## Integration Notes
- All Stripe products live under account ANAMIZED.
- Metadata on products links back to GitHub repos for traceability.
- Fail-closed. Public-goods aligned.

*Last updated 2026-08-27. Live desk: anamized.grok.me.*
