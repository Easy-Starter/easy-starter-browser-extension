<div align="center">

# Easy Starter Browser Extension

**A cross-browser Extension.js foundation for Chrome, Edge, and Firefox extensions using React and TypeScript.**

[![Use this template](https://img.shields.io/badge/Use%20this%20template-2ea44f?logo=github&logoColor=white)](https://github.com/easy-starter/easy-starter-browser-extension/generate) [![CI](https://github.com/easy-starter/easy-starter-browser-extension/actions/workflows/ci.yml/badge.svg)](https://github.com/easy-starter/easy-starter-browser-extension/actions/workflows/ci.yml) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) ![Status: foundation](https://img.shields.io/badge/status-foundation-orange) ![Extension.js](https://img.shields.io/badge/Extension.js-5B21B6) ![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) ![Cross-browser](https://img.shields.io/badge/Cross--browser-2ea44f)

[فارسی](README.fa.md) · [Documentation](https://github.com/easy-starter/easy-starter-docs) · [Report an issue](https://github.com/easy-starter/easy-starter-browser-extension/issues/new/choose)

</div>

> “What do we build for, if not to lessen each other’s hardship?”

> [!IMPORTANT]
> This repository is currently in the **foundation stage**. Do not treat it as production-ready until the first stable release.

## What it solves

Provides one architecture and build workflow for browser-specific surfaces, permissions, messaging, storage, testing, and store-ready packages.

## Use this template for

- Popup, options, side-panel, and new-tab extensions
- Content-script page enhancements
- Productivity and AI assistant extensions
- Chrome, Edge, and Firefox releases from one project

**Not intended for:** Ordinary websites or extensions that require unrelated native applications.

## Baseline

- Extension.js, React, and TypeScript
- Background, content, popup, options, and shared boundaries
- Permission-minimization and secure messaging conventions
- Browser-specific development and packaging commands
- Tests, CI, release, and store-submission checklists

Detailed architecture, conventions, deployment profiles, and extension guides belong in [`docs/`](docs/). Feature work starts from [`specs/`](specs/), and agent rules live in [`AGENTS.md`](AGENTS.md).

## Quick start

1. Click **Use this template** or run:

   ```bash
   gh repo create my-project --template easy-starter/easy-starter-browser-extension --private --clone
   cd my-project
   ```

2. Set the project name, package metadata, and environment values.
3. Start the project:

   ```bash
   cp .env.example .env.local
   make setup
   make dev
   make check
   ```

4. Write the first feature specification under `specs/`.
5. Implement the feature and keep `make check` green.

## Working agreement

- Read `AGENTS.md` and the relevant specification before changing code.
- Reuse existing patterns before adding abstractions or dependencies.
- Never commit credentials or production data.
- Run the repository quality checks before opening a pull request.
- Record architecture-changing decisions in `docs/decisions/`.

## Documentation

Start with `docs/getting-started.md`. Broader AI-first development guidance is maintained in [Easy Starter Docs](https://github.com/easy-starter/easy-starter-docs).

## Contributing and support

See [`CONTRIBUTING.md`](CONTRIBUTING.md) for contribution rules and [`SUPPORT.md`](SUPPORT.md) for help. Security issues must follow [`SECURITY.md`](SECURITY.md).

## License

Released under the [MIT License](LICENSE).
