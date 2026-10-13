# Security policy

This policy covers every repository of [ladohq](https://github.com/ladohq) that has no
`SECURITY.md` of its own: LADO's kits (`kit-*`) and any repository added later.
[ladohq/lado](https://github.com/ladohq/lado/security/policy) and
[ladohq/marketplace](https://github.com/ladohq/marketplace/security/policy) have their own.

## Reporting a vulnerability

Please report a vulnerability privately, through GitHub's private vulnerability reporting:
open the affected repository's **Security** tab and choose **Report a vulnerability**. Do
not open a public issue, pull request or discussion about it.

Say which repository and which version (tag) is affected, what the problem is and how to
reproduce it. For a kit, a problem may be in its prompts and skills (they steer agents
somewhere they should not go), in an MCP server it starts, or in its published tags (a tag
moved or the repository taken over).

## Supported versions

Only the latest release (the newest `vX.Y.Z` tag) of each repository is supported: a fix
comes as its next release.

## What to expect

The maintainers aim to answer a report within 7 days. There is no fixed deadline for a
fix: the maintainers tell you what they found and keep you informed until the fix is
released.
