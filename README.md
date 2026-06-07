## Branch Protection Policy

The `main` branch is protected to ensure controlled and secure code integration.

### Rules

* Direct pushes to the `main` branch are not allowed.
* All changes must be submitted through a Pull Request (PR).
* At least one reviewer approval is required before merging.
* All review comments must be resolved before merge.
* Force pushes are restricted.
* Branch deletion is not permitted.

### Merge Workflow

```text
Feature Branch
      ↓
Pull Request
      ↓
Reviewer Approval
      ↓
Merge into Main
      ↓
Slack Notification
      ↓
Email Notification
```

### Purpose

This policy ensures:

* Controlled code changes
* Reviewer validation before merge
* Better auditability
* Automated stakeholder notifications after successful merges
* Improved governance and release visibility
