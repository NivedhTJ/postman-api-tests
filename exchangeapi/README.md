# Exchange API Postman Collection
This repository contains a Postman collection for interacting with the Exchange API, a free and fast currency exchange rates API with no rate limits and support for over 200 currencies including cryptocurrencies.

## Overview
This collection includes requests to:

- List all available currencies (latest)
- Get exchange rates for a given base currency (latest)
- Get exchange rates for a given base currency on a specific date

## Collection Details
- **Collection Name:** exchangeapi.postman
- **Base URL Variable:** `{{url}}` with default value
`https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest`

## How to Use

- Import the collection JSON file or link into Postman.

- Set the url variable if you want to target a specific API version or date.

- Use the predefined requests and fill in the path variables such as:
  - {{currency}} (e.g., usd, eur, btc)
  - {{yyyy-mm-dd}} (date in YYYY-MM-DD format for historical rates)

- Send the requests to retrieve currency data in JSON format.
