# [multi-tag-drilldown-input][gh-page]


The multi-tag-drilldown-input library wraps3 components: the suggestion engine,
[Bloodhound], the typeahead component [Typeahead] and the multitags input [bootstrap-tagsinput] to provide a select module for hierarchical information.
It allows for the selection of values dependent on each other by drilling down from one to the next.
Each value can be passed as a url, a function that received the previously selected values, or a static list.

![multi-tag-drilldown-input](demo.gif)

<!-- section links -->

[gh-page]: https://github.com/insurify/multi-tag-drilldown-input/
[bloodhound]: https://github.com/twitter/typeahead.js/blob/master/doc/bloodhound.md
[typeahead]: https://github.com/twitter/typeahead.js/blob/master/doc/jquery_typeahead.md
[bootstrap-tagsinput]: http://bootstrap-tagsinput.github.io/bootstrap-tagsinput/examples/

## Getting Started

How you acquire multitag-drilldown-input.js:
Download the js file from the dist directory

**Note:**  it has a dependency on
[bloodhound.js] 0.8.0
[typeahead.jquery.js]
[bootstrap-tagsinput]
[jQuery] 1.9+.

<!-- section links -->

[zipball]: http://twitter.github.com/typeahead.js/releases/latest/multitag-drilldown-input.js.zip
[bloodhound.js]: http://twitter.github.com/typeahead.js/releases/latest/bloodhound.js
[typeahead.jquery.js]: http://twitter.github.com/typeahead.js/releases/latest/typeahead.jquery.js
[bootstrap-tagsinput]: https://github.com/bootstrap-tagsinput/bootstrap-tagsinput/blob/master/dist/bootstrap-tagsinput.js
[jquery]: http://jquery.com/

## Examples

For some working examples of multi-tag-drilldown-input, visit the [examples page] (in progress).

<!-- section links -->

[examples page]: http://insurify.github.io/multi-tag-drilldown-input/examples

## Browser Support

- Chrome
- Firefox 3.5+
- Safari 4+
- Internet Explorer 8+
- Opera 11+


## Issues

Discovered a bug? Please create an issue here on GitHub!

https://github.com/insurify/multi-tag-drilldown-input/issues

## Versioning

For transparency and insight into our release cycle, releases will be numbered
with the following format:

`<major>.<minor>.<patch>`

And constructed with the following guidelines:

- Breaking backwards compatibility bumps the major
- New additions without breaking backwards compatibility bumps the minor
- Bug fixes and misc changes bump the patch

For more information on semantic versioning, please visit http://semver.org/.

## Developers

If you plan on contributing to multi-tag-drilldown-input, be sure to read the
[contributing guidelines]. A good starting place for new contributors are issues
labeled with [entry-level]. Entry-level issues tend to require minor changes
and provide developers a chance to get more familiar with multi-tag-drilldown-input before
taking on more challenging work.

In order to build and test multi-tag-drilldown-input, you'll need to install its dev
dependencies (`$ npm install`) and have [gulp]
installed (`$ npm install -g gulp`). Below is an overview of the available

The main gulp task rebuilds the .js and .css and creates minified versions.

<!-- section links -->

[contributing guidelines]: https://github.com/insurify/multi-tag-drilldown-input/blob/initial_version/CONTRIBUTING.md

## Maintainers

- **Natalia Vidal**

  - [@erikiva](https://twitter.com/erikiva)
  - [GitHub](https://github.com/erikiva)

- **You?**

## Authors

- **Natalia Vidal**

  - [@erikiva](https://twitter.com/erikiva)
  - [GitHub](https://github.com/erikiva)

- **Ifzal Ahmed**

  - [GitHub](https://github.com/ifzal)

- **Bilal Mughal**

  - [GitHub](https://github.com/mbilalmughal)

- **Tod Kiryazov**

  - [@todkiry](https://twitter.com/todkiry)

- **Steven Moseley**

  - [GitHub](https://github.com/stevenmoseley)

## License

Copyright 2018 Insurify, Inc.

Licensed under the MIT License
