# Project Status Badges

<sup>By [Esoteric Enderman][author]</sup>

[![Project status: unfinished][status]](#unfinished)

Badges for quickly and easily indicating the [status](#project-status) of a project.

Project Status Badges are a collection of [4 unique status badges][badges] that you can use to indicate the [development status](#project-status) of your project. For example, you can put them in your project's README.md file.

The badges were derived from [Shields.io Badges][shields], a [CC0][shields-license-statement] project which provides badges as a service. This means that the [project status badges][badges] will be visually compatible with the [Shields.io Badges][shields] - so you can use both in your project's README.md file.

## Features

* [Project Status Badge: 'Maintained'][maintained]
* [Project Status Badge: 'Finished'][finished]
* [Project Status Badge: 'Unfinished'][unfinished]
* [Project Status Badge: 'Abandoned'][abandoned]

## Usage

### Copying The Badge (Recommended)

1. Copy-paste the badge(s) you want to use into your project. To keep things organised you can put the badge(s) in a folder such as `assets/images/badges`.
2. Add the following text to your `README.md` file:
   ```markdown
   [![Project status: CURRENT_PROJECT_STATUS](./assets/images/badges/CURRENT_PROJECT_STATUS.svg)](https://gitlab.com/esoterictemplates/assets/images/symbols/project-status-badges/-/tree/VERSION#CURRENT_PROJECT_STATUS)
   ```

   Alternatively, you can use link aliases to keep things short and organised.

   ```markdown
   [![Project status: CURRENT_PROJECT_STATUS][status]][project-status]

   [status]: ./assets/images/badges/CURRENT_PROJECT_STATUS.svg
   [project-status]: https://gitlab.com/esoterictemplates/assets/images/symbols/project-status-badges/-/tree/VERSION#CURRENT_PROJECT_STATUS
   ```

   Replace:
   * `CURRENT_PROJECT_STATUS` with the lowercase project status you want to use; and
   * `VERSION` with the [version](#versions) of the badge you want to use. You may want to use `master` instead, which will link to the most up-to-date explanation of the project status.

   > [!NOTE]
   > If you put your badge into a different folder or named the file differently, you will need to adjust the file path so that it leads to the correct location.

### Linking To This Repository

1. Add the following text to your `README.md` file:
   ```markdown
   [![Project status: CURRENT_PROJECT_STATUS](https://gitlab.com/esoterictemplates/assets/images/symbols/project-status-badges/-/raw/VERSION/assets/images/badges/CURRENT_PROJECT_STATUS.svg)](https://gitlab.com/esoterictemplates/assets/images/symbols/project-status-badges/-/tree/VERSION#CURRENT_PROJECT_STATUS)
   ```

   Alternatively, you can use link aliases to keep things short and organised.

   ```markdown
   [![Project status: CURRENT_PROJECT_STATUS][status]][project-status]

   [status]: https://gitlab.com/esoterictemplates/assets/images/symbols/project-status-badges/-/raw/VERSION/assets/images/badges/CURRENT_PROJECT_STATUS.svg
   [project-status]: https://gitlab.com/esoterictemplates/assets/images/symbols/project-status-badges/-/tree/VERSION#CURRENT_PROJECT_STATUS
   ```

   Replace:
   * `CURRENT_PROJECT_STATUS` with the lowercase project status you want to use; and
   * `VERSION` with the [version](#versions) of the badge you want to use. You may want to use `master` instead, which will link to the most up-to-date explanation of the project status.

   > [!WARNING]
   > If this repository ever goes offline, links to the badges will stop working!

## Versions

This repository uses the format `badge-version` for its tags, where:
* `badge` is the lowercase project status (e.g., `maintained`, `abandoned`); and
* `version` is the [Semantic Versioning][semver] string which describes the version of the `badge`.

## Links

* [GitLab][project-gitlab]
* [GitHub][project-github]
* [Gitea][project-gitea]
* [GitGud][project-gitgud]
* [GitFlic][project-gitflic]
* [git.gay][project-git.gay]
* [Bitbucket][project-bitbucket]
* [Buddy][project-buddy]
* [Codeberg][project-codeberg]
* [Disroot][project-disroot]
* [Moe's Git][project-moe-git]
* [FramaGit][project-framagit]
* [SourceForge][project-sourceforge]
* [tangled][project-tangled]
* [〄.ai][project-sij.ai]
* [Launchpad][project-launchpad]
* [pub.solar][project-pub.solar]
* [repo.or.cz][project-repo.or.cz]
* [HelixTeamHub][project-helixteamhub]
* [Credit][credit]

## Project Status

This system defines **4 distinct states** at which a project can be:

* [Maintained][maintained]
* [Finished][finished]
* [Unfinished][unfinished]
* [Abandoned][abandoned]

These statuses can be organised and described by the following table:

| v [Stable version](#stable-versions)? \ [WIP](#work-in-progress-projects)? > | Yes                                               | No                                              |
|------------------------------------------------------------------------------|---------------------------------------------------|-------------------------------------------------|
| Yes                                                                          | ![Project Status Badge: 'Maintained'][maintained] | ![Project Status Badge: 'Finished'][finished]   |
| No                                                                           | ![Project Status Badge: 'Unfinished'][unfinished] | ![Project Status Badge: 'Abandoned'][abandoned] |

### Stable Versions

A **stable version** of a project is defined as a version or revision of the project that you would consider *complete* - it should:

* contain all of the features that were originally planned for the project; and
* not contain any known bugs (ideally, it shouldn't contain any bugs or issues).

### Work in Progress Projects

A project is **work in progress** if:

* it may still be updated in the future; or
* it is actively being developed right now.

### Maintained

![Project Status Badge: 'Maintained'][maintained]

**Maintained** projects are mature, have at least one [stable version](#stable-versions) and are still being *developed*, or they are simply being *kept up-to-date*. This is the 'ideal' state for a project.

### Finished

![Project Status Badge: 'Finished'][finished]

**Finished** projects are self-explanatory: the project has been marked as *complete* and won't be worked on anymore. This is the best-case scenario for projects you don't want to work on anymore.

### Unfinished

![Project Status Badge: 'Unfinished'][unfinished]

**Unfinished** projects are still in a *work-in-progress* state and may not have all of their intended features implemented. There may be bugs or issues.

### Abandoned

![Project Status Badge: 'Abandoned'][abandoned]

**Abandoned** projects are those which do not have a stable (complete) version and which the author(s) decided are not worth working on anymore.

## Verification

The [badges][badges] and [icon][icon] of this project have been verified using the [W3C Markup Validation Service][markup-validator]. See the output for yourself here:

* [Maintained][maintained-validation]
* [Finished][finished-validation]
* [Unfinished][unfinished-validation]
* [Abandoned][abandoned-validation]
* [Icon][icon-validation]

## License

ISC License

Copyright 2025 Esoteric Enderman

Permission to use, copy, modify, and/or distribute this software for any purpose with or without fee is hereby granted, provided that the above copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.

## Topics

<sup>[svg](https://gitlab.com/explore/projects/topics/svg), [readme](https://gitlab.com/explore/projects/topics/readme), [image](https://gitlab.com/explore/projects/topics/image), [images](https://gitlab.com/explore/projects/topics/images), [badge](https://gitlab.com/explore/projects/topics/badge), [readme-badges](https://gitlab.com/explore/projects/topics/readme-badges), [badges](https://gitlab.com/explore/projects/topics/badges)</sup>

<!--- Link aliases --->

[project]: ./

[project-gitlab]: https://gitlab.com/esoterictemplates/assets/images/symbols/project-status-badges
[project-github]: https://github.com/esoterictemplates/project-status-badges
[project-gitea]: https://gitea.com/esoterictemplates/project-status-badges
[project-gitgud]: https://gitgud.io/templates/assets/images/symbols/project-status-badges
[project-gitflic]: https://gitflic.ru/project/esoterictemplates/project-status-badges
[project-git.gay]: https://git.gay/templates/project-status-badges
[project-bitbucket]: https://bitbucket.org/esotericenderman/project-status-badges/
[project-buddy]: https://eu.buddy.works/enderman/project-status-badges
[project-codeberg]: https://codeberg.org/esoterictemplates/project-status-badges
[project-disroot]: https://git.disroot.org/templates/project-status-badges
[project-moe-git]: https://git.moe.team/esoterictemplates/project-status-badges
[project-framagit]: https://framagit.org/esoterictemplates/assets/images/symbols/project-status-badges
[project-sij.ai]: https://sij.ai/enderman/project-status-badges
[project-launchpad]: https://launchpad.net/badges
[project-sourcehut]: https://git.sr.ht/~enderman/project-status-badges
[project-sourceforge]: https://sourceforge.net/projects/badges/
[project-tangled]: https://tangled.sh/@enderman.dev/project-status-badges
[project-pub.solar]: https://git.pub.solar/templates/project-status-badges
[project-helixteamhub]: https://helixteamhub.cloud/enderman/projects/templates/repositories/project-status-badges
[project-repo.or.cz]: https://repo.or.cz/badges.git

[author]: https://enderman.dev

<!--- Links --->

[cc]: https://creativecommons.org/

[shields]: https://shields.io/badges
[shields-license-statement]: https://github.com/badges/shields/tree/29e39351ae557d536580d90521c390514b867e19?tab=readme-ov-file#license

[semver]: https://semver.org/

<!--- Markup Validation Service --->

[markup-validator]: https://validator.w3.org/

[maintained-validation]: https://validator.w3.org/check?uri=https%3A%2F%2Fgitlab.com%2Fesoterictemplates%2Fassets%2Fimages%2Fsymbols%2Fproject-status-badges%2F-%2Fraw%2Fmaster%2Fassets%2Fimages%2Fbadges%2Fmaintained.svg%3Fref_type%3Dheads&charset=%28detect+automatically%29&doctype=Inline&group=0
[finished-validation]: https://validator.w3.org/check?uri=https%3A%2F%2Fgitlab.com%2Fesoterictemplates%2Fassets%2Fimages%2Fsymbols%2Fproject-status-badges%2F-%2Fraw%2Fmaster%2Fassets%2Fimages%2Fbadges%2Ffinished.svg%3Fref_type%3Dheads&charset=%28detect+automatically%29&doctype=Inline&group=0&user-agent=W3C_Validator%2F1.3+
[unfinished-validation]: https://validator.w3.org/check?uri=https%3A%2F%2Fgitlab.com%2Fesoterictemplates%2Fassets%2Fimages%2Fsymbols%2Fproject-status-badges%2F-%2Fraw%2Fmaster%2Fassets%2Fimages%2Fbadges%2Funfinished.svg%3Fref_type%3Dheads&charset=%28detect+automatically%29&doctype=Inline&group=0&user-agent=W3C_Validator%2F1.3+
[abandoned-validation]: https://validator.w3.org/check?uri=https%3A%2F%2Fgitlab.com%2Fesoterictemplates%2Fassets%2Fimages%2Fsymbols%2Fproject-status-badges%2F-%2Fraw%2Fmaster%2Fassets%2Fimages%2Fbadges%2Fabandoned.svg%3Fref_type%3Dheads&charset=%28detect+automatically%29&doctype=Inline&group=0&user-agent=W3C_Validator%2F1.3+

[icon-validation]: https://validator.w3.org/check?uri=https%3A%2F%2Fgitlab.com%2Fesoterictemplates%2Fassets%2Fimages%2Fsymbols%2Fproject-status-badges%2F-%2Fraw%2Fmaster%2Fdocs%2Fassets%2Fimages%2Ficons%2Fproject-status-badges%2Ficon.svg%3Fref_type%3Dheads&charset=%28detect+automatically%29&doctype=Inline&group=0&user-agent=W3C_Validator%2F1.3+

<!--- Files --->

[license]: ./LICENSE

[credit]: ./docs/CREDIT.md

[badges]: ./assets/images/badges/
[icon]: ./docs/assets/images/icons/project-status-badges/icon.svg

<!--- Badges --->

[status]: ./assets/images/badges/unfinished.svg

[maintained]: ./assets/images/badges/maintained.svg
[finished]: ./assets/images/badges/finished.svg
[unfinished]: ./assets/images/badges/unfinished.svg
[abandoned]: ./assets/images/badges/abandoned.svg

<!--
Credit
======

The ISC License <https://www.isc.org/licenses/>
===============
Copyright (c) 1995-2003 Internet Software Consortium <https://www.isc.org/>
Copyright (c) 2004-2013 Internet Systems Consortium Incorporated (ISC) <https://www.isc.org/>
Licensed "like SPDX: 0BSD" <https://www.isc.org/licenses/>
-->
