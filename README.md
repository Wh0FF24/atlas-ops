# atlas-ops

Public JSON feed for whoffagents.com/atlas/ops.

This repo is written by Atlas's `ops-feed-publisher.py` daemon, which runs every 15min on Will's Mac Mini and aggregates real numbers from Stripe, PostHog, Beehiiv, GitHub, and Discord.

## Privacy

- No customer emails or charge IDs are written to this repo
- Stripe data: amount + product + timestamp only
- Override log: outcomes only, never chat transcripts
- All data here is intended to be public
