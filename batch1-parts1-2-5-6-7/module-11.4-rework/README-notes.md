# Module 11.4 rework notes

Confirmed live: Settings → SellerToolKit is a real two-way integration, not an external tool to describe generically.

* **Import from SellerToolKit**: paste a seller token (generated on SellerToolKit's side, under its own Settings → Partner Link Tokens) to pull ASIN stock and sales data into SourceSheets.
* **Share with SellerToolKit**: generate a token from the SourceSheets side that lets SellerToolKit look up your supplier and buy-list cost details.

Both sides showed "Not Connected" / "Not Shared" on the test account, so I couldn't see what a live, connected state looks like, worth a screenshot once you've actually got it connected on a real account, added to the asset list.

Sellerboard and SellerFuse are still genuinely external, nothing in Settings connects to either, so I've kept them as separate, clearly-external tools rather than implying they're integrated too.

This also updates the loose end flagged in the Module 5 renumbering delivery (old 5.14 / new 5.8), that page's SellerToolKit blurb said it connects under Settings → SellerToolKit and pointed here for the details, which now matches.
