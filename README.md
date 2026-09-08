# similardocs

Search my markdown notes by meaning, not keywords

Started as a weekend hack, grew on me.

## Features

- sentence-transformers when available, TF-IDF fallback
- Interactive REPL and one-shot modes
- Vectors cached to .npy so re-runs are instant
- Reranks by recency when scores tie

## Getting started

```bash
pip install -r requirements.txt
```

## How to use

```bash
python search.py ./notes
>> how do I back up my database?
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── tests/
│   └── test_smoke.py
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── LICENSE
├── requirements.txt
└── search.py
```

## Development

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
python -m pytest -q
```

## Changelog

- `0.1.1` - fix edge case in argument parsing
- `0.1.0` - first working version

## License

MIT - see [LICENSE](LICENSE).
