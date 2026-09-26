# Ontology for Social Research: A Critical Introduction

To go beyond the quantitative and qualitative divide in the social sciences, this book proposes ontology as the way forward. You will learn how to situate methods based on their assumptions about social reality and how to implement this philosophy into practical research.

GENERATED from `templates/README.md` by `configure.mjs`. Edit the template.

- **Read it:** https://ontology-for-social-research-a-criti.confused4now.org
- **Slug:** `ontology-for-social-research-a-criti` — this book's permanent key in the platform registry. It
  never changes and is never reused.
- **Maintainer:** Brandon Sommer, Caroline Laschkolnig
- **Licence:** CC-BY-SA-4.0 for the text, unless a file says otherwise.

## What is where

| Path | What |
|---|---|
| `chapters/` | The book. One markdown file per page; concept pages in `chapters/Definitions/` |
| `assets/` | Pictures, one folder per chapter |
| `glossary.md` | The glossary |
| `index.md` | The front page. An ordinary page, edited like a chapter |
| `admin/` | The browser editor. Tooling, never published with the book |
| `templates/`, `configure.mjs` | Every generated file, and the renderer that fills them from `textbook.config.json` and the registry |
| `.github/workflows/` | This book's own automation |

## Changing a generated file

`README.md`, `CONTRIBUTING.md`, `.lycheeignore` and `admin/config.yml` are
generated. Edit the copy under `templates/`, then:

```sh
node configure.mjs
```

It reads `textbook.config.json` (which holds the slug and nothing else) and this
book's entry in the platform registry, and rewrites the managed files. Everything
else — the repository, the branches, the domain, the endpoints — lives in the
registry, so changing any of it is a pull request against
`textbookproject2026-alt/textbook-registry`, not a change here.

`.github/workflows/apply-config.yml` runs the same command on any pull request
that touches the config, a template or the renderer, and commits the result back
into the pull request.

## Contributing

See `CONTRIBUTING.md`. Readers can suggest an edit from any page of the site
without an account.
