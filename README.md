# Blaque Baux Backlash

**Max-Pain Pin vs Gamma Snap (options-expiry inversion) — STUB (blocked on data).**

Inverts the "max pain" pin thesis: rather than betting price gravitates to the max-open-interest strike by Friday expiry, buy straddles / directional breakouts when price sits near max pain at 2pm ET on expiration day, betting the final-hour unwind of gamma suppression produces a violent SNAP away, not convergence.

> **Status: STUB / DATA-BLOCKED.** Specified and queued but **not yet built** — it needs an options open-interest-by-strike feed (to compute max pain) plus intraday expiration-day prices. Alpaca serves only daily price/volume — neither the option chain nor the intraday path is available (see block/bight for the same limit).

> **Not investment advice.** Educational/research software. See [DISCLAIMER](DISCLAIMER.md) and [LICENSE](LICENSE).

## Honest null (to be tested once the feed exists)

Is the 'pin' a myth in modern markets — does removing gamma suppression in the final hour cause a directional snap away from max pain (tradable), or is the pin real/already priced so the snap is just noise minus the spread?

## Why it's a stub

The Blaque Baux research stack runs on Alpaca SIP **daily OHLCV + crypto**. Max-pain pinning and the expiration-day
gamma snap cannot be tested on daily price bars — they require an options open-interest-by-strike feed (to compute max pain) plus intraday expiration-day prices. Alpaca serves only daily price/volume — neither the option chain nor the intraday path is available (see block/bight for the same limit). When that feed is wired in, this becomes
`backlash_1` with the family's standard scorecard, causal signals, and an honest verdict. It is the options-expiry
inversion (N) of the batch-3 set, kin to the data-blocked `bight`/`broaching` options sleeves.

## Status

**Stub.** Placeholder for a queued inversion awaiting options + intraday data. No code, no backtest, no live capital yet.
