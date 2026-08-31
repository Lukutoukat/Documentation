# Fall 2026 Team

## Working Principles

### Dailies

- Daily meetings in Discord voice chat
- Monday, Wednesday, Friday at 12:00
- One SCRUM master

### In-person Meetings

- Tuesday 14:00 -> 17:00
- With the customer every 2nd Thursday at 16:00 (starting at 17.9)

### Sprints

- In GitHub project
- 2 weeks, (Sprint 0) 31.8 -> 16.9, (Sprint 1) 17.9 -> 1.10 ...

### Branching

Branches are
- `develop` for merging features in development
- `staging` for pushing features to staging env
- `production` for pushing features to production env
- **Feature branches** for each issue / task, which are then merged into `develop`

### Pull Requests

- PRs created when pushing to `staging` or `production`
- Two reviewers. One review is enough to push.

### Definition of Done

- Passing tests
- Proper documentation
- Clean code
- Merged into `staging` or `production`

### Code Standards

- Commits have to follow the [Conventional Commits](https://www.conventionalcommits.org) format
  - feat: added a button
  - fix: wrong action when pressing a button
  - chore: updated version
  - docs: updated X documentation

