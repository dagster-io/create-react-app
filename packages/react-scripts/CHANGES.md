### 5.0.3 (May 3, 2022)

- Merge upstream changes, including v5.0.1
- Upgrade `@svgr/webpack` for security fix
- Update CSP handling
  - Skip CSP plugin if none is provided
  - Generate CSP configuration file in production build, if `outputFilename` is specified, to allow setting it CSP as header

### 5.0.2 (April 12, 2022)

- Replace eslint config with `@dagster-io/eslint-config` to avoid mismatch errors with `eslint-plugin-react` in our apps.

### 5.0.1 (January 17, 2022)

- Fix some dependencies and metadata.

### 5.0.0 (January 14, 2022)

- Initial commit.
