# .github

Default community health files for the organization. GitHub applies these to
any repo in the org that does not have its own version.

- `pull_request_template.md`: default PR description
- `ISSUE_TEMPLATE/`: default issue forms (bug, feature, task)

This repo is **public**, so keep it generic. No client data, internal system
names, hostnames, or contact details.

A repo that needs project-specific fields should add its own `.github/`
templates. Those override these defaults (all-or-nothing per file type: a repo
with any `ISSUE_TEMPLATE/` folder ignores this one entirely).
