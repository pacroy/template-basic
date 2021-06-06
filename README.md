# Basic Template

[![Lint Code Base](https://github.com/pacroy/template-basic/actions/workflows/linter.yml/badge.svg)](https://github.com/pacroy/template-basic/actions/workflows/linter.yml)

## Features Included

- GitHub Actions Workflows
  - [linter.yml] - [Superlinter] workflow.

## Usage

1. Click <kbd>Use this template</kbd> to [create a new repository from this template].
2. Review and update [linter.yml] or remove if you don't need it.

- [Create repository secret] `LINTER_VALIDATE_ALL_CODEBASE` and set to `true` if you want superlinter to always scan all code base. Otherwise, set to `false` to scan only those changed.
- Update or remove environment variables in `Lint Code Base` step as you wish. See comments for how to customize each of them.

3. Review and update linter's configurations in [.github/linters] folder

- Customize [.markdown-lint.yml] for markdown linter. See [MarkdownLint Configuration] for more detail.
- Customize [.hadolint.yaml] for dockerfile linter. See [Dockerfile Linter Configuration] for more detail.
- Customize [.jscpd.json] for duplicate code check.

[Superlinter]: <https://github.com/github/super-linter>
[linter.yml]: <.github/workflows/linter.yml>
[create a new repository from this template]: <https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-on-github/creating-a-repository-from-a-template>
[Create repository secret]: <https://docs.github.com/en/actions/reference/encrypted-secrets#creating-encrypted-secrets-for-a-repository>
[.markdown-lint.yml]: <.github/linters/.markdown-lint.yml>
[.hadolint.yaml]: <.github/linters/.hadolint.yaml>
[MarkdownLint Configuration]: <https://github.com/igorshubovych/markdownlint-cli#configuration>
[Dockerfile Linter Configuration]: <https://github.com/hadolint/hadolint#configure>
[.jscpd.json]: <.github/linters/.jscpd.json>
[super-linter/.jscpd.json]: <https://github.com/github/super-linter/blob/master/TEMPLATES/.jscpd.json>
[.github/linters]: <.github/linters>