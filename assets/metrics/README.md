# assets/metrics/

This folder is auto-populated by the GitHub Actions metrics workflow.

Files generated here:
- `languages.svg` — Language usage breakdown
- `activity.svg` — Recent activity heatmap
- `achievements.svg` — GitHub achievements

**Setup Required:**
1. Create a GitHub Personal Access Token with `read:user` and `public_repo` scopes
2. Add it as a repository secret named `METRICS_TOKEN`
3. Run the `Update Metrics` workflow from the Actions tab
