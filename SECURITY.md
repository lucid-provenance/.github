# Security Policy

This is the default security policy for every repository in the
[lucid-provenance](https://github.com/lucid-provenance) organization that
doesn't define its own `SECURITY.md` — GitHub falls back to this file
automatically (org-wide default community health file).

## Reporting a vulnerability

**Preferred: GitHub Private Vulnerability Reporting.** Open the affected
repository, go to the **Security** tab → **Report a vulnerability**. This
creates a private advisory visible only to the maintainer and you, with
no public disclosure until a fix is ready.

If a repository has private reporting disabled, or you'd rather not use
GitHub for this, email **billwonch@outlook.com** instead. Please
include:

- The affected repository and, if known, the commit/version.
- Steps to reproduce, or a proof of concept.
- The potential impact as you understand it.

Please do not open a public GitHub issue for a suspected vulnerability.

## What to expect

Lucid Provenance is a solo-maintained project today — response times are
best-effort, not a contractual SLA. As a working target:

| Severity | Initial response | Target resolution |
|---|---|---|
| Critical | 2 business days | 7 days |
| High | 5 business days | 30 days |
| Medium / Low | 10 business days | Best effort, tracked publicly |

You'll get an acknowledgment, an assessment of severity and impact, and
updates as a fix is developed. Credit is offered in the fix's release
notes/changelog unless you ask to stay anonymous.

## Supported versions

Every `lucid-*` repository's `main` branch is the only actively supported
version — there's no long-term-support branch model today. A reported
issue is fixed against `main` and released from there.

## Scope

Covers the code in `lucid-provenance`'s own repositories. Vulnerabilities
in third-party dependencies should generally be reported upstream as
well — Dependabot and SonarQube Cloud scanning are already wired into
every repo's CI to catch known-vulnerable dependencies, but a genuinely
novel finding upstream is still worth reporting to that project directly.

## Our vulnerability management process

The fuller policy governing how findings get triaged, fixed, or formally
risk-accepted lives in
[lucid-provenance/compliance](https://github.com/lucid-provenance/compliance) —
not published here since it documents internal process detail, not the
reporting channel itself.
