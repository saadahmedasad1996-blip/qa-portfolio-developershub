# QA Portfolio – DevelopersHub SQA Program

Complete Quality Assurance work for a To-Do List & Login/Signup Web Application, covering manual testing, black-box techniques, automation, performance, security, and CI/CD — built across a structured 6-week training program.

## 📁 Repository Structure

```
├── week-1/
│   ├── SQA_Week1_TestCaseDocument.docx
│   └── SQA_Week1_BugReport.xlsx
├── week-2/
│   ├── Test_Plan_Document_Week2.docx
│   ├── black box testing.docx
│   └── Compatibility_Retesting_Report_Week2.docx
├── week-3/
│   ├── Automation scripts.docx
│   └── Week3_Final_QA_Project_Report.pdf
├── performance/
│   ├── Performance_Test_Plan.docx
│   └── Performance_Testing_Report.pdf
├── security/
│   ├── Vulnerability_Report.docx
│   └── Security_Testing_Summary.pdf
├── ci-cd/
│   ├── CICD_Workflow.docx
│   └── .github/workflows/selenium-tests.yml
├── portfolio/
│   └── Final_QA_Portfolio.pdf
└── README.md
```

## 🎯 Project Objective

To demonstrate end-to-end QA capability — from manual test design through black-box techniques, automation, non-functional testing (performance & security), and CI/CD integration — as a professional QA portfolio.

## 📱 Application Under Test

**To-Do List & Login/Signup Web Application** — modules tested: Login, Signup, To-Do Task Management, UI/UX, Navigation.

## 🧰 Tools & Technologies Used

| Category | Tools |
|---|---|
| Manual / Black-Box Testing | Equivalence Partitioning, Boundary Value Analysis |
| Test Automation | Selenium WebDriver (Python), Page Object Model, pytest |
| API Testing | Postman (GET, POST, PUT, DELETE) |
| Cross-Browser Testing | Chrome, Firefox, Edge, Chrome DevTools |
| Performance Testing | Apache JMeter |
| Security Testing | OWASP ZAP / Burp Suite Community Edition |
| Version Control | Git, GitHub |
| CI/CD | GitHub Actions |
| Documentation | Excel, Word, PDF |

## 🧪 Week-by-Week Summary

| Week | Focus | Key Result |
|---|---|---|
| Week 1 | Manual functional & UI testing | 18 test cases, 50% pass rate, 9 bugs logged |
| Week 2 | Black-box techniques (EP/BVA), cross-browser testing, retesting | 57 test cases, 89% pass rate, 10 bugs retested |
| Week 3 | Selenium automation + API testing | 3 test cases automated, REST API validated via Postman |
| Week 4 | Performance / load testing | 50–100 virtual users tested via Apache JMeter |
| Week 5 | Security testing | OWASP Top 10 based vulnerability assessment |
| Week 6 | CI/CD integration | GitHub Actions pipeline design for automated testing |

## 🚀 How the Automated Tests Run

Tests are triggered automatically on:
- Every push to `main` / `develop`
- Every Pull Request to `main`
- A nightly scheduled run (full regression)

See [`ci-cd/CICD_Workflow.docx`](./ci-cd/CICD_Workflow.docx) for full pipeline details and the sample GitHub Actions workflow file.

## 📊 Reports

All test plans, bug reports, performance results, and security findings are available in their respective folders above, and are consolidated in [`portfolio/Final_QA_Portfolio.pdf`](./portfolio/Final_QA_Portfolio.pdf).

## 👤 Author

**Saad Ahmed** — QA Engineer (Trainee), DevelopersHub Corporation
This repository was built as part of a structured 6-week QA training program covering manual testing, black-box techniques, automation, performance, security, and DevOps/CI-CD integration for QA.
