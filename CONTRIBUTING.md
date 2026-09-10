# Contributing Guide

[中文版](./CONTRIBUTING.zh-CN.md) | English

Thanks for your interest in contributing to FunnLink's open-source projects! Bug fixes, new features, docs and issues are all welcome.

---

## Workflow

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature` or `git checkout -b fix/your-bug`
3. Commit your changes following the `type: short description` convention
   (`feat` / `fix` / `refactor` / `docs` / `style` / `test` / `chore`)
4. Push to your fork: `git push origin feature/your-feature`
5. Open a Pull Request on Gitea / GitHub

## Pre-submission checklist

- Run `composer pint` (PHP) or the language's linter
- Run `composer phpstan` (PHP) or the equivalent static analyzer
- Run the test suite and confirm green
- For user-visible strings, update the `lang/*.php` translation files

## Reporting bugs

Open a [Bug report](https://github.com/funnlink/.github/issues/new?template=bug_report.md) and include:

- Reproduction steps
- Expected vs. actual behavior
- Environment info (product / version / runtime)

## Proposing features

Open a [Feature request](https://github.com/funnlink/.github/issues/new?template=feature_request.md). Describe the pain point and your proposed solution before writing code.

## Code style

- PHP: Laravel Pint preset
- JavaScript / TypeScript: project's ESLint / Prettier config
- Python: project's ruff / black config
- Naming follows each project's CLAUDE.md / CONTRIBUTING
  (InnoShop: https://github.com/innocommerce/innoshop)

## Code of Conduct

This project adheres to the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/). Participation implies acceptance of its terms.

## Contact

- Technical questions: open an issue in the relevant repo
- Business: edward@innoshop.com