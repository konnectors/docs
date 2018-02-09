# Konnectors Status

| konnector | master | prod | Issue | Guideline
| :-------: | :----: | :--: | :---: | :-------:
| [ameli] | ![Travis master][ameli-travis-master] ![GitHub master][ameli-gh-master] | ![Travis prod][ameli-travis-prod] ![GitHub prod][ameli-gh-prod] | [![PR][ameli-pr]][ameli-pr-link] [![issue][ameli-issue]][ameli-issue-link] | [![Renovate][renovate-ok]](#renovate) ![readme][readme-ko] ![Auto Build][autobuild-ko] [![Git Branch][branch-ko]](#git-branch) [![Organisation][orga-ok]](#organisation)

[ameli]: https://gitub.com/konnectors/cozy-konnector-ameli
[ameli-travis-master]: https://img.shields.io/travis/konnectors/cozy-konnector-ameli/master.svg?style=flat-square
[ameli-travis-prod]: https://img.shields.io/travis/konnectors/cozy-konnector-ameli/prod.svg?style=flat-square
[ameli-gh-master]: https://img.shields.io/github/last-commit/konnectors/cozy-konnector-ameli/master.svg?style=flat-square
[ameli-gh-prod]: https://img.shields.io/github/last-commit/konnectors/cozy-konnector-ameli/prod.svg?style=flat-square
[ameli-pr]: https://img.shields.io/github/issues-pr/konnectors/cozy-konnector-ameli.svg?style=flat-square
[ameli-pr-link]: https://github.com/konnectors/cozy-konnector-ameli/pulls
[ameli-issue]: https://img.shields.io/github/issues/konnectors/cozy-konnector-ameli.svg?style=flat-square
[ameli-issue-link]: https://github.com/konnectors/cozy-konnector-ameli/issues

## Guidelines

### Organisation

Git repository is on [Konnectors](https://github.com/konnectors/) organisation on Github.

If that is the case [![Organisation][orga-ok]](#organisation) else [![Organisation][orga-ko]](#organisation).

[orga-ok]: https://img.shields.io/badge/Organisation-Ok-brightgreen.svg?style=flat-square
[orga-ko]: https://img.shields.io/badge/Organisation-Not%20yet-lightgrey.svg?style=flat-square

### New Readme

If that is the case [![Readme][readme-ok]](#new-readme) else [![Readme][readme-ko]](#new-readme).

[readme-ok]: https://img.shields.io/badge/readme-Ok-brightgreen.svg?style=flat-square
[readme-ko]: https://img.shields.io/badge/readme-Not%20yet-lightgrey.svg?style=flat-square

### Renovate

Renovate is an open source tool to keep source code dependencies up-to-date using automated Pull Requests.

If is installed we add [![Renovate][renovate-ok]](#renovate) else [![Renovate][renovate-ko]](#renovate).

[renovate-ok]: https://img.shields.io/badge/Renovate-Ok-brightgreen.svg?style=flat-square
[renovate-ko]: https://img.shields.io/badge/Renovate-Not%20yet-lightgrey.svg?style=flat-square

### Auto build

To remove human errors we want the connectors to build automatically:

- When there are changes on the branch #master, Travis must make an automatic build on the #build branch
- When there are changes on the branch #prod, Travis must make an automatic build on the #latest branch

If that is the case [![Auto Build][autobuild-ok]](#auto-build) else [![Auto Build][autobuild-ko]](#auto-build).

[autobuild-ok]: https://img.shields.io/badge/Auto%20Build-Ok-brightgreen.svg?style=flat-square
[autobuild-ko]: https://img.shields.io/badge/Auto%20Build-Not%20yet-lightgrey.svg?style=flat-square

### Git Branch

The Git repository must contain 4 branches:

- master: The sources of the latest developments
- build: The build of #master
- prod: The sources in production
- latest: The build of #prod

If that is the case [![Git Branch][branch-ok]](#git-branch) else [![Git Branch][branch-ko]](#git-branch).

[branch-ok]: https://img.shields.io/badge/Branch-Ok-brightgreen.svg?style=flat-square
[branch-ko]: https://img.shields.io/badge/Branch-Not%20yet-lightgrey.svg?style=flat-square
