# npmtest-consul

#### test coverage for  [consul (v0.28.0)](https://github.com/silas/node-consul#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-consul.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-consul) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-consul.svg)](https://travis-ci.org/npmtest/node-npmtest-consul)

#### Consul client

[![NPM](https://nodei.co/npm/consul.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/consul)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-consul/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-consul/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-consul/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-consul/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-consul/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-consul/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-consul/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-consul/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-consul/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-consul/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-consul/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-consul/build/test-report.html](https://npmtest.github.io/node-npmtest-consul/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-consul/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-consul/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-consul/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-consul/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-consul/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-consul/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-consul/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-consul/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Silas Sewell"
    },
    "bugs": {
        "url": "https://github.com/silas/node-consul/issues"
    },
    "dependencies": {
        "papi": "^0.27.0"
    },
    "description": "Consul client",
    "devDependencies": {
        "async": "^1.4.0",
        "bluebird": "^3.1.1",
        "debug": "^2.1.3",
        "istanbul": "^0.3.8",
        "jscs": "^2.1.1",
        "jshint": "^2.5.5",
        "lodash": "^3.5.0",
        "mocha": "^2.2.1",
        "nock": "^2.9.1",
        "node-uuid": "^1.4.3",
        "should": "^7.0.2",
        "sinon": "^1.14.1",
        "temp": "^0.8.1"
    },
    "directories": {},
    "dist": {
        "shasum": "c478fe6c58b6154b72867ef57ca8cfac181fba92",
        "tarball": "https://registry.npmjs.org/consul/-/consul-0.28.0.tgz"
    },
    "gitHead": "a0726641a976a8c93bac67754a764bc90642eab3",
    "homepage": "https://github.com/silas/node-consul#readme",
    "keywords": [
        "consul"
    ],
    "license": "MIT",
    "main": "./lib",
    "maintainers": [
        {
            "name": "silas"
        }
    ],
    "name": "consul",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/silas/node-consul.git"
    },
    "scripts": {
        "acceptance": "ACCEPTANCE=true istanbul cover --report text _mocha -- test/acceptance --recursive --check-leaks --timeout 15000",
        "cover": "istanbul cover _mocha -- --recursive && open coverage/lcov-report/index.html",
        "test": "jshint lib test && jscs lib test && istanbul cover --report text _mocha -- --recursive --check-leaks && istanbul check-coverage --statements 100 --functions 100 --branches 100 --lines 100"
    },
    "version": "0.28.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
