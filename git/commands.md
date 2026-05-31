# GIT Commands

## Util Commands:
```bash
# Rebase Commands
git fetch origin
git rebase origin/develop
git push --force-with-lease

# Delete local branch
git branch -D BRANCH_NAME

# Delete remote branch
git push origin --delete BRANCH_NAME

# Remove all unstaged changes
git restore .