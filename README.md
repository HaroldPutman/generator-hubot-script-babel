# generator-hubot-script-babel 
[![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Dependency Status][daviddm-image]][daviddm-url] [![Coverage Status][coveralls-image]][coveralls-url]
> A generator for hubot scripts using babel, es2015, and mocha

## Installation

First, install [Yeoman](http://yeoman.io) and generator-hubot-script-babel using [npm](https://www.npmjs.com/) (we assume you have pre-installed [node.js](https://nodejs.org/)).

```bash
npm install -g yo
npm install -g generator-hubot-script-babel
```

Then generate your new project:

```bash
yo hubot-script-babel
```

## Usage
This is a generator for hubot scripts which are written in ES2015 JavaScript. It also provides a basic testing setup for your script, using the mocha, chai, and hubot mock adapter. 

```bash
npm test # run tests
npm run build # convert your ES2015 to ES5
```

When using `npm publish` the included npm prepublish script and .npmignore will run your ES2015 JavaScript through babel, and exclude any build files from the published package.


## License

MIT © [Simon Wears](https://github.com/munkyjunky)


[npm-image]: https://badge.fury.io/js/generator-hubot-script-babel.svg
[npm-url]: https://npmjs.org/package/generator-hubot-script-babel
[travis-image]: https://travis-ci.org/munkyjunky/generator-hubot-script-babel.svg?branch=master
[travis-url]: https://travis-ci.org/munkyjunky/generator-hubot-script-babel
[daviddm-image]: https://david-dm.org/munkyjunky/generator-hubot-script-babel.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/munkyjunky/generator-hubot-script-babel
[coveralls-image]: https://coveralls.io/repos/github/munkyjunky/generator-hubot-script-babel/badge.svg?branch=master
[coveralls-url]:https://coveralls.io/github/munkyjunky/generator-hubot-script-babel?branch=master
