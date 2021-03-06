# React-webapp-starter

100 Shapes fork of (cesarandreu/web-app)[https://github.com/cesarandreu/web-app]

## Features

* Heavily commented webpack configuration with reasonable defaults
* JSX, ES6, and ES7 support with babel.js
* CSS Modules
* Source maps included in all builds
* Development server with hot reload when possible and refresh otherwise
* Production builds with cache busting and asset minification
* Testing environment using karma to run tests and mocha as the framework
* Code coverage when tests are run
* No gulp and no grunt, just npm run-scripts

## Installation

Install [node](http://nodejs.org/), my favored approach is using [Node Version Manager](https://github.com/creationix/nvm).

Clone the repo and change `origin` git remote.

```shell
$ npm install
```

## Scripts

All scripts are run with `npm run [script]`, for example: `npm run test`.

* `build` - generate a minified build to public folder
* `start` - start development server, try it by opening `http://localhost:8080/`
* `test` - lint and run all tests
* `tdd` - continuously run unit tests watching for changes

See what each script does by looking at the `scripts` section in [package.json](./package.json).

**NOTE:** to generate a full production build you must run the build command with `NODE_ENV=production`.
