# Usage

The README covers the basics. This page collects the
longer examples and the notes that did not fit up front.

## Basic

```bash
python batch.py prompts.jsonl -o answers.jsonl --workers 4 --rpm 300
```

## Notes

- Failures go to a sidecar file with error type, message and status
- Per-row overrides for model, system, temperature and max_tokens
