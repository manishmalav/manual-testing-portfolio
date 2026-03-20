# Manual Testing Portfolio — Indeed.com Login Module

A complete manual testing project for the Login & Authentication
module of Indeed.com, demonstrating the full STLC lifecycle
with AI-assisted documentation.

## Project Overview

| Item | Details |
|------|---------|
| Application Under Test | Indeed.com |
| Module Tested | Login & Authentication |
| Testing Type | Manual + Exploratory |
| AI Tools Used | Claude AI for FRS, scenarios, test cases, bug reports |

## Deliverables

### 1. Functional Requirements Specification (FRS)
Documents all functional requirements for the Login module
across 5 sub-modules: Email/Password, Google Login,
Forgot Password, Session Management, Security/Lockout.

### 2. Test Scenarios — 49 Total
| Sub-module | Scenarios |
|------------|-----------|
| Email / Password Login | 17 |
| Google / Social Login | 7 |
| Forgot Password | 11 |
| Session Management | 7 |
| Security / Lockout | 7 |
| **Total** | **49** |

### 3. Test Cases — 49 Detailed Cases
Each test case includes:
- Unique TC ID
- Preconditions
- Step-by-step test steps
- Test data
- Expected result
- Priority (High / Medium / Low)
- Type (Positive / Negative / Edge Case)

### 4. Bug Reports — 2 Real Bugs Found
| Bug ID | Title | Severity | Priority |
|--------|-------|----------|----------|
| BR-LGN-001 | Email/password form bypassed when Gmail active in browser | Medium | High |
| BR-LGN-002 | Google OAuth forced even in InPrivate/Incognito mode | High | High |

### 5. Test Execution
Live execution performed on Indeed.com across Chrome and
Edge browsers. Cross-browser testing revealed consistent
reproduction of both bugs.

## Key Testing Skills Demonstrated

- Requirements analysis and FRS creation
- Test scenario design (positive, negative, edge cases)
- Test case writing with step-by-step instructions
- Bug reporting with severity and priority classification
- Cross-browser testing (Chrome, Edge)
- Exploratory testing and session/cookie behaviour analysis
- AI-assisted test documentation

## Tools Used

| Tool | Purpose |
|------|---------|
| Indeed.com | Application under test |
| Excel / Google Sheets | Test case management |
| Chrome DevTools | Element inspection |
| Claude AI | AI-assisted documentation |
| Edge InPrivate | Cross-browser testing |
