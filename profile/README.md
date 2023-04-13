# CBIS GitHub Guide:

## Editing a repo:
* When working on a repo, clone it to your local machine.
* When making commits, push commits to dev branch (rather than main).
* Once commits are pushed to dev branch, initiate a pull request to merge commits from dev branch into main branch.

## Do nots:
* Do not Git Push (or make any direct changes) to the 'main' branch of a repo. Commits should be pushed to 'main' using a pull request.
* Do not upload secrets to GitHub. 'Secrets' refers to things like passwords, API keys, private tokens and SSH keys. A .gitignore file can be helpful for this purpose.
* Do not upload data sets or customer files to GitHub.

## Resources:
- GitHub CLI guides: 
  - https://gist.github.com/ccannon94/982d69b23659d66c0ca6fb1384f94c97
  -  https://www.w3schools.com/git/default.asp?remote=github

- GitHub commands glossary: 
  - https://docs.github.com/en/get-started/quickstart/github-glossary
