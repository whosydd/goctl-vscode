## v0.1.10

### Support

* Support for formatting documents that use `import` to import external dependencies.

## v0.1.9

### Support

* Support abbreviated doc code blocks, such as `@doc "foo"`

## v0.1.8

### Document

* Updated some outdated outlink.

## v0.1.7

### Optimize

* Improve error message when an error occurs in format api file.
* Add goctl output channel for debug info log print and error log print.

## v0.1.6

### Support

* Add `@handler` annotation syntax highlighting.
* Support for route jump without returns to definition.

### Fixed

* Fix some syntax highlighting errors, example `get /greet/to/:name`.

## v0.1.5

### Optimize

* Add go-zero logo.
* Optimize the formatting logic, when formatting the file, there is no need to save the file to disk.

### Fixed

* Fix the bug that the file cannot be saved when the user sets `editor.formatOnSave` is `true`.

**Note:** To upgrade this version, please make sure that the goctl command line tool is also upgraded to the latest version. To upgrade the goctl command line tool, you can rerun the [goctl command line tool installation](https://github.com/zeromicro/go-zero#6-quick-start) command.

## v0.1.4

### Snippet improvements

* Add `@handler` snippet.
* Add go style snippet (`tys` and `im`).

## v0.1.3

### Fixed

* Fixed cannot be jump to code definition in some cases.