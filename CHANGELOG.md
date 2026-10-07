# Changelog

## Unreleased

Retired this package on branch `standardize/retire`:

- Removed the six historical skills (`tailrocks-create-pr`,
  `tailrocks-refresh-pr`, `tailrocks-review-pr`, `tailrocks-merge-pr`,
  `tailrocks-pr-template`, `tailrocks-document`). The current
  pull-request lifecycle skills live in `tailrocks-repository-skills`.
- Removed the plugin manifests, catalogs, generated docs, and the
  collection-owned programs. They supported only the removed skills.
- Rewrote `README.md` as the migration notice. It names the canonical
  repository and its installation guide.
- Added `.alint.yml` with the shared retired profile. It rejects
  skills, plugin manifests, and catalogs.
