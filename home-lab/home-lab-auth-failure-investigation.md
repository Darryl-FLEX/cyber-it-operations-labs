# Home Lab Alert Investigation – Authentication Failures

## Alert Summary
- Alert Type: Authentication Failure
- Environment: Home Lab (Virtualized Linux Systems)
- Severity: Low–Medium
- Description: Multiple failed login attempts detected on a Linux server.

## Investigation Steps
- Reviewed authentication logs on the server
- Identified repeated failed login attempts
- Verified source IP and user context
- Checked for successful login attempts after failures

## Findings
- Multiple failed login attempts from a single client system
- No successful authentication observed
- Activity determined to be simulated and non-malicious

## Response Actions
- Documented findings
- Recommended monitoring for repeated attempts
- Reinforced importance of strong authentication controls

## Lessons Learned
- Authentication logs are critical for early threat detection
- Failed login patterns can indicate brute-force attempts
- Log review is central to SOC investigations

## Status
Closed – Simulated activity
