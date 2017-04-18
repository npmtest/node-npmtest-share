# npmtest-share

#### test coverage for  [share (v0.7.40)](https://github.com/josephg/sharejs)  [![npm package](https://img.shields.io/npm/v/npmtest-share.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-share) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-share.svg)](https://travis-ci.org/npmtest/node-npmtest-share)

#### A database for concurrent document editing

[![NPM](https://nodei.co/npm/share.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/share)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-share/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-share/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-share/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-share/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-share/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-share/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-share/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-share/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-share/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-share/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-share/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-share/build/test-report.html](https://npmtest.github.io/node-npmtest-share/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-share/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-share/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-share/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-share/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-share/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-share/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-share/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-share/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Joseph Gentle"
    },
    "bugs": {
        "url": "https://github.com/josephg/sharejs/issues"
    },
    "dependencies": {
        "async": "^0.9.0",
        "express": "~3",
        "hat": "^0.0.3",
        "livedb": "^0.5.12",
        "ot-json0": "^1.0.0",
        "ot-text": "^1.0.0",
        "ot-text-tp2": "^1.0.0"
    },
    "description": "A database for concurrent document editing",
    "devDependencies": {
        "browserchannel": "*",
        "browserify": "^10.0.0",
        "chai": "*",
        "coffee-script": "~1.7.x",
        "connect": "^3.3.0",
        "istanbul": "^0.3.13",
        "mocha": "^2.2.4",
        "optimist": ">= 0.2.4",
        "ot-fuzzer": "^1.0.0",
        "redis": "^0.12.1",
        "serve-static": "^1.9.2",
        "sinon": "^1.14.1",
        "uglify-js": "^2.4.20"
    },
    "directories": {},
    "dist": {
        "shasum": "5a19ffda12f936b5f84a3d678e6dc0b76ce55f10",
        "tarball": "https://registry.npmjs.org/share/-/share-0.7.40.tgz"
    },
    "engine": "node >= 0.10",
    "gitHead": "135c38078746dbe167bb5af68909d64a8dcef861",
    "homepage": "https://github.com/josephg/sharejs",
    "keywords": [
        "operational transformation",
        "ot",
        "concurrent",
        "collaborative",
        "database",
        "server"
    ],
    "licenses": [
        {
            "type": "BSD",
            "url": "http://www.freebsd.org/copyright/freebsd-license.html"
        }
    ],
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "josephg"
        },
        {
            "name": "nateps"
        }
    ],
    "name": "share",
    "optionalDependencies": {
        "express": "~3"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/josephg/sharejs.git"
    },
    "scripts": {
        "build": "make",
        "coverage": "node node_modules/istanbul/lib/cli cover node_modules/mocha/bin/_mocha test/server test/browser",
        "prepublish": "make",
        "test": "node_modules/mocha/bin/mocha test/server test/browser"
    },
    "version": "0.7.40"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
