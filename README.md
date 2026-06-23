# English Homework Pages

This repository is a simple GitHub Pages project for English homework and test pages.

## Structure

```text
.
├── .codex/
│   └── agents/
│       └── english-homework-manager.toml
├── index.html
├── style.css
├── english-homework/
│   ├── index.html
│   └── style.css
└── simple-static/
    ├── index.html
    └── style.css
```

The root `index.html` is the public catalog. Each homework or test page should live in its own folder with an `index.html` file.

The catalog table uses a stable numeric `ID` column. IDs should start at `1` and increment by one for each new page.

## Adding a new page

1. Create a new folder, for example `unit-2-test/`.
2. Add `unit-2-test/index.html` and optional `unit-2-test/style.css`.
3. Add a new row to the table in the root `index.html` with the next numeric ID, title, date created, and link.
4. Use a relative link like `unit-2-test/`.

GitHub Pages will publish the page at:

```text
https://mishamyro.github.io/HW/unit-2-test/
```

## Agent

Use the project agent `english-homework-manager` when asking Codex to create,
edit, publish, delete, or list homework/test pages in this repository.
