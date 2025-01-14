# Changelog

## [Unreleased][]

## [4.0.0][] - 2022-04-11

### Changed

-   **Breaking**: Updated browser support, check
    [Browserslist configuration](https://browserslist.dev/?q=bGFzdCAzIG1ham9yIHZlcnNpb25zLCBzaW5jZSAyMDE5LCBlZGdlID49IDE1LCBub3QgaWUgPiAw)
-   **Breaking**: All additional options such as `noLeading`, `noTrailing` and
    `debounceMode` are now part of options object instead of function arguments
-   Upgrade package

## [3.0.1][] - 2020-11-02

### Fixed

-   Accessing `package.json` being restricted since it’s no longer exported
    ([#43](https://github.com/niksy/throttle-debounce/pull/43))

## [3.0.0][] - 2020-10-28

### Changed

-   Avoid having bundles like Webpack load the UMD module
    ([#42](https://github.com/niksy/throttle-debounce/pull/42))
-   Upgrade package

### Removed

-   **Breaking**: Drop Node 8 support, package is no longer tested against it,
    but it should still work since there are no code changes

## [2.3.0][] - 2020-08-12

### Added

-   Support for UMD package
    ([#41](https://github.com/niksy/throttle-debounce/pull/41))

## [2.2.1][] - 2020-06-08

### Changed

-   Upgrade package
-   Add Browserstack testing
-   Add more detailed usage example to README
    ([#36](https://github.com/niksy/throttle-debounce/pull/36))
-   Use ES2015+ features

[2.2.1]: https://github.com/niksy/throttle-debounce/tree/v2.2.1
[2.3.0]: https://github.com/niksy/throttle-debounce/tree/v2.3.0
[3.0.0]: https://github.com/niksy/throttle-debounce/tree/v3.0.0
[3.0.1]: https://github.com/niksy/throttle-debounce/tree/v3.0.1
[unreleased]: https://github.com/niksy/throttle-debounce/compare/v4.0.0...HEAD
[4.0.0]: https://github.com/niksy/throttle-debounce/tree/v4.0.0
