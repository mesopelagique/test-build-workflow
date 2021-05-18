# test-build-workflow

Repository used to test database https://github.com/mesopelagique/build-action without the action, just the database and github workflow

⚠️ The current workflow reference `${{ secrets.SERVER_URL }}` so if you copy it in your repository you must provide the URL to download a 4D v19 instance in your [repository secret](https://docs.github.com/en/actions/reference/encrypted-secrets).
> The url to define secrets is `https://github.com/<owner>/<reponame>/settings/secrets/actions`

## main branch

[![build](https://github.com/mesopelagique/test-build-workflow/actions/workflows/build.yml/badge.svg)](https://github.com/mesopelagique/test-build-workflow/actions/workflows/build.yml?query=branch%3Amain)

## branch with compilation failure

[![build](https://github.com/mesopelagique/test-build-workflow/actions/workflows/build.yml/badge.svg?branch=feature%2Ffailure)](https://github.com/mesopelagique/test-build-workflow/actions/workflows/build.yml?query=branch%3Afeature%2Ffailure)

## download last release compiled and attached

[![release](https://img.shields.io/github/v/release/mesopelagique/test-build-workflow.svg)](https://github.com/mesopelagique/test-build-workflow/releases/latest)

status of release

[![release workflow](https://github.com/mesopelagique/test-build-workflow/actions/workflows/release.yml/badge.svg)](https://github.com/mesopelagique/test-build-workflow/actions/workflows/release.yml)
