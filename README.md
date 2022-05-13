# App1

> This app is compliant with version [1.0.0](https://github.com/policy-as-versioned-code/policy/releases/tag/1.0.0) of the company policy **only**

## Test policy locally

```bash
$ docker run --rm -ti -v $(pwd):/apps ghcr.io/policy-as-versioned-code/policy-checker
Found kustomization.yaml
Checking policy version...
Policy version: 1.0.0
Fetching Policy...
Policy fetched.
Running policy checker...

Applying 1 policy to 1 resource...
(Total number of result count may vary as the policy is mutated by Kyverno. To check the mutated policy please try with log level 5)

pass: 1, fail: 0, warn: 0, error: 0, skip: 0
```