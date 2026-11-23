# Lafke

Lafke records the trust decision for each dependency in `lafke.lock`, fails CI when that
state drifts, and analyzes your own source code for vulnerabilities, committed secrets and
unsafe infrastructure settings. Analysis runs locally; your source code is never uploaded.

## Get started

```sh
curl -fsSL https://lafke.sh/install | sh
lafke scan .
```

Documentation: [lafke.dev](https://lafke.dev)

## Repositories

| Repository | What it is |
| --- | --- |
| [lafke/lafke](https://github.com/lafke/lafke) | The command-line interface, GitHub Action and pre-commit hook. |
| [lafke/engine-releases](https://github.com/lafke/engine-releases) | Prebuilt, attested releases of `lafke-engine`, the source-code analysis engine. |
| [lafke/demo](https://github.com/lafke/demo) | Intentionally vulnerable sample code that shows Lafke findings in GitHub Actions. |

## Contributing and security

- Contribution guidelines: [CONTRIBUTING.md](https://github.com/lafke/.github/blob/main/CONTRIBUTING.md)
- Report a vulnerability privately: [SECURITY.md](https://github.com/lafke/.github/blob/main/SECURITY.md)
- Questions and help: [SUPPORT.md](https://github.com/lafke/.github/blob/main/SUPPORT.md)
