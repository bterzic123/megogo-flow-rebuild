# Growth Audit — MEGOGO

**Live:** https://bterzic123.github.io/megogo-flow-rebuild/ · prototype only: https://bterzic123.github.io/megogo-flow-rebuild/?view=proto

Today every new MEGOGO install allows tracking, lands on the home feed and never sees the subscription. TV and Movies waits four taps in, under Account → Subscriptions. This audit rebuilds the first launch in MEGOGO's own design so it asks what the user came to watch and answers it with the subscription, at the prices the app already shows.

Two views: an **Overview** with five ranked ideas, and a **Prototype** with three phones side by side: an install from the «Холостяк» Facebook ad, a movie fan and a workout fan.

## The five ideas

| # | Idea | Expected effect |
| :-- | :-- | :-- |
| 1 | Show the subscription once, at the end of first launch | CR +10–20% |
| 2 | Ask what they came to watch, with your own home tiles | CR +8–20% |
| 3 | Name what they picked in the subscription headline | CR +15–20% |
| 4 | Make the wait read their picks back | CR +10–15% |
| 5 | Put your 4.5 stars next to the price | CR +10–15% |

The X on the subscription screen closes straight into the app. There is no second paywall.

## Grounding

Screens, copy, artwork and prices come from the MEGOGO iOS app as recorded on 12 November 2026 on a euro storefront: "Subscribe from 3,76 €/mo." for TV and Movies and "from 12,42 €" for Smartass. The rating (4.5 from 66K ratings) and the quoted review come from the Ukrainian App Store listing. The ads and their dates come from AppMagic.

*Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps — not measured lift for MEGOGO.*

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000. One static `index.html` plus `img/`, no build step.

Prepared by [Adapty](https://adapty.io) · [Book a demo](https://calendly.com/d/cty4-37z-zqj)
