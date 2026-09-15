# Security Policy

## Supported versions

| Version | Supported |
|---------|-----------|
| 1.x     | Yes       |
| 0.x     | No        |

## Reporting a vulnerability

EntropyAudit reads source files and reports patterns; it never executes the
audited code and makes no network calls. If you find a security issue - a crash
on hostile input, a path traversal, or a report that leaks file contents beyond
the line it flags - please report it privately with GitHub's "Report a
vulnerability" button on the Security tab.

We aim to acknowledge reports within 72 hours and to ship a fix in the next
patch release.
