# Changelog

## Goal 3 resource contract (2026-08-29)

### Added

- `data/redeem_codes.json` as the public redeem-code source of truth.
- `schemas/redeem-codes.v1.schema.json` for the versioned redeem-code shape.
- `data` and `schemas` in `resource_manifest.json`.
- README guidance for typed submissions, main-only release, legacy `end_at` migration, mirror
  trust, and Git revert rollback.

### Security and licensing

- The repository remains pure public resources. It must not contain editor code, build output,
  tokens, cookies, databases, or bot configuration.
- No blanket licence is granted for third-party assets; upstream terms and attribution remain the
  responsibility of each contributor and maintainer.

### Verification boundary

- The current contract is on the Goal 3 working branch until its pull request is merged to `main`.
- The editor's `resource-contract` Check and the plugin's generation validator are the semantic
  gates for duplicate codes, time ordering, file paths, headers, and complete layout.
