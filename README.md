# Setup

This project uses [uv](https://docs.astral.sh/uv/getting-started/) as per the presentation.

The repo owner has had issues with `uv pip install` so they suggest to use the following for [managing dependencies](https://docs.astral.sh/uv/guides/projects/#managing-dependencies):

- For PROD installs:    `uv add <dependency>`
- For DEV installs:     `uv add --dev <dependency>`
