# Codecamp Exercise: Git & GitHub Fundamentals

## Learning Objectives

- Initialize a Git repository and understand the working directory, staging area, and commit history
- Use `git add`, `git commit`, `git log`, and `git status` confidently
- Write commit messages following the Conventional Commits format
- Push code to a remote GitHub repository
- Create branches, switch between them, and merge changes
- Fork a repository and open a Pull Request

## Exercise Instructions

### Part 1: Basic Git Workflow

1. **Fork** this repository to your own GitHub account
2. **Clone** your fork to your local machine
3. Open `index.html` and complete the TODO sections:
   - Add your name to the hero section
   - Add at least 3 skills to the skills list
   - Add a short "About Me" paragraph
4. Stage your changes with `git add`
5. Commit with a Conventional Commit message: `feat: add personal information to portfolio`
6. Push to your fork: `git push origin main`

### Part 2: Branching & Merging

1. Create a new feature branch: `git switch -c feat/add-projects-section`
2. Add a "Projects" section to `index.html` with at least 2 project cards
3. Commit your changes: `feat: add projects section`
4. Switch back to main: `git switch main`
5. Merge the feature branch: `git merge feat/add-projects-section`
6. Delete the feature branch: `git branch -d feat/add-projects-section`
7. Push to your fork

### Part 3: Pull Request

1. Create a new branch: `git switch -c feat/add-contact-section`
2. Add a "Contact" section with an email link
3. Commit and push the branch to your fork
4. Open a **Pull Request** from your fork's `feat/add-contact-section` branch to the upstream `main` branch
5. In the PR description, write what you changed and why

## Acceptance Criteria

- [ ] `index.html` contains your name, skills, and about section
- [ ] At least 3 commits with proper Conventional Commit messages
- [ ] A "Projects" section with at least 2 project entries
- [ ] A Pull Request opened with a descriptive title and body
- [ ] Branch history shows at least one feature branch that was merged

## File Structure

```
codecamp-exercise-git-github/
├── README.md          # This file
├── LICENSE            # MIT License
├── .gitignore         # Git ignore rules
└── index.html         # Your portfolio page (edit this!)
```

## Tips

- Use `git status` frequently to see what's changed
- Use `git log --oneline` to see your commit history
- If you make a mistake, `git diff` shows what changed since the last commit
- Always write meaningful commit messages — your future self will thank you
