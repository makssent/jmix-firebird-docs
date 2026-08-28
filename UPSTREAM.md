# Upstream

The `modules/tutorial` module is derived from the tutorial in the official Jmix Documentation repository.

## Source

| | |
|---|---|
| Project | [Jmix Documentation](https://github.com/jmix-framework/jmix-docs) |
| Upstream branch | `release_3_ru` |
| Snapshot commit | [`f5c6cd0e061361b94b304d890f4ba6c157e98520`](https://github.com/jmix-framework/jmix-docs/commit/f5c6cd0e061361b94b304d890f4ba6c157e98520) |
| Snapshot date | 2026-07-31 |
| Upstream path | `content/modules/tutorial` |
| License | [CC BY 4.0](https://github.com/jmix-framework/jmix-docs/blob/f5c6cd0e061361b94b304d890f4ba6c157e98520/LICENSE.md) |

The original material is attributed to the Jmix Documentation project and its contributors.

## Changes to the tutorial

The imported tutorial was translated and adapted for this project. The current branch contains the English version; the corresponding Russian adaptation is maintained in the `release_firebird_3.0_ru` branch.

The main changes are:

- replacing HSQLDB with Firebird in setup and examples;
- adding `jmix-firebird-addon` and Jaybird configuration;
- documenting manual Liquibase changelog creation where Jmix Studio cannot generate it for Firebird;
- using command-line application startup where the Studio workflow is unavailable;
- adding Firebird and Jmix Studio limitations and related warnings;
- adding two project-specific screenshots: `modules/tutorial/images/data-in-ui/button-1.png` and `modules/tutorial/images/data-in-ui/joining-date-2.png`.

Most tutorial images, diagrams, and diagram source files remain unchanged from the upstream snapshot. Materials with a different upstream license are identified in `THIRD_PARTY_NOTICES.md`.

## Documentation added by this project

The pages and navigation under `modules/firebird` were added by this project. They cover Firebird setup, Liquibase integration, known limitations, and an application migration example. Firebird-specific explanations inserted into the adapted tutorial were also added by this project.
