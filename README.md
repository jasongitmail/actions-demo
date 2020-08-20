# Github Actions subset demo

A demo [to auto-generate Inter font subsets](https://github.com/rsms/inter/issues/108#issuecomment-676699304) using Github Actions.

On a git push to master branch, or a merged pull request, Github Actions CI will
automatically run `.github/workflows/subset.yml` and commit changes back to the
repo. This demo adds a new line to date.txt and commits it to the repo.
