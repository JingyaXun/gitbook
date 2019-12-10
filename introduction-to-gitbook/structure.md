# Bird's Eye View of Gitbook Architecture

GitBook uses a simple directory structure. All Markdown/Asciidoc files listed in the [SUMMARY](https://github.com/JingyaXun/gitbook/blob/master/SUMMARY.md) will be transformed as HTML.

A basic GitBook usually looks something like this:

```text
.
├── README.md
├── SUMMARY.md
├── chapter-1/
|   ├── README.md
|   └── something.md
└── chapter-2/
    ├── README.md
    └── something.md
```

An overview of what each of these does:

| File | Description |
| :--- | :--- |
| `README.md` | Preface / Introduction for your book \(**required**\) |
| `SUMMARY.md` | Table of Contents \(See [Pages](https://github.com/JingyaXun/gitbook/blob/master/SUMMARY.md)\) \(**optional**\) |
| `something.md` | Book Contents \(**optional**\) |

A static file is a file that is not listed in the `SUMMARY.md`. All static files, unless ignored, are copied to the output.

## Ignoring files & folders <a id="ignore"></a>

GitBook will read the `.gitignore`, `.bookignore` and `.ignore` files to get a list of files and folders to skip. The format inside those files, follows the same convention as `.gitignore`:

```text
# This is a comment

# Ignore the file test.md
test.md

# Ignore everything in the directory "bin"
bin/*
```

## Project integration with subdirectory <a id="subdirectory"></a>

For software projects, you can use a subdirectory \(like `docs/`\) to store the book for the project's documentation. You can configure the [`root` option](https://github.com/JingyaXun/gitbook/blob/master/SUMMARY.md) to indicate the folder where GitBook can find the book's files:

```text
.
└── docs/
    ├── README.md
    └── SUMMARY.md
```

