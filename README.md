Semver Demo
===

Repo Structure
---

**Failing Build** on branch `version3`

**Succeeding Build** on branch `version2.3`

Building
---
`docker run --rm -v ./:/data mcr.microsoft.com/dotnet/sdk:9.0 sh /data/build.sh`