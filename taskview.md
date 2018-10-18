# Task View: Project workflow

Brainstorming how to organize a task view proposal focused on CRAN packages that
facilitate project workflow. The packages are organized into approximate
categories, but many have features that define the other categories as well.

* [Utilities](#utilities)
* [Frameworks](#frameworks)
* [Pipelines](#pipelines)
* [Related links](#related-links)

## Utilities

These packages provide single-use functions to implement project infrastructure
or solve a specific problem. As a typical example, `usethis::use_git()`
initializes a Git repository, ignores common R files, and commits all project
files.

* [here][]
* [rrtools][]
* [usethis][]

[here]: https://cran.r-project.org/package=here
[rrtools]: https://cran.r-project.org/package=rrtools
[usethis]: https://cran.r-project.org/package=usethis

## Frameworks

These packages provide an organized directory structure and helper functions to
assist during the development of the project. As a typical example,
`ProjectTemplate::create.project()` creates an organized setup with many
subdirectories, and `ProjectTemplate::run.project()` executes each R script that
is saved in the `src/` subdirectory.

* [adapr][]
* [archivist][]
* [exreport][]
* [makeProject][]
* [ProjectTemplate][]
* [reports][]
* [represtools][]
* [RSuite][]
* [tinyProject][]
* [workflowr][]
* [zoon][]

[adapr]: https://cran.r-project.org/package=adapr
[archivist]: https://cran.r-project.org/package=archivist
[exreport]: https://cran.r-project.org/package=exreport
[makeProject]: https://cran.r-project.org/package=makeProject
[ProjectTemplate]: https://cran.r-project.org/package=ProjectTemplate
[reports]: https://cran.r-project.org/package=reports
[represtools]: https://cran.r-project.org/package=represtools
[RSuite]: https://cran.r-project.org/package=RSuite
[tinyProject]: https://cran.r-project.org/package=tinyProject
[workflowr]: https://cran.r-project.org/package=workflowr
[zoon]: https://cran.r-project.org/package=zoon

## Pipelines

These packages implement complex pipelines for processing data in a series of
interdependent steps. As a typical example, `drake::make()` builds the
dependency graph from the defined analysis steps and only executes those steps
whose upstream dependencies have been updated.

* [drake][]
* [repo][]

[drake]: https://cran.r-project.org/package=drake
[repo]: https://cran.r-project.org/package=repo

## Related links

* CRAN Task View: [Reproducible Research][ctv-rr] (literate programming)
* Task View: [Computational Environments and Reproducibility][tv-env] (software dependency management)

[ctv-rr]: https://cran.r-project.org/view=ReproducibleResearch
[tv-env]: https://github.com/o2r-project/ctv-computational-environments#readme
