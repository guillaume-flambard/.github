# Security

This is the default for repositories that do not carry their own policy. A
repository with real security surface should replace it, because the cost of a
wrong report and the cost of a missing one both land on the reporter.

## How to report

Use GitHub's private vulnerability reporting on the repository where you found
the problem. On any repository, go to `Security` then `Report a vulnerability`.
If that option is not shown, the repository has not enabled it. In that case,
open a public issue whose only content is the words "security report, please
open a private channel", with no technical detail, and wait for a response.

Never put exploit detail, credentials, or the data of a third party in a public
issue.

## What happens next

There is no response-time commitment here, and inventing one would be a promise
a single maintainer cannot keep. You will get an acknowledgement when the
maintainer reads it. If the report is not acted on, you will be told that too.

## Supported versions

Each repository documents its own. Most are pre-1.0 and support only the current
default branch.
