# Security Policy

SetCore.io is committed to ensuring the security and resilience of our infrastructure utilities and AIOps platforms. We take all vulnerability reports seriously.

## Supported Versions

We actively provide security updates for the following versions of our software:

| Version | Supported          |
| ------- | ------------------ |
| v1.x    | :white_check_mark: |
| < v1.0  | :x:                |

## Reporting a Vulnerability

**Please do not open a public GitHub Issue for security-related bugs.**

If you discover a security vulnerability (including data leaks, sandboxing bypasses, prompt injection risks, or execution flaws), please report it to us using one of the following methods:

1. **GitHub Private Vulnerability Reporting:** Navigate to the "Security" tab of the respective repository and click "Report a vulnerability".
2. **Email:** Send a detailed report to **security@setcore.io**.

### What to include in your report:
- A detailed description of the vulnerability.
- Steps to reproduce the flaw (PoC code, specific inputs, or OTLP payloads if applicable).
- Potential impact (e.g., sandbox escape, host access, resource exhaustion).

## Our Response Process

Upon receiving a valid report, the SetCore core team will:
1. Acknowledge receipt of the vulnerability within **48 hours**.
2. Work closely with you to validate and understand the root cause.
3. Keep you informed of our progress as we engineer a patch.
4. Release a coordinated security advisory along with the fix.

We ask that you practice **responsible disclosure** and refrain from publishing information about the vulnerability until we have had a reasonable amount of time to deploy a fix and protect our users.

Thank you for helping keep the SetCore.io ecosystem safe!
