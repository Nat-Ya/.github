# Definition of Done

A micro-task PR is done (ready for **human merge**) when:

1. All acceptance criteria are met and ticked in the PR.
2. Tests were written first; suite, lint, format and typecheck pass locally and in CI (commands verified in repo config).
3. Coverage on touched modules did not decrease.
4. Code reads clean: intention-revealing names, small functions, no dead code, no swallowed errors, comments only for a non-obvious *why*.
5. Scope respected: no drive-by changes; cleanup is a separate `refactor:`/`style:` commit.
6. Conventional Commits; PR body has `Closes #n`, test evidence, risks.
7. No secrets; no CI/dependency/infra change unless the task said so.
8. Docs touched when behavior changed (README / ADR / changelog entry by the Lead).
9. Lead verdict: `LGTM — ready for human merge` (`status:approved`).
