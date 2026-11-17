# lucreadorn5n-kit

Validate JSON files and print a normalized form.

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m lucreadorn5n_kit.cli --help
```

```python
from lucreadorn5n_kit.core import Lucreadorn5nTool

tool = Lucreadorn5nTool()
print(tool)
```

## Layout

```
lucreadorn5n_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 lucreadorn5n
