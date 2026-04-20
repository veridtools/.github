<img src="./verid-logo.webp" width="120" alt="Veridtools" />

# Veridtools

Open source TypeScript tooling for **DMN** — the OMG standard for modeling business decisions.

Most business logic lives where it shouldn't: in `if/else` chains that only engineers can change, in spreadsheets that only analysts can read, in enterprise platforms that require Java stacks and migration projects.

DMN solves this — a clear, executable, standards-based way to model decisions. The tooling around DMN, however, has stayed stuck in the JVM world.

Veridtools brings DMN to the JavaScript and TypeScript ecosystem.

## Packages

### Available

| Package | Description |
|---------|-------------|
| [`@veridtools/dmn-fixtures`](https://github.com/veridtools/dmn-fixtures) | Curated DMN test fixtures for JS/TS tooling — 31 groups, DMN 1.0-1.5 coverage |

### In development

More TypeScript-native DMN tooling is on the way — parsers, runners, editors, linters. Watch this space or follow individual repos for release notifications.

## What is DMN?

DMN (Decision Model and Notation) is an open standard from the [Object Management Group](https://www.omg.org/dmn/) for modeling business decisions. It's executable, vendor-neutral, and designed so business analysts and engineers can collaborate on the same artifact.

If you're building anything with non-trivial business rules — credit scoring, eligibility, pricing, routing, compliance checks — DMN is probably a better fit than your current `if/else` tower.

## Design principles

- **TypeScript-native** — runs in Node.js and the browser, no JVM required
- **Standards-compliant** — 100% aligned with the OMG DMN specification
- **Small, focused packages** — do one thing well, compose as needed
- **Minimal runtime dependencies** — understand what you're shipping
- **MIT licensed** — use freely in commercial and open source projects

## Contributing

Every Veridtools package welcomes issues, PRs and discussions. Start at the repo of the package you're using — each has its own `CONTRIBUTING.md`.

If you're building DMN tooling in JS/TS and want to collaborate, [open a discussion](https://github.com/orgs/veridtools/discussions) or reach out.

## Stay in the loop

- ⭐ Star the repos you find useful
- 👀 Watch for releases
- 💬 Join discussions at [github.com/orgs/veridtools/discussions](https://github.com/orgs/veridtools/discussions)

## License

All Veridtools packages are MIT licensed unless otherwise specified in the individual package.