# Maintainers

TUFF is my project and I make the final call on what goes in. People who've
made substantial contributions can become maintainers and help run it. These
roles cover every tuff-app repository, and they're adapted from
[Homebrew's](https://docs.brew.sh/New-Maintainer-Checklist)
[governance](https://docs.brew.sh/Homebrew-Governance), cut down for a much
smaller project.

## Current maintainers

| Name | GitHub | Role |
| --- | --- | --- |
| Rex Hall | [@rexmhall09](https://github.com/rexmhall09) | Owner |
| Alexander Weinstock | [@Osiriss664](https://github.com/Osiriss664) | Junior maintainer |

## Roles

### Owner

Has the final say. Owns the [tuff-app](https://github.com/tuff-app)
organization and is the only one who merges, tags and releases: app updates,
sandbox images, the Homebrew cask and published security advisories.

### Maintainer

Everything the owner does except merging and releasing.

- **Review pull requests first.** Say what you checked and how: what you read,
  what you ran and on which Mac. "Looks good" isn't a review. Approve only if
  you'd be happy for me to merge it as it is.
- **Push fixes to pull request branches** and work on branches in the
  repositories.
- **Triage issues, pull requests and discussions.** Reproduce bugs, ask for
  missing details, label, and close duplicates.
- **Handle private security reports** with me: triage them, draft the
  advisory and prepare the fix.

GitHub access: write access to every repository, and the organization's
security manager role. Rules on each repository stop anyone but me from
merging into `main` or creating tags, and publishing workflows wait for my
approval.

### Junior maintainer

A first step toward maintainer, for people who've contributed substantially.

- **Review pull requests,** as above.
- **Triage issues, pull requests and discussions.**
- **See private security reports** and help with the ones I ask about.

GitHub access: triage access to every repository and the organization's
security manager role. You can label, assign, close and reopen issues and pull
requests, and see every advisory and security alert. You can't push to the
repositories, merge, tag, release or run workflows; your own changes go
through pull requests from a fork, like everyone else's.

This role is meant to be temporary. In the long run I expect people to be
either a maintainer or not.

### Contributors

Everyone else. See the [contributing guide](CONTRIBUTING.md).

## Private reports

Anyone who can see private reports:

- Keeps the details private until a release ships the fix.
- Doesn't paste report details into AI tools that keep or train on your data.
- Doesn't give AI agents or other automation unattended access to private
  reports.

## Becoming a junior maintainer

I look for people who:

- have contributed substantially to TUFF, with consistently high-quality work
- have made changes beyond small, routine ones
- want to spend their TUFF time reviewing pull requests first, then triaging
  and fixing reported issues, then on their own pull requests

There's no form. I may ask you, or you can ask me in
[Discussions](https://github.com/tuff-app/TUFF/discussions).

Before you get any access:

1. Turn on [two-factor authentication](https://docs.github.com/en/authentication/securing-your-account-with-two-factor-authentication-2fa)
   for your GitHub account. The organization requires it.
2. Don't use SMS as a 2FA method or as a fallback. Use an authenticator app,
   a passkey or a security key.
3. Review your GitHub personal access tokens and delete the ones you don't
   need. Keep doing that.
4. Read this file, the [contributing guide](CONTRIBUTING.md) (including
   [AI tools](CONTRIBUTING.md#ai-tools)), the [security policy](SECURITY.md)
   and the [code of conduct](CODE_OF_CONDUCT.md).
5. Agree to be listed here under your real name.

Then accept the organization invite. New maintainers are mentioned in the
release notes.

## Becoming a maintainer

Junior maintainers become maintainers after more contributions and a
verification call with me.

## AI tools

The [same rules](CONTRIBUTING.md#ai-tools) apply to maintainers, and
maintainers are held to them more strictly. Coding with AI is fine, but you
read 100% of the code yourself, including in pull requests you review. Every
comment you write, including reviews, issue and discussion replies and
comments in the code, is written by you without AI.

## Ask when you're unsure

If you're not sure whether something is safe to do or say, especially about
a private report, ask me first.

## Stepping down

There's no activity requirement. You can step down any time, and you're
always welcome back. I'll remove access for anyone who breaks the
[code of conduct](CODE_OF_CONDUCT.md) or the private report rules above.
Access goes when the role does.
