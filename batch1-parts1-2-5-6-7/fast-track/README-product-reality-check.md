# What I found spending time in the real product

The fast-track pages in this folder are grounded in the live app, not the old book's descriptions. Worth knowing: the product has moved on further than just "SellerAmp/BuyBotPro became the ASIN Analyser." Several things exist now that the old Part 3/4/5 content doesn't mention at all, or describes differently:

**New since the old book was written, or renamed:**

- **Radar**: a live feed aggregated across every tracked supplier, already filtered to your saved preferences. There's no equivalent to this in the old book at all. For a new seller, this is arguably the actual starting point each day, more than the old "Retailers Tab."
- **"Retailers Tab" is now Sourcing Library**, split into Retail Arbitrage, Online Arbitrage, Wholesale, and Categories. Same idea, new structure, new name.
- **"Custom Scans" is now Analyse**: same job (upload a supplier file, get it matched), new name and a proper file manager (All files / Completed / Processing / Failed).
- **Picked for you (SourceScore)**: a personalised recommendation feed with a visible 0-100 score and a factor breakdown (supplier affinity, category match, ROI fit, price fit). New, not in the old book.
- **Buy List** isn't just a shortlist. It auto-buckets every product into **Strong Opportunity / Need Review / Rejected**, which maps almost exactly onto Module 7's Reject / Proceed Cautiously / Park decision logic. Worth making that link explicit in the full Module 7 rewrite too, it's a genuinely good teaching hook that already exists in the product.
- **Storefront Stalker** and **ASIN Monitor** are both live, standalone tools. Storefront Stalker tracks a competitor's whole storefront and finds what else they sell profitably. ASIN Monitor watches specific ASINs and alerts on threshold changes. Neither is mentioned anywhere in the old book.
- **SKU Format** (Settings) actually builds your Amazon SKUs for you from tokens (Supplier, Cost of Goods, Sell Price, ASIN, Quantity, Date), checked against Amazon's 40-character limit, and sends Buy List products to your Amazon inventory with it. The old Module 9 tracker content (9.1-9.3) describes a manual spreadsheet process. That may now be partly or fully replaceable by this native feature, worth checking with your team before Module 9 gets its own rework.
- **SellerToolKit integration** is two-way (import stock/sales data from it, or send it your Buy List cost data), not just an external tool to sign up for later as the old 5.14/11.4 framed it.
- **Amazon account linking** (Settings → Connected Accounts) is a real feature. Once linked, eligibility checks and fees calculate against your actual account rather than a generic estimate. Worth surfacing early in Module 5/setup, which I've done in the fast-track's 0.1.

**What this means beyond the fast-track:** Parts 3 and 4 of the full blueprint (not just the old Module 5 I already rewrote) describe a version of the SourceSheets dashboard that's noticeably behind what's actually live now. When you're ready for a fuller rework pass, not just the fast-track, Module 6 (SourceSheets Runthrough) in particular will need a proper rewrite against the real nav, not just a renumbering.
