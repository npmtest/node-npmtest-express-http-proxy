# npmtest-express-http-proxy

#### basic test coverage for  [express-http-proxy (v0.11.0)](https://github.com/villadora/express-http-proxy#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-express-http-proxy.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-express-http-proxy) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-express-http-proxy.svg)](https://travis-ci.org/npmtest/node-npmtest-express-http-proxy)

#### http proxy middleware for express

[![NPM](https://nodei.co/npm/express-http-proxy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-http-proxy)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-express-http-proxy/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-http-proxy/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-express-http-proxy/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-express-http-proxy/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-express-http-proxy/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-express-http-proxy/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-express-http-proxy/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-express-http-proxy/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-express-http-proxy/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-http-proxy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-express-http-proxy/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-express-http-proxy/build/test-report.html](https://npmtest.github.io/node-npmtest-express-http-proxy/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-express-http-proxy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-express-http-proxy/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-express-http-proxy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-http-proxy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-http-proxy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-http-proxy/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-express-http-proxy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-express-http-proxy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "villadora"
    },
    "bugs": {
        "url": "https://github.com/villadora/express-http-proxy/issues"
    },
    "contributors": [
        {
            "name": "Liam Bennett"
        },
        {
            "name": "eldereal",
            "url": "https://github.com/eldereal"
        },
        {
            "name": "Saulius Menkevičius",
            "url": "https://github.com/razzmatazz"
        },
        {
            "name": "Jérémy Lal"
        },
        {
            "name": "Wei Gao"
        },
        {
            "name": "Nik Krimm",
            "url": "https://github.com/monkpow"
        }
    ],
    "dependencies": {
        "es6-promise": "^3.2.1",
        "raw-body": "^2.1.7"
    },
    "description": "http proxy middleware for express",
    "devDependencies": {
        "body-parser": "^1.15.2",
        "express": "^4.3.1",
        "jscs": "^3.0.7",
        "jshint": "^2.5.5",
        "mocha": "^2.1.0",
        "supertest": "^1.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "f2e6ba2e9e8677b1ba335375c3cae670d5a1bb0a",
        "tarball": "https://registry.npmjs.org/express-http-proxy/-/express-http-proxy-0.11.0.tgz"
    },
    "engineStrict": true,
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "c0c8dbd54a6bbef8b773a69c30c0bb69d9e9d536",
    "homepage": "https://github.com/villadora/express-http-proxy#readme",
    "keywords": [
        "express-http-proxy"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "gstroup"
        },
        {
            "name": "monkpow"
        },
        {
            "name": "villadora"
        }
    ],
    "name": "express-http-proxy",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/villadora/express-http-proxy.git"
    },
    "scripts": {
        "jscs": "jscs index.js test/*.js",
        "lint": "jshint index.js test/*.js",
        "mocha": "mocha -R spec test/*.js",
        "test": "npm -s run mocha && npm run -s lint && npm run -s jscs",
        "test:debug": "mocha debug -R spec test/*.js"
    },
    "version": "0.11.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
