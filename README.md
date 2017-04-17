# test coverage for  [msgpack (v1.0.2)](https://github.com/msgpack/msgpack-node)  [![npm package](https://img.shields.io/npm/v/npmtest-msgpack.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-msgpack) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-msgpack.svg)](https://travis-ci.org/npmtest/node-npmtest-msgpack)
#### A space-efficient object serialization library for node.js

[![NPM](https://nodei.co/npm/msgpack.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/msgpack)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-msgpack/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-msgpack/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-msgpack/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-msgpack/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-msgpack/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-msgpack/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-msgpack/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-msgpack/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-msgpack/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-msgpack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-msgpack/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-msgpack/build/test-report.html](https://npmtest.github.io/node-npmtest-msgpack/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-msgpack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-msgpack/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-msgpack/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-msgpack/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-msgpack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-msgpack/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-msgpack/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-msgpack/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "json2msgpack": "./bin/json2msgpack",
        "msgpack2json": "./bin/msgpack2json"
    },
    "bugs": {
        "url": "https://github.com/msgpack/msgpack-node/issues"
    },
    "contributors": [
        {
            "name": "Amos Barreto",
            "url": "https://github.com/squamos"
        },
        {
            "name": "Peter Griess",
            "url": "https://github.com/pgriess"
        },
        {
            "name": "Maxwell Krohn",
            "url": "https://github.com/maxtaco"
        },
        {
            "name": "Jaye Marshall",
            "url": "https://github.com/jmars"
        },
        {
            "name": "matthiasg",
            "url": "https://github.com/matthiasg"
        },
        {
            "name": "Christopher Mooney",
            "url": "https://github.com/godsflaw"
        },
        {
            "name": "Michael Phan-Ba",
            "url": "https://github.com/mikepb"
        },
        {
            "name": "Bob Potter",
            "url": "https://github.com/bpot"
        },
        {
            "name": "rashfael",
            "url": "https://github.com/rashfael"
        },
        {
            "name": "Tom Taylor",
            "url": "https://github.com/tomtaylor"
        },
        {
            "name": "Brian White",
            "url": "https://github.com/mscdex"
        },
        {
            "name": "Keiji Yoshimi",
            "url": "https://github.com/walf443"
        }
    ],
    "dependencies": {
        "nan": "^2.0.9"
    },
    "description": "A space-efficient object serialization library for node.js",
    "devDependencies": {
        "nodeunit": "https://github.com/godsflaw/nodeunit/archive/master.tar.gz"
    },
    "directories": {
        "lib": "lib"
    },
    "dist": {
        "shasum": "923e2c5cffa65c8418e9b228d1124793969c429c",
        "tarball": "https://registry.npmjs.org/msgpack/-/msgpack-1.0.2.tgz"
    },
    "engines": {
        "node": ">=0.12.7"
    },
    "gitHead": "3c05e7fc10a2b9e8d4843f1c7e441656e9b2561d",
    "gypfile": true,
    "homepage": "https://github.com/msgpack/msgpack-node",
    "main": "./lib/msgpack",
    "maintainers": [
        {
            "name": "tomtaylor"
        },
        {
            "name": "godsflaw"
        },
        {
            "name": "pgriess"
        }
    ],
    "name": "msgpack",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/msgpack/msgpack-node.git"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "test": "./run_tests"
    },
    "version": "1.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
