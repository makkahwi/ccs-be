# Currencies Collection Showroom Backend

Strapi-Based Backend Of Currencies Collection Showroom

## Backend To-Do Tasks

- Build model count with filter APIs
- Build model createMany & updateMany APIs
- Build dedicated all stats & APIs

## How to start development

- Fork repo to own Github account
- Clnoe new repo to local machine
- Cd to root directory
- Run CLI command of... yarn
- Run CLI command of... yarn develop

### Models

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

## How to deploy & start using as a collector

If you are not a web developer (coder / programmer), we are still working to provide you with an easy approach to build your own showroom. If you are a developer, everything is ready for deployment. Just deploy to whatever service you see fit (like Vercel, Netlify, Heroku).
