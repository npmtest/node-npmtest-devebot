# npmtest-devebot

#### basic test coverage for  [devebot (v0.1.23)](https://github.com/devebot/devebot#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-devebot.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-devebot) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-devebot.svg)](https://travis-ci.org/npmtest/node-npmtest-devebot)

#### Microservice Framework

[![NPM](https://nodei.co/npm/devebot.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/devebot)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-devebot/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-devebot/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-devebot/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-devebot/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-devebot/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-devebot/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-devebot/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-devebot/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-devebot/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-devebot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-devebot/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-devebot/build/test-report.html](https://npmtest.github.io/node-npmtest-devebot/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-devebot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-devebot/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-devebot/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-devebot/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-devebot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-devebot/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-devebot/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-devebot/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Hung Pham",
        "url": "http://acegik.net/blog"
    },
    "bugs": {
        "url": "https://github.com/devebot/devebot/issues"
    },
    "dependencies": {
        "bluebird": "^3.4.0",
        "debug": "^2.2.0",
        "injektor": "^0.0.12",
        "jobdapter": "^0.1.0",
        "jsonschema": "^1.1.0",
        "lodash": "^4.13.0",
        "logdapter": "^0.0.15",
        "ws": "^1.1.0"
    },
    "description": "Microservice Framework",
    "devDependencies": {
        "chai": "^3.5.0",
        "mocha": "^2.4.5",
        "nock": "^7.2.2",
        "rewire": "^2.5.1",
        "sinon": "^1.17.3"
    },
    "directories": {},
    "dist": {
        "shasum": "2de10cc93f99bbd17ab5013d07c469501b8057a6",
        "tarball": "https://registry.npmjs.org/devebot/-/devebot-0.1.23.tgz"
    },
    "engines": {
        "node": "0.10 || 0.12 || 4"
    },
    "gitHead": "1ef084253909c03174b90a8e97111ac760b31a6d",
    "homepage": "https://github.com/devebot/devebot#readme",
    "keywords": [
        "devebot",
        "framework"
    ],
    "license": "GPL-3.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "devebot"
        },
        {
            "name": "pnhung177"
        }
    ],
    "name": "devebot",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/devebot/devebot.git"
    },
    "scripts": {
        "e2etest": "cucumber.js test/et/features/*.feature",
        "test": "npm run unitest",
        "unitest": "mocha test/ut/**/*-test.js"
    },
    "version": "0.1.23",
    "warnings": [
        {
            "code": "ENOTSUP",
            "required": {
                "node": "0.10 || 0.12 || 4"
            },
            "pkgid": "devebot@0.1.23"
        },
        {
            "code": "ENOTSUP",
            "required": {
                "node": "0.10 || 0.12 || 4"
            },
            "pkgid": "devebot@0.1.23"
        }
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
