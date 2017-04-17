# test coverage for  [localtunnel (v1.8.2)](https://github.com/localtunnel/localtunnel#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-localtunnel.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-localtunnel) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-localtunnel.svg)](https://travis-ci.org/npmtest/node-npmtest-localtunnel)
#### expose localhost to the world

[![NPM](https://nodei.co/npm/localtunnel.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/localtunnel)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-localtunnel/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-localtunnel/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-localtunnel/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-localtunnel/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-localtunnel/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-localtunnel/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-localtunnel/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-localtunnel/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-localtunnel/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-localtunnel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-localtunnel/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-localtunnel/build/test-report.html](https://npmtest.github.io/node-npmtest-localtunnel/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-localtunnel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-localtunnel/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-localtunnel/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-localtunnel/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-localtunnel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-localtunnel/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-localtunnel/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-localtunnel/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Roman Shtylman"
    },
    "bin": {
        "lt": "./bin/client"
    },
    "bugs": {
        "url": "https://github.com/localtunnel/localtunnel/issues"
    },
    "dependencies": {
        "debug": "2.2.0",
        "openurl": "1.1.0",
        "request": "2.78.0",
        "yargs": "3.29.0"
    },
    "description": "expose localhost to the world",
    "devDependencies": {
        "mocha": "~1.17.0"
    },
    "directories": {},
    "dist": {
        "shasum": "913051e8328b51f75ad8a22ad1f5c5b8c599a359",
        "tarball": "https://registry.npmjs.org/localtunnel/-/localtunnel-1.8.2.tgz"
    },
    "gitHead": "8efcb3a29415d4a0d307b3537f17118afed173d8",
    "homepage": "https://github.com/localtunnel/localtunnel#readme",
    "license": "MIT",
    "main": "./client.js",
    "maintainers": [
        {
            "name": "defunctzombie"
        }
    ],
    "name": "localtunnel",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/localtunnel/localtunnel.git"
    },
    "scripts": {
        "test": "mocha --ui qunit --reporter list --timeout 10000 -- test/index.js"
    },
    "version": "1.8.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
