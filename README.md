# YASHART Manual Testing Project

A manual testing portfolio project for the public website **YASHART — Screen Printing**. It covers test planning, scenario and test case design, execution tracking, defect reporting, requirement traceability and test summary reporting.

> **Project status:** Test design complete. **Test execution has not started** - all test cases are currently `Not Executed`, and no defects have been recorded. Sections marked *(update after execution)* are filled in only with real results.

## Application Under Test

| Item | Details |
|---|---|
| Name | YASHART — Screen Printing |
| URL | https://yashart.netlify.app/ |
| Type | Catalogue / brochure website (printing and packaging products) |
| Size | 21 products in 6 categories, one detail page per product |
| Enquiry method | WhatsApp and phone links (no cart, login, checkout, payment, search or contact form) |

## Testing Objective

- Verify that the available features (navigation, product catalogue, category filter, product detail pages, enquiry links, contact details) work as intended.
- Verify product and contact information is accurate and consistent.
- Verify usability on mobile, tablet and desktop and in common browsers.
- Document genuine defects with clear steps and evidence.

## Scope

**In scope:** header navigation, product catalogue, category filter, product detail pages, WhatsApp / phone enquiry links, contact section, responsive layout, browser compatibility, URL handling, content consistency.

**Out of scope:** automation, performance, security, backend/API testing, sending real WhatsApp messages or placing calls, and features that do not exist on the site (login, cart, checkout, payment, search, forms).

## Modules Tested

| Module | Scenarios | Test cases (planned) |
|---|---|---|
| Header & Navigation | 5 | 8 |
| Product Catalogue | 5 | 6 |
| Category Filter | 5 | 10 |
| Product Detail | 5 | 12 |
| Enquiry Links | 2 | 6 |
| Contact & Footer | 3 | 4 |
| Responsive & Compatibility | 3 | 5 |
| URL Handling & Usability | 2 | 3 |
| **Total** | **30** | **54** |

## Testing Types

Smoke, Sanity, Functional, UI, Usability, Responsive, Compatibility, Regression and Retesting.

Test design techniques: positive and negative testing, Equivalence Partitioning (product categories, viewport classes), Boundary Value Analysis (responsive breakpoints only) and Decision Table testing (enquiry link behaviour by device and handler app).

## Test Case Summary

| Item | Count |
|---|---|
| Test scenarios | 30 |
| Test cases (planned) | 54 |
| High / Medium / Low priority | 29 / 22 / 3 |

**Execution results** *(update after execution)*

| Executed | Passed | Failed | Blocked | Not Executed |
|---|---|---|---|---|
| 0 | 0 | 0 | 0 | 54 |

## Defect Summary

*(Update after execution.)* No defects have been recorded yet. Defects are logged in the `Bug Reports` sheet and as individual reports in `Bug-Reports/`, and only when actually observed during testing.

| Critical | High | Medium | Low | Total |
|---|---|---|---|---|
| - | - | - | - | - |

## Tools Used

- Microsoft Excel / Google Sheets - scenarios, test cases, execution, bug log, RTM, summary
- Microsoft Word - test plan and bug report template
- Google Chrome DevTools (device emulation, responsive mode)
- Mozilla Firefox and Microsoft Edge - compatibility checks
- Screenshot tool, Git and GitHub

*(Remove any tool you did not actually use.)*

## Project Structure

```
YASHART-Manual-Testing/
├── Documentation/
│   ├── YASHART_Test_Plan.docx
│   └── YASHART_Manual_Testing.xlsx
├── Test-Data/
│   └── YASHART_Product_Catalogue_Data.csv
├── Bug-Reports/
│   ├── BUG_Report_Template.docx
│   ├── BUG_Report_Template.md
│   └── (BUG_001.docx, BUG_002.docx ... added only for real defects)
├── Screenshots/
│   ├── Test-Evidence/
│   └── Bugs/
└── README.md
```

The workbook contains these sheets: Test Scenarios, Test Cases, Test Execution, Bug Reports, RTM, Test Summary, Instructions.

## Test Execution Process

1. Run the smoke suite first (home page loads, navigation, default filter, one product page).
2. Execute functional and UI test cases by module.
3. Execute responsive and compatibility tests.
4. Record the result for each test in the `Test Execution` sheet (date, tester, environment, browser, actual result, status).
5. For each failure, capture a screenshot, log a bug and link the Bug ID to the test case.
6. Retest fixed defects and run a regression pass on High priority cases.
7. Complete the `Test Summary` sheet (metrics calculate automatically) and write the findings and conclusion.

## Key Learnings

*(Update after execution with your real experience.)*

- Derived requirements by exploring a live site with no specification document, and documented that assumption.
- Planned tests only for features that exist, and identified features that are deliberately out of scope.
- Applied test design techniques only where they fit (for example, Boundary Value Analysis only at responsive breakpoints because the site has no numeric inputs).
- Built traceability from requirements to scenarios, test cases, results and defects.

## Conclusion

*(Update after execution.)* This project demonstrates an end-to-end manual testing workflow for a small catalogue website. Results, defects and the final conclusion will be added after the test cases have been executed.
