# Bug Report – Shoppers Stack (Online Shopping Portal)

**Prepared By:** Sanjana Kachare

## Bug 1

| Field | Details |
|-------|---------|
| **Bug ID** | BUG_001 |
| **Title** | User can register with invalid email format |
| **Module** | User Registration |
| **Severity** | High |
| **Priority** | High |
| **Steps** | 1. Go to Register 2. Enter "abc@" 3. Click Register |
| **Expected** | Error: Invalid email format |
| **Actual** | User registered successfully |

## Bug 2

| Field | Details |
|-------|---------|
| **Bug ID** | BUG_002 |
| **Title** | Cart total not updated after quantity change |
| **Module** | Shopping Cart |
| **Severity** | High |
| **Priority** | High |
| **Steps** | 1. Add product 2. Change quantity to 3 3. Check total |
| **Expected** | Total price updated |
| **Actual** | Total price remains same |

## Bug 3

| Field | Details |
|-------|---------|
| **Bug ID** | BUG_003 |
| **Title** | No error shown when checkout with empty cart |
| **Module** | Checkout |
| **Severity** | Medium |
| **Priority** | Medium |
| **Steps** | 1. Empty cart 2. Go to checkout URL |
| **Expected** | Error: Cart is empty |
| **Actual** | Checkout page loads empty |

## Bug 4

| Field | Details |
|-------|---------|
| **Bug ID** | BUG_004 |
| **Title** | Filter shows out-of-range products |
| **Module** | Product Search |
| **Severity** | Medium |
| **Priority** | Medium |
| **Steps** | 1. Set price filter 500-1000 2. View results |
| **Expected** | Only 500-1000 products shown |
| **Actual** | Products above 1000 also shown |
