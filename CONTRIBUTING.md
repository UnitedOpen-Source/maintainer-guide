# Contributing to Maintainer Guide

Thanks for your interest. This guide is written in the open, and every pattern is expected to be reviewed by people who maintain real projects.

## Opening an issue

- Search existing issues first.
- For a new pattern, describe the problem it solves, when it should not be used, and at least one public project that applies it (with a link).
- For a correction, link the page and the source that contradicts it.
- For a security concern about the site itself, do not post exploit details in a public issue; open an issue asking the maintainers for a private contact.

## Proposing a pull request

1. Open or pick an issue and say you are working on it.
2. Create a branch from `main` and keep each pull request focused on one issue.
3. Follow the pattern page template once it exists (Problem, When to use, When not to use, Template, Real examples, References).
4. Every external claim needs a working link to a primary source. Every real-world example needs a link to the public file, pull request or announcement that shows it.
5. Reference the issue in the description (`Closes #N`) and describe what changed and why.

Contributions are accepted under the repository license, [CC BY 4.0](LICENSE).

## Structural decisions

Decisions that shape the project (site generator, page structure, translation workflow, deploy target) are recorded as Architecture Decision Records in `docs/adr/`, one decision per file, named `NNNN-short-title.md`, using the format described by [Michael Nygard](https://www.cognitect.com/blog/2011/11/15/documenting-architecture-decisions): Context, Decision, Status, Consequences. Propose the ADR in a pull request before or together with the change it justifies.

## Code of Conduct

All participation follows the [UnitedOpen-Source Code of Conduct](https://unitedopensource.org/code-of-conduct).
