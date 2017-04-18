# npmtest-forever

#### test coverage for  [forever (v0.15.3)](https://github.com/foreverjs/forever#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-forever.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-forever) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-forever.svg)](https://travis-ci.org/npmtest/node-npmtest-forever)

#### A simple CLI tool for ensuring that a given node script runs continuously (i.e. forever)

[![NPM](https://nodei.co/npm/forever.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/forever)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-forever/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-forever/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-forever/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-forever/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-forever/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-forever/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-forever/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-forever/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-forever/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-forever/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-forever/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-forever/build/test-report.html](https://npmtest.github.io/node-npmtest-forever/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-forever/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-forever/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-forever/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-forever/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-forever/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-forever/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-forever/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-forever/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Charlie Robbins"
    },
    "bin": {
        "forever": "./bin/forever"
    },
    "bugs": {
        "url": "https://github.com/foreverjs/forever/issues"
    },
    "dependencies": {
        "cliff": "~0.1.9",
        "clone": "^1.0.2",
        "colors": "~0.6.2",
        "flatiron": "~0.4.2",
        "forever-monitor": "~1.7.0",
        "nconf": "~0.6.9",
        "nssocket": "~0.5.1",
        "object-assign": "^3.0.0",
        "optimist": "~0.6.0",
        "path-is-absolute": "~1.0.0",
        "prettyjson": "^1.1.2",
        "shush": "^1.0.0",
        "timespan": "~2.3.0",
        "utile": "~0.2.1",
        "winston": "~0.8.1"
    },
    "description": "A simple CLI tool for ensuring that a given node script runs continuously (i.e. forever)",
    "devDependencies": {
        "broadway": "~0.3.6",
        "eventemitter2": "0.4.x",
        "request": "2.x.x",
        "vows": "0.7.x"
    },
    "directories": {},
    "dist": {
        "shasum": "77d9d7e15fd2f511ad9d84a110c7dd8fc8ecebc2",
        "tarball": "https://registry.npmjs.org/forever/-/forever-0.15.3.tgz"
    },
    "engines": {
        "node": ">= 0.8.x"
    },
    "gitHead": "3aa17a1088eb812eb03b49219e329fb4a48b4dfc",
    "homepage": "https://github.com/foreverjs/forever#readme",
    "keywords": [
        "cli",
        "fault tolerant",
        "sysadmin",
        "tools"
    ],
    "license": "MIT",
    "main": "./lib/forever",
    "maintainers": [
        {
            "name": "indexzero"
        },
        {
            "name": "bradleymeck"
        },
        {
            "name": "julianduque"
        },
        {
            "name": "jeffsu"
        },
        {
            "name": "jcrugzz"
        }
    ],
    "name": "forever",
    "optionalDependencies": {},
    "preferGlobal": "true",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/foreverjs/forever.git"
    },
    "scripts": {
        "test": "vows test/**/*-test.js --spec -i"
    },
    "version": "0.15.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
