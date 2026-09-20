# Cross-reference cleanup notes

Pulled the live text of all three pages from the GitBook before editing, so these are precise, minimal-diff replacements, not rewrites. Only the SellerAmp/BuyBotPro-related parts changed; everything else is untouched, word for word.

## 1.2 Your Success Path
One line changed: "How to use SellerAmp or BuyBotPro" → "How to use the SourceSheets ASIN Analyser". Nothing else touched.

Also worth knowing: while pulling this page I confirmed the Milestones mechanism is real ("we verify your Milestones and add it automatically"): that resolves the flag I left in Part 5's 13.2/13.3 about the submission mechanism being my best guess. It wasn't a guess, it's correct.

## 1.4 What Tools You'll Use
The "SellerAmp or BuyBotPro (You Choose One)" section is replaced with a "SourceSheets ASIN Analyser" section, same bullet structure, updated to reflect it's a built-in tool with nothing to choose or set up externally. The beginner stack list's "SellerAmp / BuyBotPro → analyse safely" line is now "ASIN Analyser → analyse safely".

One judgement call: I also dropped "inventory/profit trackers (Sellerboard, STK)" from the "optional extras" list. STK is SellerToolKit, and per the Module 11.4 rework still pending, it's now a real two-way integration inside Settings, not an external tool to bolt on later. Sellerboard stays in as a genuine optional extra. Flag if you want STK left in for now until 11.4 is actually done, I can put it back.

## 7.2 Phase 1, item 1
This page doesn't survive as a like-for-like swap. The old page was entirely about choosing between SellerAmp and BuyBotPro and how that choice changes what opens when you click a product row, none of which exists anymore, SourceSheets has one built-in tool and no click-behaviour preference to set.

I replaced it with a same-purpose page: confirming your Preferences (Settings → Preferences) are actually filled in before you start analysing, since that's the real pre-check that matters now, and it's a small piece of what old 7.2 was already gesturing at. Filename changed to `7.2-phase-1-item-1-confirm-your-preferences-are-set.md` to match the new content, you may want to update the phase list's internal link if your GitBook navigation references the old title directly.

The old page also had a screenshot of a stale "Buy List" table (columns: ASIN / Amazon Image / Keepa Graph / Amazon Title) that doesn't match the current UI at all. Added to the asset list, needs a fresh screenshot of Settings → Preferences instead.
