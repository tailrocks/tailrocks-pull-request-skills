# Changelog

## Unreleased

- Pointed the migration guide at the current installation guide on `main`.
- Added repository maintenance instructions and refreshed the shared retired
  profile, including checks that reject native entry points and adapters.
- Regenerated the minimal retirement CI with Velnor Actions `0.1.80` and added
  strict JSON and local Markdown link checks.

## Package retirement

Retired this package in favor of `tailrocks-repository-skills`:

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
