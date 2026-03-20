# Bug Report — BR-LGN-001

| Field | Details |
|-------|---------|
| Bug ID | BR-LGN-001 |
| Title | Email/password login form bypassed when Gmail active in browser |
| Module | Login & Authentication |
| Severity | Medium |
| Priority | High |
| Status | Open |
| Environment | Chrome · Windows · indeed.com |
| Reported Date | March 2026 |

## Steps to Reproduce
1. Open Chrome with a Gmail account signed in
2. Navigate to indeed.com/login
3. Observe the login screen

## Expected Result
Standard Indeed login form appears with email and
password fields.

## Actual Result
Indeed auto-detects the Gmail session and shows only
the "Continue with Google" screen. No option to use
email/password login.

## Impact
Users with Gmail accounts cannot access password-based
login without signing out of Google first.

## Workaround
Open Indeed in Incognito mode or sign out of Google.

## Screenshot
![BR-LGN-001](../05-Test-Execution/br-lgn-001.png)
