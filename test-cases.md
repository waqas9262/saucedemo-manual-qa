# Saucedemo Manual QA Test Cases

| TC # | Test Case Title                                | Steps                                                                 | Expected Result                                      | Status |
|------|------------------------------------------------|-----------------------------------------------------------------------|------------------------------------------------------|--------|
| 1    | Login with valid credentials                   | 1. Go to login page<br>2. Enter valid username and password<br>3. Click Login | User is logged in and redirected to Products page    | Pass   |
| 2    | Login with invalid credentials                 | 1. Go to login page<br>2. Enter invalid username or password<br>3. Click Login | Error message appears and login is blocked           | Pass   |
| 3    | Add single product to cart                     | 1. Login<br>2. Click “Add to cart” on one product                     | Product appears in the cart                          | Pass   |
| 4    | Add multiple products to cart                  | 1. Login<br>2. Add several products to cart                           | All selected products appear in the cart             | Pass   |
| 5    | Remove product from cart                       | 1. Add product(s) to cart<br>2. Go to cart<br>3. Remove an item       | Item is removed from cart                            | Pass   |
| 6    | Checkout with products in cart                 | 1. Add product(s) to cart<br>2. Go to cart<br>3. Click Checkout      | User is taken to checkout flow                       | Pass   |
| 7    | Attempt checkout with empty cart               | 1. Login<br>2. Go to cart (no items)<br>3. Click Checkout             | Checkout is blocked or error shown                   | Pass   |
| 8    | Sorting products by price (low to high)        | 1. Login<br>2. Use sort dropdown, select “Price (low to high)”        | Products list is sorted from lowest to highest price | Pass   |
| 9    | Logout from the application                    | 1. Login<br>2. Open menu<br>3. Click Logout                           | User is logged out, returns to login page            | Pass   |
| 10   | Login with locked out user                     | 1. Enter locked out user<br>2. Enter password<br>3. Click Login       | Error message appears, login blocked                 | Pass   |
| 11   | Check inventory item details                   | 1. Login<br>2. Click on any product’s title/image                     | Product details page is shown                        | Pass   |
| 12   | Add product to cart from details page          | 1. Go to product details<br>2. Click “Add to cart”                    | Product added to cart                                | Pass   |
| 13   | Continue shopping from cart                    | 1. Add to cart<br>2. Go to cart<br>3. Click “Continue Shopping”       | User returns to products page                        | Pass   |
| 14   | Check cart item count badge                    | 1. Add items to cart                                                  | Cart icon shows correct number of items              | Pass   |
| 15   | Complete checkout and return to Products page  | 1. Add items to cart<br>2. Checkout<br>3. Complete purchase           | Order completes, user returns to products page       | Pass   |