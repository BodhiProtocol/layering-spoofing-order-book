# Layering & Spoofing — Order Book Replay

**An interactive replay of a simulated layering/spoofing episode — watch the fake bid depth build, the genuine fill land, and the cancel burst that follows, mapped to the actual regulations it would trip.**

Live demo → https://bodhiprotocol.github.io/layering-spoofing-order-book/

---

## Why this exists

Market abuse typologies like layering and spoofing are easy to define on paper but hard to *see* — the manipulative intent only becomes obvious when you watch the order lifecycle unfold: an order rests, adds one-sided depth, and gets pulled within moments of the opposing genuine order filling. This replays a scripted (simulated, not a real case) episode order-by-order so that pattern is visible instead of abstract.

## What's inside

- **Interactive Lab** — scrub the timeline, click any order in the book to see its full lifecycle (placed / cancelled / filled, resting time, distance from touch)
- **Book Figure** — a clean frozen frame at the fill moment, for reports or decks
- **Dissertation View** — maps each order to the regulation it would trip: MAS Securities and Futures Act s197, CFTC anti-spoofing (7 U.S.C. §6c(a)(5)(C)), EU MAR Article 12(1)(a) and Annex II
- Live spoof-to-cancel ratio and average resting-time-before-cancel metrics
- Export any frame as a PNG, or a single order's detail as a standalone citation-ready card
- Copy Link — shares the exact mode/timeline position/selected order via URL

## Tech

One self-contained `index.html`, canvas-rendered. No frameworks, no build step, no API calls.

## Part of BodhiProtocol

Tools and games that make complex systems simple.
More at [github.com/BodhiProtocol](https://github.com/BodhiProtocol).

Related tools in the capital-markets toolkit:
[Trade Lifecycle Explorer](https://bodhiprotocol.github.io/trade-lifecycle-explorer/) · [Jargon Decoder](https://bodhiprotocol.github.io/jargon-decoder/) · [Capital Markets Blueprint Explorer](https://bodhiprotocol.github.io/capital-markets-blueprint-explorer/) · [Regulatory Acronym Map](https://bodhiprotocol.github.io/regulatory-acronym-map/) · [LLM Wiki](https://bodhiprotocol.github.io/llm-wiki/)
