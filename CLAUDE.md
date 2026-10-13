# CLAUDE.md

## Git identity (mandatory)

Every commit pushed to this repository must be authored and committed as **jnanottamgy**:

- `user.name`: `jnanottamgy`
- `user.email`: `192404215+jnanottamgy@users.noreply.github.com`

A SessionStart hook in `.claude/settings.json` sets this as the repo-local git config. Before committing, confirm it with `git var GIT_AUTHOR_IDENT`; if it shows anything else, run:

```sh
git config user.name "jnanottamgy"
git config user.email "192404215+jnanottamgy@users.noreply.github.com"
```

Never commit or push under any other name or email.

## No AI attribution

Do not add `Co-Authored-By: Claude`, `Claude-Session`, "Generated with Claude Code", or any other AI attribution lines to commit messages or pull request descriptions. Commits are credited to jnanottamgy alone.
