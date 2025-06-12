# Super POM

The top level Maven POM for all Common Platform projects. It defines information such as the organisation properties and source encoding that should be consistent across all projects.

## Versioning

This project follows the HMCTS framework versioning strategy, supporting feature testing, final releases, and hotfixes.

### Strategy Overview

- **Release Branching**: Releases are managed from branches like `release/17.101.x`.
- **Feature Testing Builds**:
  - Version format: `17.101.3-SNAPSHOT`
  - Derived by incrementing the latest known patch version from the most recent `release-<version>` tag.
  - Used testing; not intended for customer use.
- **Milestone Releases**:
  - Version format: `17.101.0-M1`, `17.101.0-M2`, etc.
  - Used to denote stable intermediate points before a final release.
- **Final Releases**:
  - Version format: `17.101.0`, `17.101.1`, etc.
  - Tags are created using the format `release-<version>` (e.g., `release-17.101.0`).
- **Hotfix Releases**:
  - Patch version is incremented on an existing release branch or tag.
  - Version format remains consistent with final releases (e.g., `17.101.2`).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
