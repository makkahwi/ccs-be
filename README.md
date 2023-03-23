# Currencies Collection Showroom Backend

## Intro

- A system for currency collectors to document their collection process & publish their collection to public.
- A collector can categorize currencies by...
  - Which country / currency zone it belong to.
  - What type of currency piece (Banknote / coin).
 - A collector can track what have been collected out of total targeted pieces.

## Models

- Country
  - name
  - fullName
  - mapCode
  - continent
- Currency
  - name
  - code
  - mostRecentEdition
- ExchangeRate
  - code
  - valuePerUsd
- CurrencyEdition
  - order
  - year
- Piece
  - value
  - type
- Collection
  - frontPhoto
  - backPhoto
  - date
  - count

## APIs To Add

- Model Count with Filters
- Model CreateMany & UpdateMany APIs
- All Stats APIs

## Future Works

- Platform for several users
  - Model CRUD mine APIs
