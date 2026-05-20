# AI-Driven Development Portfolio — Seiji Shii

This repository is the source for [my AI-driven development portfolio site](https://seijishii.github.io/ai-portfolio/), built as a single static page and deployed via **GitHub Pages**.

It showcases two production services I built end-to-end with Claude Code / Cursor as my development partner:

| Service | URL | Description |
| --- | --- | --- |
| **GIVErS** | [givers.work](https://givers.work/) | Zero-fee donation platform (Go + Astro + Stripe Connect) |
| **UNOES Dictionary** | [unoes.net](https://unoes.net/) | Multi-platform dictionary app + subscription backend (Go + Flutter) |

## Highlights

- **AI-driven development workflow** — `SPEC → PLAN → UNIT_TEST → E2E_TEST → IMPL_REPORT → FEEDBACK_REVIEW → REVIEW` documented per feature
- **CLAUDE.md / memory** runbook to keep the AI grounded in project-specific rules (i18n compliance, debug-log policy, one-question-at-a-time design reviews)
- Full ownership across spec, design, implementation, testing, deployment and ongoing operations

## Local preview

```bash
# Anything that serves static files works
python3 -m http.server 8080
# → http://localhost:8080
```

## Deploy

This site is deployed via GitHub Pages from the `main` branch root.

- `.nojekyll` disables Jekyll processing
- Assets live under `assets/`
- No build step required

## License

Source code (HTML / CSS): MIT.
Logos and brand marks of the showcased services belong to the respective projects.
