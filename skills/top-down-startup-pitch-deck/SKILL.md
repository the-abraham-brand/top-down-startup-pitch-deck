---
name: top-down-startup-pitch-deck
description: Build or review a startup pitch deck that leads with the answer, follows a proven investor framework (Tagline, Founding Team, Market, Pain Points, Solution, Why Now, Unit Economics, Ask), and backs every figure with a cited, research-verified source. Use this whenever the user wants a pitch deck, investor deck, fundraising deck, seed or Series A deck, startup presentation, demo-day slides, or a product pitch deck for prospects, or asks to fix, tighten, fact-check or "make investor-ready" an existing deck, even if they don't mention sources or structure. Do not use it for internal status decks, training slides or non-pitch presentations.
---

# Top-Down Startup Pitch Deck

Investors decide in minutes and distrust numbers they cannot check. A deck that states its answer first, walks through a familiar sequence, and cites every figure earns more attention and more trust than one that builds suspense or decorates claims.

This skill produces decks with three properties:

1. **Top-down**: the opening slides state what the company does, for whom, and what it is asking for. Every slide title is a full-sentence takeaway, and the titles read in order tell the whole story.
2. **Framework-led**: a fixed investor sequence (below), adaptable to a product/prospect variant.
3. **Research-backed**: every market, pain, trend or benchmark number carries a source that was actually opened and checked. Nothing is invented.

## Mode

- **Build**: the user gives a company description, notes, a spec sheet, an old deck or a website, and wants a deck.
- **Review**: the user gives an existing deck (file or text) and wants it checked, fixed or rebuilt.

Pick the **deck type** from the request: **investor** (default; fundraising, accelerators, demo day) or **product** (prospects, customers, partners). The two share the design system and sourcing rules; the slide sequence differs. See `references/deck-structure.md`.

## Step 1: Gather the company facts

Collect from the user's material, and ask only for what is missing and essential (batch the questions into one message):

- One-line description: what it does, for whom, how it is different.
- Stage, traction (users, revenue, pilots, growth), and anything already proven.
- Team: names, roles, the one credential per person that matters for this business.
- Business model and pricing; costs per unit if known.
- The ask (amount, instrument if known, what it buys, milestones it reaches). For product decks: the offer and next step.
- Brand: colours, font, logo. If none, use the default design system.

Label every company-supplied figure as **company data**. It does not need an outside source, but it must be marked as the company's own figure and never dressed up as independent research.

## Step 2: Research and verify the numbers

These decks go to investors, so research data integrity is the priority. Read `references/research-and-sources.md` before searching. In short:

- **Plan from the solution.** Work back from the product to the problem, from the problem to the claims each slide must prove, and from each claim to who produces authoritative data on it in this industry and geography. There is no fixed source list; the right sources depend on the startup.
- **Use only trusted providers.** Each source must pass the trust test: it produced the data, or is an established publisher that verifies data and names its underlying source (such as Statista or Reuters); its method is evident; it is independent of the claim; it is dated and recent; and it fits the claim's geography, segment, year and definition. Vendor blogs, statistics roundups and self-serving vendor "studies" are leads at most, never citations.
- **Verify every figure.** Open the page, match the figure exactly, trace it to its origin, and corroborate headline and investment-critical figures with a second independent trusted source. Record the status of each: Verified, Corroborated, Mismatch or Unverified.
- Keep a **sources ledger** (format in the reference file). Every number on every slide maps to one ledger row or is marked company data.
- If a figure cannot be verified, it does not go on the slide. Replace it, reword the claim without the number, or leave `[needs source]` visible and list it for the founder. Never fabricate numbers, quotes, testimonials, logos, customers or citations.
- Build SAM and SOM bottom-up (customers × price, stated assumptions) and show the arithmetic in the speaker notes. Label any top-down TAM with its source and year.

## Step 3: Build the storyline before the slides

Write the slide titles first, as a list. Check:

- Slide 2 (Tagline) answers "what is this and why should I care" in one line, and the ask or offer appears there or on the cover subline.
- Each title is a full sentence that states the slide's conclusion ("[Segment] misses [X] in [Y] inbound calls", with the figure sourced), not a label ("The Problem").
- Read in order, the titles tell the complete pitch with no gaps.
- Each slide supports one idea; its content proves that title and nothing else.

Show this outline to the user (or include it at the top of your reply) before or alongside the build, so they can correct the story early.

## Step 4: Build the deck

- Follow the slide-by-slide spec in `references/deck-structure.md` and the look in `references/design-system.md`.
- Put a source marker next to each sourced figure (superscript number or short "Source:" line at the slide foot) and finish with a **Sources** slide listing full citations. Company figures get a "Company data" note.
- Add speaker notes to every slide: the talking points, the arithmetic behind any calculated number, and the full citation for each figure used.
- Output format: use the session's slide-deck capability if one is available (for example a slides artifact type). If the user asks for PowerPoint or no deck tool exists, build a .pptx with the pptx skill. Render and look at every slide before delivering: no overflow, clipped text or overlapping boxes.

## Step 5: Check before delivering

Run `references/review-checklist.md`. The non-negotiables:

1. The opening two slides state what the company does, for whom, and the ask or offer.
2. Every slide title is a full-sentence takeaway; the titles alone tell the story.
3. Every external number comes from a source that passes the trust test, was opened and matches exactly, and headline figures are corroborated; every internal number is labelled company data.
4. No invented testimonials, customers, logos, quotes or awards.
5. Design rules held: one typeface, no italics, restrained sizes, one accent colour, nothing clipped.

## Output

Deliver:

1. The deck.
2. **Storyline**: the slide titles in order.
3. **Sources ledger**: every figure, its source and date (as a table in the reply, and on the Sources slide).
4. **Open items**: any `[needs source]` placeholders, company figures that need confirming, and claims you softened or removed, with the reason.

In Review mode, lead with a verdict (Investor-ready / Needs fixes / Needs rebuild), then a scorecard against the checklist, the unsupported or unverifiable claims found, and the revised deck or revised slide text.
