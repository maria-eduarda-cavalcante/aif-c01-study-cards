# AWS Certified AI Practitioner (AIF‑C01) — Study Cards & Practice Exam (with Modals)

This package adds **clickable Study Card chips** that open a **modal** with:
- Full name of the AWS service/acronym
- What it is used for
- A short practical example

Also includes the **interactive mock exam** and the GitHub Pages configuration files.

## Files
- `index.html` — Single‑page app with chips → modal, and the quiz.
- `.nojekyll` — Disables Jekyll processing.
- `LICENSE` — MIT license.
- `404.html` — Redirects unknown paths to `/`.

## Deploy
1. Create a public repo (e.g., `aif-c01-study-cards`), upload all files to the repo root.
2. Settings → Pages: Deploy from a branch → `main` / `/` (root).
3. Open `https://<your-user>.github.io/aif-c01-study-cards/`.

## Accessibility
- Chips are keyboard‑focusable (`tabindex="0"`) and open the modal with **Enter**.
- Modal can be closed by clicking the overlay, the **Close** button, or pressing **Esc**.
