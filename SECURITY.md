# Security Policy

## Reporting a vulnerability

**Please do not open a public issue for security problems.**

Email **ai-reporting@duplocloud.net** with the details. Helpful things to include:

- The release or commit of this repository you used, and the inputs you set, with secrets removed
- The affected module, resource, variable or workflow
- Steps to reproduce, and what an attacker gains
- Any logs or plan output, with tokens, keys, account IDs and customer identifiers redacted

Maintainers will acknowledge the report, work on the fix privately and coordinate disclosure with you before
anything is published.

## Scope

**In scope:** this repository's OpenTofu / Terraform code (the `platform` and `app` roots and the modules) and
its GitHub Actions workflows.

**Out of scope here:** vulnerabilities in the DuploCloud Helpdesk Helm chart, the DuploCloud container images it
deploys, or the DuploCloud platform itself. Report those to the same address, and say which chart version, image
and tag you were running. Vulnerabilities in the third-party providers this code uses belong upstream.

## Supported versions

Security fixes go into the latest release. Use the newest `vX.Y.Z` tag.
