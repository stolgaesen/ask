# Contributing to ask

First off, thank you for considering contributing to `ask`! It's people like you that make open source such a great tool for the developer community.

## How Can I Contribute?

### Reporting Bugs
If you find a bug, please open an issue on GitHub. Before creating a new issue, please check if the bug has already been reported. When reporting a bug, include:
* A clear and descriptive title.
* Steps to reproduce the problem.
* Expected vs. actual behavior.

### Suggesting Enhancements
We welcome new ideas! If you have a suggestion for a new feature or an improvement:
1. Open an issue to discuss the idea.
2. Explain why this enhancement would be useful.

### Pull Requests
If you want to contribute code directly:
1. Fork the repository.
2. Create a new branch for your feature or fix (`git checkout -b feature/your-feature-name`).
3. Make your changes.
4. Ensure your code follows the project's style (simple Bash scripting).
5. Commit your changes with meaningful messages.
6. Push to your branch and open a Pull Request.

## Coding Standards
Since this is a lightweight Bash tool, please keep the following in mind:
* Use only `curl` and `jq` as external dependencies.
* Ensure the script handles environment variables (`ASK_API_URL`, `ASK_MODEL`, `ASK_API_KEY`) correctly.
* Maintain the concise output format required by the system prompt.

## License
By contributing to this project, you agree that your contributions will be licensed under the **MIT License**.