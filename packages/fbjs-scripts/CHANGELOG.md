## [Unreleased]

### Removed
- [lint] Moved config to new `eslint-config-fbjs` package.


## [0.7.1] - 2016-05-25

### Added
- `object-assign` and `immutable` are now included in `third-party-module-map.json`.

### Changed
- Upgraded `cross-spawn` dependency


## [0.7.0] - 2016-04-28

### Changed
- [lint] Upgraded config to match latest internal config. Requires ESLint >= v2.0.0 (may be using newer rules).
- [babel] `babel/default-options` expects Babel 6 and `babel-preset-fbjs` to be installed.

### Removed
- [babel] Moved all plugins into new `babel-preset-fbjs` package.


## [0.6.0] - 2016-04-04

### Added
- [babel] Added rewrite-modules plugin for Babel 6
- [babel] Added dev-expression plugin for Babel 6
- [babel] Added default-options for Babel 6
- [gulp] Added strip-provides-module to strip `@providesModule` headers
- [gulp] Added check-dependencies to ensure installed packages are compatible with package.json specification
- [node] Added check-lib-requires script to ensure all lib files can be required

### Changed
- [lint] Moved ESLint config from `eslint/.eslintrc` to `eslint/.eslintrc.js`. requires ESLint >= v1.10.
- [lint] Base config updated to match internal config

### Fixed
- [babel] Fixed the rewrite-modules plugin to support more Jest methods
- [babel] Removed dependency on babel-types


## [0.5.0] - 2015-11-11
- [babel] Add auto-importer plugin for Babel & Babel 6
- [babel] Add auto-importer plugin to default babel options


## [0.4.0] - 2015-11-09
- [babel] Add inline-requires plugin for Babel 6


## [0.3.0] - 2015-10-23

### Changed
- [lint] `comma-dangle` rule upgraded to warning
- [jest] Update `createCacheKeyFunction` to make it compatible with Jest v0.6


## [0.2.2] - 2015-10-01

### Added
- [lint] Add several globals used by Relay and others
- [babel] Added `ua-parser-js` to default module map


## [0.2.1] - 2015-09-17

### Changed
- [jest] Ignore `config` option when creating a cache key


## [0.2.0] - 2015-08-31

### Added
- Initial release as a separate module.
