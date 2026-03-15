# IMO Public Feed

Public machine-readable feed repository for IMO automation outputs.

## Purpose
This repo hosts public JSON endpoints that other IMO workflows and automation tasks can read without requiring GitHub authentication.

## Current intended paths
- `rfq/packet_candidates.json` — current shortlist of packet-eligible RFQ opportunities
- `opportunities/` — reserved for future published opportunity feeds

## Notes
- Files in this repo are intended to be overwritten by automation.
- URLs from this repo can be used directly in GPT task prompts and other read-only integrations.
