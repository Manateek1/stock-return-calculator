# Stock Return Calculator

A lightweight browser tool that calculates the dollar and percentage return on a stock investment from the purchase price, selling price, and number of shares.

[**Open the live calculator →**](https://manateek1.github.io/stock-return-calculator/)

## Use the calculator

Enter a purchase price, a selling price, and the number of shares, then select **Calculate Returns**. The calculator displays:

- Initial investment
- Final value
- Profit or loss
- Percentage return

For example, buying 10 shares at $25 and selling them at $28 gives a $250 initial investment, a $280 final value, $30 profit, and a 12% return.

## Run it locally

No installation or build step is needed.

1. Clone or download this repository.
2. Open `index.html` in a web browser.

## How it works

The page uses HTML, CSS, and vanilla JavaScript. All calculations happen in your browser; the app does not send your inputs to a server.

The calculator uses:

- **Initial investment** = purchase price × shares
- **Final value** = selling price × shares
- **Profit or loss** = final value − initial investment
- **Return (%)** = profit or loss ÷ initial investment × 100

## Scope

This is a price-only calculation. It does not include commissions, taxes, dividends, or other costs, and it does not provide investment advice.
