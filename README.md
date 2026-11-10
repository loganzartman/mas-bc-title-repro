`merch-card.title` returns the price instead of the card title for the `brand-concierge-product` variant: its layout puts the title in `heading-s` and prices in `heading-xs`, but it doesn't override `headingSelector`, so `title` reads the default `heading-xs`.

Run `python3 -m http.server 8000`, then open http://localhost:8000.
