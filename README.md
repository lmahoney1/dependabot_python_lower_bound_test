# dependabot_python_test

Example of dependabot not alerting on vulnerable dependencies specified with only a lower-bound.

```toml
dependencies = [
    "requests >= 2.0.0"
]
```

Was hoping dependabot would bump the lower-bound version to the lowest version without a vulnerability.

Vulnerable dependencies and GitHub advisory entries (not exhaustive - I didn't figure out how to search on package name):
- requests
    - https://github.com/advisories/GHSA-9wx4-h78v-vm56
    - https://github.com/advisories/GHSA-cfj3-7x9c-4p3h
    - https://github.com/advisories/GHSA-652x-xj99-gmcc
    - https://github.com/advisories/GHSA-x84v-xcm2-53pg
- fastapi
    - https://github.com/advisories/GHSA-8h2j-cgx8-6xv7
