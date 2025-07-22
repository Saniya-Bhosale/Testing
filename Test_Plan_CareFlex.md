# 🧪 Test Plan – CareFlex Functional Manual Testing

## Project Title:
CareFlex – Real-Time Health Monitoring & Doctor–Patient Dashboard

---

## Purpose:
This test plan outlines the approach for functional testing of the **CareFlex** platform’s core modules, including doctor and patient registration, login functionality, and Doctor Key-based patient mapping.

---

## Scope of Testing:

### ✅ In-Scope:
- Doctor Registration
- Doctor Login
- Patient Registration (with Doctor Key)
- Patient Login
- Email format and password validation
- Data correctness and flow validation

### ❌ Out-of-Scope:
- UI/UX (design, alignment, responsiveness)
- Wearable sensor data (e.g., EMG, GSR, SpO₂, Bioimpedance)
- Dashboard charts, alerts, or notifications
- Security testing (e.g., password encryption, SQL injection)

---

## Functional Modules to be Tested:
1. Doctor Sign-Up
2. Doctor Login
3. Patient Sign-Up (with Doctor Key validation)
4. Patient Login
5. Doctor Key validation and mapping

---

## Test Strategy:
We will use **Black Box Testing** technique with **positive and negative test cases** to validate functionality. All tests will be executed manually.

---

## Test Environment:
- Web App URL: `http://localhost:3000` 
- Browser: Google Chrome 
- Backend: Node.js 
- Database: MySQL 

---

## Entry Criteria:
- All core modules (signup, login, key linking) are developed and hosted
- Required fields and validations are implemented
- Backend is connected to a working database

## Exit Criteria:
- 100% of critical test cases passed
- All major bugs fixed or documented
- Doctor–Patient flow works as expected

---

## Deliverables:
- Test Plan Document
- Test Scenarios List
- Test Cases Excel Sheet
- Sample Test Data
- Bug Report Template
- Requirement Traceability Matrix

---

## Roles & Responsibilities:
| Role | Responsibility |
|------|----------------|
| Tester (You) | Prepare and execute test cases, report bugs |
| Developer | Fix reported bugs, support test execution |
| Reviewer/Faculty | Review testing approach and outcomes |
