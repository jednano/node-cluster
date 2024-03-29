# @jedmao/node-cluster

<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
[![GitHub Actions](https://github.com/jedmao/node-cluster/workflows/master/badge.svg)](https://github.com/jedmao/node-cluster/actions)
[![codecov](https://img.shields.io/codecov/c/gh/jedmao/node-cluster?style=flat-square)](https://codecov.io/gh/jedmao/node-cluster)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg?style=flat-square)](http://commitizen.github.io/cz-cli/)
[![XO code style](https://img.shields.io/badge/code_style-XO-5ed9c7.svg?style=flat-square)](https://github.com/xojs/xo)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)
[![types: TypeScript](https://img.shields.io/npm/types/typescript?style=flat-square)](https://typescriptlang.org)
<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- markdownlint-disable commands-show-output -->

Demonstrate using a Node.js cluster

## Scripts

The following [npm scripts](https://docs.npmjs.com/misc/scripts) are made
available to you in the project root. You can run each of them with
`npm run <script-name>`.

### build

Runs the [TypeScript][] compiler.

### test

Runs [Jest][] in [watch mode](https://jestjs.io/docs/en/cli.html#watch), which
attempts to run
[only on changed files](https://jestjs.io/docs/en/cli.html#onlychanged).

### cover

Runs [Jest][] in [coverage mode](https://jestjs.io/docs/en/cli.html#coverage),
dumping coverage results in `./coverage` and showing a text summary in the
console output.

### commit

Runs [Commitizen](http://commitizen.github.io/cz-cli/) commit wizard, ensuring
that your commit messages conform to
[Conventional Commits](https://www.conventionalcommits.org/).

### Tips

Use the [`git commit`](https://git-scm.com/docs/git-commit) command directly
with the
[`-n`, `--no-verify` option](https://git-scm.com/docs/git-commit#Documentation/git-commit.txt--n)
to bypasses the pre-commit and commit-msg hooks.

[jest]: https://jestjs.io/
[typescript]: http://www.typescriptlang.org/
