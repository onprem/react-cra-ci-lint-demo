# React CRA - Lint/CI demo

Demo React application with Linting and CI setup

### What's inside?

- ESLint: It's installed by default with CRA, we are extending it to use the `eslint-config-airbnb`.
- Prettier: An opinionated code formatter. We are using it alongside ESLint to format JS, and also CSS.
- Husky and Lint Staged: `husky` and `lint-staged` are two npm modules we used to install a pre-commit hook in git. The code is automatically formatted before a git commit is created.
- GitHub Actions: A workflow file is added to test every PR and commit to `main` branch for linting errors.


