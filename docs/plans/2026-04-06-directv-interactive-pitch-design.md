# DIRECTV Interactive Pitch — Design Document

**Date:** 2026-04-06
**Author:** Tom Nwachuku / Claude (Summit X Digital)
**Deliverable:** Interactive HTML pitch page (Haruharu Wonder style)
**Recipient:** Michael Lopez, DIRECTV

## Overview

An interactive HTML microsite presenting Charity Brands' creator-first cause marketing program for DIRECTV. Complements the existing 4-pillar proposal (sent by Nicholas England) with the influencer execution layer: specific creators, format concepts, pricing tiers, and the Propagate/Select/Charitybuzz ecosystem.

## Sections

### 1. Hero & Introduction
- Title: "DIRECTV x Charity Brands — The Creator Network"
- Animated stat counters: 600+ Creators, 73 Verticals, 150+ Series Produced, $10B+ Raised
- Brief intro bridging from the proposal to the creator pitch
- Password gate (optional)

### 2. The Opportunity (Light Proposal Callback)
- 4 cards: The Moment (TPG ownership), The Partnerships (BWF + RMHC), The Gap, The Unlock
- ~200 words total, visual and scannable

### 3. Creator-Led Giving Campaigns
- 3A: "Creators Who Move Money" — proof points (Tyler Oakley $525K single campaign, Chris Olsen GLAAD, Esther Park refugees, Dominic Wakeham veteran)
- 3B: "DIRECTV Gives" Event Architecture — internal employee events + external community events, both creator-hosted
- Charitybuzz/Prizeo integration: turnkey charitable auction/sweepstakes platform, $650M+ raised

### 4. Format Concepts
- "Home Team" Microdrama Series — short-form scripted, Propagate-produced
- "Goals for Good: The Watch Party" — live creator-hosted reaction format
- "The Giving Room" — longer-form interview/documentary series
- "Bid for Good" — Charitybuzz x DIRECTV celebrity/creator experience auctions
- Design: minimal cards with format name, hook, short paragraph

### 5. The Network (Propagate + Select Ecosystem)
- Propagate Content: $200M valuation, $50M Ares investment, 150+ series
- Select Management: 600+ creators, 73 verticals
- Artists First: Jordan Peele, John Travolta, LL Cool J
- Tom Nwachuku: Integrated Consulting stats (300+ clients, $40M+ portfolio, 530+ creators, Veteran Voices $10M)

### 6. Creator Roster (Core of the pitch)
Expandable cards (Haruharu pattern): collapsed shows photo/name/reach/tags, expanded shows about/brand history/rate card/bundles/links.

**Premium Tier (4):**
1. Chris Olsen — 17M reach, LGBTQ+ advocate, GLAAD, White House
2. Tyler Oakley — 13M reach, $1M+ raised Trevor Project via Prizeo
3. Asher Lieberman — 8.8M reach, LGBTQ+, blood donation, UPenn
4. Josh Helfgott — 7.7M reach, "Gay News," voter mobilization, Cornell

**Core Tier (5):**
5. Dominic Wakeham — 2.8M reach, U.S. Marine veteran
6. The Puig Family — 240K reach, military dad + Latina family
7. Jordan Chiles — 1.6M reach, Olympic silver medalist
8. Nick Mayhugh — 148K reach, 3x Paralympic Gold
9. Miki Rai & Dr. Kevin — combined ~280K, RN + surgical resident couple

**Discovery Tier (3):**
10. Bri Dineen — RN, mom of 2, mental health/family
11. Esther Park (Lavendaire) — 762K reach, $40K+ raised for refugees
12. Tyanna Myers — 196K reach, Deaf culture, GMA featured

### 7. Investment Scenarios (Pricing)
Three tiers:
- **The Pilot** ($75K–$125K): 4-5 creators, 90 days, proof of concept
- **The Program** ($250K–$400K): All 13 creators, 6 months, multi-platform
- **The Institution** ($500K–$750K): Full roster + format production, 12 months

### 8. Timeline
12-month CSS grid Gantt chart aligned to proposal phases.

### 9. Next Steps
4-step numbered list.

### 10. Contact / Close
Stephen Adler contact info. Confidential footer.

## Design System

**Palette (softened DIRECTV-adjacent):**
- Deep color: muted navy/slate (not corporate DIRECTV blue)
- Background: warm cream/off-white
- Accent: soft gold or warm coral for highlights
- Tier colors: Premium = accent, Core = sage/slate, Discovery = lavender
- Text: near-black primary, muted secondary

**Typography:** Jost (display/numbers) + DM Sans (body/nav) — proven in Haruharu

**Layout:** max-width 1100px, sticky frosted-glass nav, smooth scroll, CSS-only expand cards

**Interactions:** onclick class toggle for cards (no JS framework), CSS transitions, scroll-margin-top for nav anchoring

## Reference Files
- Haruharu pitch: /Users/bytedance/Projects/select-v2/projects/haruharu-wonder/src/pitch.html
- Quest Stacks pitch: /Users/bytedance/Projects/select-v2/projects/quest-stacks/site/strategy.html
- DIRECTV proposal: /Users/bytedance/Projects/partners/charity-brands/direct-tv/unpacked/word/document.xml
- Select creator data: /Users/bytedance/Projects/select-v2/CREATOR_BIOS.md, CREATOR_MASTER_INDEX.md
- Charitybuzz strategy: /Users/bytedance/Projects/partners/charitybuzz/strategy/
