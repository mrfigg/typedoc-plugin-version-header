# typedoc-plugin-version-header

A plugin for TypeDoc that makes the project's version appear only in the page header.

## Example

A basic example is available at [https://mrfigg.github.io/typedoc-plugin-version-header](https://mrfigg.github.io/typedoc-plugin-version-header).

## Installation

```sh
$ npm install -D typedoc-plugin-version-header
```

## Options

The following options are added to TypeDoc when the plugin is installed:

| Option                  | Type   | Default          | Description                                                                                                                                                                                                                                                                                                                               |
| ----------------------- | ------ | ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **versionHeaderFormat** | string | `"v{{version}}"` | The format of the version number in the header. Use `{{version}}` to insert the full version number, or `{{major}}`/`{{minor}}`/`{{patch}}` to insert individual parts of the version number. If `{{name}}` is used, it will be replaced with the project's name and the `versionHeaderFormat` will be applied to the entire header link. |
