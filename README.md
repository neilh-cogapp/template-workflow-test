# template-workflow-test

[![PyPI](https://img.shields.io/pypi/v/template-workflow-test.svg)](https://pypi.org/project/template-workflow-test/)
[![Changelog](https://img.shields.io/github/v/release/neilh-cogapp/template-workflow-test?include_prereleases&label=changelog)](https://github.com/neilh-cogapp/template-workflow-test/releases)
[![Tests](https://github.com/neilh-cogapp/template-workflow-test/actions/workflows/test.yml/badge.svg)](https://github.com/neilh-cogapp/template-workflow-test/actions/workflows/test.yml)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/neilh-cogapp/template-workflow-test/blob/master/LICENSE)

null

## Installation

Install this tool using `pip`:
```bash
pip install template-workflow-test
```
## Usage

For help, run:
```bash
template-workflow-test --help
```
You can also use:
```bash
python -m template_workflow_test --help
```
## Development

To contribute to this tool, first checkout the code. Then create a new virtual environment:
```bash
cd template-workflow-test
python -m venv venv
source venv/bin/activate
```
Now install the dependencies and test dependencies:
```bash
pip install -e '.[test]'
```
To run the tests:
```bash
pytest
```
