# Useful Wiki documentation

This repository contains the public documentation for Useful Wiki. Maintain these docs as content consumed by Useful Wiki itself.

## Scope and sources

- Work only in this documentation repository. Inspect the sibling `useful-wiki` application or `js-html-editor` source read-only when useful; do not modify them as part of a docs change.
- `docs/*.html` pages are the source of truth. Do not create a duplicate Markdown documentation set, synchronized JSON sidecars, a generated site, or an application scaffold. The root README is a short repository entry point; this file contains contributor instructions.
- Verify feature names, limits, shortcuts, and behavior against the current Useful Wiki source and interface. Read the relevant source rather than repeating stale README or downloaded-guide claims. For example, current heading support includes `h1` through `h6`.
- Keep user and developer guidance useful in equal measure. Explain the task, steps, expected outcome, and consequential limitations. Do not claim registration, deployment, tests, or audit results that have not actually been verified.

## HTML format

- Use full UTF-8 HTML documents with `<!DOCTYPE html>`, `<html lang="en">`, `<meta charset="utf-8">`, `<meta name="useful-wiki-format" content="1">`, a title of 1–200 characters, and a body.
- The page title is independent of its filename and is displayed by the app. Prefer `h2` and `h3` body sections; avoid repeating the title as a body heading.
- Use the editor's supported paragraphs, headings, inline formatting, links, lists, checklists, blockquotes, code, tables, images, columns, and tabs. Preserve relevant `style` and `data-*` attributes. Do not introduce scripts, external stylesheets, iframes, executable embeds, or arbitrary website markup.
- Put structural blocks on separate lines. Preserve inline spacing and code whitespace. Escape text and attributes correctly. Follow `docs/06-editing-from-your-repository.html` for layout markup and the version-1 envelope.
- Keep repository-relative page links and image references. Never save session-bound `/api/projects/...` URLs or local machine paths as content links.
- Numeric filename prefixes control navigation order. Update the welcome index, README, and affected links when adding, removing, or moving a page. Preserve explicit heading IDs that other content links to.

## Screenshots and public content

- Store factual application screenshots under `docs/assets/screenshots/` and reference them relatively from pages. Use descriptive alt text and captions explaining the step and the actual state shown.
- Capture the real application. Do not fabricate controls, success states, authentication, project registrations, save results, or deployments. Keep screenshot edits limited to clearly indicated presentation needs such as cropping or redaction, without changing what the application shows.
- Label local preview screenshots accurately. `Save preview` affects browser storage; `Save to repository` creates a real Git commit. Never describe a demo screenshot as evidence of production behavior being exercised.
- Do not publish credentials, tokens, session data, private content, or another installation's service configuration. Use reader-owned services and clearly marked example values. Do not read `.env.local` to produce documentation.
- Keep image references portable and files reasonably sized. The app's raster upload limit is 900 KB; page documents are limited to 700 KB. Screenshots in the reserved `assets/` directory stay outside page navigation.

## Review

- Check HTML parsing, version metadata, unique meaningful titles, relative links, and referenced asset existence. Open changed pages in Useful Wiki and check headings, code, tables, images, and narrow-screen readability where relevant.
- Compare instructions and screenshots for consistent labels and steps. Check all relevant panels in tabbed content, including inactive tabs.
- Review the complete diff and report verification honestly. Application test commands belong in the application repository; documentation edits do not require changing its source or configuration.
- Keep version-control actions scoped to documentation files and preserve unrelated work.
