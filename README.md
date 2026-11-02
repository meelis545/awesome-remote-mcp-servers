# qqq-automation

This branch is the fork's default branch and holds only automation. Once a day
it checks the listing PR jaw9c/awesome-remote-mcp-servers#1411 (head branch `add-qqq-ai-visibility`). If
GitHub reports a merge conflict, it rebuilds that branch on the upstream default
branch with only the QQQ entry added again and force-pushes it.

The fork's `main` mirrors upstream and is not used. Run by hand: Actions →
"Keep QQQ listing PR mergeable" → Run workflow.
