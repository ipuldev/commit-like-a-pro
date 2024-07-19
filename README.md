# How to Write Commit Messages Like a Pro

Commit messages might not have strict rules, but they are a vital part of collaborative software development. While individual preferences can vary, clear and structured commit messages are essential when working in a team. They help maintain clean, understandable, and maintainable code.

## The Importance of Good Commit Messages

Good commit messages:

1. **Improve Code Readability**: Clear messages make it easier to understand the history of changes in the codebase.
2. **Facilitate Collaboration**: Team members can quickly grasp what changes were made and why.
3. **Aid in Debugging**: When something goes wrong, precise commit messages help trace back to when and why a particular change was made.
4. **Support Code Reviews**: They provide context to reviewers, making the review process smoother and more efficient.

## Examples of Poor Commit Messages

Here are some examples of my previous commit messages that illustrate what to avoid:

- `commit 1`
- `commit 2 update`
- `small update`
- `update create`
- `fix bug`
- `clean nightmare code`
- `delete project HAHAH`

These messages are vague, uninformative, and often humorous inappropriately. They fail to communicate the nature of the changes effectively, which can be problematic for team members trying to understand the code history.

## Adopting Semantic Versioning for Commit Messages

To write better commit messages, we can adopt **semantic versioning (SEMVER)** principles. SEMVER provides a systematic way to craft commit messages, ensuring they are meaningful and structured.

## Semantic Commit Messages

Semantic commit messages follow a specific format: `<type>: <subject>`. Here are the common types used in semantic commits:

1. **feat**: A new feature for the user (e.g., `feat: add user login feature`).
2. **fix**: A bug fix for the user (e.g., `fix: resolve issue with user authentication`).
3. **docs**: Documentation-only changes (e.g., `docs: update README with setup instructions`).
4. **style**: Changes that do not affect the meaning of the code (e.g., white-space, formatting, missing semi-colons) (e.g., `style: format code according to new style guide`).
5. **refactor**: A code change that neither fixes a bug nor adds a feature (e.g., `refactor: improve code structure in user service`).
6. **perf**: A code change that improves performance (e.g., `perf: optimize database queries for user data`).
7. **test**: Adding missing tests or correcting existing tests (e.g., `test: add unit tests for user controller`).
8. **chore**: Changes to the build process or auxiliary tools and libraries such as documentation generation (e.g., `chore: update dependencies to latest version`).

## Example Commit Messages

- `feat: add user registration functionality`
- `fix: correct validation error on user profile update`
- `docs: create API documentation for user endpoints`
- `style: apply consistent indentation across all files`
- `refactor: reorganize user service into separate modules`
- `perf: enhance database indexing for faster queries`
- `test: implement integration tests for user module`
- `chore: configure CI/CD pipeline for automated deployment`

## Best Practices for Writing Commit Messages

1. **Use the imperative mood**: Treat your commit message like a command (e.g., "Add feature" instead of "Added feature").
2. **Be concise but descriptive**: Summarize the change in the subject line, and if needed, provide additional details in the body.
3. **Separate subject from body**: Use a blank line between the subject and body for clarity.
4. **Limit the subject line to 50 characters**: Keep it brief and to the point.
5. **Capitalize the subject line**: Start with a capital letter.
6. **Do not end the subject line with a period**: It's unnecessary and clutters the message.

## Detailed Example

Here's an example of a detailed commit message:

