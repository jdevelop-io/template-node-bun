# Template Node

[![Build Workflow](https://github.com/jdevelop-io/template-node/actions/workflows/build.yml/badge.svg)](https://github.com/jdevelop-io/template-node/actions/workflows/build.yml)
[![License](https://img.shields.io/github/license/jdevelop-io/template-node)](/LICENSE)
[![WakaTime](https://wakatime.com/badge/user/b5dd94a4-c0ea-4c12-9cb2-41f984e74fdc/project/e774c158-4cbd-4a4e-a265-1c08e6e84c3d.svg)](https://wakatime.com/badge/user/b5dd94a4-c0ea-4c12-9cb2-41f984e74fdc/project/e774c158-4cbd-4a4e-a265-1c08e6e84c3d)

**Template Node** is a Node.js project scaffolding tool designed to speed up the initial setup of Node.js applications.
This repository provides a solid foundation for building scalable and maintainable Node.js projects, with built-in best practices and commonly used configurations.

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

### Project Structure

```plaintext
template-node
├── .github
│   └── workflows
│       └── build.yml
├── node_modules
├── LICENSE
├── README.md
├── bun.lockb
└── package.json
```

### Contributing

Contributions are welcome! If you have any ideas, suggestions, or issues, feel free to open an issue or submit a pull request.

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
