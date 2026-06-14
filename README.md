# mdscraper

Combine text files into a single Markdown document.

Scans a directory for text files and concatenates them into one Markdown file,
optionally adding per-file headers and a table of contents. Supports
`.gitignore`-style filtering via an ignore file.

## Usage

```bash
mdscraper .                       # Combine files in the current directory → stdout
mdscraper -o output.md .          # Write to a file
mdscraper -r .                    # Recurse into subdirectories
mdscraper --toc .                 # Add a table of contents
mdscraper --ignore-file .mdscraper .
```

## Install

```bash
uv tool install --editable .
```

## License

Copyright (C) 2026 Paul Payne. Licensed under the GNU AGPLv3 — see [LICENSE](LICENSE).
