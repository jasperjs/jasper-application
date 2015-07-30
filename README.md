# Jasper Application

Jasper - is a set of libraries that provides the ability to create scalable, flexible single page applications (SPA).

Jasper works over AngularJS and provide component based principle to build rich javascript applications.

## Get started

### Reqruirements

- [NodeJs](http://nodejs.org/)
- [Grunt](http://gruntjs.com/) - for building and testing jasper application: `npm install -g grunt-cli`
- [Yeoman](http://yeoman.io/) - for scaffolding jasper application: `npm install -g yo`


### Creating application

1. Clone or download this repository
2. Run `npm install` to install all dependencies
3. Run `yo jasper my-app` to create jasper application files
4. Run `grunt` to build created application
5. Browse to 'index.html' to see the application

To test application run `grunt test`

Altogether:

``` shell
git clone git@github.com:jasperjs/jasper-application.git
cd jasper-application
npm install
yo jasper jasper-app
grunt test
```

To start develop server run `node server`, then navigate to http://localhost:<port>/

See [documentation](https://github.com/jasperjs/jasper-application/wiki) how to create jasper application components.

When your application is done - run `grunt package` to create distributable application package.
Package will appear in 'dist' folder of the application.