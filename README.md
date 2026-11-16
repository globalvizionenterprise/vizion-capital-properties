# FLIPVIZION (working name)

A new GLOBAL VIZION ENTERPRISE entity — our own AI real-estate wholesaling
platform. Ordered by Keyz 2026-11-15 from an Instagram reel.

## The source (found 2026-11-15)

Reel by @nephy_invests (Nephy M), posted 2026-11-15:
https://www.instagram.com/reel/Dfx8QoWMNCl/
Caption gist: wholesaling real estate with AI — flipping contracts with $0.
Hashtags: #wholesalingrealestate #contractflipping #probate.
Raw lookups saved in research/ (post JSON, media understanding, comments).

## What the reel demonstrates (the product class)

The reel demos a site called tranchi.ai (a third-party product — we build our
own equivalent in this class; we do not copy its code, design, data, or name):

1. **Browse Deals** — a searchable property-deal feed.
2. **Filters** — by deal type; the reel uses **Probate**. Listings shown in
   Ohio in the ~$29k–$41k range.
3. **Value spread on every deal** — the platform's estimated value vs the
   property's appraised value (reel example: est. $36,818 vs appraised
   $103,000). The gap is the wholesale opportunity.
4. **Contract screen** — a deal opens into a contract view with the purchase
   price pre-filled (reel example: $36,817.90).
5. **Flip This Contract** — one action to assign/flip the contract.
6. **Get Cash Buyers** — match the contract to cash buyers.
7. **Profit calculator** — resale/assignment math on screen (reel example:
   80,000 − 36,818 = 43,182 potential profit).

Wholesaling model: get a distressed property under contract below market,
assign the contract to a cash buyer, keep the spread — no purchase, no loan.

## Our build (v1 scope)

Separate site, own brand, own code — same class of tool:

- Browse Deals feed with type filters (Probate, Foreclosure, Vacant,
  Tax Delinquent, Pre-Probate) and state/city search.
- Deal cards: asking price vs estimated market value, spread $ and %,
  beds/baths/sqft, days-on-market signal.
- Deal detail → contract view (purchase price, earnest, assignment fee).
- Profit calculator (ARV − purchase − repairs − fees = spread).
- Flip This Contract flow (contract summary → assign).
- Cash Buyers board (buyer criteria: areas, max price, property types).
- **Data honesty:** v1 ships with a clearly labeled DEMO dataset. Live deal
  data needs a real source (public probate/court records, MLS/wholesaler
  feeds) — that wiring is a later stage, chosen with Keyz.

## Status

- 2026-11-15: research saved, v1 site build started.
- Working name FLIPVIZION until Keyz picks a final name (repo/site rename in
  one step, same as Vizion Chat / DragonDance pattern).
