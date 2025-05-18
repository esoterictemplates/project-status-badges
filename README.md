<!---
ISC License

Copyright 2025 Esoteric Enderman

Permission to use, copy, modify, and/or distribute this software for any purpose with or without fee is hereby granted, provided that the above copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
--->

# Project Status Badges

<sup>By [Esoteric Enderman][author]</sup>

[![Project status: unfinished][status]][project-status]

Project status badges for quickly and easily indicating the [status](#project-status) of a project.

## Links

- [GitLab][project-gitlab]
- [GitHub][project-github]
- [Codeberg][project-codeberg]
- [Sourcehut][project-sourcehut]
- [Credit][credit]

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

&copy; 2025 [Esoteric Enderman][author]

[Project Status Badges][project] are licensed under the [ISC License][license].

<!--- Link aliases --->

[project]: ./

[project-gitlab]: https://gitlab.com/esoterictemplates/project-status-badges
[project-github]: https://github.com/esoterictemplates/project-status-badges
[project-codeberg]: https://codeberg.org/esoterictemplates/project-status-badges
[project-sourcehut]: https://git.sr.ht/~esotericenderman/project-status-badges

[author]: https://enderman.dev

<!--- Links --->

[cc]: https://creativecommons.org/

<!-- Markup Validation Service -->

[markup-validator]: https://validator.w3.org/

[maintained-validation]: https://validator.w3.org/check?uri=https%3A%2F%2Fgitlab.com%2Fesoterictemplates%2Fproject-status-badges%2F-%2Fraw%2Fmain%2Fassets%2Fimages%2Fbadges%2Fmaintained.svg%3Fref_type%3Dheads&charset=%28detect+automatically%29&doctype=Inline&group=0
[finished-validation]: https://validator.w3.org/check?uri=https%3A%2F%2Fgitlab.com%2Fesoterictemplates%2Fproject-status-badges%2F-%2Fraw%2Fmain%2Fassets%2Fimages%2Fbadges%2Ffinished.svg%3Fref_type%3Dheads&charset=%28detect+automatically%29&doctype=Inline&group=0&user-agent=W3C_Validator%2F1.3+
[unfinished-validation]: https://validator.w3.org/check?uri=https%3A%2F%2Fgitlab.com%2Fesoterictemplates%2Fproject-status-badges%2F-%2Fraw%2Fmain%2Fassets%2Fimages%2Fbadges%2Funfinished.svg%3Fref_type%3Dheads&charset=%28detect+automatically%29&doctype=Inline&group=0&user-agent=W3C_Validator%2F1.3+
[abandoned-validation]: https://validator.w3.org/check?uri=https%3A%2F%2Fgitlab.com%2Fesoterictemplates%2Fproject-status-badges%2F-%2Fraw%2Fmain%2Fassets%2Fimages%2Fbadges%2Fabandoned.svg%3Fref_type%3Dheads&charset=%28detect+automatically%29&doctype=Inline&group=0&user-agent=W3C_Validator%2F1.3+

[icon-validation]: https://validator.w3.org/check?uri=https%3A%2F%2Fgitlab.com%2Fesoterictemplates%2Fproject-status-badges%2F-%2Fraw%2Fmain%2Fdocs%2Fassets%2Fimages%2Ficons%2Fproject-status-badges%2Ficon.svg%3Fref_type%3Dheads&charset=%28detect+automatically%29&doctype=Inline&group=0&user-agent=W3C_Validator%2F1.3+

<!--- Files --->

[license]: ./LICENSE

[credit]: ./docs/CREDIT.md

[badges]: ./assets/images/badges/
[icon]: ./docs/assets/images/icons/project-status-badges/icon.svg

<!--- Badges --->

[project-status]: https://gitlab.com/esoterictemplates/project-status-badges#project-status

[status]: ./assets/images/badges/unfinished.svg

[maintained]: ./assets/images/badges/maintained.svg
[finished]: ./assets/images/badges/finished.svg
[unfinished]: ./assets/images/badges/unfinished.svg
[abandoned]: ./assets/images/badges/abandoned.svg
