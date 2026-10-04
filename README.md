# ft_package

A useful test package for 42 Python Piscine.

## Build

To build the package distribution archives, run `build`:

```bash
python3 -m build
```

This will generate the source distribution and wheel archive inside the `dist/` directory:
- `dist/ft_package-0.0.1.tar.gz`
- `dist/ft_package-0.0.1-py3-none-any.whl`

## Installation

Install using one of the built distributions:

```bash
pip install ./dist/ft_package-0.0.1.tar.gz
# or
pip install ./dist/ft_package-0.0.1-py3-none-any.whl
```

Verify the installation:

```bash
pip show -v ft_package
```

## Usage

```python
from ft_package import count_in_list

print(count_in_list(["toto", "tata", "toto"], "toto"))  # output: 2
print(count_in_list(["toto", "tata", "toto"], "tutu"))  # output: 0
```
