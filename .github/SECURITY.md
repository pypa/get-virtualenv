# Security Policy

`public/virtualenv.pyz` is the zipapp [bootstrap.pypa.io](https://bootstrap.pypa.io/virtualenv.pyz) serves. virtualenv's
[release workflow](https://github.com/pypa/virtualenv/blob/main/.github/workflows/release.yaml) builds it, attests its
provenance and commits it here, so a flaw in the zipapp is a flaw in virtualenv.

Report vulnerabilities through [virtualenv's security policy](https://github.com/pypa/virtualenv/security/policy); its
[advisory form](https://github.com/pypa/virtualenv/security/advisories/new) takes private reports. That policy covers
these files too.

[Verify a release](https://virtualenv.pypa.io/en/latest/how-to/verify-release.html) shows how to check that a downloaded
`virtualenv.pyz` came from that workflow.
