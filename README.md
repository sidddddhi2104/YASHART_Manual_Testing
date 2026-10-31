# YASHART Manual Testing Project

A manual testing portfolio project for the public website **YASHART — Screen Printing**. It covers test planning, scenario and test case design, test execution, defect reporting, requirement traceability and test summary reporting.

> **Project status:** Test execution completed. All 54 test cases were executed, with 51 Passed and 3 Failed. Three defects were identified and documented.

## Application Under Test

| **Item** | **Details** |
|---|---|
| Name | YASHART — Screen Printing |
| URL | [https://yashart.netlify.app/](https://yashart.netlify.app/) |
| Type | Catalogue / brochure website (printing and packaging products) |
| Size | 21 products in 6 categories, one detail page per product |
| Enquiry method | WhatsApp and phone links (no cart, login, checkout, payment, search or contact form) |

## Testing Objective

- Verify that the available features (navigation, product catalogue, category filter, product detail pages, enquiry links and contact details) work as intended.
- Verify product and contact information for accuracy and consistency.
- Verify usability on mobile, tablet and desktop viewport sizes and across tested browsers.
- Document genuine defects with clear reproduction steps and evidence.

## Scope

**In scope:** Header navigation, product catalogue, category filter, product detail pages, WhatsApp / phone enquiry links, contact section, responsive layout, browser compatibility, URL handling and content consistency.

**Out of scope:** Automation, performance, security, backend/API testing, sending real WhatsApp messages or placing calls, and features that do not exist on the site (login, cart, checkout, payment, search and forms).

## Modules Tested

| **Module** | **Scenarios** | **Test Cases** |
|---|---:|---:|
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

Smoke, Sanity, Functional, UI, Usability, Responsive and Compatibility Testing.

Test design techniques: Positive and negative testing, Equivalence Partitioning (product categories and viewport classes), Boundary Value Analysis (responsive breakpoint testing) and Decision Table testing (enquiry link behaviour by device and handler app).

## Test Execution Summary

All 54 planned test cases were executed.

| **Metric** | **Result** |
|---|---:|
| Total Test Cases | 54 |
| Executed | 54 |
| Passed | 51 |
| Failed | 3 |
| Blocked | 0 |
| Not Executed | 0 |
| Execution Percentage | 100% |
| Pass Percentage | 94.4% |

## Defect Summary

Three defects were identified and documented during test execution.

| **Bug ID** | **Defect Description** | **Related Test Case** | **Status** |
|---|---|---|---|
| BUG-001 | Call Now option not visible in mobile view | TC_047 | Open |
| BUG-002 | Telephone number not visible at tablet resolution (768×1024) | TC_048 | Open |
| BUG-003 | WhatsApp logo visually inconsistent across pages | TC_054 | Open |
| **Total** | **3 defects** | | **3 Open** |

All identified defects are documented in the Bug Reports sheet of the Excel workbook.

## Testing Environment

- Operating System: Windows 11
- Microsoft Edge: 155.0.4283.45 (64-bit)
- Google Chrome: Used for applicable test cases
- Responsive viewport testing: Mobile, tablet and desktop resolutions
- Tester: Siddhi Kamble

## Tools Used

- Microsoft Excel – Test scenarios, test cases, test execution, bug tracking, RTM and test summary.
- Microsoft Word – Test plan and documentation.
- Microsoft Edge DevTools – Responsive viewport testing.
- Google Chrome – Browser testing and UI verification.
- Git and GitHub – Project version control and portfolio hosting.
- Screenshot tool – Test evidence and defect documentation.

## Project Structure

```text
YASHART-Manual-Testing/
├── Documentation/
│   ├── YASHART_Test_Plan.docx
│   └── YASHART_Manual_Testing.xlsx
├── Test-Data/
│   └── YASHART_Product_Catalogue_Data.csv
├── Bug-Reports/
│   ├── BUG_Report_Template.docx
│   └── BUG_Report_Template.md
├── Screenshots/
│   ├── Test-Evidence/
│   └── Bugs/
└── README.md
```

The Excel workbook contains the following sheets:

1. Instructions
2. Test Scenarios
3. Test Cases
4. Test Execution
5. RTM
6. Test Summary
7. Bug Reports

## Test Execution Process

1. Reviewed the live website and identified available functionality.
2. Prepared test scenarios and detailed test cases for the identified modules.
3. Executed test cases covering functional, UI, usability, responsive and compatibility aspects.
4. Recorded execution dates, testing environment, browser details, actual results and statuses in the Test Execution sheet.
5. Documented failed test cases and created corresponding defect records with unique Bug IDs.
6. Linked defects to their respective test cases.
7. Updated the RTM and Test Summary sheets to reflect the execution results.

## Key Learnings

- Derived test requirements by exploring a live website without an official requirements document.
- Identified actual website functionality and excluded non-existing features from the testing scope.
- Designed 30 test scenarios and 54 test cases across eight modules.
- Applied test design techniques such as Equivalence Partitioning, Boundary Value Analysis and Decision Table testing.
- Practised executing test cases and recording actual results instead of relying only on expected results.
- Identified and documented three UI and responsive-related defects.
- Maintained traceability between test scenarios, test cases, execution results and defect reports.
- Used Excel to maintain execution records, defect tracking and test summary metrics.
- Used Git and GitHub to maintain and publish the project.

## Conclusion

The YASHART Manual Testing project demonstrates an end-to-end manual testing workflow for a catalogue-based website.

A total of 54 test cases were executed, of which 51 passed and 3 failed, resulting in a 94.4% pass percentage. Three defects were identified and documented, relating to telephone contact visibility across responsive viewport sizes and WhatsApp logo consistency across pages.

The project provided practical experience in test planning, test case design, manual execution, defect reporting, requirement traceability and test summary preparation.
