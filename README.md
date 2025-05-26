# Credit Card Validator

A simple JavaScript tool to validate credit card numbers using the **Luhn algorithm** and detect the **card type** (e.g., Visa, Mastercard, American Express, Discover).

## 📌 Features

- Validates credit card numbers using the **Luhn algorithm**
- Detects card types:
  - Visa
  - Mastercard
  - American Express
  - Discover
- Auto-formats card number input with spaces (e.g., `4111 1111 1111 1111`)
- Includes test cases for validation accuracy
- Works entirely in the browser – no backend required

## 🛠️ How It Works

1. **Input Sanitization**: Removes all non-digit characters from the card number.
2. **Length Check**: Ensures the card number is exactly 16 digits.
3. **Luhn Algorithm**: Validates the card number mathematically.
4. **Card Type Detection**: Uses regex patterns to identify the card issuer.
5. **User Feedback**: Displays validation result and card type on the page.

## 🧪 Included Tests

The script includes a small test suite that checks known valid and invalid card numbers and logs results to the browser console.

Example output in console:

```
Test 1: 4111 1111 1111 1111 => true (Expected: true) - PASS
Test 2: 5500 0000 0000 0004 => true (Expected: true) - PASS
...
```

## 📁 Usage

To run this project:

1. Save the code in an `.html` file.
2. Open it in any modern web browser.
3. Enter a credit card number and click "Validate".
4. View the result and card type on the screen.
5. Open the browser console to see test results.

---

> 💡 Tip: Use `F12` or `Ctrl+Shift+I` to open Developer Tools and view the console output.

--- 
