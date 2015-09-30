# Jasper

Jasper is a set of libraries which enable developers to create scalable and flexible single page applications (SPA) using component approach. Jasper is built on AngularJS.

Jasper applications are written in JavaScript or any language that is transpiled to it, like [TypeScript](http://typescriptlang.org).

## Getting started

### Requirements

- [NodeJs](http://nodejs.org/)
- [Grunt](http://gruntjs.com/) - for building and testing jasper application: `npm install -g grunt-cli`
- [Yeoman](http://yeoman.io/) - for scaffolding jasper application: `npm install -g yo`


### Creating an application and running tests

1. Clone or download this repository
2. Run `npm install` to install all dependencies
3. Run `yo jasper my-app` to create jasper application files
4. Run `grunt` to build created application
5. Browse to 'index.html' to see the application

To test application run `grunt test`.

Altogether:

``` shell
git clone git@github.com:jasperjs/jasper-application.git
cd jasper-application
npm install
yo jasper jasper-app
grunt test
```

To start developing server run `node server`, then navigate to `http://localhost:{port}`.


### Creating application components

See this [documentation](https://github.com/jasperjs/jasper-application/wiki).


### Packaging the application

At any time run `grunt package` to create distributable application package. It will appear in the `dist` folder of the application.
