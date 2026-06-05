# Test Cases – Shoppers Stack (Online Shopping Portal)

**Prepared By:** Sanjana Kachare

## Module 1: User Registration

| TC ID | Test Case | Expected Result | Status |
|-------|-----------|-----------------|--------|
| TC_001 | Valid Registration | User registered successfully | Pass |
| TC_002 | Existing email | Error: Email already exists | Pass |
| TC_003 | Empty fields | Error: All fields required | Pass |
| TC_004 | Invalid email | Error: Invalid email format | Pass |
| TC_005 | Short password | Error: Min 8 characters | Pass |

## Module 2: User Login

| TC ID | Test Case | Expected Result | Status |
|-------|-----------|-----------------|--------|
| TC_006 | Valid Login | User logged in successfully | Pass |
| TC_007 | Invalid Password | Error: Invalid credentials | Pass |
| TC_008 | Empty Fields | Error: Fields cannot be empty | Pass |
| TC_009 | Forgot Password | Password reset email sent | Pass |
| TC_010 | Unregistered email | Error: User not found | Pass |

## Module 3: Product Search & Filter

| TC ID | Test Case | Expected Result | Status |
|-------|-----------|-----------------|--------|
| TC_011 | Valid search | Relevant products displayed | Pass |
| TC_012 | Invalid search | No products found message | Pass |
| TC_013 | Filter by category | Only category products shown | Pass |
| TC_014 | Filter by price | Products within range shown | Pass |
| TC_015 | Empty search | Error or all products shown | Pass |

## Module 4: Shopping Cart

| TC ID | Test Case | Expected Result | Status |
|-------|-----------|-----------------|--------|
| TC_016 | Add to cart | Product added to cart | Pass |
| TC_017 | Remove from cart | Product removed from cart | Pass |
| TC_018 | Update quantity | Price updated correctly | Pass |
| TC_019 | Empty cart checkout | Error: Cart is empty | Pass |
| TC_020 | Cart total | Correct total displayed | Pass |

## Module 5: Payment & Checkout

| TC ID | Test Case | Expected Result | Status |
|-------|-----------|-----------------|--------|
| TC_021 | Valid payment | Payment successful | Pass |
| TC_022 | Invalid card | Error: Invalid card details | Pass |
| TC_023 | Empty address | Error: Address required | Pass |
| TC_024 | Order confirmation | Confirmation email received | Pass |
| TC_025 | Order tracking | Order status displayed | Pass |
