# Repositories

## Owned

| Name | URL | Type | Status | Why It Matters |
|---|---|---|---|---|
| TBD | TBD | core | inbox | Future owned tooling for drafting, publishing, and review automation. |

## External References

| Name | URL | Type | Status | Why Track It |
|---|---|---|---|---|
| Ghost | https://github.com/TryGhost/Ghost | publishing | active | Mature open-source publishing stack for newsletters, memberships, and editorial workflows. |
| Quarto | https://github.com/quarto-dev/quarto-cli | publishing | active | Turns Markdown and notebooks into polished reports, articles, slides, and sites. |
| Marp CLI | https://github.com/marp-team/marp-cli | slides | active | Lightweight Markdown-to-slides pipeline that fits repeatable briefings, workshop decks, and social-carousel drafts. |
| Eleventy | https://github.com/11ty/eleventy | static-site | active | Flexible static-site generator for content libraries, editorial microsites, and archives without a heavy framework. |
| Typst | https://github.com/typst/typst | typesetting | active | Modern programmable typesetting engine for report-style PDFs and more polished long-form output. |
| Pagefind | https://github.com/Pagefind/pagefind | search | active | Adds static site search without a server, useful for archives, notes, and long-form libraries. |
| Docling | https://github.com/docling-project/docling | ingestion | active | Converts PDFs, slides, and office files into structured Markdown/JSON, which is useful before editing or republishing source material. |
| Decap CMS | https://github.com/decaporg/decap-cms | editorial-cms | active | Adds a Git-backed editorial UI for Markdown content, which is useful when non-terminal drafting or review flows become necessary. |
| markdownlint-github | https://github.com/github/markdownlint-github | quality | active | Reuses GitHub's Markdown lint profile to keep README, article, and documentation formatting consistent across the repo. |

## Official References

| Name | URL | Type | Status | Why Track It |
|---|---|---|---|---|
| Ghost Publishing Docs | https://docs.ghost.org/publishing/ | docs | active | Explains structured authoring, rich media, and API-friendly publishing flows. |
| Quarto Publishing Docs | https://quarto.org/docs/output-formats/html-publishing | docs | active | Useful for shipping HTML reports and microsites from a Markdown-first workflow. |
| Quarto Publishing Basics | https://quarto.org/docs/publishing/ | docs | active | Covers deployment targets and practical publishing paths for documents, sites, blogs, and books. |
| GitHub Pages Custom Workflows | https://docs.github.com/en/pages/getting-started-with-github-pages/using-custom-workflows-with-github-pages | docs | active | Helpful when the content pipeline needs custom build and deploy steps. |
| Decap CMS Editorial Workflow Docs | https://decapcms.org/docs/backends-overview/ | docs | active | Clarifies how a Git-based CMS integrates with GitHub-style storage and editorial review flows. |
| Docling Documentation | https://docling-project.github.io/docling/ | docs | active | Useful reference for structured document conversion outputs before wiring an ingestion pipeline. |
| Marp Docs | https://marp.app/ | docs | active | Official entry point for the Markdown slide ecosystem and conversion workflow around Marp CLI. |
| Eleventy Docs | https://www.11ty.dev/docs/ | docs | active | Useful for content collections, templating choices, and low-overhead publishing architecture. |
| Typst Documentation | https://typst.app/docs/ | docs | active | Covers syntax, layouts, and automation primitives for high-quality typeset publishing workflows. |

## Fork Candidates

| Name | URL | Decision | Notes |
|---|---|---|---|
| Zerox | https://github.com/getomni-ai/zerox | review | Promising OCR-to-Markdown ingestion layer for turning PDFs and scans into editable source material. |
| Docling | https://github.com/docling-project/docling | review | Stronger general-purpose ingestion candidate than ad hoc converters if the pipeline needs reproducible document-to-Markdown transforms. |
| Marp CLI | https://github.com/marp-team/marp-cli | review | Worth testing if the repo starts generating recurring slide decks or visual briefings from Markdown sources. |
| Typst | https://github.com/typst/typst | review | Worth testing when report formatting quality or template-driven PDF generation becomes a first-class requirement. |
