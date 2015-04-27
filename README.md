# Clearfix

The `clearfix` module is a minimal clearfix helper class.

## Dependencies

The `clearfix` module depends on one other module:

* [settings.defaults](https://github.com/treeframework/settings.defaults)

If you install the `clearfix` module using Bower or npm, you will get these
dependencies at the same time. If not using Bower or npm, please be sure to
install and @import these dependencies in the relevant way.

## Installation

You can install `clearfix` module via Bower, npm, or copy and paste.

### Install using Bower:

```sh
$ bower install tree-clearfix --save
```

Once installed, `@import` into your project in its Trump layer:

```scss
@import "bower_components/tree-clearfix/trump.clearfix";
```

### Install using npm:

```sh
$ npm install tree-clearfix --save
```

### Install via file download

The least recommended option for installation is to simply download
`_trump.clearfix.scss` into your project and `@import` it into your project in
its Trump layer.

## Usage

Basic usage of the `clearfix` module uses the required classes:

```html
<div class="u-clearfix">...</div>
```

## Credits

* **[inuitcss](https://github.com/inuitcss)** Powerful, Sass-based, OOCSS
framework designed with scalability and performance in mind.
