# winzy-weather

[![PyPI](https://img.shields.io/pypi/v/winzy-weather.svg)](https://pypi.org/project/winzy-weather/)
[![Changelog](https://img.shields.io/github/v/release/sukhbinder/winzy-weather?include_prereleases&label=changelog)](https://github.com/sukhbinder/winzy-weather/releases)
[![Tests](https://github.com/sukhbinder/winzy-weather/workflows/Test/badge.svg)](https://github.com/sukhbinder/winzy-weather/actions?query=workflow%3ATest)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/sukhbinder/winzy-weather/blob/main/LICENSE)

Weather using the excellent wttr.in

## Installation

First configure your Winzy project [to use Winzy](https://github.com/sukhbinder/winzy).

Then install this plugin in the same environment as your Winzy application.
```bash
pip install winzy-weather
```
## Usage

Usage instructions go here.

## Development

To set up this plugin locally, first checkout the code. Then create a new virtual environment:
```bash
cd winzy-weather
python -m venv venv
source venv/bin/activate
```
Now install the dependencies and test dependencies:
```bash
pip install -e '.[test]'
```
To run the tests:
```bash
python -m pytest
```
