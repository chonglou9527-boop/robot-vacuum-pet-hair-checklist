# Robot Vacuum Pet-Hair Spec-Check List

A one-page, spreadsheet-ready checklist for verifying the claims on a robot vacuum listing before you buy one for a pet-hair household. It turns common marketing claims (suction rating, runtime, bin capacity, brand stability) into concrete yes/no questions you can hold up against a specific model.

## Why this exists

Published suction and runtime numbers are usually best-case figures, not the numbers a robot vacuum hits during normal, everyday cleaning. Bin capacity gets marketed in absolute terms that don't tell you how many days that actually buys a specific household. Brand stability (who owns and services the company) never appears on a spec sheet at all, even though it affects app support and spare-parts availability for years after purchase. This checklist collects the questions worth asking about each of those before comparing models on price alone.

## How to use it

1. Download [`robot-vacuum-spec-check-list.csv`](./robot-vacuum-spec-check-list.csv).
2. Open it in any spreadsheet tool (Google Sheets, Excel, Numbers).
3. Add a column for each model you're actually comparing.
4. Fill in an answer for every row before you buy — most of these answers aren't on the product page, so you may need to check the manufacturer's own support site, an independent review, or ask the retailer directly.

## The checklist

| Category | Question to ask before buying | Why it matters |
|---|---|---|
| Suction claim | What suction mode (max, standard, or quiet) was the published Pa figure measured in? | Published Pa figures are the ceiling, not the daily setting. Hands-on testing we reviewed suggests many robots run well under that ceiling on their default mode, but this isn't a confirmed industry-wide spec, so verify it for your specific model rather than assuming it. |
| Runtime claim | Was the advertised runtime measured at the lowest suction setting? | Runtime drops well below the advertised figure once you switch to a stronger mode for carpet or heavy shedding. |
| Navigation type | Does it use LiDAR, or camera-only (vSLAM) navigation? | Camera-only navigation struggles more in low light and has a harder time telling objects apart; LiDAR is the current baseline. |
| Obstacle handling | Has it been tested specifically around thin-framed furniture (dining chairs, metal-leg stools)? | This is a common blind spot across brands and price points regardless of sensor sophistication. |
| Mop mechanism | Is the mop a continuous roller, a spinning disc/pad, or a flat static pad, and how is it rewetted/scraped between passes? | Reported real-world mopping results vary more by maintenance engineering than by mop-type category alone. |
| Auto-empty | Does it auto-empty the dust bin, and how many days between manual bag/filter changes? | Determines real hands-off maintenance frequency, especially for heavy-shedding households. |
| Auto mop-wash | Does the dock wash and dry mop pads with hot water, or just rinse with cold water? | Hot-water washing and hot-air drying cut down on the odor buildup that plain rinsing doesn't fully solve. |
| Battery lifespan | Any published guidance on when battery capacity starts degrading? | Batteries in this category typically start measurably degrading somewhere in the 2-to-4-year window; factor this into a per-year cost comparison. |
| Replacement parts | Are brushes, filters, mop pads, and dust bags sold separately, and at what recurring cost? | Ongoing consumables are a real cost of ownership that doesn't show up in the sticker price. |
| Brand stability | Who currently owns and services this brand? Any recent bankruptcy, restructuring, or ownership change? | A financially unstable brand is a risk to years of app support, firmware updates, and spare-parts availability. |
| Review source | Does the review or best-of list disclose an affiliate/commission relationship with the products it ranks? | Not disqualifying by itself, but worth weighing against independent, non-commissioned test data when claims conflict. |
| Fit for your floors | Is this a vacuum-only, hybrid with mop lift, or hybrid with full mop detach? | Determines whether carpet-specific mop-clearance issues apply to your home at all. |

## Sourcing notes

- Rows about suction/runtime measurement conditions reflect patterns observed across hands-on testing, not a published industry standard — they're a starting point to verify against a specific model, not a guarantee.
- Rows about battery lifespan, brand stability, and cost of ownership are based on manufacturer support pages and public reporting available at the time this was written; check current sources before relying on them, since ownership and warranty terms change.
- This file has no tracking, no required signup, and no ads. Copy it, edit it, or use it however's useful.

## License

MIT — see [LICENSE](./LICENSE).

## Background

This checklist was put together while researching and writing a longer breakdown of robot vacuum buying claims for pet owners, published at [neurad.org](https://neurad.org/2026/09/18/robot-vacuum-for-pet-hair/). That article goes into more depth on each row above, including the specific testing and reporting behind the sourcing notes.
