# English Homework Pages Template

This is a simple static GitHub Pages template for English homework and test pages.
It can be copied or pushed to any repository that publishes GitHub Pages from the repository root.

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

## Publishing

In GitHub repository settings, enable GitHub Pages with:

- Source: deploy from a branch
- Branch: `main`
- Folder: `/` root

After publishing, GitHub Pages will serve the root catalog at the repository's Pages URL. Page links are relative, so the project works under any account or repository name.

## Adding a new page

1. Create a new folder, for example `unit-2-test/`.
2. Add `unit-2-test/index.html` and optional `unit-2-test/style.css`.
3. Add a new row to the table in the root `index.html` with the next numeric ID, title, date created, and link.
4. Use a relative link like `unit-2-test/`.

GitHub Pages will publish the page at a URL like:

```text
https://<username>.github.io/<repository>/unit-2-test/
```

## Agent

Use the project agent `english-homework-manager` when asking Codex to create, edit, publish, delete, or list homework/test pages in a repository using this structure.
