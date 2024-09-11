# Contributing to AWS EC2 Group Module

Thank you for considering contributing to this project! We welcome contributions from the community and aim to make it as easy as possible to get involved.

## Code of Conduct

This project adheres to the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [security@asyrafnorafandi.dev](mailto:security@asyrafnorafandi.dev).

## Reporting Issues

If you encounter a bug, performance issue, or have a question, please check our [issue tracker](https://github.com/asyrafnorafandi/terraform-aws-ec2-group/issues) and ensure the issue has not been reported already. If it hasn't, feel free to [open a new issue](.github/ISSUE_TEMPLATE/bug_report.md).

## How to Contribute

1. **Fork the repository** and create your branch from `main`.
2. **Write clear and concise code** that follows our [style guide](STYLE_GUIDE.md).
3. **Test your changes** to ensure the module behaves as expected.
4. **Create a pull request** following the template provided.
   - Include a clear description of what the PR changes.
   - Reference the issue number your PR is related to (if applicable).
   - Ensure that your changes follow the [Coding Guidelines](#coding-guidelines).
5. **Wait for reviews** and address any feedback.

## Submitting Pull Requests

All pull requests should:

- Be based on the latest `main` branch.
- Include tests for the proposed changes.
- Pass all checks (linting, testing).
- Provide a detailed description of the change and its impact.

## Coding Guidelines

To ensure consistency across the codebase, please adhere to the following standards:

- **Code Formatting:** You can run the following command to format your code:

  ```bash
  terraform fmt
  ```

- **Commit Messages:** Follow [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) for commit messages. For example:
  - `fix: resolve navbar alignment issue`
  - `feat: add user authentication`

---

## Testing

Please make sure all tests pass before submitting a PR. If you add new functionality, include corresponding unit/integration tests.

- **Run Tests:**

  ```bash
  terraform init
  terraform test
  ```

- **End-to-End Testing:** If applicable, ensure your changes work across various environments by adding E2E tests.

---

Thank you for contributing!
