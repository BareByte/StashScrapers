# Stash Scrapers

This repository hosts BareByte's gay-themed metadata scrapers for [Stash](https://github.com/stashapp/stash).

## Install

Settings » Metadata Providers » Available Scrapers » Add Source

* **Name**: `BareByte`
* **Local Path**: `barebyte`

Choose one of following channels for **Source URL**:

* `main`: `https://barebyte.github.io/StashScrapers/main/index.yml`
* `dev`: `https://barebyte.github.io/StashScrapers/dev/index.yml`

## Scrapers

### Hunk Channel

* Scrape scene from URL

## Validation

The scrapers in this repository can be validated against a schema and checked for common errors.

First, install the validator's dependencies - inside the [`./validator`](./validator) folder, run: `yarn`.

Then, to run the validator, use `node validate.js` in the root of the repository.  
Specific scrapers can be checked using: `node validate.js scrapers/foo.yml scrapers/bar.yml`
