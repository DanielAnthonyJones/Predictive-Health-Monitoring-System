# Predictive-Health-Monitoring-System
A project for an app prediciting and monitoring risk of diabetes and potentially further health conditions.

## Problem

...

## Getting started

Requires [uv](https://docs.astral.sh/uv/) and Python 3.13.

```bash
git clone https://github.com/DanielAnthonyJones/Predictive-Health-Monitoring-System.git
cd Predictive-Health-Monitoring-System
uv sync
uv run pre-commit install
```

Dataset [data/README.md](data/README.md).

## Development

```bash
uv run pytest                      # tests
uv run pre-commit run --all-files  # all checks
```
Checks are run automatically every commit and in CI. Changes are maid through a pull request that passes all checks.

## Author

Daniel Jones - BSc (Hons) Data Science and Analytics, University of Westminster
