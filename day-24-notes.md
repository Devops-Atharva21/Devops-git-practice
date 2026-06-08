***What is a Fast-Forward Merge?

A fast-forward merge occurs when the target branch has no new commits since the feature branch was created. Git simply moves the branch pointer forward.

Example
main
  \
   feature-login

After merge:

main -> latest commit
***When Does Git Create a Merge Commit?

Git creates a merge commit when both branches contain unique commits and histories have diverged.

***What is a Merge Conflict?

A merge conflict occurs when Git cannot automatically decide which change to keep, usually when the same line is modified in multiple branches.

***What Does Rebase Actually Do?

Rebase takes your branch commits and replays them on top of another branch.

**How Is History Different From Merge?

Merge
A---B---C
     \   \
      D---E

Creates:

A---B---C-----M
     \     /
      D---E
Rebase
A---B---C---D'---E'

Linear history.

***Why Never Rebase Shared Commits?

Rebase rewrites commit history. If others already pulled those commits, rebasing creates different commit IDs and causes confusion.

***When To Use Rebase vs Merge?

*** Rebase
Clean history
Before creating PR
Local feature branches

***Merge
Preserve complete history
Shared branches
Team collaboration

***What Does Squash Merge Do?

Combines multiple commits into a single commit before merging.

***When Would You Use Squash Merge?
Cleanup noisy commit history
Small features
Pull Requests

***When Would You Use Regular Merge?
Preserve development history
Team collaboration
Auditing changes
Trade-Off of Squashing

**Advantage

Cleaner history.

**Disadvantage

Individual commit history is lost.
