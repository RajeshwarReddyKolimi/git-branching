# Git branching and rebasing

## Steps followed

- Created a new repository.
- Renamed master branch to main branch
- Added project.txt file.
- Staged and committed.
- Created 2 branches featureA, featureB.
- Checked to featureA, made some changes to project.txt, staged and committed.
- Checked to featureB, made some other changes to project.txt, staged and committed.
- Now navigated back to featureA, rebased featureB by `git rebase featureB`.
- There are conflicts and resolved them using git status and mergetool.
- Deleted featureB.