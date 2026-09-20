# Module 6 rework notes

## What changed
This is a full rewrite, not a renumbering. Old Module 6 described the pre-revamp SourceSheets UI ("Retailers Tab" / "Sheet View" language, per your note that the old blueprint was written against the old version of the product). Everything here is rebuilt against the live nav and live sheet viewer, verified directly in the browser rather than inferred.

New structure:
- **Module intro**: same tone/length as the other module intros
- **6.1 The SourceSheets Stack**: General group (Dashboard, Picked for you, Sourcing Library, Radar, Analyse, Buylist) and Tools group (Storefront Stalker, ASIN Monitor, ASIN Analyser), with a "what to focus on first" steer toward Radar then Sourcing Library
- **6.2 How to Read a Daily Sheet**: the real column list, Filters panel fields, the saved-preferences confirmation UI, eligibility checking and its Amazon-account dependency, Price History range toggles, Compact view
- **6.3 Using a SourceSheet in Practice**: the 4 row action icons, the full product detail modal panel by panel, and a "don't evaluate on Profit/ROI alone" guidance note
- **6.4 How to Quickly Filter Out Time-Wasting Products**: Filters as first pass, Buy List auto-bucketing as second pass, explicitly framed as triage rather than a Module 7 substitute

## Verified live, not guessed
Every UI detail in these four pages was confirmed directly in the browser against your real account: the nav groupings, the sheet columns, the Filters panel fields, the "Already filtered to your saved preferences" confirmation text, the Check eligibility behaviour (stays "Not checked" with no Amazon account linked under Settings → Connected Accounts), the preset system ("No saved presets yet" / Save as preset), the Price History range toggles, Compact view, the 4 row action icons (confirmed via element lookup, not guesswork), and the detail modal's six panels.

## One thing to double check
Check eligibility staying "Not checked" across every row is consistent with no Amazon Seller Central account being linked in that test account's Settings, and I've written 6.2 to state that as the reason. I couldn't fully confirm it (i.e. I didn't have a linked account to test the working case against), so if there's a second reason eligibility checks can fail, flag it and I'll adjust the wording.

## Cross-references this creates or affects
- 6.3 points back to Module 5 (ASIN Analyser) for "Open in ASIN Analyser" and forward to Module 7 for full evaluation
- 6.4 points forward to Module 7 and ties Buy List's auto-bucketing to the 7 Gates logic, same hook used in fast-track 0.3
- Old Module 6 sub-pages should be fully replaced, not merged, given the UI they describe no longer exists

## Still open from earlier flags (not part of this delivery)
- 1.2, 1.4, and 7.2 still name SellerAmp/BuyBotPro and need the same cross-reference cleanup flagged in Module 5's notes
- Module 9 (inventory tracker) decision still pending: noted separately
