# Dependency trust, tracked in your repository

Lafke is a command-line tool that keeps a record of what you decided about each
dependency, and checks your own code for problems.

- **Trust decisions:** each dependency's decision lives in `lafke.lock`, and CI fails when
  that state drifts.
- **Source analysis:** finds vulnerabilities, committed secrets and unsafe infrastructure
  settings in your code.
- **Local by default:** analysis runs on your machine, and your source code is never
  uploaded.

## Get started

```sh
curl -fsSL https://lafke.sh/install | sh
lafke scan .
```

Read the [documentation](https://lafke.dev) for the full guide.

## Projects

| Project | What it is |
| --- | --- |
| [CLI](https://github.com/lafke/lafke) | The command-line interface, GitHub Action and pre-commit hook. |
| [Engine releases](https://github.com/lafke/engine-releases) | Prebuilt, attested releases of `lafke-engine`, the source-code analysis engine. |
| [Demo](https://github.com/lafke/demo) | Intentionally vulnerable sample code that shows findings in GitHub Actions. |

## Get involved

- [Contribution guidelines](https://github.com/lafke/.github/blob/main/CONTRIBUTING.md)
- [Report a vulnerability privately](https://github.com/lafke/.github/blob/main/SECURITY.md)
- [Questions and help](https://github.com/lafke/.github/blob/main/SUPPORT.md)
