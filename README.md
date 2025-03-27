
# goit-js-hw-01

  

This repository contains three JavaScript functions solving different tasks.

  

## `task-1.js` - `makeTransaction(quantity, pricePerDroid)`

Calculates the total cost of purchasing droids.

**Params:**
-  `quantity` (number) – number of droids
-  `pricePerDroid` (number) – cost per droid

**Example:**

```js
makeTransaction(5, 3000); // "You ordered 5 droids worth 15000 credits!"
```
  
---
## `task-2.js` - `getShippingMessage(country, price, deliveryFee)`

Calculates  total  shipping  cost.

**Params:**

- `country` (string) – destination
- `price` (number) – item  price
- `deliveryFee` (number) – shipping  cost

**Example:**
```js
getShippingMessage('Australia', 120, 50); // "Shipping to Australia will cost 170 credits"
```

---

## `task-3.js` - `getElementWidth(content, padding, border)`

Calculates the total width of an element.

**Params:**
- `content`, `padding`, `border` (string) – sizes in "px"

**Example:**
```js
getElementWidth('50px', '8px', '4px'); // 74
```
