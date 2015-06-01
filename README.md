# heroku-buildpacks-sourceversion
Writes the SOURCE_VERSION variable (usually the Git SHA) to a file for use by the app.

This is an experimental buildpack with work in progress. Suggestions appreciated!


## Changelog

* 2015-06-01 output `source_version` file to publicly viewable dir so it can be read by front-end.
* 2015-06-01 use JSON format for file; rename to `source_version.json`
