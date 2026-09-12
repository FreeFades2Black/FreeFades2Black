# ADR-0001: Serverless GitHub Actions SVG Telemetry vs External Dynamic Badge Services

**Status:** Accepted  
**Date:** 2026-05-15  
**Lead Architect:** William Free Hall (Free) <whall4.wh@gmail.com>

## 1. Context & Operational Challenge
Displaying live GitHub engineering metrics, commit streaks, and technical skills on the root developer profile. External third-party dynamic badge APIs (e.g. `github-readme-stats.vercel.app`) suffer frequent 502 bad gateway outages, slow page load times, and API rate-limit drops.

## 2. Options Considered
* **Option A: External Third-Party Dynamic Badge Services**
  - *Evaluation:* Fragile; external service downtimes leave broken image placeholders across profile README.
* **Option B: Automated GitHub Actions Workflow Generating Static SVGs Committed Directly to Repo**
  - *Evaluation:* Scheduled GitHub Action runs nightly, generates optimized SVGs directly into repository tree; profile loads instantaneously from GitHub CDN with 100% uptime guarantee.

## 3. Decision & Trade-Off Accepted
We adopted **Option B (Serverless SVG Telemetry)**.  
**Trade-Off Accepted:** Telemetry updates on a 24-hour cadence rather than live real-time; eliminates all external SaaS dependencies.
