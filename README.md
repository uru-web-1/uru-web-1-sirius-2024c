# uru-web-1-sirius-2024c

Web Components framework from the Web 1 course at Universidad Rafael Urdaneta (2024C term). It contains the Atomic framework plus a second one, Sirius.

**Note:** This repository is archived and read-only, and it is coursework. Its GitHub description says it has some bugs.

## Contents

- **`Atomic/`** — the same Atomic framework as in [`uru-web-1-atomic-2024c`](https://github.com/uru-web-1/uru-web-1-atomic-2024c): `Atom*` components, demo pages and JSDoc output.
- **`Sirius/public/`** — the Sirius framework: ES modules in `js/`, styles in `css/` and a demo page per component in `html/`.

Sirius components:

- **`SiriusCheckbox`, `SiriusLabel`, `SiriusIcon`, `SiriusSvg`** — basic elements.
- **`SiriusListBox`, `SiriusExchangeList`** — list widgets.
- **`SiriusTreeViewV1`, `SiriusTreeViewV2`** — two tree view versions.

Support code includes a base `SiriusElement`, `SiriusLogger` and a `deep-freeze` helper. Each component registers its own custom element tag.

## Usage

Serve `Atomic/public/` or `Sirius/public/` with a static file server and open a page from `html/`. Both folders have a `package.json` whose only dependency is `jsdoc`.

## License

No license file.
