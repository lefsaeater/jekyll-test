# Field Notes

A custom editorial blog built with Jekyll and deployed through GitHub Pages.

## Publish the site

1. Push the files to the `main` branch.
2. Open **Settings > Pages** in this GitHub repository.
3. Under **Build and deployment**, select **GitHub Actions** as the source.
4. The `Deploy Jekyll site to Pages` workflow will publish the site at <https://lefsaeater.github.io/jekyll-test/>.

Every push to `main` triggers another deployment.

## Write a post

Create a Markdown file in `_posts` named `YYYY-MM-DD-post-title.md`:

```yaml
---
title: Your post title
subtitle: A one-sentence introduction.
category: Notes
image: "https://example.com/your-image.jpg"
image_alt: A useful description of the image
---

Write the post here.
```

Edit `_config.yml` to change the site title, description, author details, or repository URL. The About page lives in `about.md`.

## Run locally

Install Ruby and Bundler, then run:

```powershell
bundle install
bundle exec jekyll serve
```

Open <http://localhost:4000/jekyll-test/>.