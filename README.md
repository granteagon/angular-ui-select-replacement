# AngularJS ui-select [![Build Status](https://travis-ci.org/granteagon/angular-ui-select-replacement.svg?branch=master)](https://travis-ci.org/granteagon/angular-ui-select-replacement) [![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/granteagon/angular-ui-select-replacement?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

AngularJS-native version of [Select2](http://ivaynberg.github.io/select2/) and [Selectize](http://brianreavis.github.io/selectize.js/). [http://angular-ui.github.io/angular-ui-select-replacement/](http://angular-ui.github.io/angular-ui-select-replacement/)

[Getting Started](https://github.com/granteagon/angular-ui-select-replacement/wiki/Getting-Started)

- [Examples](http://angular-ui.github.io/angular-ui-select-replacement/#examples)
- [Examples Source](./docs/examples)
- [Documentation](https://github.com/granteagon/angular-ui-select-replacement/wiki)

## Please Note

This is a fork of `angular-ui-select`.  We will be maintaining this repository
in a different direction than the angular-ui team.  We do intend to respond to
issues and pull requests in a timely manner.

## Latest Changes

- Check [CHANGELOG.md](/CHANGELOG.md)

## Installation Methods

### npm
```
$ npm install angular-ui-select-replacement
```
### bower
```
$ bower install angular-ui-select-replacement
```

## Development

### Prepare your environment
* Install [Node.js](http://nodejs.org/) and NPM (should come with)
* Install global dev dependencies: `npm install -g gulp`
* Install local dev dependencies: `npm install` in repository directory

### Development Commands

* `gulp` to jshint, build and test
* `gulp build` to jshint and build
* `gulp test` for one-time test with karma (also build and jshint)
* `gulp watch` to watch src files to jshint, build and test when changed
* `gulp docs` build docs and examples

## Contributing

- Check [CONTRIBUTING.md](/CONTRIBUTING.md)
- Run the tests
- Try the [examples](./docs/examples)

When issuing a pull request, please exclude changes from the "dist" folder to avoid merge conflicts.
