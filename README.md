# Template Node

[![Build Workflow](https://github.com/jdevelop-io/template-node/actions/workflows/build.yml/badge.svg)](https://github.com/jdevelop-io/template-node/actions/workflows/build.yml)
[![Tests Workflow](https://github.com/jdevelop-io/template-node/actions/workflows/tests.yml/badge.svg)](https://github.com/jdevelop-io/template-node/actions/workflows/tests.yml)
[![License](https://img.shields.io/github/license/jdevelop-io/template-node)](/LICENSE)
[![WakaTime](https://wakatime.com/badge/user/b5dd94a4-c0ea-4c12-9cb2-41f984e74fdc/project/e774c158-4cbd-4a4e-a265-1c08e6e84c3d.svg)](https://wakatime.com/badge/user/b5dd94a4-c0ea-4c12-9cb2-41f984e74fdc/project/e774c158-4cbd-4a4e-a265-1c08e6e84c3d)

**Template Node** is a Node.js project scaffolding tool designed to speed up the initial setup of Node.js applications.
This repository provides a solid foundation for building scalable and maintainable Node.js projects, with built-in best practices and commonly used configurations.

## Features

- **TypeScript**: Use TypeScript for a better development experience and improved code quality.
- **ESLint**: Lint your code with ESLint to maintain consistent coding standards.
- **Prettier**: Format your code with Prettier to keep it clean and consistent.
- **Jest**: Test your code with Jest to ensure its correctness and reliability.
- **Husky**: Use Husky to run tasks on Git hooks and enforce code quality.
- **Lint-Staged**: Run ESLint and Prettier on staged files to catch errors before committing.
- **Commitlint**: Enforce conventional commit messages to keep your commit history clean and organized.
- **GitHub Actions**: Use GitHub Actions for continuous integration and automated testing.

## Getting Started

### Prerequisites

Make sure you have Node.js and Bun installed on your machine before running the project.

- [Node.js](https://nodejs.org/) (v22.5.1 or later)
- [Bun](https://bun.js.org/) (v1.1.17 or later)

### Installation

1. Clone the repository:

   ```bash
   git clone --depth 1 https://github.com/jdevelop-io/template-node.git
   cd template-node
   ```

2. Remove the `.git` directory to start with a clean git history:

   ```bash
   rm -rf .git
   ```

3. Initialize a new git repository:

   ```bash
   git init
   ```

4. Install the dependencies:
   ```bash
   bun install
   ```

### Scripts

- `bun run build` : Build the project.
- `bun run test` : Run the tests.
- `bun run test:watch` : Run the tests in watch mode.
- `bun run test:coverage` : Run the tests with coverage.
- `bun run test:coverage:watch`: Run the tests with coverage in watch mode.
- `bun run lint` : Lint the code and fix linting errors.
- `bun run lint:check` : Check the code for linting errors.
- `bun run format` : Format the code and fix formatting errors.
- `bun run format:check` : Check the code for formatting errors.

### Project Structure

```plaintext
template-node
├── .github
│   ├── workflows
│   │   ├── build.yml
│   │   └── tests.yml
├── node_modules
├── coverage
├── build
├── src
├── README.md
├── LICENSE
├── commitlint.config.mjs
├── eslint.config.mjs
├── jest.config.ts
├── lint-staged.config.mjs
├── prettier.config.mjs
├── tsconfig.json
├── bun.lockb
└── package.json
```

### Contributing

Contributions are welcome! If you have any ideas, suggestions, or issues, feel free to open an issue or submit a pull request.

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
