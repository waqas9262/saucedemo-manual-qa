# Bug Reports - Saucedemo

---

## Bug 1: Login allows blank password
**Environment:**  
Web, Chrome (latest)

**Steps to Reproduce:**  
1. Go to Saucedemo login page.
2. Enter a valid username, leave password blank.
3. Click "Login".

**Expected Result:**  
User should see an error: "Password is required."

**Actual Result:**  
User is logged in successfully.

**Severity:**  
High

---

## Bug 2: Cart badge not updating after removing item
**Environment:**  
Web, Chrome (latest)

**Steps to Reproduce:**  
1. Log in as a standard user.
2. Add an item to cart.
3. Go to cart and remove the item.

**Expected Result:**  
Cart badge (top-right) should show zero or disappear.

**Actual Result:**  
Cart badge still shows '1' even when cart is empty.

**Severity:**  
Medium

---

## Bug 3: Sorting not applied to products
**Environment:**  
Web, Chrome (latest)

**Steps to Reproduce:**  
1. Log in as a standard user.
2. Change the product sort order to "Price (low to high)".

**Expected Result:**  
Products should be sorted from lowest to highest price.

**Actual Result:**  
Product order does not change.

**Severity:**  
Medium

---

## Bug 4: Error message overlaps login button on small screens
**Environment:**  
Mobile browser, Chrome on Android

**Steps to Reproduce:**  
1. Go to Saucedemo on a mobile device.
2. Try logging in with wrong credentials.

**Expected Result:**  
Error message should be clear and not overlap other elements.

**Actual Result:**  
Error message overlaps with the login button.

**Severity:**  
Low

---

## Bug 5: Checkout does not require postal code
**Environment:**  
Web, Chrome (latest)

**Steps to Reproduce:**  
1. Add item to cart.
2. Go to checkout.
3. Leave postal code blank and try to continue.

**Expected Result:**  
App should require user to enter postal code.

**Actual Result:**  
Checkout proceeds without postal code.

**Severity:**  
High