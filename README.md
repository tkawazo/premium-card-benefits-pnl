# Premium corporate card: benefits P&L model

An interactive, single-file model of the unit economics of a premium B2B card (Black / World Elite tier). Open `index.html` in any browser, or view it on GitHub Pages.

**All default values are illustrative assumptions.** They are not data from any issuer, network or benefit provider.

## Why I built it

When I owned the credit card P&L at a large LatAm bank, the hardest decisions weren't about growth. They were about the **benefits stack**: which benefits customers actually use, what each one costs per card, and who pays for it (issuer, network or partner). Premium benefits are a usage bet. A lounge program that looks cheap in a benchmark can erase the margin of a whole low-spend segment.

This model makes that trade-off explicit in one screen.

## What it models

| Block | Lines |
|---|---|
| Revenue | Domestic and cross-border interchange, FX markup, annual fee, network incentives |
| Benefits cost | Rewards/cashback (bps of spend), lounge (usage × visits × cost per visit), insurance, concierge/lifestyle, share funded by the network |
| Operating cost | Processing and scheme fees, fraud and credit losses, amortized metal card issuance |
| Outputs | Contribution margin (total and per card), benefits cost as % of revenue, **maximum rewards rate before margin hits zero**, and a sensitivity grid of spend segment × lounge usage |

Market presets (Mexico, Colombia, Brazil) change spend, interchange, FX and cost assumptions so you can compare how the same program behaves in each market.

## How I'd use it in practice

1. Replace the assumptions with real cohort data (spend per card, benefit usage by segment).
2. Find the segments where margin is thinnest in the sensitivity grid.
3. Run customer discovery with those accounts: which benefits drive activation and retention, and which ones are "nice to have"?
4. Rebalance the stack: renegotiate or cut low-usage benefits, push network-funded features, reinvest in the benefits that drive usage.

That was the playbook behind a card value proposition redesign I led, which **cut loyalty costs by 10% while complaints fell 15% and NPS improved**.

## Built with

Plain HTML/CSS/JS, no dependencies. Prototyped with Claude Code.
