## Goal

<!-- TL;DR first, for every reviewer: one line each; the detail goes below. -->

- **Goal:** <!-- what this pull request achieves, in one sentence -->
- **Why:** <!-- the problem, finding or ticket it answers -->
- **Done when:** <!-- the observable result that shows it worked -->

## What changes

<!-- The files or components touched, and anything a reviewer should look at first. Link the JIRA ticket. -->

JIRA:

## Checklist

- [ ] The repository's formatter, linter and tests pass for what I touched, with no new warnings and no suppressions.
- [ ] A test fails without my change: for a defect, I checked that the test catches it, not only that the suite is green.
- [ ] Documentation is part of the change: a new or changed command, flag, setting, endpoint or behaviour is described
      where this repository documents it (README, book), in this pull request.

## If this pull request syncs two branches

A sync or forward-merge, anything whose purpose is that two long-lived branches (`development` and a `release/vX.Y.Z`
line) now agree, is merged with **Create a merge commit**: not Squash, and not Rebase. Squashing gets the files right
and the history wrong, and git reads only the history: the merge-base does not move, and the next sync conflicts again.

- [ ] If this is a sync or forward-merge, I will use a true merge.
