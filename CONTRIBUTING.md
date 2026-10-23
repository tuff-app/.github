# Contributing to TUFF

Thanks for helping! TUFF is a small project, so a bug report, a docs fix or a
benchmark from your Mac genuinely makes a difference. You don't need to know
Swift or Metal, and most useful work needs no model download.

This guide covers every tuff-app repository. Some repositories add their own
notes: [TUFF's CONTRIBUTING.md](https://github.com/tuff-app/TUFF/blob/main/CONTRIBUTING.md)
covers building and testing the app, and each README says what's in it.

## Easy ways to help

- **Benchmark your Mac.** Open Benchmarks in TUFF, run it, and share. I only
  have a 16 GB M2, so every other Mac helps. See
  [benchmarks](https://github.com/tuff-app/TUFF/blob/main/docs/BENCHMARKS.md).
- **Report a bug.** In the app, **Help > Report a Bug** fills in your version,
  Mac and model.
- **Fix something that bugged you,** or pick up a
  [good first issue](https://github.com/issues?q=org%3Atuff-app%20is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22).
- **Ask or suggest** in [Discussions](https://github.com/tuff-app/TUFF/discussions).

The [roadmap](https://github.com/tuff-app/TUFF/blob/main/docs/ROADMAP.md) has
the bigger open problems.

## Pull requests

1. Fork, branch, and make your change.
2. Open a pull request. Drafts are welcome, and for anything big open one
   early so we can agree on the approach first.
3. GitHub runs the checks. Your first PR may wait for me to start them.
4. A [maintainer](MAINTAINERS.md) may review it first. I merge it, or explain
   what needs to change.

You don't need an issue or permission for small fixes. If you're taking an
existing issue, leave a quick comment so two people don't do the same work.
Significant contributions are mentioned in the release notes.

## AI tools

Use whatever you like: Claude, Codex, or nothing. I use AI on TUFF too. Just
stand behind your PR:

- Read the code you're changing, and check your agent's explanation against it.
- Review every line yourself. Remove anything you can't explain.
- Report real test output. "The agent said it passed" isn't evidence, and
  saying you couldn't test something is completely fine.
- Answer review questions yourself.

## The fine print

Keep credentials, private chats and model weights out of PRs and
screenshots. Contributions are licensed under
[Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0). Please follow the
[code of conduct](CODE_OF_CONDUCT.md). Security problems go to
[private reporting](SECURITY.md), not public issues.
