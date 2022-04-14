# TypeScript esbuild problem matchers

This [Visual Studio Code extension] provides problem matchers for TypeScript
projects built with [esbuild].

## Problem matchers

The following problem matchers are available.

- `$ts-esbuild` (when running esbuild normally)
- `$ts-esbuild-watch` (when running esbuild in `--watch` mode)

## Compatibility

The problem matchers have been tested on the latest version of esbuild available
at the time, which is: `0.14`. If the matchers stop working in a future version,
please open an issue or a pull request so it can be kept up to date.

[esbuild]: https://esbuild.github.io
[Visual Studio Code extension]: https://marketplace.visualstudio.com/items?itemName=nhedger.ts-esbuild-problem-matchers

## License

This extension is open-sourced software licensed under the [MIT license](LICENSE.md).
