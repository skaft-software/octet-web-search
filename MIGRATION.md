# Repository extraction: octet-web-search

This public repository stages the complete tracked `extensions/octet-web-search` source tree from
[skaft-software/octet@6b0717548d420909b3ee991bf940011e578b12eb](https://github.com/skaft-software/octet/tree/6b0717548d420909b3ee991bf940011e578b12eb/extensions/octet-web-search).
`MIGRATION-SOURCE.json` records every original file's SHA-256 and executable mode.
The source is copied without modification; this initial commit does not rewrite
or retain the original Git history. That history remains available in the source repository.

## Status

**Staging, not a completed cutover or qualified standalone release.** Octet remains
the source of truth until its migration PR passes integration checks. Existing
release assets and installed bundles are not moved or replaced by this import.
No CI, registry publication, native signing, or release qualification is claimed.
Examples, builtins, SDKs, and agent internals remain in the octet repository.

## Remaining gates

- Replace monorepo-relative build, test, documentation, and asset references.
- Port relevant CI and deterministic packaging with source provenance checks.
- Keep exact host compatibility until a separately reviewed compatibility policy exists.
- Verify existing install/update/checksum and release flows before removing source.
- Preserve original security boundaries and third-party licenses.

Serve and the browser client need coordinated host-adapter and bundle validation.
The macOS companion has an upstream-documented missing shared-client API; source
extraction does not fix or qualify it. The iOS companion remains source-only and
has no qualified live-host pairing path.

The copied README uses historical monorepo paths. Resolve those references against
the pinned original checkout above until standalone documentation is integrated.
