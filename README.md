# English Homework Pages

This repository is a simple GitHub Pages project for English homework and test pages.

## Structure

```text
.
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

## Adding a new page

1. Create a new folder, for example `unit-2-test/`.
2. Add `unit-2-test/index.html` and optional `unit-2-test/style.css`.
3. Add a new row to the table in the root `index.html`.
4. Use a relative link like `unit-2-test/`.

GitHub Pages will publish the page at:

```text
https://mishamyro.github.io/HW/unit-2-test/
```
