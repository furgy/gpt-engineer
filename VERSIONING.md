# Versioning

This project uses Semantic Versioning (SemVer).

## Version Format

`X.Y.Z` where:
- `X` (major): Breaking changes
- `Y` (minor): New features (backward compatible)
- `Z` (patch): Bug fixes (backward compatible)

## Version Source

Version is stored in `VERSION` file (simple X.Y.Z format).

The `pyproject.toml` version must match `VERSION` file.

## Version Bump Commit

When pushing to main, the version MUST be bumped:
- Update VERSION file
- Commit message must include version bump (e.g., `Bump version to 0.2.0`)

## CI Check

CI workflow validates that commits to main contain version bumps.
