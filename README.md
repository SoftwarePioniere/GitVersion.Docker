# GitVersion.Docker

Docker Images for GitVersion 4 - beta

https://github.com/GitTools/GitVersion

## How To Run

_/repo_ have to point to the Repository Root Directory.

Run with PowerShell:
```powershell
docker run --rm -v "$(PWD):/repo" softwarepioniere/gitversion:4.0.0-beta0014
```

Run with Bash:
```bash
docker run --rm -v "${PWD}:/repo" -v "${PWD}:/repo" softwarepioniere/gitversion:4.0.0-beta0014
```