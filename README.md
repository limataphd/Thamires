# Thamires A. Lima — Quarto personal website

This folder contains a Quarto website prepared for GitHub Pages.

## Files to edit first

- `index.qmd` — home page
- `about.qmd` — short professional bio
- `research.qmd` — research themes and interests
- `publications.qmd` — selected publications
- `teaching.qmd` — teaching and mentoring
- `cv.qmd` — CV and contact page
- `styles.css` — visual styling
- `assets/profile-placeholder.svg` — replace with a professional photo
- `assets/Thamires_Lima_CV.pdf` — add your CV PDF with this exact name

## Option 1: Publish using GitHub Actions

1. Create a new public GitHub repository, for example `thamires-lima.github.io` or `personal-website`.
2. Upload all files in this folder to the repository.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **GitHub Actions**.
5. Push or upload the files. The workflow in `.github/workflows/publish.yml` will render the Quarto website and deploy it.

## Option 2: Render locally and publish from `/docs`

1. Install Quarto: https://quarto.org/docs/get-started/
2. Open this folder in RStudio, Positron, VS Code, or Terminal.
3. Run:

```bash
quarto render
```

4. Commit and push all files, including the generated `docs/` folder.
5. In GitHub, go to **Settings → Pages** and choose **Deploy from a branch**, then select the `main` branch and `/docs` folder.

## Customization checklist

- Replace the profile placeholder with a professional photo.
- Add your current CV PDF to `assets/Thamires_Lima_CV.pdf`.
- Replace the publication placeholders with your strongest selected publications.
- Update the professional summary for each job target if needed.
