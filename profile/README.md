# CBIS GitHub Guide:

## Introduction:
-GitHub is software meant for version control when doing collaborative work. It is built on top of software called Git.

-Repositories (repos) are directories of files included in a codebase. 

-GitHub can be used both through the browser and through the command line interface (CLI). 

-The browser is easiest if you only want to perform basic operations, such as downloading a repo.

## Downloading files through a browser:
-Data files and scripts can be be downloaded directly from a repo but in 'raw' format, which is not practically helpful if the raw format is ugly.

-For this reason, downloading an entire repo can sometimes be the easiest way to access files on GitHub.

-To do this, click on the home page of a repo, then click on the green drop down button labeled 'Code' and select 'Download ZIP'. This will download the repo as a ZIP file.

## Editing a repo:
-When working on a repo, clone it to your local machine.

-When making commits, push commits to dev branch (rather than main).

-Once commits are pushed to dev branch, initiate a pull request to merge commits from dev branch into main branch.

## Do nots:
-Do not Git Push (or make any direct changes) to the 'main' branch of a repo. Commits should be pushed to 'main' using a pull request.

-Do not upload secrets to GitHub. 'Secrets' refers to things like passwords, API keys, private tokens and SSH keys. A .gitignore file can be helpful for this purpose.

-Do not upload data sets or customer files to GitHub.

## Glossary:
Branch--A branch is a parallel version of a repository. Allows you to work freely without disrupting the "live" version of a repo. When you've made the changes you want to make, you can merge your branch back into the main branch to publish your changes.

Clone--A clone is a local branch of a repository. This allows for code to be available offline while also being able to push commits when online.

Commit--An individual change to a file or set of files.

Fetch--'git fetch' updates your local working branch from the remote repository but allows you to review changes before accepting them.

Fork--A personal copy of another user's repo that lives on your account. Common way to mess around with popular, open-sourced software.

Hook--A function that allows you to tap in to a module to either provide different behavior or to react when something happens. There are several types of hooks. A 'webhook' provides a way for notifications to be delivered to an external server, for example.

Merge--Applies changes from one branch into another. Commonly achieved with a git pull.

Pull--Refers to fetching changes and merging them.

Pull Request--Proposed changes to a repo that can be accepted or rejected by a repo's collaborators.

Push--Send your committed changes to a remote repo on GitHub. 

README--Markdown document used to explain a repo. Include as much information about the repo and how to use it as possible.

Repository--A project folder.

Revert--A pull request to undo a previous pull request.

Stage--Before a commit is added to a repo, it is 'staged' first to allow the committer to review the change.

## Resources:
-GitHub CLI guides: 

-- https://gist.github.com/ccannon94/982d69b23659d66c0ca6fb1384f94c97

-- https://www.w3schools.com/git/default.asp?remote=github

-GitHub glossary: 

-- https://docs.github.com/en/get-started/quickstart/github-glossary
