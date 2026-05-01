# yey-day-app

This is the live deployment repository for yey-day.

## About

This repository contains the production build of yey-day, automatically deployed from the main repository.

- **Source Repository**: [MaxLabs-AB/yey-day](https://github.com/MaxLabs-AB/yey-day)
- **Live Site**: https://maxlabs-ab.github.io/yey-day-app/

## Deployment

This repository is automatically updated whenever changes are merged to the main branch of the source repository.

**Do not make manual changes to this repository** - they will be overwritten on the next deployment.

## What's Deployed

Only production files are deployed:
- `index.html` - Main application file
- Asset folders (images, css, js, etc.)

Development files (workflows, automation scripts, etc.) are excluded.

## Rollback

If you need to rollback a deployment:
1. Clone this repository
2. Check the git history: `git log --oneline`
3. Revert to a previous commit: `git revert <commit-sha>` or `git reset --hard <commit-sha> && git push --force`
4. Or manually checkout a specific version: `git checkout <commit-sha> -- .`

Note: The deployment history is preserved to make rollbacks easier.

---

_Last deployed: $(date -u '+%Y-%m-%d %H:%M:%S UTC')_
