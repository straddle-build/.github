# Straddle Build community files

This repository maintains the [Straddle Build organization profile](https://github.com/straddle-build) and shared contribution and security guidance for its developer tools.

## Find the file to update

Each file serves a specific purpose.

| File | Purpose |
| --- | --- |
| [profile/README.md](profile/README.md) | Public organization landing page with links to the Wizard, skills, CLI, and SDKs |
| [CONTRIBUTING.md](CONTRIBUTING.md) | Shared contribution and review process |
| [SECURITY.md](SECURITY.md) | Private vulnerability reporting instructions |
| [PULL_REQUEST_TEMPLATE.md](PULL_REQUEST_TEMPLATE.md) | Shared prompts for proposed changes and verification |
| [.github/ISSUE_TEMPLATE/config.yml](.github/ISSUE_TEMPLATE/config.yml) | Links shown when opening an issue |

GitHub uses supported community files from this repository as defaults when a repository has no corresponding file of its own. See [GitHub's community file guidance](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file) for the inheritance rules.

## Review a change

Follow these steps before submitting documentation changes:

1. Check product names, package names, and commands against the owning repository and its published release.
2. Verify relative links from the file's directory and open each external destination.
3. Read the rendered Markdown, including the organization profile, for clear headings and usable code examples.
4. Follow the [contribution process](CONTRIBUTING.md) and include the checks you ran.

Keep installation and API details in the owning tool or SDK repository. The organization profile helps readers choose a starting point and links to those instructions.
