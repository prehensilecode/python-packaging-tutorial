A sample Python module.

Following the [Python Packaging Tutorial](https://packaging.python.org/en/latest/tutorials/packaging-projects/)

Added features:
- module-scope "constant"
- command-line script/entrypoint `get_rate`

## Build instructions
1. Requires 
 - `build`
 - `hatchling`
2. `python3 -m build`
3. `python3 -m pip install -U ./dist/foobar-0.0.X-py3-none-any.whl`
