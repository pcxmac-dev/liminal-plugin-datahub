# Changelog

## 1.1.1 (2026-11-02)

The plugin imports the library as `liminal_lib` and depends on liminal-lib (the app, renamed liminal-app, is no longer needed to run the tests; the user, 2026-11-02: "lets rename the app to liminal-app").

## 1.1.0 (2026-11-01)

- Released as its own package, `liminal-plugin-datahub`, registered under the entry point group
  `liminal.providers`; its version is the distribution's. The mirrors' git submodules stay with the
  app (`data/github/datasets/`, `LIMINAL_DATA_REPOS`): the plugin names each repository and file.
- Plugin API 1.4.

## 1.0.0 (2026-10-31)

- Built into the app (then massive-collate): the three mirrors declared by this plugin (plugin API
  1.4).
