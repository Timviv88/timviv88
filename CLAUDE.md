# CLAUDE.md

## Repository Overview

This is a **GitHub Profile Repository** (`Timviv88/timviv88`). It is a special repository whose `README.md` is rendered directly on the owner's GitHub profile page at `github.com/Timviv88`.

## Project Structure

```
.
├── CLAUDE.md      # Guidelines for AI assistants working on this repo
└── README.md      # GitHub profile page content (rendered on github.com/Timviv88)
```

This is a documentation-only repository. There is no application code, build system, test suite, or CI/CD pipeline.

## Key Facts

- **Language:** Markdown
- **Purpose:** GitHub profile landing page
- **Branch strategy:** `main` is the default/production branch
- **Single file of consequence:** `README.md` — any changes here immediately affect the public GitHub profile

## Development Workflow

1. Edit `README.md` with valid GitHub-flavored Markdown
2. Commit to `main` (or merge a PR into `main`) for changes to appear on the profile
3. No build step, no tests, no deployment — GitHub renders `README.md` automatically

## Conventions and Guidelines

- **Markdown flavor:** GitHub-flavored Markdown (GFM). Supports tables, task lists, syntax-highlighted code blocks, and HTML subsets allowed by GitHub.
- **Images/media:** Reference images via absolute URLs or relative paths committed to the repo. GitHub renders them inline.
- **HTML:** Limited HTML is supported in GitHub profile READMEs (e.g., `<img>`, `<a>`, `<details>`, `<summary>`, `<picture>`). Avoid `<script>`, `<style>`, and `<iframe>` — GitHub strips them.
- **Keep it concise:** Profile READMEs should load quickly and be scannable. Avoid excessively large images or very long content.

## What NOT to Do

- Do not add application code, package managers, or build tooling unless the owner explicitly wants to add dynamic profile features (e.g., GitHub Actions workflows for auto-updating stats).
- Do not remove or rename `README.md` — it is the sole file that GitHub uses for profile rendering.
- Do not commit secrets, tokens, or private information — this repository is public.
