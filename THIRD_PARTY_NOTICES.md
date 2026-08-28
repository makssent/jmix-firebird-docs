# Third-Party Notices

This file identifies third-party materials present in or displayed by this documentation. These materials remain under their respective licenses and are not relicensed by the repository's root `LICENSE`.

## Jmix Documentation

- **Paths:** `modules/tutorial`, except the two project-specific screenshots identified in `UPSTREAM.md` and the JetBrains SVG files listed below.
- **Additional displayed asset:** `modules/tutorial/pages/project-setup.adoc` embeds `content/modules/ROOT/images/store/login-form.png` from the Jmix Documentation repository through an external URL.
- **Source:** [jmix-framework/jmix-docs](https://github.com/jmix-framework/jmix-docs), branch `release_3_ru`, path `content/modules/tutorial`. The external login screenshot is loaded from branch `release_3`, path `content/modules/ROOT/images/store/login-form.png`.
- **License:** [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0).
- **Changes:** Tutorial text and navigation were translated and adapted for Firebird. Most imported images, diagrams, and diagram source files are unchanged. The external login screenshot is unmodified. See `UPSTREAM.md` for details.

## JetBrains SVG Assets

- **Paths:**
  - `modules/tutorial/images/common/add.svg`
  - `modules/tutorial/images/common/arrow-right.svg`
  - `modules/tutorial/images/common/edit.svg`
  - `modules/tutorial/images/common/move-down.svg`
  - `modules/tutorial/images/common/move-up.svg`
  - `modules/tutorial/images/common/refresh.svg`
  - `modules/tutorial/images/common/start-debugger.svg`
  - `modules/tutorial/images/common/suspend.svg`
- **Source:** JetBrains s.r.o. and contributors; imported unchanged through the Jmix Documentation snapshot identified above. Each file contains its original copyright and license notice.
- **License:** Apache License 2.0. See `LICENSES/Apache-2.0.txt`.
- **Changes:** None in this repository.

## Antora Default UI

- **Paths:**
  - `supplemental-ui/layouts/default.hbs`
  - `supplemental-ui/partials/header-content.hbs`
- **Source:** [Antora Default UI](https://gitlab.com/antora/antora-ui-default), corresponding upstream paths `src/layouts/default.hbs` and `src/partials/header-content.hbs`.
- **License:** Mozilla Public License 2.0. See `LICENSES/MPL-2.0.txt`.
- **Changes:** Modified to set the page language dynamically and provide the documentation language switch while removing unused default navigation items.
