# Super POM

The top level Maven POM for all Common Platform projects. It defines information such as the organisation properties and source encoding that should be consistent across all projects.

## Versioning

This project uses GitHub Actions to dynamically set the Maven version during build time:

- **Release builds**: When a GitHub Release is published, the tag (e.g. `v1.2.3`) is stripped of the leading `v` and used directly as the version (e.g. `1.2.3`).
- **Push builds**: When changes are pushed to `main` or `master`, the most recent tag is found, the patch number is incremented (e.g. `v1.2.3` → `1.2.4-SNAPSHOT`), and used as the version.
- **Fallback**: If no previous tags are found, the default version `17.0.1-SNAPSHOT` is used.

The resolved version is passed to Maven using the `-Drevision=...` flag, which is defined in the `pom.xml`.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details