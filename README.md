As of Dec 2025, this README is a WIP. The most important piece of this repo is the training deck. (See the link in the top right under the description.)

# About

This repo is a template for someone to have a basic mkdocs setup with Jupyter using jupyterlite.

The code along with the training were part of a [PyTexas 2026](https://www.pytexas.org/2026/) talk per [here](https://www.pytexas.org/2026/schedule/talks/#python-in-the-browser-building-interactive-documentation-with-mkdocs-jupyterlite).

# Setup

This project uses [uv](https://docs.astral.sh/uv/getting-started/) as per the presentation.

The repo owner has had issues with `uv pip install` so they suggest to use the following for [managing dependencies](https://docs.astral.sh/uv/guides/projects/#managing-dependencies):

- For PROD installs:    `uv add <dependency>`
- For DEV installs:     `uv add --dev <dependency>`

If you have uv already installed, sync should be sufficient.
