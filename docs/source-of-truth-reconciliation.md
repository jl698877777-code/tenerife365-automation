# Source of Truth Reconciliation

## Purpose
This file reconciles older transcript-derived knowledge with current uploaded operational exports.

## Current Source Priority
1. Direct CSV exports from Hostaway / PriceLabs uploaded in the current workflow.
2. GitHub master-property-database.csv.
3. Reconstructed memory / transcript files.
4. Older notes marked INFERRED or VERIFY.

## Corrected Property Code
- Use ARENA821, not LAS821.
- ARENA821 is management-only.
- Gross booking revenue belongs to owner side; Tenerife365 should only count management fee or operator income.

## Corrected Hostaway Listing IDs from Listings.csv
- 401C: 268694
- CAM10: 268695
- 401A: 268697
- 401B: 268698
- 115: 268699
- 401D: 335538
- CAM7: 370937
- CHA13: 371409
- MARTE112: 389736
- ARENA821: 519084

## Known Older Conflicts
Older transcript reconstruction mentioned:
- CHA13 Hostaway ID 415010
- ARENA821 Hostaway ID 559732

These should not override the current CSV-derived IDs unless Javi later confirms the older IDs are still active in Hostaway.

## Open Reconciliation Items
1. Confirm whether Maspalomas Dunes is an active Tenerife365-managed listing, a renamed ARENA821 listing, or out of scope.
2. Confirm canonical Outlook account.
3. Confirm channel IDs for Booking, Airbnb, Expedia per property.
4. Confirm PriceLabs base/min/max prices after any manual changes.
