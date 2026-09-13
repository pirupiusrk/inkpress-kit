# inkpress-kit

My tiny static site generator, ~100 lines of Python

Small but I use it weekly.

## Examples

```bash
mkdir posts && echo '# hello' > posts/first.md
python build.py
# site lands in dist/
```

## What it does

- Index page with post list by date
- RSS feed generation
- Markdown posts with fenced code and tables
- Single template, plain str.format, no Jinja

## Installation

```bash
pip install -r requirements.txt
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── development.md
│   └── roadmap.md
├── examples/
│   └── quickstart.md
├── .gitignore
├── CHANGELOG.md
├── build.py
└── requirements.txt
```

## Changelog

- `0.1.1` - fix edge case in argument parsing
- `0.1.0` - first working version
