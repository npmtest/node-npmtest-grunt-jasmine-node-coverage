# npmtest-grunt-jasmine-node-coverage

#### test coverage for  [grunt-jasmine-node-coverage (v1.1.1)](https://github.com/jribble/grunt-jasmine-node-coverage)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-jasmine-node-coverage.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-jasmine-node-coverage) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-jasmine-node-coverage.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-jasmine-node-coverage)

#### Grunt task for running jasmine using istanbul for code coverage reports. Based off of grunt-jasmine-node by Omar Gonzalez (s9tpepper).

[![NPM](https://nodei.co/npm/grunt-jasmine-node-coverage.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-jasmine-node-coverage)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-jasmine-node-coverage/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-jasmine-node-coverage/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-jasmine-node-coverage/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-jasmine-node-coverage/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-jasmine-node-coverage/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-jasmine-node-coverage/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-jasmine-node-coverage/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-jasmine-node-coverage/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-jasmine-node-coverage/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-jasmine-node-coverage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-jasmine-node-coverage/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-jasmine-node-coverage/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-jasmine-node-coverage/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-jasmine-node-coverage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-jasmine-node-coverage/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-jasmine-node-coverage/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-jasmine-node-coverage/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-jasmine-node-coverage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-jasmine-node-coverage/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-jasmine-node-coverage/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-jasmine-node-coverage/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jarrod Ribble"
    },
    "bugs": {
        "url": "https://github.com/jribble/grunt-jasmine-node-coverage/issues"
    },
    "contributors": [
        {
            "name": "Juga Paazmaya",
            "url": "https://paazmaya.fi"
        }
    ],
    "dependencies": {
        "deepmerge": "^0.2.10",
        "istanbul": "^0.4.5",
        "jasmine": "^2.4.1",
        "jasmine-reporters": "^2.2.0",
        "jasmine-spec-reporter": "^2.5.0"
    },
    "description": "Grunt task for running jasmine using istanbul for code coverage reports. Based off of grunt-jasmine-node by Omar Gonzalez (s9tpepper).",
    "devDependencies": {
        "grunt": "^1.0.1",
        "grunt-eslint": "^18.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "fcd6d6b6b32548736339a53e7e7396327e9f9478",
        "tarball": "https://registry.npmjs.org/grunt-jasmine-node-coverage/-/grunt-jasmine-node-coverage-1.1.1.tgz"
    },
    "engines": {
        "node": ">=4.2.0"
    },
    "files": [
        "tasks",
        "LICENSE-MIT",
        "package.json",
        "README.md"
    ],
    "gitHead": "045ebdddf220240be5664238a9c4bf0b41c9a07f",
    "homepage": "https://github.com/jribble/grunt-jasmine-node-coverage",
    "keywords": [
        "gruntplugin",
        "grunt",
        "plugins",
        "builds",
        "ci",
        "jasmine",
        "istanbul",
        "coverage"
    ],
    "license": "MIT",
    "main": "tasks/jasmine-node-task.js",
    "maintainers": [
        {
            "name": "jribble"
        },
        {
            "name": "paazmaya"
        }
    ],
    "name": "grunt-jasmine-node-coverage",
    "optionalDependencies": {},
    "peerDependencies": {
        "grunt": "^1.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/jribble/grunt-jasmine-node-coverage.git"
    },
    "scripts": {
        "lint": "grunt eslint",
        "test": "grunt test"
    },
    "version": "1.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
