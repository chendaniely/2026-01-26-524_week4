# 2026-01-26-pytest

[![codecov](https://codecov.io/github/chendaniely/2026-01-26-524_week4/graph/badge.svg?token=p2ZqsZUSsf)](https://codecov.io/github/chendaniely/2026-01-26-524_week4)

## Lecture 1

- Badges (code coverage + codecov.io)
- Quarto website examples, front page, setup, get started pages
- CI: website deployment preview
- discuss semantic versioning and convensional commits


## Lecture 2

- Semantic release based on tag version
- Licensing

## Class notes

badges and external CI/CD tools:

- code coverage: https://py-pkgs.org/08-ci-cd#recording-code-coverage
    - install code coverage github app
    - find repo
    - click configure
    - setup
        - use github actions
        - select pytest
        - change `--cov-report=xml`
            - pytest --cov --cov-branch --cov-report=xml
        - get token info for CODECOV_TOKEN (from configure page)
        - check for the link (else you probably didn't have a token)
        - refresh the codecoverage repo page
    - badge
        - configuration page there's a badge + graphs section
        - copy the markdown badge (we are using quarto + quartodoc, rst is for sphinx)