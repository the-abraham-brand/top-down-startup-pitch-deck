---
name: review
description: Top-Down Startup Pitch Deck review command. Audit an existing pitch deck for answer-first storyline, investor essentials, design discipline, and above all whether every number is backed by a real, matching source; return a verdict, scorecard, list of unsupported claims, and fixed slides. Use when the user runs /top-down-startup-pitch-deck:review, or shares a deck and asks to check, fact-check, tighten or "make it investor-ready".
---

# /top-down-startup-pitch-deck:review

Review a pitch deck and return a verdict, a scorecard and the fixes.

1. Load the `top-down-startup-pitch-deck` skill from this plugin (via the Skill tool) and follow it in **Review** mode. If it cannot be loaded, read `../top-down-startup-pitch-deck/SKILL.md` and its `references/` folder directly.
2. Read the deck from the attachment (.pptx, .pdf, or a slides link the session can open) or pasted text. Extract every slide's headline, body and every number.
3. List every figure in a ledger. For each external figure, look for the source: first any citation on the slide, then research, choosing authoritative sources for this deck's industry, problem and geography. Apply the trust test and verification steps in `../top-down-startup-pitch-deck/references/research-and-sources.md`. Mark each as Verified, Corroborated (two independent trusted sources), Mismatch (the source says something different; state what), Untrusted source (traced only to a vendor blog, roundup or self-serving study), Unverified (no source found) or Company data.
4. Score the deck against `../top-down-startup-pitch-deck/references/review-checklist.md`.
5. Deliver: the verdict (Investor-ready / Needs fixes / Needs rebuild), the scorecard, the figure ledger with statuses, the top issues in order of importance, and rewritten headlines and slide text. Offer to rebuild the deck with the fixes applied; if the user asked for a rebuild, do it.

Never "fix" an unverified number by inventing a source. Replace it with a verified figure, reword the claim, or mark it `[needs source]`.
