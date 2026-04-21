<h1 align="center"><img src="./verid-logo.webp" width="75" alt="Veridtools Logo" /> <p>Verid</p></h1>

Open source TypeScript tooling for **DMN** — the OMG standard for modeling business decisions.

Most business logic lives where it shouldn't: in `if/else` chains that only engineers can change, in spreadsheets that only analysts can read, in enterprise platforms that require Java stacks and migration projects.

DMN solves this — a clear, executable, standards-based way to model decisions. The tooling around it, however, has stayed stuck in the JVM world.

Veridtools brings DMN to the JavaScript and TypeScript ecosystem.

---

## Packages

### Available

| Package | Description |
|---------|-------------|
| [`@veridtools/dmn-fixtures`](https://github.com/veridtools/dmn-fixtures) | Test fixtures for DMN tooling — 36 groups, ~316 files, full DMN 1.0–1.5 coverage |
| [`@veridtools/dmn-diff`](https://github.com/veridtools/dmn-diff) | Semantic diff for DMN files — ID-based identity, severity classification (breaking / non-breaking / cosmetic), four output formats, CI/CD-native exit codes |
| [`@veridtools/dmn-diff-highlight`](https://github.com/veridtools/dmn-diff-highlight) | Visual highlighting for DMN diffs — plain JS and React exports, composable theme system |

### In development

More TypeScript-native DMN tooling is on the way — parsers, runners, linters, editors. Watch this space or follow individual repos for release notifications.

---

## What is DMN?

DMN (Decision Model and Notation) is an open standard from the [Object Management Group](https://www.omg.org/dmn/) for modeling business decisions. It's executable, vendor-neutral, and designed so business analysts and engineers can work on the same artifact.

If you're building anything with non-trivial business rules — credit scoring, eligibility checks, pricing logic, compliance rules — DMN is probably a better fit than your current approach.

---

## Design principles

- **TypeScript-native** — runs in Node.js and the browser, no JVM required
- **Standards-compliant** — aligned with the OMG DMN specification, tested against the official TCK
- **Small, focused packages** — each does one thing well and composes with the rest
- **Minimal dependencies** — understand exactly what you're shipping
- **MIT licensed** — use freely in commercial and open source projects

---

## Contributing

Every package welcomes issues, pull requests and discussions. Start at the repo for the package you're using — each has its own `CONTRIBUTING.md`.

If you're building DMN tooling in JS/TS and want to collaborate, [open a discussion](https://github.com/orgs/veridtools/discussions) or reach out directly.

---

## Stay in the loop

- ⭐ Star the repos you find useful
- 👀 Watch for releases
- 💬 Discuss at [github.com/orgs/veridtools/discussions](https://github.com/orgs/veridtools/discussions)

---

## License

All Veridtools packages are MIT licensed unless otherwise noted in the individual package repository.
