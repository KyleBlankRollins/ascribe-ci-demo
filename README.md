# ascribe-ci-demo

A demo of [Ascribe](https://github.com/ascribed-dev/ascribe)'s checks in GitHub Actions. The content is a copy of Ascribe's `examples/quill` project, the docs for Quill, a made-up docs-sync tool, and the workflow is the one from Ascribe's "Checks in CI" guide: every pull request runs `ascribe check --deny-warnings --format github` and `ascribe fmt --check --format github`, and each problem shows on the pull request's lines.
