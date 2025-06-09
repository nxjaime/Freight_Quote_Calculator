# Freight Quote Calculator

This repository contains a single-page web application for estimating freight quotes.
The application is distributed as an HTML file named `FQ Project Testing v1.2.1`.

## Usage
1. Clone this repository.
2. Open `FQ Project Testing v1.2.1` in your web browser.
3. Fill out the form with shipment details such as origin, destination, trailer type, and cost.
4. Press **Calculate Quote** to compute the estimate. Each calculation is stored in your browser using IndexedDB so you can retrieve quote history later if needed.
5. Use **Copy to Clipboard** to copy the quote summary.

The app retrieves current fuel prices from the EIA API and factors them into your quote.

### GitHub Storage

If you provide a GitHub personal access token and repository name in the form, the app will also update a `quotes.json` file on that repo's `gh-pages` branch whenever a quote is calculated. Your token and repo are saved locally in your browser.
