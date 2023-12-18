# buildpack-antiword

A Cloud-Native Buildpack for installing [antiword](https://en.wikipedia.org/wiki/Antiword).

## Usage

Simply add this buildpack to your CNB app build. The buildpack will be automatically detected.

## Development

The buildpack is internally driven by the `build.json` file. Any changes to the build/compile process should be performed there, with the `bin/build` script left as generic as possible.
