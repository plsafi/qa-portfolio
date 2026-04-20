## Bug Report

| ID | Area         | Description                        | Steps                     | Expected Result              | Actual Result                 | Severity | Priority |
| -- | ------------ | ---------------------------------- | ------------------------- | ---------------------------- | ----------------------------- | -------- | -------- |
| 1  | Cart         | Error message when adding product  | Add product to cart       | Product added without errors | Error shown but product added | Medium   | Medium   |
| 2  | Cart         | Missing quantity +/- buttons       | Go to cart                | Quantity can be adjusted     | No controls available         | High     | High     |
| 3  | Cart         | Incorrect item total calculation   | Add product → check total | Correct item total           | Only full cart total works    | High     | High     |
| 4  | Cart         | Remove button not working          | Try removing item         | Item removed                 | Nothing happens               | Critical | Critical |
| 5  | Cart         | Allows quantity = 0                | Set quantity to 0         | Validation prevents it       | Accepted with no change       | Medium   | Low      |
| 6  | Cart         | Total calculation incorrect        | Add multiple items        | Correct total                | Incorrect calculation         | Critical | Critical |
| 7  | Checkout     | Missing payment gateway (404)      | Go to payment             | Payment options available    | 404 error                     | Critical | Critical |
| 8  | Checkout     | Button without label               | Fill billing form         | Button has label             | No text on button             | Medium   | Medium   |
| 9  | Checkout     | Typo in label                      | Open form                 | Correct label                | "Type Billing Address"        | Low      | Low      |
| 10 | Checkout     | Postcode incorrect value           | Check postcode field      | Correct value displayed      | "Missing value"               | Medium   | Medium   |
| 11 | Navigation   | Undefined category not working     | Click category            | Category loads               | Not working                   | High     | High     |
| 12 | Navigation   | Chainsaw category → 404            | Open category             | Product list displayed       | 404 error                     | High     | High     |
| 13 | Products     | Sorting low→high incorrect         | Sort products             | Correct order                | Wrong order                   | Medium   | Medium   |
| 14 | Products     | Sorting high→low incorrect         | Sort products             | Correct order                | Wrong order                   | Medium   | Medium   |
| 15 | Product Page | Quantity buttons not working       | Click +/-                 | Quantity changes             | Not working                   | High     | High     |
| 16 | Product Page | Error on add to cart               | Add product               | No error                     | Error shown                   | Medium   | Medium   |
| 17 | Product Page | Add to favorites unauthorized      | Click favorite            | Product added                | Unauthorized error            | High     | High     |
| 18 | UI           | Incorrect logo display             | Open homepage             | Correct logo                 | Wrong image                   | Low      | Low      |
| 19 | UI           | Missing search bar/icon            | Check header              | Search available             | Missing                       | Medium   | Medium   |
| 20 | UI           | Typo "Sorth"                       | Check sort dropdown       | "Sort"                       | "Sorth"                       | Low      | Low      |
| 21 | UI           | Typo "Serch"                       | Check button              | "Search"                     | "Serch"                       | Low      | Low      |
| 22 | UI           | Typo "Reltded products"            | Product page              | Correct text                 | Typo                          | Low      | Low      |
| 23 | Layout       | Add to cart button broken (Chrome) | Open product page         | Proper layout                | Misaligned                    | Medium   | Medium   |
| 24 | Layout       | Product names right-aligned        | Category page             | Proper alignment             | Misaligned                    | Low      | Low      |
| 25 | Layout       | Title alignment issues             | Firefox/Edge              | Proper alignment             | Misaligned                    | Low      | Low      |
| 26 | Layout       | Buttons overlap                    | Chrome                    | Proper spacing               | Overlapping                   | Medium   | Medium   |
| 27 | Layout       | Badge text color incorrect         | Check UI                  | White text                   | Black text                    | Low      | Low      |
| 28 | Layout       | No text wrapping                   | Firefox                   | Text wraps                   | Doesn't wrap                  | Medium   | Medium   |
| 29 | User         | Username not displayed             | Login                     | Username visible             | "User Data not found"         | Medium   | Medium   |
| 30 | Profile      | First/Last name swapped            | Open profile              | Correct mapping              | Swapped values                | Medium   | Medium   |
| 31 | Profile      | City not found                     | Check profile             | Correct value                | Missing                       | Medium   | Medium   |
| 32 | Profile      | State/Country swapped              | Check profile             | Correct mapping              | Swapped                       | Medium   | Medium   |
| 33 | Invoice      | Payment method missing             | Open invoice              | Method visible               | "Method not found"            | High     | High     |
| 34 | Invoice      | City/Country swapped               | Open invoice              | Correct values               | Swapped                       | Medium   | Medium   |
| 35 | Invoice      | Address undefined                  | Open invoice              | Proper address               | "undefined"                   | High     | High     |

