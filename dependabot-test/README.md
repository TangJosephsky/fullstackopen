# dependabot-test

> ⚠️ **These fixtures are intentionally insecure and exist solely to trigger Dependabot vulnerability alerts for testing/demo purposes. Do NOT use these packages in any production or real project.**

This directory contains minimal, isolated `package.json` manifests that pin known-vulnerable npm package versions. GitHub Dependabot will scan them and raise security alerts, which can then be used to exercise Dependabot workflows and alert-management features.

## Fixtures

### `package.json` (fixture-1)

| Package | Pinned version | Known vulnerability |
|---------|---------------|---------------------|
| [lodash](https://www.npmjs.com/package/lodash) | 4.17.15 | [CVE-2021-23337](https://github.com/advisories/GHSA-35jh-r3h4-6jhm) – Command injection via `_.template` |

### `fixture-2/package.json`

| Package | Pinned version | Known vulnerability |
|---------|---------------|---------------------|
| [minimist](https://www.npmjs.com/package/minimist) | 1.2.5 | [CVE-2021-44906](https://github.com/advisories/GHSA-xvch-5gv4-984h) – Prototype pollution |
| [serialize-javascript](https://www.npmjs.com/package/serialize-javascript) | 1.9.1 | [CVE-2020-7660](https://github.com/advisories/GHSA-h9rv-jmmf-4pgx) – Arbitrary code injection |

## Removing these fixtures

Simply delete this directory (`dependabot-test/`) or the individual sub-directories. No application code depends on them.
