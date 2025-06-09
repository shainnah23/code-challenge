# code-challenge
This repository contains three simple calculators written in JavaScript:

## 1. Boda Fare Calculator

- **Location:** [bodaFareCalculator/fare.js](bodaFareCalculator/fare.js)
- **Function:** Calculates the total fare for a boda boda ride based on distance in kilometers.

## 2. Chai Calculator

- **Location:** [chaiCalculator/chai.js](chaiCalculator/chai.js)
- **Function:** Calculates the required ingredients to make a specified number of cups of Kenyan Chai.

## 3. Mobile Money Fee Estimator

- **Location:** [mobileMoneyEstimator/fee.js](mobileMoneyEstimator/fee.js)
- **Function:** Estimates the transaction fee for sending money via mobile money, applying a 1.5% fee with minimum and maximum limits.

---

### How to Use

Each calculator is a standalone JavaScript function. To use, open the relevant `.js` file and call the function in a browser environment (as they use `prompt` and `console.log`).

Example:
```js
// In browser console or script tag
calculateBodaFare();
calculateChaiIngredients();
estimateTransactionFee();