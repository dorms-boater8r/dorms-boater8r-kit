# dorms-boater8r-kit

Summarize numeric CSV columns (n / min / max / mean).

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m dorms_boater8r_kit.cli --help
```

```python
from dorms_boater8r_kit.core import DormsBoater8rTool

tool = DormsBoater8rTool()
print(tool)
```

## Layout

```
dorms_boater8r_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 dorms-boater8r
