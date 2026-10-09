# Maintainer Guide

Practical governance patterns for healthy, sustainable open source projects.

## Why

Most open source projects never write down how they decide things, who can merge, where to report a vulnerability, or what happens when the only maintainer steps away. The rules exist anyway, but only in one person's head, and they surface at the worst moment: a disputed pull request, a leaked exploit, a project that silently stops answering.

Good material on these topics exists, from the [Open Source Guides](https://opensource.guide/) to the [CHAOSS](https://chaoss.community/) metrics and the [OpenSSF](https://openssf.org/) security guidance. What is often missing is the last step: a short, opinionated page that tells a maintainer when a pattern fits, when it does not, and gives them a file they can copy into their repository today.

## What it is

Maintainer Guide aims to be a documentation site, written in MDX, where each governance pattern follows the same structure:

- **Problem**: the situation the pattern addresses.
- **When to use** and **when not to use**: the trade-offs, stated plainly.
- **Template**: a ready-to-copy file (for example `GOVERNANCE.md`, `SECURITY.md`, an ADR).
- **Real examples**: public projects that apply the pattern, each with a verified link.
- **References**: the primary sources the pattern builds on.

The guide is written in English first, with Brazilian Portuguese and Spanish translations planned.

## What it is not

- Not legal advice. Licensing, trademarks and foundation membership are mentioned only where they affect governance, with pointers to primary sources.
- Not a certification or a maturity score. Projects are free to take one pattern and ignore the rest.
- Not a replacement for the sources it cites. Where an established guide already covers a topic well, this guide links to it instead of rewriting it.
- Not a rulebook for UnitedOpen-Source projects. Examples from the organization are used only when they are verifiable in public repositories.

## Planned scope for v0.1.0

- MDX site generator decision (ADR), scaffold, CI and deploy
- A shared pattern page template
- Pattern: decision-making models (BDFL, maintainers council, lazy consensus)
- Pattern: Architecture Decision Records, with a template
- Pattern: contributor ladder
- Pattern: `SECURITY.md` and coordinated vulnerability disclosure
- Pattern: succession and bus factor
- Pattern: archiving a project responsibly
- Translation plan for pt-BR and es

Topics planned for later versions include issue triage, release policy, and funding and sustainability.

## Principles

1. **Every pattern says when not to use it.** A governance model that fits a foundation project can smother a two-person library. Each page names the cost, not only the benefit.
2. **Copyable over comprehensive.** Each pattern ships a template that works when pasted into a repository, with placeholders clearly marked.
3. **Every example links to a public source.** No anonymous success stories. If a claim about a project cannot be linked, it is left out.
4. **Small pages, stable structure.** Readers should be able to land on any pattern and find the same sections in the same order.
5. **Accessible and translatable from the start.** Plain language, descriptive link text, and content kept separate from layout so translations do not fork the structure.

## Getting involved

The project is at its starting point, so the most useful contributions are discussion on the scope and the first pattern pages.

- Look for issues labeled [`good first issue`](https://github.com/UnitedOpen-Source/maintainer-guide/labels/good%20first%20issue).
- Read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.
- All participation follows the [UnitedOpen-Source Code of Conduct](https://unitedopensource.org/code-of-conduct).

## License

The content of this repository is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). See [LICENSE](LICENSE).
