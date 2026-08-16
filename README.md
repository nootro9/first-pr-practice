# First PR Practice

A tiny toy project for practicing the GitHub pull request workflow.

## What's here

`convert.py` provides simple temperature conversion helpers:

- `celsius_to_fahrenheit(celsius)`
- `fahrenheit_to_celsius(fahrenheit)`

## Usage

```python
from convert import celsius_to_fahrenheit

celsius_to_fahrenheit(100)  # 212.0
```

## Running tests

```bash
python -m unittest discover -s tests -t .
```

This project is intentionally simple — it exists to receive small, safe first contributions like typo fixes or a missing test.
