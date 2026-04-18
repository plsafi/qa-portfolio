# Bug Reports

| Bug ID | Title | Steps to reproduce | Expected result | Actual result | Severity |
| --- | --- | --- | --- | --- | --- |
| BUG_001 | No clear feedback when clicking login multiple times quickly | 1. Open https://www.saucedemo.com/<br>2. Enter username: standard_user<br>3. Enter password: secret_sauce<br>4. Click “Login” button multiple times quickly | User should be logged in once and system should handle multiple clicks properly | System behavior is unclear when clicking multiple times quickly (potential for multiple requests or lack of feedback) | Medium |
| BUG_002 | Missing error message when password field is empty | 1. Open https://www.saucedemo.com/<br>2. Enter username: standard_user<br>3. Leave password field empty<br>4. Click “Login” button | User should see an error message like “Password is required” and login should be blocked | Login is blocked, but error message may be unclear or not properly displayed (or generic message shown) | Low / Medium |
