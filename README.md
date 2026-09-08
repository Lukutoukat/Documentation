# Fall 2026 Team

## Working Principles

### Dailies

- Daily meetings in Discord voice chat
- Monday, Wednesday, Friday at 12:00
- One SCRUM master

### In-person Meetings

- Tuesday 14:00 -> 17:00 in Luola 
- With the customer every 2nd Thursday at 16:00 (starting at 17.9)

### Sprints

- In GitHub project
- 2 weeks, (Sprint 0) 31.8 -> 16.9, (Sprint 1) 17.9 -> 1.10 ...

### Pushing to main
- All changes must be pushed to main no later than Wednesday at 5:00 PM before the customer meeting.

### Branching

There are two main branches:

**dev** (staging)
- Development branch used for active feature development
- All new features are developed against this branch
- This branch is deployed into our `staging` environment on the k8s cluster
- Lint and tests must pass on PRs before merging back into dev

**main** (production)
- The primary production branch
- Only accepts PRs from the `dev` branch. Features are first finished on the `dev` branch and then merged into this branch in bulk.
- Lint and test must pass on PRs before merging from `dev`

The flow is: `dev` -(new branch)-> `feat/my-feature` -(PR)-> `dev` -(PR)-> `main`

### Pull Requests

- PRs created when pushing to `main` and `dev`
- Assign two random reviewers, preferably not involved with the PR. One review is enough to push.

### Definition of Done

- Passing tests
- Proper documentation
- Clean code
- Merged into `dev` (staging) or `main` (production)

### Code Standards

- Commits have to follow the [Conventional Commits](https://www.conventionalcommits.org) format
  - feat: added a button
  - fix: wrong action when pressing a button
  - chore: updated version
  - docs: updated X documentation

