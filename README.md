# OrangeHRM QA Case Study

A hands-on Software Testing project focused on practicing manual testing, test documentation, exploratory testing, bug reporting, and test automation using [OrangeHRM](https://www.orangehrm.com/).

This project is built as a QA portfolio to demonstrate fundamental software testing skills through real-world business workflows in an open-source HR management system.

## Project Overview

| Information          | Description                                             |
| -------------------- | ------------------------------------------------------- |
| Application          | OrangeHRM                                               |
| Version              | OrangeHRM 5.x                                           |
| Testing Type         | Manual Testing, Exploratory Testing, Automation Testing |
| Automation Tool      | Playwright                                              |
| Programming Language | TypeScript                                              |
| Test Documentation   | Excel / Markdown                                        |
| Bug Tracking         | GitHub Issues                                           |
| Environment          | Docker (Local)                                          |
| Project Status       | In Progress                                             |

## Testing Scope

This project focuses on two core functional modules:

### 1. PIM – Employee Management

Testing employee management workflows, including:

- Add Employee
- Employee List and Search
- Edit Employee Information
- Input Validation
- Data Integrity

### 2. Leave – Leave Management

Testing leave management workflows, including:

- Apply for Leave
- View and Cancel Leave Requests
- Leave Request Approval
- Leave Request Rejection
- Workflow and Status Validation
- Role-based Access Control

## Testing Activities

The following testing activities are included in this project:

- **Test Planning:** Define testing scope, objectives, approach, and test environment.
- **Test Scenario Design:** Identify functional scenarios and potential edge cases.
- **Test Case Design:** Apply techniques such as Equivalence Partitioning, Boundary Value Analysis, and State Transition Testing where appropriate.
- **Test Execution:** Execute test cases and record actual results.
- **Exploratory Testing:** Explore application behavior beyond predefined test cases.
- **Bug Reporting:** Document defects with reproduction steps, expected results, actual results, and supporting evidence.
- **Test Automation:** Automate selected regression test cases using Playwright and TypeScript.

## Project Structure

```text
orangehrm-qa-case-study/
│
├── docs/
│   ├── Test-Plan.md
│   ├── Test-Scenarios.xlsx
│   ├── Test-Cases.xlsx
│   └── Test-Summary-Report.md
│
├── tests/
│   ├── pim/
│   └── leave/
│
├── exploratory-testing/
│   ├── PIM-Session.md
│   └── Leave-Session.md
│
├── evidence/
│   ├── screenshots/
│   └── bug-evidence/
│
├── playwright.config.ts
├── package.json
└── README.md
```

_Note: The project structure and deliverables will be updated as the project progresses._

## Testing Tools & Technologies

| Tool / Technology | Purpose                                |
| ----------------- | -------------------------------------- |
| OrangeHRM         | Application Under Test                 |
| Docker            | Local application deployment           |
| Playwright        | UI test automation                     |
| TypeScript        | Automation scripting                   |
| Git & GitHub      | Version control and project management |
| GitHub Issues     | Defect tracking                        |
| Excel / Markdown  | Test documentation                     |

## Test Execution & Reporting

Test execution results are documented with:

- Test Case ID
- Actual Result
- Execution Status (Pass / Fail / Blocked)
- Execution Date
- Tester
- Supporting Evidence

Identified defects are tracked through GitHub Issues and linked to their corresponding test cases where applicable.

## How to Run the Project

### 1. Start OrangeHRM

OrangeHRM is deployed locally using Docker.

### 2. Install Dependencies

```bash
npm install
```

### 3. Install Playwright Browsers

```bash
npx playwright install
```

### 4. Run Automated Tests

```bash
npx playwright test
```

### 5. View HTML Test Report

```bash
npx playwright show-report
```

## Project Objectives

Through this case study, I aim to strengthen my practical understanding of:

- Software Testing Life Cycle (STLC).
- Functional and negative testing.
- Test case design techniques.
- Exploratory testing.
- Defect lifecycle and bug reporting.
- UI test automation with Playwright.
- Test documentation and reporting.

## Disclaimer

This is an independent QA practice project using the open-source OrangeHRM application. It is not an official testing project conducted for or affiliated with OrangeHRM.

