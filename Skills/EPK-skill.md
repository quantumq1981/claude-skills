EPK-SKILL.MD

---
name: generating-corporate-gig-epks
description: Generates Electronic Press Kits (EPKs) for high-volume corporate, wedding, and casino-lounge gigging artists. Use when a working musician or bandleader needs a booking-focused press kit for talent buyers, casino entertainment directors, corporate event planners, or wedding coordinators — prioritizing compliance, scalability, and repertoire over artistic narrative or streaming metrics.
---

# Generating Corporate Gig EPKs

## Quick Start

Collect artist data using the schema below, then generate a one-to-two-page EPK structured for talent buyer skimmability (10-15 second scan time). Lead with compliance/risk signals, not bio.

```json
{
  "artist_identity": {
    "primary_name": "Chris Zemba Band",
    "market_location": "Pittsburgh, PA",
    "experience_years": 18,
    "roles": "Bandleader, Guitarist, Vocalist"
  },
  "compliance_and_risk": {
    "insured_status": true,
    "w9_ready": true,
    "coi_available": true
  },
  "ensemble_scalability": {
    "configurations_offered": ["Solo Acoustic", "Duo", "Trio", "4-Piece", "6-Piece w/ Horns"],
    "side_projects_offered": ["80s Tribute Act", "Sinatra-Style Lounge Trio"]
  },
  "market_specialties": {
    "event_types": ["Weddings", "Corporate Galas", "Casino Lounges", "Private Parties"],
    "proven_clientele": ["Rivers Casino", "Hard Rock Pittsburgh", "PNC Corporate Events"]
  },
  "repertoire_and_sound": {
    "total_song_count": 350,
    "genres_covered": ["Classic Rock", "Funk", "Top 40", "Modern Country", "Motown"],
    "core_artists_covered": ["Bruno Mars", "Journey", "Bruce Springsteen", "Morgan Wallen"]
  },
  "production_logistics": {
    "self_contained_pa": true,
    "max_venue_capacity_handled": 500,
    "max_set_length_hours": 4
  }
}
```

Output: a formatted EPK (markdown or PDF-ready doc) that reads like a vendor capability sheet — because that's what talent buyers in this market are actually evaluating.

## Workflow

Progress:
- [ ] Step 1: Intake artist data against the full schema — do not skip compliance fields, they are non-negotiable for corporate/casino buyers
- [ ] Step 2: Validate scalability array has at least 2 configurations (buyers need budget flexibility options)
- [ ] Step 3: Confirm repertoire count and genre breadth support "keep the room full" positioning
- [ ] Step 4: Draft EPK sections in buyer-priority order (see structure below)
- [ ] Step 5: Compress to 1-2 pages; cut anything that reads as "artistic bio" rather than "vendor capability"
- [ ] Step 6: Insert a one-line CTA with booking contact and COI/W-9 availability restated

### EPK Section Order (buyer-priority, not artist-priority)

1. **Header** — Name, market base, years active, one-line positioning (e.g., "18-Year Pittsburgh-Based Corporate & Casino Entertainment Act")
2. **Compliance Snapshot** — Insured ✅ / W-9 Ready ✅ / COI Available on Request ✅ (badge/checkmark format, not prose)
3. **Configurations & Pricing Flexibility** — List scalable lineups so a buyer can immediately see they can fit any budget tier
4. **Proven Clientele** — Named venues/brands (social proof for risk-averse buyers)
5. **Repertoire Strength** — Song count + genre spread + name-drop core artists covered
6. **Production Capability** — Self-contained PA, max capacity, max set length (answers "will this act cause logistical problems?")
7. **Contact/Booking CTA**

## Examples

**Example 1:**
Input: Solo wedding guitarist, 5 years experience, no horn section, self-contained small PA, 150 total songs, acoustic/pop covers only, insured but no COI yet.
Output: EPK emphasizes intimate ceremony/cocktail-hour fit, positions "Solo Acoustic" as the core offering rather than downplaying lack of scale, lists insured status but notes "COI available upon request" only if `coi_available` is true — otherwise omit the line entirely rather than stating an absence.

**Example 2:**
Input: 6-piece band with horn section, casino lounge residency history, 400+ songs, Top 40/Motown/Classic Rock, fully insured with COI ready.
Output: EPK leads with casino clientele names, headlines "Scalable from Duo to Full Horn Band," emphasizes 4-hour set capability and self-contained PA for large-capacity rooms — this is the flagship configuration for the sector.

## Best Practices

- **Lead with risk mitigation.** Insurance/W-9/COI status goes above the fold — corporate and casino buyers filter on this before reading anything else.
- **Show the scaling range, not just the max.** A buyer with a $2,000 budget and a buyer with a $12,000 budget should both see themselves in the configurations list.
- **Quantify repertoire.** "350 songs across 6 genres" is a stronger trust signal than a vague "wide variety of music."
- **Name-drop venues/brands, not just genres.** "Performed at Rivers Casino" beats "experienced casino performer."
- **State capacity numbers plainly.** Max venue capacity and set length are logistics filters buyers use to shortlist/reject fast — don't bury them in prose.
- **Keep it to 1-2 pages.** This audience skims; treat it like a vendor spec sheet, not a magazine feature.

## Common Pitfalls

- **Do not lead with artistic bio or "sound story."** This audience does not care about influences or creative journey — it reads as unpreparedness for commercial work.
- **Do not omit compliance fields even if incomplete.** If `insured_status` is false, don't leave it blank — either state a path to obtaining it or omit the section header entirely rather than raising an unanswered red flag.
- **Do not bury scalability in paragraph form.** Use a list/table so a buyer can pattern-match to their budget in seconds.
- **Do not include streaming stats, follower counts, or release dates** unless specifically requested — irrelevant to this buyer's decision criteria.
- **Do not overstate max capacity or set length.** Buyers will hold the act to these numbers; inflated logistics claims damage repeat-booking trust in a small regional circuit.