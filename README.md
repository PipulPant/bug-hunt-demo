# QualityKart — QA Interview Practice Site

QualityKart is a single-file static e-commerce demo used for practice and UI flow walkthroughs.

Live Site: https://pipulpant.github.io/bug-hunt-demo/

## Project Files

- `qualitykart-qa-practice.html` — complete app (HTML, CSS, JS in one file)
- `qualitykart-readme.md` — this short guide
- `.github/workflows/deploy-pages.yml` — GitHub Pages deployment workflow

## Login Users

- `standard_user / quality_kart`
- `problem_user / quality_kart`

## Main Site Areas

- Top nav + search
- Listing page + filters/sorting
- Product detail page
- Cart drawer
- Checkout + confirmation
- Content pages (Customer Service, Registry, Gift Cards, Sell, Books, etc.)

## Local Run

Open directly in browser:

- `file:///Users/pipulpant/Downloads/interview-bugs/bug-hunt-demo/qualitykart-qa-practice.html`

No build tools or backend required.

## Deploy (GitHub Pages)

This repo already includes a workflow:

- `.github/workflows/deploy-pages.yml`

Deployment behavior:

1. On push to `main`, GitHub Actions runs Pages deploy.
2. `qualitykart-qa-practice.html` is published as `index.html`.
3. Site is served from your GitHub Pages URL.

## Notes for Future Updates

- Keep the single-file architecture.
- Keep the main browsing and checkout flow stable.
