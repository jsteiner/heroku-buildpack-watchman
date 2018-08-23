# Heroku Buildpack Watchman

Installs [watchman](https://facebook.github.io/watchman/) on Heroku. Caches the
binary for subsequent deploys.

## Usage

To use the latest stable version run:

    heroku buildpacks:set jsteiner/watchman

Or use the source code in this repository:

    heroku buildpacks:set https://github.com/jsteiner/heroku-buildpack-watchman
