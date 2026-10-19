# Cloud Engineering Portfolio

Responsive, static portfolio showcasing three cloud engineering projects. The site is built with **HTML, CSS and JavaScript**, so it requires no framework, build step or paid hosting.

## Preview locally

Open `index.html` in a browser, or run `python -m http.server 8000` in this directory and open `http://localhost:8000`.

## Publish on GitHub Pages

1. Create a **public** GitHub repository named `cloud-engineering-portfolio`.
2. Upload the **contents of this folder** (including `.github/` and `assets/`) to the repository root.
3. Under **Settings → Pages → Build and deployment**, select `GitHub Actions` as source.
4. Push to `main`; the workflow `.github/workflows/pages.yml` deploys the static website.
5. Your project-site URL will be `https://YOUR-USERNAME.github.io/cloud-engineering-portfolio/`.

## Personalization

- Replace `Abdulrahman` and the wordmark in `index.html` and the three pages in `projects/`, if needed.
- Replace `abuda7mm` in the HTML links with your GitHub username if different.
- Keep the repository names the same as in links or update each case-study GitHub button.
- SVG architecture images in `assets/` can be edited or replaced without touching the layout.
- Each case study includes written context, the architecture diagram, implementation steps and a short excerpt from the actual project.

## Structure

```text
index.html
styles.css
script.js
assets/
  architecture-aws.svg
  architecture-kubernetes.svg
  architecture-operations.svg
  favicon.svg
projects/
  aws-infrastructure.html
  kubernetes-cicd.html
  cloud-operations.html
.github/workflows/pages.yml
```

All design diagrams are original SVG illustrations rather than screenshots of AWS or GitHub products.
