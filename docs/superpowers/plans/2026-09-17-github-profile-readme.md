# GitHub Profile README Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Create a polished, modern, tech-stack-oriented GitHub Profile README for Sheharyar Nadeem (`SheyBoiCarti/SheyBoiCarti`).

**Architecture:** Use structured Markdown and centered HTML containers (`<div align="center">`) embedding dynamic SVG widgets (`readme-typing-svg`, `github-readme-stats`, `github-readme-streak-stats`) and standard `shields.io` badges.

**Tech Stack:** Markdown, HTML/CSS attributes, shields.io badges, readme-typing-svg, github-readme-stats, Git.

## Global Constraints
- Strictly avoid employment/experience history; focus purely on tech stack, engineering topics, and projects.
- Use username `SheyBoiCarti` for all GitHub stats endpoints and links.
- Use `https://linkedin.com/in/sheharyar-nadeem/` and `mailto:Sheharyarnadeem45@gmail.com` for contact links.
- Consistent dark-mode aesthetic (`tokyonight` / `radical` theme for stats).

---

### Task 1: Draft the Complete Enhanced README.md

**Files:**
- Modify: `README.md`

**Interfaces:**
- Consumes: Spec `docs/superpowers/specs/2026-09-17-github-profile-readme-design.md`
- Produces: Formatted `README.md` with header, typing animation, categorized badges, projects table, stats cards, and social links.

- [ ] **Step 1: Write the updated README.md**

Write the complete new content to `README.md`:
- Centered header with dynamic typing SVG.
- Core technical focus bullets.
- Categorized shields.io tech stack badges (Languages, AI/ML, Backend, Frontend, Databases, DevOps, Game Dev).
- Flagship projects showcase (CVRAG, CCTV Classifier, PRIMED, UNI_FEVER).
- GitHub analytics and streak cards in dark theme.
- Connect with me badge links.

- [ ] **Step 2: Verify file structure and valid Markdown**

Inspect `README.md` to ensure all HTML tags (such as `<div>`, `<p>`, `<a>`, `<img>`) are correctly paired and closed.

---

### Task 2: Validate Links and Endpoint Accessibility

**Files:**
- Verify: `README.md`

- [ ] **Step 1: Run link and badge syntax verification**

Check all external URLs and image sources (shields.io, readme-typing-svg, github-readme-stats) using PowerShell to ensure no 404 or formatting errors:
```powershell
pwsh -Command "$content = Get-Content README.md -Raw; $matches = [regex]::Matches($content, 'https://[^\s\)\"\''`]+'); foreach ($m in $matches) { Write-Output $m.Value }"
```

- [ ] **Step 2: Commit the updated README.md**

```bash
git add README.md
git commit -m "feat: revamp profile README with tech-stack focus, dynamic stats, and project showcase"
```
