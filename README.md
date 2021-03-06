# readme-includes [![NPM version](https://badge.fury.io/js/readme-includes.svg)](http://badge.fury.io/js/readme-includes)

> Snippets for your GitHub project's readme.

[verb](https://github.com/assemble/verb) and [generator-verb](https://github.com/assemble/generator-verb) depend on this library.

## Table of contents

<!-- toc -->

* [Install](#install)
* [Usage](#usage)
* [Included templates](#included-templates)
* [Examples](#examples)
* [Related projects](#related-projects)
* [Contributing](#contributing)
* [Author](#author)
* [License](#license)

_(Table of contents generated by [verb])_

<!-- tocstop -->

## Install

Install with [npm](https://www.npmjs.com/)

```bash
npm i readme-includes --save-dev
```

## Usage

Any template from this library can be included in another template using the `{%= include() %}` tag.

**Example**

```js
// add installation instructions to a readme, like those above
{%= include('install-npm') %}
```

## Included templates

See an **up-to-date list** of the includes in the [templates/example.md](templates/examples.md) directory:

* [twitter.md](templates/twitter.md)
* [tests.md](templates/tests.md)
* [tests-grunt.md](templates/tests-grunt.md)
* [run-verb.md](templates/run-verb.md)
* [maintainers.md](templates/maintainers.md)
* [license-mit.md](templates/license-mit.md)
* [issues.md](templates/issues.md)
* [install.md](templates/install.md)
* [install-npm.md](templates/install-npm.md)
* [install-grunt.md](templates/install-grunt.md)
* [install-global.md](templates/install-global.md)
* [install-bower.md](templates/install-bower.md)
* [history.md](templates/history.md)
* [github.md](templates/github.md)
* [footer.md](templates/footer.md)
* [download.md](templates/download.md)
* [contributors.md](templates/contributors.md)
* [contributing.md](templates/contributing.md)
* [contributing-extra.md](templates/contributing-extra.md)
* [contributing-detailed.md](templates/contributing-detailed.md)
* [clone.md](templates/clone.md)
* [cli.md](templates/cli.md)
* [build-docs.md](templates/build-docs.md)
* [benchmarks.md](templates/benchmarks.md)
* [authors.md](templates/authors.md)
* [author.md](templates/author.md)

## Examples

> Usage examples for all of the included templates

### [twitter.md](templates/twitter.md)

**Include:**

```js
{%= include("twitter.md") %}
```

### [tests.md](templates/tests.md)

**Include:**

```js
{%= include("tests.md") %}
```

### [tests-grunt.md](templates/tests-grunt.md)

**Include:**

```js
{%= include("tests-grunt.md") %}
```

### [run-verb.md](templates/run-verb.md)

**Include:**

```js
{%= include("run-verb.md") %}
```

### [maintainers.md](templates/maintainers.md)

**Include:**

```js
{%= include("maintainers.md") %}
```

### [license-mit.md](templates/license-mit.md)

**Include:**

```js
{%= include("license-mit.md") %}
```

### [issues.md](templates/issues.md)

**Include:**

```js
{%= include("issues.md") %}
```

### [install.md](templates/install.md)

**Include:**

```js
{%= include("install.md") %}
```

### [install-npm.md](templates/install-npm.md)

**Include:**

```js
{%= include("install-npm.md") %}
```

### [install-grunt.md](templates/install-grunt.md)

**Include:**

```js
{%= include("install-grunt.md") %}
```

### [install-global.md](templates/install-global.md)

**Include:**

```js
{%= include("install-global.md") %}
```

### [install-bower.md](templates/install-bower.md)

**Include:**

```js
{%= include("install-bower.md") %}
```

### [history.md](templates/history.md)

**Include:**

```js
{%= include("history.md") %}
```

### [github.md](templates/github.md)

**Include:**

```js
{%= include("github.md") %}
```

### [footer.md](templates/footer.md)

**Include:**

```js
{%= include("footer.md") %}
```

### [download.md](templates/download.md)

**Include:**

```js
{%= include("download.md") %}
```

### [contributors.md](templates/contributors.md)

**Include:**

```js
{%= include("contributors.md") %}
```

### [contributing.md](templates/contributing.md)

**Include:**

```js
{%= include("contributing.md") %}
```

### [contributing-extra.md](templates/contributing-extra.md)

**Include:**

```js
{%= include("contributing-extra.md") %}
```

### [contributing-detailed.md](templates/contributing-detailed.md)

**Include:**

```js
{%= include("contributing-detailed.md") %}
```

### [clone.md](templates/clone.md)

**Include:**

```js
{%= include("clone.md") %}
```

### [cli.md](templates/cli.md)

**Include:**

```js
{%= include("cli.md") %}
```

### [build-docs.md](templates/build-docs.md)

**Include:**

```js
{%= include("build-docs.md") %}
```

### [benchmarks.md](templates/benchmarks.md)

**Include:**

```js
{%= include("benchmarks.md") %}
```

### [authors.md](templates/authors.md)

**Include:**

```js
{%= include("authors.md") %}
```

### [author.md](templates/author.md)

**Include:**

```js
{%= include("author.md") %}
```

## Related projects

* [template](https://github.com/jonschlinkert/template): Render templates using any engine. Supports, layouts, pages, partials and custom template types. Use template… [more](https://github.com/jonschlinkert/template)
* [verb](https://github.com/assemble/verb): Documentation generator for GitHub projects. Extremely powerful, easy to use, can generate anything from API… [more](https://github.com/assemble/verb)

## Contributing

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/assemble/readme-includes/issues/new)

## Author

***

+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert)

## License

Copyright (c) 2014-2015 Jon Schlinkert
Released under the MIT license.

***

_This file was generated by [verb-cli](https://github.com/assemble/verb-cli) on May 14, 2015._