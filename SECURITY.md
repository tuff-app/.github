# Security

This covers every tuff-app repository: the app, the sandbox, the Homebrew tap
and the website.

Please don't open a public issue for a security problem. Report it privately
through GitHub's vulnerability reporting on the repository it affects:

- [TUFF](https://github.com/tuff-app/TUFF/security/advisories/new), the app,
  engines, local server, downloads and updates. Use this one if you're not sure.
- [sandbox](https://github.com/tuff-app/sandbox/security/advisories/new), the
  VM that runs web and file search.
- [homebrew-tap](https://github.com/tuff-app/homebrew-tap/security/advisories/new)
- [tuff-app.github.io](https://github.com/tuff-app/tuff-app.github.io/security/advisories/new)

Tell me what's affected (version or commit), how to reproduce it, and what
an attacker could do. Leave out personal data, keys and model weights.

The most useful reports involve model files or downloads that aren't
validated properly, path traversal, unsafe offsets, web search reaching
places it shouldn't, a way out of the sandbox, leaked API keys, or the local
server being reachable from outside your Mac. Wrong answers, high memory use
and slow models aren't security issues on their own.

Fixes go into the latest release. TUFF is a personal project, not built for
multi-user or security-critical use. Give me a chance to ship a fix before
publishing details; I'm happy to credit you in the advisory. The
[maintainers](MAINTAINERS.md) can also see private reports and help fix them.
