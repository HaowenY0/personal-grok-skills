---
name: elephant-poker
description: "Single-file Texas Hold'em GTO solver and live advisor (大象Poker). Supports MTT, Squid (N-1/N+1/N+3), follow mode, review, lab, preflop CFR, and river nodes. Use when the user asks about poker strategy, GTO ranges, squid pressure, or wants to open the 大象Poker tool."
type: tool
lifecycle: active
---

# Elephant Poker — Single-file GTO Solver

Self-contained HTML app (`大象Poker.html`) for Texas Hold'em GTO analysis. No external dependencies. Open in Chrome or Edge.

## Features

- **Guest entry** or local login/register
- **Formats**: MTT (no squid) and Squid table (N-1, N+1, N+3, custom)
- **Follow mode**: Live hand input → instant advice + sizing
- **Review mode**: Save hands and compare actual vs engine
- **Lab**: Squid pressure EV, Preflop RFI/CFR, River CFR nodes
- **Next hand rotation**, GTO sizing suggestions, equity vs range

## How to Use

1. Open `大象Poker.html` in a modern browser.
2. Click **游客进入**.
3. Choose MTT or Squid.
4. Use Follow mode for real-time recommendations or Lab for deeper analysis.

## Core Logic Notes

- Preflop: Approximate RFI charts + CFR+ for HU spots
- Postflop: Hand shape recognition + EV calculations with size candidates
- Squid: Finite / N+k pressure converted to perceived ante
- All calculations run client-side

## Files

- `大象Poker.html` — complete single-file application (~104 KB)

Place this skill folder where Grok can access it, or serve the HTML directly.
