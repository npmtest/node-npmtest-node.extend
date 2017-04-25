# npmtest-node.extend

#### basic test coverage for  [node.extend (v2.0.0)](https://github.com/dreamerslab/node.extend#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-node.extend.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node.extend) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node.extend.svg)](https://travis-ci.org/npmtest/node-npmtest-node.extend)

#### A port of jQuery.extend that actually works on node.js

[![NPM](https://nodei.co/npm/node.extend.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node.extend)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node.extend/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node.extend/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node.extend/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node.extend/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node.extend/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-node.extend/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-node.extend/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node.extend/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node.extend/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node.extend/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node.extend/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node.extend/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node.extend/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node.extend/build/test-report.html](https://npmtest.github.io/node-npmtest-node.extend/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node.extend/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node.extend/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node.extend/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node.extend/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node.extend/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node.extend/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node.extend/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node.extend/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "dreamerslab"
    },
    "bugs": {
        "url": "https://github.com/dreamerslab/node.extend/issues"
    },
    "contributors": [
        {
            "name": "Jordan Harband"
        }
    ],
    "dependencies": {
        "is": "^3.2.1"
    },
    "description": "A port of jQuery.extend that actually works on node.js",
    "devDependencies": {
        "@ljharb/eslint-config": "^11.0.0",
        "covert": "^1.1.0",
        "eslint": "^3.19.0",
        "jscs": "^3.0.7",
        "tape": "^4.6.3"
    },
    "directories": {},
    "dist": {
        "shasum": "7525a2875677ea534784a5e10ac78956139614df",
        "tarball": "https://registry.npmjs.org/node.extend/-/node.extend-2.0.0.tgz"
    },
    "engines": {
        "node": ">=0.4.0"
    },
    "gitHead": "d43f2482b94b90a28a108827e9042f5ede8e826a",
    "homepage": "https://github.com/dreamerslab/node.extend#readme",
    "keywords": [
        "extend",
        "jQuery",
        "jQuery extend",
        "clone",
        "copy",
        "inherit"
    ],
    "license": "(MIT OR GPL-2.0)",
    "main": "index",
    "maintainers": [
        {
            "name": "dreamerslab"
        },
        {
            "name": "ljharb"
        }
    ],
    "name": "node.extend",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/dreamerslab/node.extend.git"
    },
    "scripts": {
        "coverage": "covert test/index.js",
        "coverage-quiet": "covert test/index.js --quiet",
        "eslint": "eslint *.js */*.js",
        "jscs": "jscs *.js */*.js",
        "lint": "npm run jscs && npm run eslint",
        "posttest": "npm run coverage-quiet",
        "pretest": "npm run lint",
        "test": "npm run --silent tests-only",
        "tests-only": "node test"
    },
    "testling": {
        "files": "test/index.js",
        "browsers": [
            "iexplore/6.0..latest",
            "firefox/3.0..6.0",
            "firefox/15.0..latest",
            "firefox/nightly",
            "chrome/4.0..10.0",
            "chrome/20.0..latest",
            "chrome/canary",
            "opera/10.0..latest",
            "opera/next",
            "safari/4.0..latest",
            "ipad/6.0..latest",
            "iphone/6.0..latest"
        ]
    },
    "version": "2.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
