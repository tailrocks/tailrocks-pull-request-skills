# Repository maintenance

Keep the [migration notice](README.md), changelog, license, and retirement
checks here. Maintain the active skills in the canonical package linked from
the notice. Preserve this repository's history.

Use the [retired repository standard][standard]. Update the pinned Alint
profile revision and digest together. Run `alint check --fail-on-warning`.

Change CI through the Velnor configuration. Run `velnor-actions generate`
with the version in the release manifest.

[standard]: https://github.com/tailrocks/tailrocks-skills/blob/main/docs/standards/structure.md#retired-repository
