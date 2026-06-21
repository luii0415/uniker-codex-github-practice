# Codex GitHub workflow

Use this checklist when asking Codex to work with GitHub.

## Start safely

Ask Codex:

```text
Check the current Git status first.
Do not edit files yet.
Tell me the current branch, remote, changed files, and safest next action.
```

## Commit

Ask Codex:

```text
Review the changed files.
If the changes are safe, stage them and create one commit with a short message.
Show me the commit hash afterward.
```

## Push

Ask Codex:

```text
Push this branch to GitHub.
If there is no upstream branch, set the upstream branch.
Then show me the GitHub branch URL.
```

## Pull

Ask Codex:

```text
Pull the latest main branch safely.
Use fast-forward only if possible.
If there is a conflict, stop and explain the conflicting files first.
```

## Merge

Ask Codex:

```text
Create a pull request from this feature branch into main.
Summarize what changed, then merge it only after the PR is clean.
```

