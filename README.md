# Project Status Badges

<sup>By [Esoteric Enderman][author]</sup>

[![Project status: maintained][status]](#maintained)

Badges for quickly and easily indicating the [status](#project-status) of a project.

Project Status Badges are a collection of [unique status badges][badges] that you can use to indicate the [development status](#project-status) of your project. For example, you can put them in your project's `README.md` file.

The badges were derived from [Shields.io Badges][shields], a [CC0][shields-license-statement] project which provides badges as a service. This means that the [project status badges][badges] will be visually compatible with the [Shields.io Badges][shields] - so you can use both in your project.

## Features

* [Project Status Badge: 'Maintained'][maintained]
* [Project Status Badge: 'Finished'][finished]
* [Project Status Badge: 'Unfinished'][unfinished]
* [Project Status Badge: 'Abandoned'][abandoned]

## Usage

### Copying The Badge (Recommended)

1. Copy-paste the badge(s) you want to use into your project. To keep things organised you can put the badge(s) in a folder such as `assets/images/badges`.

> [!NOTE]
> If you put your badge into a different folder or named the file differently, you will need to adjust the file paths so that they lead to the correct location.

#### Markdown

2. Add the following text to your file:
   ```markdown
   [![Project status: CURRENT_PROJECT_STATUS](./assets/images/badges/CURRENT_PROJECT_STATUS.svg "The status of this project")](https://gitlab.com/esoterictemplates/assets/images/symbols/project-status-badges/-/tree/DOCUMENTATION_VERSION#CURRENT_PROJECT_STATUS "The status of this project")
   ```

   Alternatively, you can use link aliases to keep things short and organised.

   ```markdown
   [![Project status: CURRENT_PROJECT_STATUS][status]][project-status]

   [status]: ./assets/images/badges/CURRENT_PROJECT_STATUS.svg (The status of this project)
   [project-status]: https://gitlab.com/esoterictemplates/assets/images/symbols/project-status-badges/-/tree/DOCUMENTATION_VERSION#CURRENT_PROJECT_STATUS (The status of this project)
   ```

   Replace:
   * `CURRENT_PROJECT_STATUS` with the lowercase project status you want to use; and
   * `DOCUMENTATION_VERSION` with the [documentation version](#versions) you want to use.

### Linking To This Repository

> [!WARNING]
> If this repository ever goes offline, links to the badges will stop working! In that case, images will no longer load if you [link to this repository](#linking-to-this-repository).

#### Markdown

1. Add the following text to your file:
   ```markdown
   [![Project status: CURRENT_PROJECT_STATUS](https://gitlab.com/esoterictemplates/assets/images/symbols/project-status-badges/-/raw/VERSION/assets/images/badges/CURRENT_PROJECT_STATUS.svg "The status of this project")](https://gitlab.com/esoterictemplates/assets/images/symbols/project-status-badges/-/tree/DOCUMENTATION_VERSION#CURRENT_PROJECT_STATUS "The status of this project")
   ```

   Alternatively, you can use link aliases to keep things short and organised.

   ```markdown
   [![Project status: CURRENT_PROJECT_STATUS][status]][project-status]

   [status]: https://gitlab.com/esoterictemplates/assets/images/symbols/project-status-badges/-/raw/VERSION/assets/images/badges/CURRENT_PROJECT_STATUS.svg (The status of this project)
   [project-status]: https://gitlab.com/esoterictemplates/assets/images/symbols/project-status-badges/-/tree/DOCUMENTATION_VERSION#CURRENT_PROJECT_STATUS (The status of this project)
   ```

   Replace:
   * `CURRENT_PROJECT_STATUS` with the lowercase project status you want to use;
   * `VERSION` with the [version](#versions) of the badge you want to use; and
   * `DOCUMENTATION_VERSION` with the [documentation version](#versions) you want to use.

## Versions

This repository uses the format `badge-version` for its tags, where:
* `badge` is the lowercase project status (e.g., `maintained`, `abandoned`); and
* `version` is the [Semantic Versioning][semver] string which describes the version of the `badge`.

This repository also uses regular [Semantic Versioning][semver] strings for the documentation (the [explanations](#project-status) of the project status).

You can also use the name of a branch in [links](#usage) to get the most recent badges and documentation on that branch. Use the `main` branch to be fully up-to-date.

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
* [Azure DevOps][project-devops]
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

* contain all of the features that were originally planned for the project (if any); and
* not contain any known bugs or issues (ideally, it shouldn't contain any bugs or issues).

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

**Abandoned** projects are those which do not have a [stable (complete) version](#stable-versions) and which the author(s) decided are not worth working on anymore.

## Verification

The [badges][badges] and [icon][icon] of this project have been verified using the [Nu HTML Checker][nu-markup-validator], [W3C Markup Validation Service][markup-validator], and the [W3C RDF Validation Service][rdf-validator]. See the output for yourself here:

### Markup Validation

#### Nu

* [Maintained][nu-maintained-validation]
* [Finished][nu-finished-validation]
* [Unfinished][nu-unfinished-validation]
* [Abandoned][nu-abandoned-validation]
* [Icon][nu-icon-validation]

#### W3C

* [Maintained][maintained-validation]
* [Finished][finished-validation]
* [Unfinished][unfinished-validation]
* [Abandoned][abandoned-validation]
* [Icon][icon-validation]

### RDF Validation

* [Maintained][maintained-rdf-validation]
* [Finished][finished-rdf-validation]
* [Unfinished][unfinished-rdf-validation]
* [Abandoned][abandoned-rdf-validation]
* [Icon][icon-rdf-validation]

## License

ISC License

Copyright 2025 Esoteric Enderman

Permission to use, copy, modify, and/or distribute this software for any purpose with or without fee is hereby granted, provided that the above copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.

## Topics

<sup>[badge](https://gitlab.com/explore/projects/topics/badge "GitLab topic: 'badge'"), [badges](https://gitlab.com/explore/projects/topics/badges "GitLab topic: 'badges'"), [image](https://gitlab.com/explore/projects/topics/image "GitLab topic: 'image'"), [images](https://gitlab.com/explore/projects/topics/images "GitLab topic: 'images'"), [readme](https://gitlab.com/explore/projects/topics/readme "GitLab topic: 'readme'"), [readme-badges](https://gitlab.com/explore/projects/topics/readme-badges "GitLab topic: 'readme-badges'"), [svg](https://gitlab.com/explore/projects/topics/svg "GitLab topic: 'svg'")</sup>

[project]: ./ (This project)

[project-gitlab]: https://gitlab.com/esoterictemplates/assets/images/symbols/project-status-badges (This project on GitLab)
[project-github]: https://github.com/esoterictemplates/project-status-badges (This project on GitHub)
[project-gitea]: https://gitea.com/esoterictemplates/project-status-badges (This project on Gitea)
[project-gitgud]: https://gitgud.io/templates/assets/images/symbols/project-status-badges (This project on GitGud)
[project-gitflic]: https://gitflic.ru/project/esoterictemplates/project-status-badges (This project on GitFlic)
[project-git.gay]: https://git.gay/templates/project-status-badges (This project on git.gay)
[project-bitbucket]: https://bitbucket.org/esotericenderman/project-status-badges/ (This project on Bitbucket)
[project-buddy]: https://eu.buddy.works/enderman/project-status-badges (This project on Buddy)
[project-codeberg]: https://codeberg.org/esoterictemplates/project-status-badges (This project on Codeberg)
[project-disroot]: https://git.disroot.org/templates/project-status-badges (This project on Disroot)
[project-moe-git]: https://git.moe.team/esoterictemplates/project-status-badges (This project on Moe's Git)
[project-framagit]: https://framagit.org/esoterictemplates/assets/images/symbols/project-status-badges (This project on FramaGit)
[project-sij.ai]: https://sij.ai/enderman/project-status-badges (This project on 〄.ai)
[project-launchpad]: https://launchpad.net/badges (This project on Launchpad)
[project-devops]: https://dev.azure.com/esoterictemplates/Project%20Status%20Badges/_git/Project%20Status%20Badges (This project on Azure DevOps)
[project-sourceforge]: https://sourceforge.net/projects/badges/ (This project on SourceForge)
[project-tangled]: https://tangled.sh/@enderman.dev/project-status-badges (This project on tangled)
[project-pub.solar]: https://git.pub.solar/templates/project-status-badges (This project on pub.solar)
[project-helixteamhub]: https://helixteamhub.cloud/enderman/projects/templates/repositories/project-status-badges (This project on HelixTeamHub)
[project-repo.or.cz]: https://repo.or.cz/badges.git (This project on repo.or.cz)

[author]: https://enderman.dev (Esoteric Enderman's website)


[cc]: https://creativecommons.org/ (Creative Commons)

[shields]: https://shields.io/badges (Shields.io Badges)
[shields-license-statement]: https://github.com/badges/shields/tree/29e39351ae557d536580d90521c390514b867e19?tab=readme-ov-file#license (The Shields.io Badges license statement)

[semver]: https://semver.org/ (Semantic Versioning)


[markup-validator]: https://validator.w3.org/ (The W3C Markup Validator)
[nu-markup-validator]: https://validator.nu/ (The Nu Markup Validator)
[rdf-validator]: https://www.w3.org/RDF/Validator/ (The W3C RDF Validator)

[maintained-validation]: https://validator.w3.org/check?uri=https%3A%2F%2Fgitlab.com%2Fesoterictemplates%2Fassets%2Fimages%2Fsymbols%2Fproject-status-badges%2F-%2Fraw%2Fmain%2Fassets%2Fimages%2Fbadges%2Fmaintained.svg%3Fref_type%3Dheads&charset=%28detect+automatically%29&doctype=Inline&group=0&user-agent=W3C_Validator%2F1.3+ (The markup validation of the "maintained" project status badge)
[finished-validation]: https://validator.w3.org/check?uri=https%3A%2F%2Fgitlab.com%2Fesoterictemplates%2Fassets%2Fimages%2Fsymbols%2Fproject-status-badges%2F-%2Fraw%2Fmain%2Fassets%2Fimages%2Fbadges%2Ffinished.svg%3Fref_type%3Dheads&charset=%28detect+automatically%29&doctype=Inline&group=0&user-agent=W3C_Validator%2F1.3+ (The markup validation of the "finished" project status badge)
[unfinished-validation]: https://validator.w3.org/check?uri=https%3A%2F%2Fgitlab.com%2Fesoterictemplates%2Fassets%2Fimages%2Fsymbols%2Fproject-status-badges%2F-%2Fraw%2Fmain%2Fassets%2Fimages%2Fbadges%2Funfinished.svg%3Fref_type%3Dheads&charset=%28detect+automatically%29&doctype=Inline&group=0&user-agent=W3C_Validator%2F1.3+ (The markup validation of the "unfinished" project status badge)
[abandoned-validation]: https://validator.w3.org/check?uri=https%3A%2F%2Fgitlab.com%2Fesoterictemplates%2Fassets%2Fimages%2Fsymbols%2Fproject-status-badges%2F-%2Fraw%2Fmain%2Fassets%2Fimages%2Fbadges%2Fabandoned.svg%3Fref_type%3Dheads&charset=%28detect+automatically%29&doctype=Inline&group=0&user-agent=W3C_Validator%2F1.3+ (The markup validation of the "abandoned" project status badge)

[icon-validation]: https://validator.w3.org/check?uri=https%3A%2F%2Fgitlab.com%2Fesoterictemplates%2Fassets%2Fimages%2Fsymbols%2Fproject-status-badges%2F-%2Fraw%2Fmain%2Fdocs%2Fassets%2Fimages%2Ficons%2Fproject-status-badges%2Ficon.svg%3Fref_type%3Dheads&charset=%28detect+automatically%29&doctype=Inline&group=0&user-agent=W3C_Validator%2F1.3+ (The markup validation of this project's icon)


[nu-maintained-validation]: https://validator.nu/?showsource=yes&doc=https%3A%2F%2Fgitlab.com%2Fesoterictemplates%2Fassets%2Fimages%2Fsymbols%2Fproject-status-badges%2F-%2Fraw%2Fmain%2Fassets%2Fimages%2Fbadges%2Fmaintained.svg%3Fref_type%3Dheads (The markup validation of the "maintained" project status badge)
[nu-finished-validation]: https://validator.nu/?showsource=yes&doc=https%3A%2F%2Fgitlab.com%2Fesoterictemplates%2Fassets%2Fimages%2Fsymbols%2Fproject-status-badges%2F-%2Fraw%2Fmain%2Fassets%2Fimages%2Fbadges%2Ffinished.svg%3Fref_type%3Dheads (The markup validation of the "finished" project status badge)
[nu-unfinished-validation]: https://validator.nu/?showsource=yes&doc=https%3A%2F%2Fgitlab.com%2Fesoterictemplates%2Fassets%2Fimages%2Fsymbols%2Fproject-status-badges%2F-%2Fraw%2Fmain%2Fassets%2Fimages%2Fbadges%2Funfinished.svg%3Fref_type%3Dheads (The markup validation of the "unfinished" project status badge)
[nu-abandoned-validation]: https://validator.nu/?showsource=yes&doc=https%3A%2F%2Fgitlab.com%2Fesoterictemplates%2Fassets%2Fimages%2Fsymbols%2Fproject-status-badges%2F-%2Fraw%2Fmain%2Fassets%2Fimages%2Fbadges%2Fabandoned.svg%3Fref_type%3Dheads (The markup validation of the "abandoned" project status badge)

[nu-icon-validation]: https://validator.nu/?showsource=yes&doc=https%3A%2F%2Fgitlab.com%2Fesoterictemplates%2Fassets%2Fimages%2Fsymbols%2Fproject-status-badges%2F-%2Fraw%2Fmain%2Fdocs%2Fassets%2Fimages%2Ficons%2Fproject-status-badges%2Ficon.svg%3Fref_type%3Dheads (The markup validation of this project's icon)


[maintained-rdf-validation]: https://www.w3.org/RDF/Validator/rdfval?URI=https%3A%2F%2Fgitlab.com%2Fesoterictemplates%2Fassets%2Fimages%2Fsymbols%2Fproject-status-badges%2F-%2Fraw%2Fmain%2Fassets%2Fimages%2Fbadges%2Fmaintained.svg%3Fref_type%3Dheads&PARSE=Parse+URI%3A+&TRIPLES_AND_GRAPH=PRINT_TRIPLES&FORMAT=PNG_EMBED (The RDF validation of the "maintained" project status badge)
[finished-rdf-validation]: https://www.w3.org/RDF/Validator/rdfval?URI=https%3A%2F%2Fgitlab.com%2Fesoterictemplates%2Fassets%2Fimages%2Fsymbols%2Fproject-status-badges%2F-%2Fraw%2Fmain%2Fassets%2Fimages%2Fbadges%2Ffinished.svg%3Fref_type%3Dheads&PARSE=Parse+URI%3A+&TRIPLES_AND_GRAPH=PRINT_TRIPLES&FORMAT=PNG_EMBED (The RDF validation of the "finished" project status badge)
[unfinished-rdf-validation]: https://www.w3.org/RDF/Validator/rdfval?URI=https%3A%2F%2Fgitlab.com%2Fesoterictemplates%2Fassets%2Fimages%2Fsymbols%2Fproject-status-badges%2F-%2Fraw%2Fmain%2Fassets%2Fimages%2Fbadges%2Funfinished.svg%3Fref_type%3Dheads&PARSE=Parse+URI%3A+&TRIPLES_AND_GRAPH=PRINT_TRIPLES&FORMAT=PNG_EMBED (The RDF validation of the "unfinished" project status badge)
[abandoned-rdf-validation]: https://www.w3.org/RDF/Validator/rdfval?URI=https%3A%2F%2Fgitlab.com%2Fesoterictemplates%2Fassets%2Fimages%2Fsymbols%2Fproject-status-badges%2F-%2Fraw%2Fmain%2Fassets%2Fimages%2Fbadges%2Fabandoned.svg%3Fref_type%3Dheads&PARSE=Parse+URI%3A+&TRIPLES_AND_GRAPH=PRINT_TRIPLES&FORMAT=PNG_EMBED (The RDF validation of the "abandoned" project status badge)

[icon-rdf-validation]: https://www.w3.org/RDF/Validator/rdfval?URI=https%3A%2F%2Fgitlab.com%2Fesoterictemplates%2Fassets%2Fimages%2Fsymbols%2Fproject-status-badges%2F-%2Fraw%2Fmain%2Fdocs%2Fassets%2Fimages%2Ficons%2Fproject-status-badges%2Ficon.svg%3Fref_type%3Dheads&PARSE=Parse+URI%3A+&TRIPLES_AND_GRAPH=PRINT_TRIPLES&FORMAT=PNG_EMBED (The RDF validation of this project's icon)


[license]: ./LICENSE (This project's license)

[credit]: ./docs/CREDIT.md (The credits for this project)

[badges]: ./assets/images/badges/ (The badges of this project)
[icon]: ./docs/assets/images/icons/project-status-badges/icon.svg (The icon of this project)


[status]: ./assets/images/badges/maintained.svg (The status of this project)

[maintained]: ./assets/images/badges/maintained.svg (The "maintained" project status badge)
[finished]: ./assets/images/badges/finished.svg (The "finished" project status badge)
[unfinished]: ./assets/images/badges/unfinished.svg (The "unfinished" project status badge)
[abandoned]: ./assets/images/badges/abandoned.svg (The "abandoned" project status badge)
