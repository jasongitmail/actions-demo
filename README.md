# Github Actions subset demo

A demo for <https://github.com/rsms/inter/> to auto-generate subsets.

On a git push to master branch, or a merged pull request, Github Actions CI will
automatically run `.github/workflows/subset.yml` and commit changes back to the
repo. This demo adds a new line to date.txt and commits it to the repo.
