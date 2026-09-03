# Week 01 Learning Log

## Day 3 — Git toolchain and repository structure

- Date: 2026-08-28
- Goal: Organise the repository so future labs, incidents, and evidence are easy to review and reproduce.
- What I changed: Created dedicated folders for documentation, runbooks, incidents, scripts, diagrams, evidence, and learning logs. Added a safety-focused `.gitignore`.
- What broke: No issue observed.
- One concept I can explain: `git add` selects the exact content for the next commit; it does not upload anything to GitHub.
- One question / next step: How does a branch and pull request add review before a change is merged?


## Day 4 — GitHub Flow

- Change: Added a repository structure section to README.
- Validation: Reviewed the local diff and confirmed only intended documentation changed.
- Risk: Incorrect directory descriptions could confuse repository users.
- Rollback: Create a follow-up branch and PR to remove or correct the section.
- Result: The repository structure is easier for reviewers to understand.