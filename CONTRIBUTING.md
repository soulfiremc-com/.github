# Contributing to SoulFire projects

Contributions can include bug fixes, documentation, tests, examples, and features.
Each repository's README and contribution guide explain its build and validation workflow.

## Choose the right repository

Use the [project directory](SUPPORT.md#project-directory) to find the repository that owns your change.
Search its open and closed issues before opening a report.
Use its issue forms for reproducible bugs, feature proposals, and documentation corrections.
Small fixes can go directly to a pull request. Discuss substantial API or architectural changes before implementation.
For usage questions, ask in the [Discord community](https://soulfiremc.com/discord).
For vulnerabilities, use the private contacts in [SECURITY.md](SECURITY.md).
Follow the [code of conduct](CODE_OF_CONDUCT.md).

## Prepare and verify a change

Read the repository's local instructions and use its pinned tools and lockfiles.
Use its existing formatting, naming, and generated-file conventions.
Keep the change focused on one problem. Avoid unrelated dependency updates or broad refactors.
Add targeted tests for changed logic where practical. Test outcomes rather than source text or documentation strings.
Update relevant examples and documentation with behavior changes.
Remove obsolete code rather than leaving placeholders or shims.
Run the repository's documented checks before submission.

Use bots only on servers that you own or have permission to test.
Remove credentials, API tokens, account data, and proxy keys from evidence.
Respect license notices and submit only material that you have the right to contribute.

## Submit and review

Use [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) for commits and pull request titles.
Use a meaningful scope, imperative wording, and a subject under 72 characters.
For non-trivial changes, add a body that explains the motivation and important tradeoffs.
For breaking changes, include a `BREAKING CHANGE:` footer and migration steps.
Do not bypass Git hooks. Let configured checks finish.

Complete the pull request template with the problem, resulting behavior, affected components, and a related issue if one exists.
Use `Closes #123` only if the change fully resolves that issue.
Include exact validation commands, results, and any checks that you could not run.
For visible changes, include screenshots with the relevant version and environment.
Open a draft for early feedback on substantial work.
Respond to review comments and rerun affected checks after revisions.
Maintainers decide whether a change fits the project and is ready to merge after CI passes.

## Maintain these shared files

Edit the common policy or form here for an organization-wide change.
For project-specific commands and fields, edit the owning repository's local files.
Keep the public profile's links aligned with the project directory in SUPPORT.md.

Before submission, verify local links and parse changed YAML.
Check that form field IDs are unique and descriptions explain the information a reporter needs to provide.
Avoid default labels unless the label exists in every repository that inherits the form.
Preview changed Markdown and review the forms against [GitHub's form schema](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/syntax-for-githubs-form-schema).
