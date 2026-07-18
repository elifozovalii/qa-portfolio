# Login Test Cases

| Test ID | Test Scenario | Steps | Expected Result | Priority |


| TC-001 | Login with valid credentials | Enter valid email and password | User logs in successfully | High |
| TC-002 | Login with invalid password | Enter wrong password | Error message displayed | High |
| TC-003 | Login with invalid email | Enter invalid email | Error message displayed | High |
| TC-004 | Empty email | Leave email blank | Validation message displayed | Medium |
| TC-005 | Empty password | Leave password blank | Validation message displayed | Medium |
| TC-006 | Empty fields | Click Login without entering data | Required field validation | High |
| TC-007 | Password masking | Type password | Password is hidden | Medium |
| TC-008 | Remember Me | Select Remember Me | Session remembered | Low |
| TC-009 | SQL Injection | Enter | Login prevented | Critical |
| TC-010 | XSS Injection | Enter | Script is not executed | Critical |
