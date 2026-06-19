# Contributing

Thanks for your interest in contributing to the **KODI – Kommunen Digital** open-source
projects. These repositories are reference applications for German municipal ("Kommune")
digital services, maintained by the *Kodi-Entwicklergemeinschaft* developer community.

## Ground rules

- **Be respectful.** All interaction is governed by our [Code of Conduct](CODE_OF_CONDUCT.md).
- **One change, one purpose.** Keep pull requests focused — a single feature or fix.
- **Discuss big changes first.** Open an issue before starting substantial work so we can
  align on approach.

## Workflow

1. **Fork** the repository and create a branch from `main`
   (e.g. `feature/short-description` or `fix/short-description`).
2. Make your change. Match the existing code style of the repository.
3. Test locally — make sure the project builds/runs.
4. **Open a pull request** against `main`. Fill in the PR template.
5. A maintainer reviews. `main` is protected: every change lands via reviewed PR —
   direct pushes, force-pushes and branch deletion are blocked.

## Pull request checklist

- [ ] Branched from the latest `main`
- [ ] Scoped to a single concern
- [ ] No secrets, credentials, real tenant data, or `.env` files committed
- [ ] Builds / runs locally
- [ ] PR description explains **what** and **why**

## Security

Never open a public issue for a security vulnerability. See [SECURITY.md](SECURITY.md)
for private reporting.

## Licensing

Unless a repository states otherwise, contributions are accepted under that repository's
license (most are **EUPL-1.2**). By submitting a pull request you agree your contribution
is licensed under the same terms.
