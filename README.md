[![Creative Commons License](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](http://creativecommons.org/licenses/by-nc-sa/4.0/).


# Data Management Plan "emlp-md"

This repository contains the version history of the data management plan for the project:

> Groundbreaking models for spectroscopy and charge transport in molecular dynamics simulations

To rebuild and work on the data management plan, `dmp.pdf`,
you need to set up the repository as follows:

```bash
git clone git@github.com:reproducible-reporting/dmp-emlp-md .git
cd dmp-emlp-md
./setup-venv-pip.sh
direnv allow
pre-commit install
stepup -n
```

This is a living document of which the latest Git commit contains the most up-to-date information.
No version numbers are assigned.
