# Security policy

## Reporting a vulnerability

**Do not open a public issue.** A public report tells everyone about the problem, including
people who would use it, before there is anything to update to.

Two private routes, in this order:

1. **GitHub Private Vulnerability Reporting** — on the repository, open the **Security** tab and
   choose *Report a vulnerability*. This reaches the maintainers directly and stays private until
   an advisory is published. Use it when it is available on that repository.
2. **Email security@d8b.dev** when the first route is not offered.

Useful in a report: which version, what an attacker can achieve, and the smallest set of steps
that shows it. A proof of concept is welcome and not required.

## What happens next

These projects are maintained by a small team with day jobs, so the honest expectation is a
reply within a few working days rather than within hours. You will get:

- confirmation that the report arrived and was understood,
- an assessment of whether it is exploitable and how severely,
- a fix prepared privately — GitHub's draft advisories allow that — and coordinated publication
  once it is available,
- credit in the advisory, unless you prefer otherwise.

If a report goes unanswered for two weeks, treat that as a failure on our side rather than a
verdict on the finding, and say so publicly if you judge that appropriate.

## Which versions are covered

The latest release of each repository. Older releases are not patched retroactively unless the
repository's own README says otherwise.
