# npmtest-clappr

#### basic test coverage for  [clappr (v0.2.66)](https://github.com/clappr/clappr)  [![npm package](https://img.shields.io/npm/v/npmtest-clappr.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-clappr) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-clappr.svg)](https://travis-ci.org/npmtest/node-npmtest-clappr)

#### An extensible media player for the web

[![NPM](https://nodei.co/npm/clappr.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/clappr)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-clappr/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-clappr/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-clappr/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-clappr/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-clappr/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-clappr/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-clappr/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-clappr/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-clappr/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-clappr/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-clappr/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-clappr/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-clappr/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-clappr/build/test-report.html](https://npmtest.github.io/node-npmtest-clappr/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-clappr/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-clappr/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-clappr/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-clappr/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-clappr/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-clappr/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-clappr/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-clappr/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Globo.com"
    },
    "bugs": {
        "url": "https://github.com/clappr/clappr/issues"
    },
    "contributors": [
        {
            "name": "Globo.com"
        }
    ],
    "dependencies": {},
    "description": "An extensible media player for the web",
    "devDependencies": {
        "babel-core": "^6.18.2",
        "babel-loader": "^6.4.1",
        "babel-plugin-add-module-exports": "^0.2.0",
        "babel-plugin-transform-es2015-classes": "^6.6.4",
        "babel-preset-es2015": "^6.5.0",
        "chai": "^3.2.0",
        "check-dependencies": "^1.0.1",
        "clappr-zepto": "0.0.7",
        "clean-webpack-plugin": "^0.1.14",
        "coveralls": "^2.11.4",
        "css-loader": "^0.28.0",
        "directory-named-webpack-plugin": "^2.1.0",
        "dotenv": "^4.0.0",
        "eslint": "^3.1.0",
        "file-loader": "^0.11.1",
        "gulp": "^3.8.1",
        "hls.js": "^0.7.5",
        "html-loader": "^0.4.3",
        "isparta": "^4.0.0",
        "istanbul": "^0.4.2",
        "istanbul-instrumenter-loader": "^2.0.0",
        "jscs": "^3.0.3",
        "jshint": "^2.9.1",
        "karma": "^1.1.1",
        "karma-chai": "^0.1.0",
        "karma-chai-sinon": "^0.1.5",
        "karma-chrome-launcher": "^2.0.0",
        "karma-cli": "^1.0.0",
        "karma-coverage": "^1.1.1",
        "karma-firefox-launcher": "^1.0.0",
        "karma-mocha": "^1.1.0",
        "karma-sinon": "^1.0.4",
        "karma-sinon-chai": "^1.1.0",
        "karma-webpack": "^2.0.1",
        "lodash.isequal": "^4.2.0",
        "lodash.isplainobject": "^4.0.4",
        "lodash.merge": "^4.4.0",
        "lodash.once": "^4.0.0",
        "lodash.result": "^4.3.0",
        "lodash.uniqby": "^4.3.0",
        "lolex": "^1.5.2",
        "mkdirp": "^0.5.1",
        "mocha": "^3.1.2",
        "node-bourbon": "^4.2.8",
        "node-sass": "^4.3.0",
        "s3": "^4.1.1",
        "sass-loader": "^6.0.2",
        "sinon": "^2.0.0",
        "sinon-chai": "^2.8.0",
        "sshpk": "^1.6.2",
        "svg-inline-loader": "^0.7.1",
        "sync-pkg": "^0.7.1",
        "uglify-js": "^2.8.22",
        "url-loader": "^0.5.6",
        "webpack": "^2.4.1",
        "webpack-dev-server": "^2.4.2",
        "yargs": "^7.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "657baf9d34c105cd1b41dbe2c72643077bb98285",
        "tarball": "https://registry.npmjs.org/clappr/-/clappr-0.2.66.tgz"
    },
    "gitHead": "fecae5209b575e7e2aa797a8dad7ec7724491319",
    "homepage": "https://github.com/clappr/clappr",
    "license": "BSD-3-Clause",
    "main": "./dist/clappr.js",
    "maintainers": [
        {
            "name": "bernardocamilo"
        },
        {
            "name": "flavioribeiro"
        },
        {
            "name": "gustavocsb"
        },
        {
            "name": "leandromoreira"
        },
        {
            "name": "thiagopnts"
        },
        {
            "name": "towerz"
        }
    ],
    "name": "clappr",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/clappr/clappr.git"
    },
    "scripts": {
        "build": "webpack --progress",
        "check_code_style": "jscs src/ --esnext",
        "fix_code_style": "jscs src/ --esnext --fix",
        "lint": "eslint src/ test/",
        "lock": "rm -rf npm-shrinkwrap.json node_modules && npm install --silent && npm shrinkwrap",
        "release": "webpack --progress --output-filename clappr.min.js",
        "start": "webpack-dev-server --host 0.0.0.0 --content-base public/ --output-public-path latest/ --hot",
        "test": "karma start --single-run",
        "watch": "webpack --progress --watch"
    },
    "version": "0.2.66",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
