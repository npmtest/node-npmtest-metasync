# npmtest-metasync

#### test coverage for  [metasync (v0.2.1)](https://github.com/metarhia/MetaSync#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-metasync.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-metasync) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-metasync.svg)](https://travis-ci.org/npmtest/node-npmtest-metasync)

#### Metasync is a Meta Async Programming Approach

[![NPM](https://nodei.co/npm/metasync.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/metasync)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-metasync/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-metasync/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-metasync/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-metasync/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-metasync/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-metasync/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-metasync/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-metasync/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-metasync/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-metasync/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-metasync/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-metasync/build/test-report.html](https://npmtest.github.io/node-npmtest-metasync/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-metasync/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-metasync/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-metasync/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-metasync/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-metasync/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-metasync/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-metasync/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-metasync/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Timur Shemsedinov"
    },
    "bugs": {
        "url": "https://github.com/metarhia/MetaSync/issues"
    },
    "contributors": [
        {
            "name": "Timur Shemsedinov"
        },
        {
            "name": "Oleksandr Kovalchuk"
        },
        {
            "name": "Vladyslav Dukhin"
        },
        {
            "name": "Alexey Orlenko"
        },
        {
            "name": "Arthur Myronenko"
        },
        {
            "name": "Alexey Kachan"
        }
    ],
    "dependencies": {
        "metarhia-common": "0.0.x"
    },
    "description": "Metasync is a Meta Async Programming Approach",
    "devDependencies": {
        "eslint": "3.x"
    },
    "directories": {},
    "dist": {
        "shasum": "722691101069cd30675efe9b98c5228c0dcde6d6",
        "tarball": "https://registry.npmjs.org/metasync/-/metasync-0.2.1.tgz"
    },
    "engines": {
        "node": ">=6.0.0"
    },
    "gitHead": "71f5a85e7231a46d6a476998aa65bb220e944758",
    "homepage": "https://github.com/metarhia/MetaSync#readme",
    "jshintConfig": {
        "esversion": 6,
        "predef": [],
        "node": true,
        "indent": 2,
        "maxcomplexity": 7
    },
    "keywords": [
        "async",
        "callback",
        "impress",
        "utility",
        "utilities",
        "datacollector",
        "composition",
        "metasync"
    ],
    "license": "MIT",
    "main": "./metasync.js",
    "maintainers": [
        {
            "name": "aqrln"
        },
        {
            "name": "belochub"
        },
        {
            "name": "timur.shemsedinov"
        }
    ],
    "name": "metasync",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/metarhia/MetaSync.git"
    },
    "scripts": {
        "lint": "eslint .",
        "test": "node tests/examples && node tests/chain && npm run lint"
    },
    "version": "0.2.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
