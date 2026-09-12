# Operational Runbook: Profile SVG Generation Workflow Permission Triage

**Severity:** P3 / Profile Metric Stale  
**Target Systems:** GitHub Actions, Profile Workflow

## Diagnostic Workflow
1. Verify GitHub Actions workflow permissions under Repository Settings -> Actions -> General:
   - Ensure `Workflow permissions` is set to `Read and write permissions`.
2. Check recent workflow runs:
   ```bash
   gh run list --workflow=profile-telemetry.yml
   ```
3. If failed with `Permission to repository denied to github-actions[bot]`, add explicit permission block:
   ```yaml
   permissions:
     contents: write
   ```
