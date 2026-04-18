# Test cases

| Test Case ID | Title | Preconditions | Environment | Steps | Expected Result | Status |
| --- | --- | --- | --- | --- | --- | --- |
| TC-001 | Login with valid credentials | None | Chrome/Windows 10 | 1. Open https://www.saucedemo.com/
2. Enter username: standard_user
3. Enter password: secret_sauce
4. Click “Login” button | User is successfully logged in and redirected to the products page | Pass |
| TC_002 | Login with invalid credentials | None | Chrome/Windows 10 | 1. Open https://www.saucedemo.com/
2. Enter username: standard_user
3. Enter password: wrong_password
4. Click “Login” button | Error message “Username and password do not match any user in this service” is displayed | Pass |
| TC_003 | Login with empty credentials | None | Chrome/Windows 10 | 1. Open https://www.saucedemo.com/
2. Leave username field empty
3. Leave password field empty
4. Click “Login” button | Error message “Username is required” is displayed | Pass |
| TC_004 | Login without password | None | Chrome/Windows 10 | 1. Open https://www.saucedemo.com/
2. Enter username: standard_user
3. Leave password field empty
4. Click “Login” button | Error message “Password is required” is displayed | Pass |
| TC_005 | Add to cart | User is logged in (standard_user / secret_sauce) | Chrome/Windows 10 | 1. Open product list page
2. Click “Add to cart” on any product (e.g. Sauce Labs Backpack)
3. Click cart icon (top right corner) | Selected product is displayed in the cart with correct name and price | Pass |
| TC_006 | Remove product from cart | User has at least one product in cart | Chrome/Windows 10 | 1. Open cart
2. Click “Remove” button for product
3. Check cart content | Product is removed from cart and cart is empty (or updated correctly) | Pass |
| TC_007 | Start checkout process from cart | User has at least one product in cart | Chrome/Windows 10 | 1. Open cart
2. Click “Checkout” button
3. Enter first name: John
4. Enter last name: Doe
5. Enter postal code: 12345
6. Click “Continue” | User is redirected to checkout overview page with correct product details and price summary | Pass |
| TC_008 | Complete purchase successfully | User is on checkout overview page | Chrome/Windows 10 | 1. Verify product details and total price
2. Click “Finish” button | Order is successfully completed and confirmation message “Thank you for your order” is displayed | Pass |