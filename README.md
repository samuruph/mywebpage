# samuruph.com

Personal webpage for [Samuele Ruffino](https://samuruph.com).

Built with [Hugo](https://gohugo.io) and the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme.

## Structure

```
content/
  posts/          # blog posts
  projects/       # project write-ups
  publications/   # research publications
static/
  images/         # photos and thumbnails
  pdfs/           # paper PDFs and other documents
  videos/         # demo videos
assets/css/       # custom CSS overrides
layouts/          # custom Hugo layout overrides
```

## Local development

**Prerequisites:** [Hugo extended](https://gohugo.io/installation/) (v0.120+)

```bash
# Clone with submodules (PaperMod theme)
git clone --recurse-submodules <repo-url>
cd mywebpage

# Serve locally with live reload
hugo server -D
```

The site will be available at `http://localhost:1313`.

## Adding content

```bash
# New blog post
hugo new posts/my-post.md

# New project
hugo new projects/my-project.md

# New publication
hugo new publications/my-paper.md
```

## Deployment

The site builds to the `public/` directory (git-ignored). Deploy by running:

```bash
hugo --minify
```

and uploading `public/` to your hosting provider, or configure a CI pipeline to do so automatically.

## Theme

[PaperMod](https://github.com/adityatelange/hugo-PaperMod) is included as a git submodule. To update it:

```bash
git submodule update --remote themes/PaperMod
```
