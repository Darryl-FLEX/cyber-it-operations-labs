# Cyber IT Operations Labs

A hands-on portfolio of documented IT support, Linux administration, cybersecurity monitoring, troubleshooting, and incident-response exercises.

[![Linux](https://img.shields.io/badge/Linux-Administration-FCC624?logo=linux&logoColor=black)](linux/)
[![Security Operations](https://img.shields.io/badge/Security-Operations-0EA5E9)](soc/)
[![Home Lab](https://img.shields.io/badge/Home%20Lab-Virtualized-8B5CF6)](home-lab/)
[![Documentation](https://img.shields.io/badge/Focus-Technical%20Documentation-16A34A)](#documentation-standard)

## Purpose

This repository demonstrates how I approach technical work:

1. Define the objective and environment.
2. Perform the task or investigation in a controlled lab.
3. Record the commands, observations, and decision points.
4. Document findings, response actions, and outcomes.
5. Separate hands-on lab evidence from production or employer experience.

> **Scope:** All security investigations in this repository are simulated or lab-based. They do not contain employer data, military operational details, real customer information, protected health information, credentials, or production incident records.

## Portfolio Map

### Linux Administration

| Lab | Skills demonstrated |
|---|---|
| [Linux Basics — Essential Commands](linux/linux-basics-commands.md) | Filesystem navigation, file operations, command-line fundamentals, and use of manual pages |
| [Users, Groups, and Permissions](linux/linux-users-permissions.md) | User administration, groups, ownership, permissions, and least privilege |
| [Services and systemctl](linux/linux-services-systemctl.md) | Service status, start/stop/restart, startup configuration, and troubleshooting |
| [Logs and Troubleshooting](linux/linux-logs-troubleshooting.md) | `journalctl`, log filtering, authentication events, service errors, and real-time monitoring |

### Security Operations

| Investigation | Skills demonstrated |
|---|---|
| [Multiple Failed Login Attempts](soc/soc-alert-investigation-auth-failure.md) | Alert triage, authentication analysis, timeline review, findings, recommendations, and closure |
| [Suspicious Process Activity](soc/soc-alert-investigation-suspicious-process.md) | Process context, parent/child analysis, execution path, related-event review, and monitoring recommendations |

### Virtual Home Lab

| Investigation | Skills demonstrated |
|---|---|
| [Authentication Failures in a Virtualized Linux Lab](home-lab/home-lab-auth-failure-investigation.md) | Controlled event generation, Linux authentication-log review, source/user context, and documentation |

## Skills Demonstrated

- Linux command-line administration
- User, group, ownership, and permission management
- `systemd`, `systemctl`, and service troubleshooting
- `journald` and Linux log analysis
- Authentication-event investigation
- Suspicious-process triage
- Incident notes, findings, recommendations, and closure
- Least privilege and security-minded operations
- Clear technical documentation

## Documentation Standard

Each writeup aims to include:

- **Objective** — what the lab or investigation is intended to demonstrate
- **Environment** — systems and tools used
- **Actions** — commands or investigation steps performed
- **Evidence** — observations and relevant context
- **Analysis** — why the evidence matters
- **Outcome** — result, recommendation, or lesson learned
- **Scope statement** — confirmation that the activity is simulated or lab-based when applicable

## Planned Additions

- [ ] Windows support and troubleshooting lab
- [ ] Active Directory user and group administration lab
- [ ] PowerShell system-inventory and health-check script
- [ ] Linux hardening checklist with before/after evidence
- [ ] SIEM query examples using sanitized sample logs
- [ ] Vulnerability-management workflow with remediation tracking
- [ ] Healthcare IT access and privacy scenario using fictional data

## About the Author

**Darryl Dorcely** — IT Support and Cybersecurity Professional · U.S. Army Reserve IT Specialist (25B) · CompTIA Security+ and Network+

- [GitHub Profile](https://github.com/Darryl-FLEX)
- [LinkedIn](https://www.linkedin.com/in/darryl-dorcely-185511169)
