# Bug Report — BR-LGN-002

| Field | Details |
|-------|---------|
| Bug ID | BR-LGN-002 |
| Title | Google OAuth forced even in InPrivate/Incognito mode |
| Module | Login & Authentication |
| Severity | High |
| Priority | High |
| Status | Open |
| Environment | Edge InPrivate · Windows · indeed.com |
| Reported Date | March 2026 |

## Steps to Reproduce
1. Open Edge InPrivate window
2. Navigate to indeed.com/login
3. Observe the login screen

## Expected Result
Standard email/password login form should appear since
no Google session exists in private mode.

## Actual Result
Indeed still detects the Google account and forces
OAuth flow even in InPrivate mode.

## Impact
Email/password login path is completely inaccessible
for users with active Google accounts regardless of
browser mode.

## Severity Justification
High — core authentication flow inaccessible. Only
workaround is using a non-Google email account.

## Screenshot
![BR-LGN-002](../05-Test-Execution/br-lgn-002.png)
