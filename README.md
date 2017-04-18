# npmtest-testling

#### test coverage for  [testling (v1.7.1)](https://github.com/substack/testling)  [![npm package](https://img.shields.io/npm/v/npmtest-testling.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-testling) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-testling.svg)](https://travis-ci.org/npmtest/node-npmtest-testling)

#### write tests for browser code

[![NPM](https://nodei.co/npm/testling.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/testling)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-testling/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-testling/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-testling/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-testling/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-testling/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-testling/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-testling/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-testling/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-testling/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-testling/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-testling/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-testling/build/test-report.html](https://npmtest.github.io/node-npmtest-testling/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-testling/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-testling/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-testling/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-testling/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-testling/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-testling/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-testling/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-testling/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Halliday",
        "url": "http://substack.net"
    },
    "bin": {
        "testling": "bin/cmd.js"
    },
    "browserify": "browser.js",
    "bugs": {
        "url": "https://github.com/substack/testling/issues"
    },
    "bundleDependencies": [
        "browser-launcher"
    ],
    "dependencies": {
        "bouncy": "~3.2.0",
        "browser-launcher": "~0.3.2",
        "browserify": "3.x.x",
        "concat-stream": "~1.0.0",
        "ecstatic": "~0.4.5",
        "ent": "~0.0.5",
        "glob": "~3.2.1",
        "jsonify": "~0.0.0",
        "object-inspect": "~0.1.3",
        "optimist": "~0.5.2",
        "resolve": "~0.4.0",
        "shallow-copy": "~0.0.0",
        "shell-quote": "~1.3.1",
        "tap-finished": "~0.0.0",
        "win-spawn": "~2.0.0",
        "xhr-write-stream": "~0.1.2"
    },
    "description": "write tests for browser code",
    "devDependencies": {
        "tape": "~0.3.3"
    },
    "directories": {},
    "dist": {
        "shasum": "bfcfa877c8b15dd28d920692c03d8d64ca47874e",
        "tarball": "https://registry.npmjs.org/testling/-/testling-1.7.1.tgz"
    },
    "engines": {
        "node": ">=0.6"
    },
    "gitHead": "6d4783a1e81151930cc7378f3e70a0325d320679",
    "homepage": "https://github.com/substack/testling",
    "keywords": [
        "test",
        "browser",
        "headless"
    ],
    "license": "MIT/X11",
    "main": "index.js",
    "maintainers": [
        {
            "name": "substack"
        }
    ],
    "name": "testling",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/substack/testling.git"
    },
    "scripts": {
        "prepublish": "mkdir -p bundle && browserify browser/prelude.js -o bundle/prelude.js"
    },
    "version": "1.7.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
