# Problem Solver Lab

A professional blog site built with Jekyll and designed for GitHub Pages project hosting.

## Live URLs

- Site home: `https://kingalok.github.io/problem-solver-lab/`
- First post: `https://kingalok.github.io/problem-solver-lab/blog/from-spark-to-dark-factory/`
- Second post: `https://kingalok.github.io/problem-solver-lab/blog/agents-will-be-everywhere-guardrails-must-be-too/`

## Included

- Clean responsive design
- Post index homepage
- About page
- Posts:
  - From Spark to Dark Factory: 6 Levels of AI Delivery (+ 3 Roles)
  - Agents Will Be Everywhere. Guardrails Must Be Too.
- GitHub Actions workflow for Pages deployment

## Image setup

Use these exact file names:

- `assets/images/AI-Dev1.png`
- `assets/images/AI-Dev2.png`
- `assets/images/AI-Dev3.jpeg`

## Run locally (optional)

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://127.0.0.1:4000/problem-solver-lab/`.

## Publish on GitHub Pages

1. Push to `main`.
2. In repository settings, set Pages source to `GitHub Actions`.
3. Workflow file `.github/workflows/pages.yml` will build and deploy automatically.
