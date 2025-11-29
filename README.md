# Git Workflow Practice

![Git](https://img.shields.io/badge/Git-F05033?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-5-E34F26?logo=html5&logoColor=white)

Hands-on practice with Git workflows, branching strategies, and local-to-remote synchronization.

## What I Practiced

✅ Creating and switching branches  
✅ Making isolated changes on feature branches  
✅ Merging branches back to main  
✅ Resolving merge conflicts  
✅ Local repository management  
✅ Pushing local changes to remote (GitHub)  
✅ SSH authentication workflow
✅ Inspecting commit history  
✅ Rewriting/adjusting history

## Branching Strategy Practiced

```bash
# Create feature branch
git checkout -b feature-name

# Work on feature
git add .
git commit -m "Add feature"

# Merge back to main
git checkout main
git merge feature-name

# Push to remote
git push origin main
```

## Commit History Tools

```bash
# Detailed commit history
git log

# One-line, simplified history
git log --oneline

# Graph view for visual understanding
git log --oneline --graph --decorate --all
```

## Resetting Commits

```bash
# Soft reset (keeps changes staged)
git reset --soft <commit-hash>

# Mixed reset (default — keeps changes in working directory)
git reset <commit-hash>

# Hard reset (discard changes and move HEAD)
git reset --hard <commit-hash>
```

⚠️ git reset --hard is destructive — use with caution.

## Local Development

Open button.html in your browser.

## Skills Demonstrated

- Understanding of Git branching model
- Local and remote repository synchronization
- Merge conflict resolution
- Professional Git workflow habits
- Commit history navigation
- History rewriting and recovery

---

_Part of my AI Engineering learning roadmap (2025-2026)_
