# Postage Stamp Cost Calculator

Single-page calculator for a small crafts seller who ships handmade goods and forgets how many stamps a lumpy envelope needs.

## Features

- Enter package weight (ounces) and pick a mail type:
  - First-Class Letter — $0.68 base, +$0.24/oz after 1 oz (max 3.5 oz)
  - First-Class Large Envelope — $1.35 base, +$0.25/oz after 1 oz (max 13 oz)
  - Priority Mail Flat Rate — $9.65 flat (up to 70 lbs)
- Instant cost breakdown: base rate, weight-overage fee, total
- History of the last 5 calculations (weight → mail type → cost)
- Clear History button
- All state lives in memory; no backend required

## Run

Open `index.html` in any browser, or:

```bash
python3 -m http.server 8000
```

Rates are fixed, hardcoded USPS-style tiers — no live API needed.
