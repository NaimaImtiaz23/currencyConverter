# Currency Converter

A lightweight web-based currency converter that fetches live exchange rates and displays country flags for selected currencies.

## GitHub Repository Description
Simple and responsive currency converter built with vanilla JavaScript, powered by live exchange rates and dynamic country flag updates.

## Overview
This project provides a clean interface for converting one currency to another in real time. Users can enter an amount, choose source and target currencies, and get an updated conversion result using live exchange rate data.

## Features
- Live currency conversion using external exchange-rate API data
- Dynamic currency dropdowns populated from a currency-country mapping
- Automatic flag updates when currencies are changed
- Input validation with sensible defaults
- Error handling for failed API requests

## Tech Stack
- HTML5
- CSS3
- Vanilla JavaScript (ES6+)
- Font Awesome (icon)
- Exchange-rate API: `@fawazahmed0/currency-api` via jsDelivr
- Flag images: `flagsapi.com`

## Project Structure
```text
currencyConverter/
|-- index.html
|-- style.css
|-- app.js
|-- codes.js
```

## Getting Started
1. Clone the repository:
```bash
git clone <your-repo-url>
```
2. Open the project folder.
3. Launch `index.html` in your browser.

No build tools or package installation are required.

## Usage
1. Enter an amount in the input field.
2. Select the source currency.
3. Select the target currency.
4. Click **Exchange** to view the converted amount.

## Notes
- Internet access is required to fetch exchange rates and flag images.
- Default conversion is set to `USD` to `PKR` on initial load.

## Possible Enhancements
- Add swap button functionality for quick source/target reversal
- Add currency search in dropdowns
- Add historical rates and trend visualization
- Add unit and integration tests

## License
No license is currently specified for this repository.
