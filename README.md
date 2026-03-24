# git-linear-control

A minimalist web project built with a terminal-first **CI/CD** workflow.

## 🛠 Tech Stack
- **Project Management:** [Linear](https://linear.app) (Tracking via SQST team)
- **Version Control:** Git & [GitHub](https://github.com/atxatlarge-code)
- **Deployment:** Vercel (Auto-deploy on merge to main)

## 🚀 The Workflow
This project follows a strict "Proper CI/CD" loop:
1. **Issue:** Create a task in Linear (e.g., `SQST-2`).
2. **Branch:** Create a feature branch named after the issue: `git checkout -b atx/sqst-X-feature-name`.
3. **Commit:** Link the work in the commit message: `git commit -m "feat: description for SQST-X"`.
4. **PR:** Open a Pull Request via GitHub CLI: `gh pr create`.
5. **Deploy:** Merge to `main` to trigger the automated production build.

## 📝 Current Features
- [x] Initial project structure
- [x] Integrated Linear + GitHub workflow
- [x] CSS "Operational" pulse animation (SQST-2)
