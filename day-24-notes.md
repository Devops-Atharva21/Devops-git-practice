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
