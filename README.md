# SKIN/OS

Static Italian skincare routine with seven confirmed The Ordinary formulas. Public source contains general product information and a sample weekly plan, no personal medical history or purchase details. Checks and recovery preference stay in browser localStorage; no analytics, account, or sync.

## Use

Replace the repository root index.html with this file. For the PWA and offline shell, also copy sw.js, manifest.webmanifest, icon-192.png and icon-512.png to the same folder. Enable GitHub Pages for that branch and folder. Relative paths support /skinos/ hosting. Serve over HTTPS. Open online once before testing offline. Browser installation availability varies.

index.html also works alone for the routine and checks; missing companion files disable PWA/offline functionality. Existing v1 draft checks are intentionally not reused because their numeric step IDs describe different routines.

The checklist selects dates in the current local week. AM and PM checks have separate date/product keys. Recovery changes both checklist and weekly table; no automatic restart. Clearing browser site data removes local progress. Local progress is visible to others using the same browser profile.

## Content

Official manufacturer directions were consulted on 2026-10-27; product cards link to the exact formulas. Once-weekly retinol and reduced amount are plan adaptations, not manufacturer dosing instructions. Glycolic is paused. Antioxidant AM and peptides on non-retinol PM evenings keep the schedule simple.

Science descriptions distinguish ingredient function, manufacturer claims and the limits of the cited primary retinol trial. No EPUBs were available; no book-derived claims are included.

## Verification

JavaScript syntax checked for page and service worker. All 14 AM/PM weekly combinations checked for retinol placement, SPF placement and glycolic exclusion; recovery removes optional serums and retinol. DOM smoke checks cover period selection, recovery, table rendering and storage writes. Native browser/mobile rendering, installation and offline behavior have not been verified on a device.

No GitHub commit or deployment was performed.
