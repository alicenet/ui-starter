# UI Starter

Below you'll find tooling for starting up a repo. We've included some examples of what we use through out Alicenet projects.

# Formatting

-   Prettier (https://prettier.io/)
-   Husky (https://typicode.github.io/husky)

# Linting

-   ESLint (https://eslint.org/docs/latest/)
-   lint-staged (https://github.com/okonet/lint-staged)
-   commitLint (https://commitlint.js.org/#/)

# Prettier

See the `.prettierrc` file for details.

# Husky

See the `.husky` directory for details

## commit-msg

This script checks commit messages using (commitLint)[https://commitlint.js.org/#/] to check against formatting found (here)[https://github.com/conventional-changelog/commitlint/#what-is-commitlint]

## pre-commit

This script runs `lint-staged` commands found in `.lintstagedrc.json` file. Currently runs:

-   Prettier
-   ESLint

# ESLint

Linter is used by husky to check files before committing.

# lint-staged

Used to run commands when committing. See Husky section for details.

# commitLint

Used to check commit messages against formatting found (here)[https://github.com/conventional-changelog/commitlint/#what-is-commitlint].
