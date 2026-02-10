# SOC Alert Investigation – Multiple Failed Login Attempts

## Alert Summary
- Alert Type: Authentication Failure
- Source: System logs
- Severity: Medium
- Description: Multiple failed login attempts detected on a user account within a short time window.

## Initial Assessment
Reviewed alert details to determine whether the activity was a user error or potential brute-force attempt.

## Investigation Steps
- Reviewed authentication logs for failed login events
- Checked timestamps and frequency of attempts
- Identified the affected user account
- Verified source IP and login origin
- Looked for successful login attempts following failures

## Findings
- Multiple failed login attempts occurred within minutes
- No successful login detected after failures
- Activity likely caused by user entering incorrect credentials
- No signs of account compromise identified

## Response Actions
- Documented the incident
- Recommended password reset for affected user
- Suggested monitoring the account for additional suspicious activity

## Lessons Learned
- Importance of monitoring authentication failures
- Value of log analysis in detecting potential threats
- Reinforced need for strong password and MFA policies

## Status
Closed – No compromise detected
