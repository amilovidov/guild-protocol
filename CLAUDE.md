# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a **documentation and research repository** for the Guild Protocol - a P2P protocol for organizing knowledge work through outcome-based matching, portable reputation, and transparent pricing. There is no source code, build system, or tests.

## Repository Structure

```
.
├── whitepaper.md                              # Core protocol architecture (quests, teams, reputation, guilds, arbitration)
├── staffing-industry-analysis.md              # Staffing industry exploitation analysis with sourced data
├── customer-discovery-research.md             # Customer journey analysis (fringe projects, startups, OSS foundations)
├── customer-discovery-research.pdf            # PDF version of customer discovery research
├── knowledge-work-decommoditization-research.pdf  # Deep research on structural shifts in pricing/assembly/governance
├── guild_protocol_pitch_deck.pptx             # Pitch deck
├── research/
│   ├── gemini-customer-discovery-prompt.md    # Gemini Deep Research prompt for customer discovery
│   └── gemini-research-prompt.md              # Gemini Deep Research prompt for market intelligence
└── marketing/
    ├── linkedin-post-v2.md                    # LinkedIn post draft v2
    └── linkedin-post-with-research.md         # LinkedIn post with sourced research citations
```

## Key Concepts

The protocol organizes around:
- **Quests**: Discrete work engagements with defined scope, measurable outcomes, and escrowed budgets (Solo/Party/Raid/Campaign scales)
- **Teams**: Dynamically assembled via algorithmic matching, fluid membership, functional roles (Lead/Operator/Coordinator/Specialist/Apprentice)
- **Reputation**: Earned through verified quest outcomes, not credentials - immutable, transparent, portable
- **Guilds**: Three configurations - Local (metro-rooted), Traveling (go where work is), Virtual (fully distributed)
- **Arbitration**: Third-party verification for dispute resolution

## Working with This Repository

When editing documents:
- Maintain consistency with terminology defined in the whitepaper
- Numbers and statistics should have verifiable sources (see marketing/linkedin-post-with-research.md for source citation pattern)
- The whitepaper is the source of truth for protocol mechanics

When adding research:
- Follow the structured format in existing research documents (Who Is Buyer, Discovery Journey, Pain Points, Communities, Trust Signals)
- Distinguish between empirical data and speculation
- Include sources for all claims
