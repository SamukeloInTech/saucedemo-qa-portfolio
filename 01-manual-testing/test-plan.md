# SauceDemo Manual Test Plan

## 1. Introduction
This document outlines the test strategy, scope, and schedule for manual testing of the SauceDemo e-commerce website.

## 2. Test Objectives
- Verify the end-to-end functionality of the e-commerce flow (Login -> Inventory -> Cart -> Checkout).
- Identify and document UI/UX defects.
- Validate the system against boundary values and equivalent partitions.

## 3. Scope
### ✅ In-Scope
The following features will be tested manually:
- User Login & Authentication
- Product Inventory (sorting, viewing)
- Shopping Cart (add, remove, update quantity)
- Checkout Process (information entry, order overview, completion)
- BVA and EP on input fields (Zip code, login inputs, etc.)

### ❌ Out-of-Scope
The following will NOT be tested in this project:
- API / Backend testing
- Performance and Load testing
- Security / Penetration testing
- Mobile App testing (Desktop web only)

## 4. Test Environment
- **OS:** Windows 11
- **Browsers:** Google Chrome (Latest), Microsoft Edge (Latest)
- **System Under Test:** https://www.saucedemo.com/

## 5. Test Strategy
- **Equivalence Partitioning (EP):** Dividing input data into valid and invalid classes to reduce redundant tests.
- **Boundary Value Analysis (BVA):** Testing the edges (min/max) of input ranges.
- **Regression Testing:** Re-running core tests after a defect fix to ensure nothing breaks.
- **Exploratory Testing:** Simultaneous learning, test design, and test execution.

## 6. Defect Management
Bugs will be tracked in Jira using a standard defect lifecycle (Open -> In Progress -> Ready for Testing -> Closed). Exported bug reports will be documented in the `02-jira-workflow` folder.

## 7. Test Deliverables
- Test Plan (This document)
- Test Cases (Located in `01-manual-testing`)
- Bug Reports (Located in `02-jira-workflow`)
- Test Execution Report
