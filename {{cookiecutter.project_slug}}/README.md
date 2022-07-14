# {{ cookiecutter.project_name }}

## About

{{ cookiecutter.project_short_description }}

## Usage

Lorem ipsum.

## Install

### Via PyPI

```bash
pip install {{ cookiecutter.project_slug }}
```

#### Manually

Clone this repo, change into the cloned directory, and install:

```bash
cd {{ cookiecutter.project_slug }}
pip install .
```

## Development

### Testing

To run all tests with tox: `tox`

Or run tests directly with pytest:
```bash
pip install -r requirements/test.txt
pytest
```

### Publishing to PyPI

This repository contains a [Makefile](Makefile) with commands to aid in
building packages and publishing to [PyPI][pypi].

To check that the package is valid:
```bash
make package-check
```

To upload the package to PyPI (this requires PyPI credentials and being
listed as a collaborator on the {{ cookiecutter.project_slug }} project):
```bash
make package-upload
```

To clean up package distribution files:
```bash
make clean
```

## Credits

This package was created with [Cookiecutter](Cookiecutter) and
[Artefactual's fork](Artefactual) of the
[audreyr/cookiecutter-pypackage](pypackage) project template.

[am]: https://archivematica.org
[pypi]: https://pypi.org/
[Cookiecutter]: https://github.com/audreyr/cookiecutter
[Artefactual]: https://github.com/artefactual-labs/cookiecutter-pypackage
[pypackage]: https://github.com/audreyr/cookiecutter-pypackage
