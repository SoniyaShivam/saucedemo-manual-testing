# SauceDemo Manual Testing Portfolio

## Project Overview
A beginner QA portfolio project focused on manual functional testing of the [SauceDemo](https://www.saucedemo.com/) demo e-commerce application.

The project demonstrates test case design, test execution, result documentation, evidence collection, and investigation of unexpected application behavior.

## Testing Scope
- Login with valid credentials
- Add products to the cart
- Remove products from the cart
- Checkout with an empty cart
- Checkout with a valid product
- Validate generated order PDF details

## Test Execution Summary

| Test Case | Scenario | Result |
|---|---|---|
| TC-001 | Login with valid credentials | PASS |
| TC-002 | Add product to cart | PASS |
| TC-003 | Remove product from cart | PASS |
| TC-004 | Checkout with an empty cart | Needs Investigation |
| TC-005 | Checkout with a valid product | PASS |

## Potential Defect
**Title:** Checkout completion with an empty cart

The application displayed an order confirmation after checkout was completed with no products listed. The generated PDF contained no products and showed a total cost and tax of $0.00.

This behavior is documented as a potential defect pending confirmation of the application's expected behavior.

## Repository Structure
- `Test-Cases/` — Manual test cases and execution summary
- `Bug-Reports/` — Potential defect documentation
- `Screenshots/` — Testing screenshots and supporting evidence

## Testing Approach
1. Execute each test scenario manually.
2. Compare actual behavior against expected results.
3. Record pass results and unexpected behavior.
4. Capture screenshots and supporting evidence.
5. Document findings for further investigation.

## Tools
- SauceDemo web application
- Web browser
- Manual testing and test documentation
- GitHub

## Disclaimer
This project uses a demo application for learning and portfolio purposes. The documented potential defect has not been independently confirmed against formal requirements.
