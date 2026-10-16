# Sahan's actual GitHub profile README

This is **not a website** and intentionally contains **no featured-project section**. The profile is rendered by GitHub from `README.md`, using GitHub Flavored Markdown, a small amount of supported HTML, SVG image assets, and GitHub Actions. No separate HTML, CSS, JS, build step, server, or hosting is required.

## Installation

1. Open `https://github.com/sahanRanasingha/sahanRanasingha` (the **public** profile repository).
2. Upload `README.md`, the entire `assets/` folder and `.github/workflows/snake.yml` **to matching paths** in that repository. Do not upload the ZIP itself or nest the contents in an extra folder.
3. Commit your changes to the default branch. Visit `https://github.com/sahanRanasingha` to view the new README.
4. Open the profile repository's **Actions** tab, select **Generate Snake**, then click **Run workflow**. After it succeeds, the `output` branch will hold the animation. Daily updates then run automatically.
5. If publishing fails with a 403 permission error, inspect **Settings → Actions → General → Workflow permissions** and applicable organization/repository policies; write access may be restricted.

## Folder layout

```
README.md
assets/
  hero-dark.svg
  hero-light.svg
  pipeline-dark.svg
  pipeline-light.svg
  terminal-dark.svg
  terminal-light.svg
  skills-carousel-dark.svg
  skills-carousel-light.svg
.github/
  workflows/
    snake.yml
```

## Important notes

- SVGs contain only SVG markup and animation styles within the SVG image files. They are not webpage CSS/JavaScript. If a viewer doesn't animate SVGs, the artwork remains readable as a static image.
- GitHub themes use `<picture>` to switch the image variant. Mobile may scale the images down; accessible alt text is included.
- The animated text, stats, skill icons and badges are from external image providers. They can be unavailable, rate limited, or cached. If desired, remove any third-party images from the Markdown.
- The contribution snake is **not** included as a pre-rendered result. It will only exist after the GitHub Action has run successfully.
- Edit job title, university, links and profile details directly in `README.md`. Text embedded in an SVG should be changed in both dark and light versions to stay consistent.
- Test the real GitHub appearance by committing the files and viewing your public profile. Static preview images are illustrations and do not guarantee pixel-identical GitHub rendering.
