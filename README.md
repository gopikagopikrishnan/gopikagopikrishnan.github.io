# Gopika Gopikrishnan Portfolio

Personal academic portfolio website for Gopika Gopikrishnan, built with Jekyll using the Academic Pages template.

Live site: https://gopikagopikrishnan.github.io/

## Overview

This repository contains the source for a GitHub Pages site that includes:

- About and profile information
- Publications and CV pages
- Projects and portfolio content
- Talks, teaching, and supporting static assets

The site is configured as a GitHub Pages user site, so the repository name should be:

`gopikagopikrishnan.github.io`

## Site Configuration

The main GitHub Pages settings live in `_config.yml`.

Expected values for this site:

- `url: https://gopikagopikrishnan.github.io`
- `baseurl: ""`
- `repository: gopikagopikrishnan/gopikagopikrishnan.github.io`

If the repository name changes, these values may need to be updated as well.

## Run Locally

This site builds successfully in WSL with Ruby, Bundler, and Node installed.

### WSL setup

```bash
sudo apt update
sudo apt install ruby-dev ruby-bundler nodejs build-essential gcc make
bundle install
```

If Bundler cannot write to system directories, install gems locally:

```bash
bundle config set --local path 'vendor/bundle'
bundle install
```

### Start the local server

```bash
bundle exec jekyll serve -l -H localhost
```

The site will be available at:

`http://localhost:4000`

If `_config.yml` changes, restart the Jekyll server.

## Build Locally

To generate the static site without serving it:

```bash
bundle exec jekyll build
```

The generated output is written to `_site/`.

## Deploy To GitHub Pages

1. Create a public GitHub repository named `gopikagopikrishnan.github.io`.
2. Push this repository to GitHub.
3. In GitHub, open `Settings > Pages`.
4. Set `Source` to `Deploy from a branch`.
5. Select branch `main` and folder `/(root)`.
6. Save the settings and wait for GitHub Pages to publish.

The published site URL will be:

`https://gopikagopikrishnan.github.io/`

## Git Commands

If this folder is already a Git repository and you need to point it to the GitHub Pages repository:

```bash
git remote set-url origin https://github.com/gopikagopikrishnan/gopikagopikrishnan.github.io.git
git push --force-with-lease -u origin main
```

Use `--force-with-lease` only when the remote branch contains placeholder commits that should be replaced by the local site history.

## Project Structure

- `_config.yml`: Site-wide Jekyll and GitHub Pages configuration
- `_pages/`: Main site pages such as About, CV, Projects, and Publications
- `_posts/`: Blog posts
- `_portfolio/`: Portfolio entries
- `_publications/`: Publication entries
- `_talks/`: Talks and presentations
- `_teaching/`: Teaching-related content
- `images/`: Images and icons used across the site
- `files/`: Downloadable files such as PDFs
- `_site/`: Generated build output

## Notes

- Root-relative links and assets should remain compatible with the user-site root URL.
- Some project image references on the Projects page expect matching files in `images/`.
- This repository is based on the Academic Pages template: https://academicpages.github.io/

## License

See `LICENSE` for licensing details.
