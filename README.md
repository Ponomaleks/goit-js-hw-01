# goit-js-hw-01

# JavaScript Fundamentals: Tasks Summary

This project contains three basic JavaScript tasks designed to practice function declarations, template literals, and numerical operations.

---

## Task 1: Droid Sales Station
**File:** `task-1.js`

Declare a function `makeTransaction(quantity, pricePerDroid)` that calculates the total cost of an order.
- **Parameters:**
  - `quantity` (Number): The number of ordered droids.
  - `pricePerDroid` (Number): The cost of a single droid.
- **Returns:** A string: `"You ordered <quantity> droids worth <totalPrice> credits!"`.

---

## Task 2: Shipping Cost Calculation
**File:** `task-2.js`

Declare a function `getShippingMessage(country, price, deliveryFee)` to calculate the total order price including delivery.
- **Parameters:**
  - `country` (String): The delivery destination.
  - `price` (Number): The price of the goods.
  - `deliveryFee` (Number): The cost of shipping.
- **Returns:** A string: `"Shipping to <country> will cost <totalPrice> credits"`.

---

## Task 3: Element Width Calculation
**File:** `task-3.js`

Declare a function `getElementWidth(content, padding, border)` that calculates the total width of an element based on the `border-box` model.
- **Parameters:**
  - `content` (String): Content width (e.g., `"50px"`).
  - `padding` (String): Horizontal padding per side (e.g., `"8px"`).
  - `border` (String): Border thickness per side (e.g., `"4px"`).
- **Formula:** $Total Width = content + (2 \times padding) + (2 \times border)$
- **Key Logic:** The function converts string values (with "px") into numbers for calculation and returns the total as a number.
