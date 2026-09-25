# Top-Down Startup Pitch Deck

**By [Abraham](https://theabrahambrand.com)**

A Claude plugin that builds and reviews startup pitch decks that lead with the answer, follow a proven investor framework, and back every figure with a cited, research-verified source.

## Why it exists

Most pitch decks bury the ask and decorate slides with statistics nobody can trace. Investors notice both. Top-Down Startup Pitch Deck fixes the two together:

- **Answer first**: the cover and first slide say what the company does, for whom, and what it is asking for. Every slide headline is a full-sentence takeaway, and the headlines read in order tell the whole pitch.
- **Research-backed**: every market, pain, trend and benchmark figure is researched, opened at the source, matched exactly, and cited on the slide and on a closing Sources slide. The company's own numbers are labelled as company data. Nothing is invented.

## What's included

| Skill | How it runs | What it does |
|---|---|---|
| **top-down-startup-pitch-deck** | Automatically, whenever you ask for a pitch, investor, fundraising or product pitch deck | Framework, sourcing rules, design system and checklist |
| **/top-down-startup-pitch-deck:build** | You run it with company notes, a spec sheet or an old deck | Researches the numbers, drafts the storyline, builds the deck with source footers, speaker notes and a Sources slide |
| **/top-down-startup-pitch-deck:review** | You run it with an existing deck | Verdict, six-part scorecard, every figure checked (Verified / Corroborated / Mismatch / Untrusted source / Unverified / Company data), and rewritten slides |

## The framework

**Investor deck:** Cover (with the ask) → 01 Tagline → 02 Founding Team → 03 Market → 04 Pain Points → 05 Solution → 06 Why Now → 07 Unit Economics → Traction* → Competition* → The Ask → Sources

**Product deck (for prospects):** Cover → The Problem → The Solution → How It Works → What You Get → Who It's For → Pricing → Why Us → Get Started → Sources

*Optional.

## Research data integrity

Decks built with this plugin are meant for investors, so the research rules are strict:

- **Research follows the solution.** The plugin works back from the product to the problem, to the claims each slide must prove, to who holds authoritative data on those claims in that industry and geography. No fixed source list: a UAE healthtech deck and an Indian fintech deck need different sources.
- **Trusted providers only.** Every source must pass five tests: it produced the data or is an established publisher that verifies data and names its underlying source (such as Statista or Reuters), its method is evident, it is independent of the claim, it is dated and current, and it fits the claim's geography, segment and definition. Vendor blogs, statistics roundups and self-serving vendor studies are never cited.
- **Every figure verified.** Each source page is opened, the figure matched exactly and traced to its origin; headline and investment-critical figures are corroborated by a second independent source.
- **Market sizing done properly.** TAM is cited; SAM and SOM are built bottom-up with the arithmetic in the speaker notes.
- **Nothing invented.** Anything that can't be verified is replaced, reworded, or marked `[needs source]` for the founder.

## Design

Minimal tech: charcoal background, one warm gold accent, off-white type, one typeface, no italics, restrained type sizes, generous space. Your brand colours, font and logo replace the defaults when you supply them.

## Installation

In Claude Code:

```
/plugin marketplace add the-abraham-brand/top-down-startup-pitch-deck
/plugin install top-down-startup-pitch-deck@top-down-startup-pitch-deck
```

In the Claude app, install it from the plugin directory once it's listed.

## Works well with

[Top-Down Brief](https://github.com/the-abraham-brand/top-down-brief), for the answer-first emails, memos and investor updates that go with the deck.

## Credits

Top-Down Startup Pitch Deck is designed and maintained by Abraham ([theabrahambrand.com](https://theabrahambrand.com)). Its storyline applies the Pyramid Principle described by Barbara Minto in *The Pyramid Principle: Logic in Writing and Thinking*. This is an independent project, not affiliated with or endorsed by Barbara Minto or Minto International.

## License

MIT © 2026 Abraham
