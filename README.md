# KK-67
This is a repo for updating the organizations **public** README.md

# Contributing to organization KK-67

## Naming conventions

We use the following naming conventions:

- FEAT - For developing new feature
- CHANGE - Updating/modifying existing code
- DRAFT - For work in progress code
- DELETE - Removal off code (no additions)

Commit messages need to follow one of these four tags before additional message i. e:
Commit messages also need to be written in present time.

`FEAT: add new component`

## Code reviews

Everytime a member of the group creates a merge request, it needs to reviewed and verified by atleast one person before merging it.
After the PR has been verfiied and accepted, the creator of the PR needs to merge it into the master branch.

Remember to squash commits when merging, since commit messages after dosen't make much sense in the master branch.

## Workflow

Everything that is merged or committed and pushed to `master` goes straight to production (need pipelines here) if all the tests are passing (need GitHub actions configured). Because of that, the preferred workflow is to create a new PR (Pull Request) in GitHub. There you can request a code review from one of your teammates before your contribution is merged to `master`.
