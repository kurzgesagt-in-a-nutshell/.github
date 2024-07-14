# Contributor Guidelines
<sub><b>In certain cases we may deny a PR that does not follow these guidelines.</b></sub>

Thank you for considering contributing to the Kurzgesagt discord bot! We appreciate your interest in helping make our bot better. To ensure a smooth collaboration, please read and follow these guidelines.

## Getting Started

1. **Fork the Repository:** Start by forking our repository on GitHub. You'll be working on your own fork, and you can later submit pull requests to contribute your changes.

2. **Clone Your Fork:** Clone your forked repository to your local development environment.

3. **Join Our Discord Server:** Join our Discord server to discuss ideas, ask questions, and get feedback from the community. [Click Here](https://discord.gg/kurzgesagt) to join the server.

## Licensing

By contributing to our project, you agree that your code will be licensed under the same license as the project itself (usually specified in the project's `LICENSE` file).

---
## Code & Formatting Standards

- Use dedicated, well-named variables and functions so the purpose is clearly discernible. 
- Use doc-strings in each file, class and function to detail the purpose of the code.
- For complex logic, use comments to allow a reviewer or future dev to easily understand what the code does.
- We use `black` and `isort` to enforce formatting standards.

If a function that contains a doc-string or comments is edited, make sure they are updated to correctly describe the code.

## Branch Etiquette

Our repositories will consist of two everlasting branches: `master` (or `main`) and `staging`. 

General Rules of Thumb

1. Keep your branch up to date with master and staging.
2. Before approving a pull request make sure the incoming branch is not behind the base branch.
3. Rebase Rebase Rebase.
4. It is your job to deal with conflicts on your branch.

Branch out from staging into the appropriate naming scheme. If your branch is a new feature name it `feature/feature-name`, and if your branch is a bugfix name it `bugfix/issue-####`.

Do your work. Often times this can consist over a longer period. In this time, changes could have been made to staging. To avoid conflicts with your branch, it is recommended to `git fetch` often and keep your branch up to date with our base branches.

Once you are finished with the work on your branch and ready to merge, again clarify that your branch is caught up with staging. You will push your branch to the remote repository to then create a pull request into staging. 

#### Hotfixes
Hotfixes are limited to major security issues and critical bugs. These will be primarily worked on by our BirdBot Devs. Hotfixes ignore the staging process and branch off of and right back into master. They are named in the scheme of `hotfix/issue-####` or `hotfix/name`

#### Releases

Once a release milestone is met, a version branch is made off of staging for testing and final touchups. No new features are implemented in this phase. 

Once all changes are ready for production, the release branch is merged into staging and master.

---

This workflow is intended to minimize the number of conflicts that arise in development allowing us to focus more on improving the code. In the case of a conflict, the dev working on the branch should have a better understanding of the code changed and be better equipped to respond to the conflict.

---

## Issues

We use issues to keep track of our development and allow a smoother process. 

- Create an issue for each feature/bug/enhancement you are working on. This will help avoid unnecessary effort in the case another dev is already working on the same issue.
- Use appropriate tags to allow for easy filtering of issues.
- Provide as much information in an issue to allow for another dev to pick it up in case it goes stale.

## Pull Requests

- Use clear and descriptive titles.
- Include a detailed description of changes in the PR. Mention any related GitHub issues if applicable.
- Ensure that your code passes all tests and doesn't introduce any new issues.
- Be responsive to feedback.

## Conclusion

We greatly appreciate your interest and contributions to the Kurzgesagt Community. If you have any questions or need assistance, don't hesitate to reach out on our [Discord server](https://discord.gg/kurzgesagt) or by opening an issue on GitHub.

Happy coding! 🦆