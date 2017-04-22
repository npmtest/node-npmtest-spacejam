# npmtest-spacejam

#### basic test coverage for  [spacejam (v1.6.1)](https://github.com/practicalmeteor/spacejam)  [![npm package](https://img.shields.io/npm/v/npmtest-spacejam.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-spacejam) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-spacejam.svg)](https://travis-ci.org/npmtest/node-npmtest-spacejam)

#### Run your meteor package tinytests and mocha tests from the command line with phantomjs.

[![NPM](https://nodei.co/npm/spacejam.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/spacejam)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-spacejam/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-spacejam/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-spacejam/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-spacejam/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-spacejam/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-spacejam/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-spacejam/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-spacejam/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-spacejam/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-spacejam/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-spacejam/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-spacejam/build/test-report.html](https://npmtest.github.io/node-npmtest-spacejam/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-spacejam/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-spacejam/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-spacejam/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-spacejam/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-spacejam/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-spacejam/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-spacejam/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-spacejam/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Spacejam.io",
        "url": "http://spacejam.io/"
    },
    "bin": {
        "spacejam": "bin/spacejam",
        "spacejam-mocha": "bin/spacejam-mocha",
        "spacejam-init-bashrc": "bin/spacejam-init-bashrc",
        "meteor-mocha": "bin/meteor-mocha",
        "mrun": "bin/mrun",
        "mtp": "bin/mtp",
        "set-meteor-env": "bin/set-meteor-env",
        "unset-meteor-env": "bin/unset-meteor-env",
        "mongo-reset": "bin/mongo-reset",
        "mdeploy": "bin/mdeploy",
        "mpublish": "bin/mpublish",
        "mmpublish": "bin/mmpublish",
        "npm-publish": "bin/npm-publish"
    },
    "bugs": {
        "url": "https://github.com/practicalmeteor/spacejam/issues"
    },
    "dependencies": {
        "chai": "1.9.2",
        "glob": "4.0.6",
        "loglevel": "1.1.0",
        "phantomjs-prebuilt": "^2.1.7",
        "psext": "0.0.4",
        "rc": "0.5.1",
        "semver": "4.1.0",
        "underscore": "1.7.0"
    },
    "description": "Run your meteor package tinytests and mocha tests from the command line with phantomjs.",
    "devDependencies": {
        "coffee-script": "1.8.0",
        "mocha": "1.21.5",
        "sinon-chai": "2.6.0",
        "tmp": "0.0.25",
        "xmldom": "0.1.19",
        "xpath": "0.0.9"
    },
    "directories": {},
    "dist": {
        "shasum": "d4d939cff22649370c25ede4c1b125576e735016",
        "tarball": "https://registry.npmjs.org/spacejam/-/spacejam-1.6.1.tgz"
    },
    "engines": {
        "node": ">= 0.10.x",
        "npm": ">= 1.4.x"
    },
    "gitHead": "c7a577588f4d326145a37d7de202d53876caeb4c",
    "homepage": "https://github.com/practicalmeteor/spacejam",
    "keywords": [
        "spacejam",
        "meteor",
        "test-packages",
        "test-in-console",
        "tinytest",
        "mocha",
        "mocha.js",
        "practicalmeteor",
        "practicalmeteor:mocha",
        "practicalmeteor:mocha-console-runner",
        "ci",
        "continuous integration",
        "cd",
        "continuous delivery"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/practicalmeteor/spacejam/blob/master/LICENSE.txt"
        }
    ],
    "main": "lib/main.js",
    "maintainers": [
        {
            "name": "jsep"
        },
        {
            "name": "practicalmeteor"
        },
        {
            "name": "rbabayoff"
        }
    ],
    "name": "spacejam",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/practicalmeteor/spacejam.git"
    },
    "scripts": {
        "compile": "cake compile",
        "prepublish": "cake compile",
        "test": "bin/npm-test.sh"
    },
    "version": "1.6.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
