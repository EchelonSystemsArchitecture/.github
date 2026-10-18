# Contributing to Echelon projects

These guidelines apply to every repository in the organization that does not have its own `CONTRIBUTING.md`.

## Workflow

1. **Branch** from `main`: `feature/<short-name>`, `fix/<short-name>` or `docs/<short-name>`.
2. **Commit** in small steps with messages that say *what changed and why*.
3. **Open a pull request** early. Describe the change, how you tested it, and anything you are unsure about.
4. **One teammate reviews** before merging. Do not merge your own pull request unless the repository says otherwise.
5. **Squash or rebase** to keep `main` readable. Never force-push `main`.

## Quality

- Run the project's tests before asking for review. If there are no tests for the code you changed, add one.
- A bug fix should come with a test that fails without the fix.
- Report results honestly: what you measured, on what data, with what limits. Null and negative results are results.
- Keep generated files, large binaries and datasets out of git unless the repository is meant to hold them.

## Security and privacy

- Never commit secrets (API keys, tokens, passwords) or personal data. If you do, tell an owner immediately so the
  secret can be rotated; deleting it in a later commit is not enough.
- Private repositories stay private. Do not paste their contents into public places.
- Check licences before copying code from elsewhere, and record where it came from.

## Issues

Use the issue templates. Describe the problem or idea, what you expected, and what happened. For anything large,
open an issue and agree on the approach before writing code.

## Getting added or listed

Organization owners manage membership and access. To be listed on the organization page, edit the contributors table
in `profile/README.md` of the `.github` repository in a pull request.
