# npmtest-js-csp

#### basic test coverage for  [js-csp (v0.9.2)](https://github.com/ubolonton/js-csp#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-js-csp.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-js-csp) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-js-csp.svg)](https://travis-ci.org/npmtest/node-npmtest-js-csp)

#### CSP channels with ES6 generators, inspired by Clojurescript's core.async and Go

[![NPM](https://nodei.co/npm/js-csp.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/js-csp)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-js-csp/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-js-csp/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-js-csp/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-js-csp/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-js-csp/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-js-csp/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-js-csp/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-js-csp/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-js-csp/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-js-csp/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-js-csp/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-js-csp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-js-csp/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-js-csp/build/test-report.html](https://npmtest.github.io/node-npmtest-js-csp/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-js-csp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-js-csp/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-js-csp/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-js-csp/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-js-csp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-js-csp/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-js-csp/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-js-csp/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nguyễn Tuấn Anh"
    },
    "browserify": {
        "transform": [
            "loose-envify"
        ]
    },
    "bugs": {
        "url": "https://github.com/ubolonton/js-csp/issues"
    },
    "dependencies": {
        "babel-runtime": "^6.22.0",
        "lodash": "^4.17.4"
    },
    "description": "CSP channels with ES6 generators, inspired by Clojurescript's core.async and Go",
    "devDependencies": {
        "babel-cli": "^6.22.2",
        "babel-core": "^6.22.1",
        "babel-eslint": "^7.1.1",
        "babel-loader": "^6.2.10",
        "babel-plugin-rewire": "^1.0.0",
        "babel-plugin-transform-flow-strip-types": "^6.22.0",
        "babel-plugin-transform-runtime": "^6.22.0",
        "babel-preset-es2015": "^6.22.0",
        "babel-preset-stage-0": "^6.22.0",
        "babel-template": "^6.22.0",
        "babel-types": "^6.22.0",
        "chai": "^3.5.0",
        "chokidar-cli": "^1.2.0",
        "cross-env": "^3.1.4",
        "eslint": "^3.15.0",
        "eslint-config-airbnb": "^14.1.0",
        "eslint-import-resolver-webpack": "^0.8.1",
        "eslint-loader": "^1.6.1",
        "eslint-plugin-babel": "^4.0.1",
        "eslint-plugin-flowtype": "^2.30.0",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-jsx-a11y": "^4.0.0",
        "eslint-plugin-mocha": "^4.8.0",
        "eslint-plugin-react": "^6.9.0",
        "eslint-watch": "^2.1.14",
        "flow-bin": "^0.38.0",
        "istanbul": "^1.1.0-alpha.1",
        "jsdom": "^9.10.0",
        "jsdom-global": "^2.1.1",
        "mocha": "^3.2.0",
        "ncp": "^2.0.0",
        "rimraf": "^2.5.4",
        "transducers.js": "^0.3.2",
        "webpack": "^2.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "19dd97965942694098db095beb632b2a95139214",
        "tarball": "https://registry.npmjs.org/js-csp/-/js-csp-0.9.2.tgz"
    },
    "engines": {
        "node": ">= 4.1.0",
        "npm": ">=3.0.0"
    },
    "files": [
        "lib",
        "es",
        "build",
        "src",
        "CHANGELOG.md",
        "README.md"
    ],
    "gitHead": "0388e5e6b1455bdfc60d8f68f4f6f30e37f7afb0",
    "homepage": "https://github.com/ubolonton/js-csp#readme",
    "jsnext:main": "./es/csp.js",
    "keywords": [
        "async",
        "channel",
        "clojure",
        "clojurescript",
        "concurrency",
        "core.async",
        "coroutines",
        "csp",
        "es6",
        "generators",
        "go",
        "yield"
    ],
    "license": {
        "type": "MIT",
        "url": "https://github.com/ubolonton/js-csp/raw/master/LICENSE"
    },
    "main": "./lib/csp.js",
    "maintainers": [
        {
            "name": "colorvisa"
        },
        {
            "name": "ubolonton"
        }
    ],
    "module": "./es/csp.js",
    "name": "js-csp",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ubolonton/js-csp.git"
    },
    "scripts": {
        "babel:es": "babel -d es src",
        "babel:node": "babel -d lib src",
        "build": "npm run build:node && npm run build:es && npm run build:browser",
        "build:browser": "webpack --config webpack.config.js",
        "build:es": "node -e \"require('ncp').ncp('./src', './es')\" && cross-env ES_PRESETS=true BABEL_ENV=production npm run babel:es",
        "build:node": "node -e \"require('ncp').ncp('./src', './lib')\" && cross-env BABEL_ENV=production npm run babel:node",
        "clean": "rimraf lib build",
        "flow:status": "flow status; test $? -eq 0 -o $? -eq 2",
        "flow:stop": "flow stop",
        "flow:watch": "npm run flow:status && chokidar './src/**/*.js' './test/**/*.js' -c 'npm run flow:status'",
        "lint": "esw -w './src/**/*.js' './test/**/*.js'",
        "prepublish": "npm run build",
        "test": "mocha",
        "test:coverage": "istanbul cover node_modules/mocha/bin/_mocha",
        "test:watch": "mocha --watch --reporter progress"
    },
    "version": "0.9.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
