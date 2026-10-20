# Security policy

Report suspected vulnerabilities privately using the affected repository's
**Security → Report a vulnerability** form when available. Avoid public issues
for unpatched vulnerabilities, credentials, or sensitive data.

For private repositories without that form, contact an organization owner through
an existing private channel. Do not include live credentials or personal data.

Include the affected version or commit, a minimal reproduction, expected behavior,
and potential impact. Maintainers will assess the report and coordinate a fix and
any disclosure. Do not test against systems you are not authorized to assess.

Dependency version updates are reviewed through `dev` where configured. GitHub's
native Dependabot security updates target the default branch; transfer fixes to
other maintained branches with review and validation rather than blindly changing
the base of a pull request across diverged branches.
