# Contributing to EntropyAudit

Thanks for considering a contribution. EntropyAudit is a static auditor: it
parses Python source with the standard library `ast` module and never executes
the code it reads.

## Development setup

- Python 3.11+. There is nothing to install; the package uses the standard
  library only.

```bash
python -m compileall -q src
PYTHONPATH=src python -m unittest discover -s tests -v
