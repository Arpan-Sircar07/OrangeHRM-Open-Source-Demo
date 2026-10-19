# OrangeHRM – Manual Software Testing Project

A manual software testing documentation project for the OrangeHRM Open Source Demo HRMS, focused on test planning, test scenario identification, structured test case design, and fundamental software testing techniques.

## Project Overview

| Item | Details |
|---|---|
| Project Name | OrangeHRM Manual Testing |
| Application | OrangeHRM Open Source Demo |
| Project Type | Software QA Portfolio Project |
| Testing Approach | Manual Testing |
| Documentation | Test Plan, Test Scenarios, Test Cases |
| Version | 1.0 |
| Status | Test planning and documentation completed |

**Application URL:** https://opensource-demo.orangehrmlive.com/web/index.php/auth/login

## Objectives

- Define the scope, strategy, and approach for manual testing of an HRMS application.
- Identify positive, negative, and validation-related test scenarios.
- Design structured test cases with preconditions, test data, execution steps, and expected results.
- Apply fundamental test design techniques to improve test coverage.
- Establish a consistent format for future defect reporting.

## Testing Scope

The planned test coverage includes:

- **Authentication:** Valid and invalid login credentials, required-field validation, and logout.
- **Session Management:** Session handling and potential session-expiration scenarios.
- **Dashboard and Navigation:** Access to available modules and navigation consistency.
- **Employee Management:** Employee search, filtering, and form validation where accessible.
- **User Management:** Potential user-related workflows where accessible.
- **Input Validation:** Required fields, invalid inputs, and documented field-length boundaries.
- **UI and Usability:** Labels, validation messages, readability, and interface consistency.

## Testing Types Considered

- Functional Testing
- Positive Testing
- Negative Testing
- Smoke Testing
- Regression Testing
- Exploratory Testing
- UI and Usability Testing
- Compatibility Testing

These testing types describe the planned approach and do not indicate completed test execution.

## Test Design Techniques

| Technique | Purpose |
|---|---|
| Boundary Value Analysis (BVA) | Identify test values around known input boundaries. |
| Equivalence Partitioning | Group inputs into classes expected to behave similarly. |
| Decision Table Testing | Evaluate combinations of conditions and expected outcomes. |
| State Transition Testing | Examine behavior as the application moves between states. |
| Use Case Testing | Cover typical user workflows. |
| Error Guessing | Consider common input and workflow failure conditions. |
| Checklist-Based Testing | Apply a consistent checklist to common UI and functional checks. |

## Test Case Documentation

Test cases are organized around a structured format containing:

- Test Case ID and feature/module
- Preconditions
- Test data
- Step-by-step test procedures
- Expected results
- Execution status, where applicable

Example scenarios include successful login, invalid-password handling, empty-field validation, logout behavior, and input-boundary checks.

## Test Environment

| Component | Planned Configuration |
|---|---|
| Application | OrangeHRM Open Source Demo |
| Browser | Google Chrome |
| Operating System | Windows 11 |
| Test Data | Illustrative valid and invalid inputs |
| Method | Manual test planning and test case design |

The browser and operating-system configuration represents the intended environment; compatibility and application behavior have not been verified through execution.

## Repository Structure

```text
OrangeHRM-Manual-Testing/
├── README.md
├── OrangeHRM_Software_Test_Plan_Professional.pdf
└── OrangeHRM_Test_Scenarios_and_Test_Cases.xlsx
```

*Adjust the filenames above if your uploaded files use different names in the GitHub repository.*

## Defect Reporting Approach

If testing is performed, defects can be documented using the following fields:

- Defect ID and title
- Affected module
- Preconditions and reproduction steps
- Expected and actual results
- Severity and priority
- Supporting evidence
- Status

No actual defects are claimed in this project.

## Current Project Status

**Documentation completed; test execution not performed.**

The project demonstrates manual test planning and test case design. The scenarios and expected results are proposed coverage, not verified application behavior. No pass/fail metrics, confirmed defects, or application quality conclusions are claimed.

## Future Enhancements

- Execute the documented test cases against the demo application.
- Record actual results and attach screenshots as evidence.
- Create a defect log for reproducible issues.
- Add execution metrics and a test summary report after testing.
- Expand coverage based on verified application behavior and available requirements.

## Disclaimer

This is an independent QA portfolio project using the publicly available OrangeHRM demo application. It is intended for educational and professional demonstration purposes and is not an official OrangeHRM testing report.

---

**Prepared by:** Arpan Sircar  
**Project:** OrangeHRM Manual Software Testing
