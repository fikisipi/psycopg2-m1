psycopg2-m1: an Apple Silicon binary for the psycopg2 Postgres adapter
=============================================

### `pip install psycopg2-m1`

[![M1 wheel build](https://github.com/fikisipi/psycopg2-m1/actions/workflows/packages.yml/badge.svg)](https://github.com/fikisipi/psycopg2-m1/actions/workflows/packages.yml)

* Versions targeted: 3.7, 3.8, 3.9, 3.10
* Build: [GitHub Action](https://github.com/fikisipi/psycopg2-m1/blob/master/.github/workflows/packages.yml)

### Disclaimer

The author and repo are not affiliated with the original `psycopg2` and `psycopg2-binary` projects. 

### TODO

Set up an action that will publicly announce & provision an M1 Action Runner instance to produce the binary in a tamper-proof way.

### FAQ: How to run M1 Github Actions

Use https://github.com/mas-cli/m1-github-actions-runner on an M1 machine and prefix your build with `arch -arm64e <command>`
