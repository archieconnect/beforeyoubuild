# CLAUDE.md — Session Instructions & Project Context

## How I want you to work with me

**Be analysis-first and a critical thinker above all.** Challenge assumptions (including mine), check your reasoning, and surface trade-offs. If something is unclear, ask clarifying questions rather than filling gaps with guesses. I'd much rather hear "I'm not sure" or "here are the unknowns" than a confident but weak answer.

Avoid fluff, academic jargon, and performative language. Be direct, structured, and concise, but don't oversimplify complex problems. Nuance matters.

I appreciate a collaborative tone — think thought partner, not instructor. It's okay to have a point of view as long as it's grounded in strong reasoning. Light warmth or humor is welcome when appropriate, but clarity comes first.

We tend to burn tokens wildly, and chats often end fast. **Please be concise even if you're not set to be concise.**

**Primary directive: Honesty over helpfulness.** If something doesn't apply to my context, say so. If multiple paths exist, lay them out and help me choose rather than pretending there's a single right answer.

---

## Project: UserLens (userlens.ca)

UX research consultancy founded by **Archie (Archana Hublikar)**. Site is a static HTML/CSS/JS build — single self-contained files, no framework, no build step.

### Positioning
- Embedded research partner on a flexible retainer
- Sector-neutral (retail, financial services, logistics, travel, enterprise tech, government)
- Not project-based / one-off studies — sustained engagements, typically 3+ months
- Every engagement led by Archie directly, not a junior team

### Key files (all in outputs/)
| File | Purpose |
|------|---------|
| `userlens-homepage-v4.html` | Main homepage — primary working file |
| `userlens-case-travel-resort.html` | Case study: Travel · Rapid Research on Resort Bookings |
| `userlens-case-travel-zero-booking.html` | Case study: Travel · Package Booking (zero booking story) |
| `userlens-case-travel.html` | Redirect → userlens-case-travel-zero-booking.html |
| `userlens-case-booking.html` | Redirect → userlens-case-travel-zero-booking.html |
| `userlens-case-retail.html` | Case study: Retail |
| `userlens-case-inspiration.html` | Case study: Inspiration |
| `squarespace-footer-injection.html` | Footer carousel for Squarespace injection |

### Homepage structure (userlens-homepage-v4.html)
- **Hero** — headline, sub, engagement model line, CTA buttons
- **Problem** — why it matters section
- **Zones (Services)** — 4 zone rows with situational "This is for you if" prompts ✓ all 4 done
- **Work** — case study carousel (12 cards) — teaser rewrites pending for most cards
- **About** — founder bio, stats, credentials strip
- **Testimonials**
- **Comparison table**
- **Contact form**

### Pending work
- [ ] Rewrite homepage carousel cards 1, 2, 5, 7, 9, 10, 11, 12 as teasers (card 3 done)
- [ ] Government services page (content drafted in chat, not yet built)
- [ ] Contact form backend (Azure — decision pending)
- [ ] Site deployment to userlens.ca

### File rules
- Do NOT delete files — overwrite with redirect if needed
- Do NOT rename files without asking first
- Do NOT add pricing to the site
- Keep copy sector-neutral unless explicitly building a government or sector-specific variant
- Images live in `images/` folder relative to HTML files

### Brand / tone for site copy
- Direct, senior, no UX jargon for civilians
- Teasers over outcomes on case study cards — don't reveal the punchline
- "Archie" is the preferred casual name; "Archana" in formal contexts

### Outreach context (for strategy conversations)
- Current active contract: Amazon (hourly, embedded model — proof point for retainer positioning)
- Target: warm network first, then LinkedIn content cadence
- Government clients need different language: citizens not customers, program justification not budget, Policy on Service and Digital framework

---

## Notes on previous sessions
Long sessions have caused context loss multiple times. If context feels thin, ask Archie to confirm current file state before editing.
