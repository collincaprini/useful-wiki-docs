# Useful Wiki documentation

The public documentation content for Useful Wiki, written in its own editable HTML format. Pages in `docs/` are the source of truth; there is no generated website or synchronized JSON copy.

Start with [the guide index](docs/00-welcome.html). The guide serves people using Useful Wiki and developers running or contributing to it.

## Connect this repository

Use these settings when registering this repository in a configured Useful Wiki instance:

| Field | Value |
| --- | --- |
| Repository | `collincaprini/useful-wiki-docs` |
| Project name | Useful Wiki documentation |
| Experience | Documentation |
| Branch | `main` |
| Content folder | `docs` |

These are intended registration settings, not a claim that the repository is already connected or deployed. Registration adds metadata without changing repository files; saving a page in a connected project creates a commit.

## Read the guide

| Use the app | Build and maintain it |
| --- | --- |
| [Getting started](docs/01-getting-started.html) | [Running locally](docs/07-running-locally.html) |
| [Writing pages](docs/02-writing-pages.html) | [Architecture and trust boundaries](docs/08-architecture.html) |
| [Organizing pages](docs/03-organizing-pages.html) | [Contributing](docs/09-contributing.html) |
| [Sharing and access](docs/04-sharing-and-access.html) | [Editing from your repository](docs/06-editing-from-your-repository.html) |
| [Troubleshooting](docs/05-troubleshooting.html) | [Markdown and portable files](docs/12-markdown-and-portable-files.html) |

Detailed feature guides cover [rich text and layouts](docs/10-rich-text-and-layouts.html), [images and links](docs/11-images-and-links.html), [navigation and search](docs/13-navigation-and-search.html), and [appearance and shortcuts](docs/14-appearance-and-shortcuts.html).

Screenshots live in `docs/assets/screenshots/`. Screenshots showing **Local preview** illustrate the app with example pages, including locally loaded samples for editor and navigation features: **Save preview** stays in browser storage, while **Save to repository** publishes a Git commit in a connected project. Captions identify the state shown; a screenshot of a preview is not proof of a live registration or deployment.

## Edit the docs

Read [AGENTS.md](AGENTS.md) and [the repository editing guide](docs/06-editing-from-your-repository.html). Preserve HTML version-1 metadata, relative links, and supported editor elements. Verify feature claims against the current app. Keep credentials and private content out of this public repository.
