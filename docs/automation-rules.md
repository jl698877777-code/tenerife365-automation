# Tenerife365 Automation Rules

## Core Operating Rules

1. Minimum stay should normally be 3 nights unless a specific property or season rule says otherwise.
2. Analyze revenue by property group:
   - Javi-owned / fixed-rent properties: count revenue, platform payout and operating profit as Javi income.
   - Management-only properties: only count management fee or operator income.
3. LAS821 is management-only. Do not treat owner platform payout as Javi operating income.
4. Future recommendations should use existing amenities, furniture and hardware unless new purchases are explicitly requested.
5. Booking.com pre-arrival communication must avoid phone numbers, WhatsApp, emails, direct-booking invitations or off-platform contact requests before check-in.
6. Guest review replies should not use emojis and should be signed as: Javilin – Tenerife365 Team.

## Audit Priority

1. Pricing below minimum price.
2. Long orphan gaps or empty periods.
3. Low occupancy in next 30 / 60 / 90 days.
4. Booking.com cancellation exposure.
5. Listing quality problems: title, photos, amenities, location wording, guest friction.
6. Blocked-night anomalies.
7. Revenue separation errors between Javi properties and management-only properties.

## Security Rules

1. Never commit API keys.
2. Never commit Hostaway, Booking, Airbnb or PriceLabs passwords.
3. Never commit guest passports or personal documents.
4. Never commit owner bank details.
5. Use .env locally for secrets.
