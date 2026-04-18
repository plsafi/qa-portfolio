##Login

| Test Case ID | Title | Preconditions | Environment | Steps | Expected Result | Status |
| --- | --- | --- | --- | --- | --- | --- |
| TC-001 | Login with valid credentials | None | Chrome/Windows 10 | 1. Open https://www.saucedemo.com/<br>2. Enter username: standard_user<br>3. Enter password: secret_sauce<br>4. Click “Login” button | User is logged in and redirected to products page | Pass |
| TC-002 | Login with invalid password | None | Chrome/Windows 10 | 1. Open https://www.saucedemo.com/<br>2. Enter username: standard_user<br>3. Enter password: wrong_password<br>4. Click “Login” button | Error message is displayed | Pass |
| TC-003 | Login with empty credentials | None | Chrome/Windows 10 | 1. Open https://www.saucedemo.com/<br>2. Leave fields empty<br>3. Click “Login” button | Error message “Username is required” is displayed | Pass |
| TC-004 | Login without password | None | Chrome/Windows 10 | 1. Open https://www.saucedemo.com/<br>2. Enter username<br>3. Leave password empty<br>4. Click “Login” button | Error message “Password is required” is displayed | Pass |

##Cart


| Test Case ID | Title | Preconditions | Environment | Steps | Expected Result | Status |
| --- | --- | --- | --- | --- | --- | --- |
| TC-005 | Add product to cart | User is logged in | Chrome/Windows 10 | 1. Open products page<br>2. Click “Add to cart” on a product<br>3. Open cart | Product is visible in cart with correct details | Pass |
| TC-006 | Remove product from cart | Product is in cart | Chrome/Windows 10 | 1. Open cart<br>2. Click “Remove”<br>3. Check cart | Product is removed from cart | Pass |

##Checkout


| Test Case ID | Title | Preconditions | Environment | Steps | Expected Result | Status |
| --- | --- | --- | --- | --- | --- | --- |
| TC-007 | Complete checkout form | Product is in cart | Chrome/Windows 10 | 1. Open cart<br>2. Click “Checkout”<br>3. Enter user data<br>4. Click “Continue” | User is redirected to overview page | Pass |
| TC-008 | Complete purchase | User is on overview page | Chrome/Windows 10 | 1. Verify order details<br>2. Click “Finish” | Order confirmation is displayed | Pass |
