# npmtest-pngquant

#### basic test coverage for  [pngquant (v1.2.0)](https://github.com/papandreou/node-pngquant#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-pngquant.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pngquant) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pngquant.svg)](https://travis-ci.org/npmtest/node-npmtest-pngquant)

#### The pngquant utility as a readable/writable stream

[![NPM](https://nodei.co/npm/pngquant.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pngquant)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pngquant/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pngquant/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pngquant/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pngquant/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pngquant/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pngquant/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pngquant/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pngquant/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pngquant/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pngquant/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pngquant/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pngquant/build/test-report.html](https://npmtest.github.io/node-npmtest-pngquant/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pngquant/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pngquant/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pngquant/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pngquant/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pngquant/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pngquant/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pngquant/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pngquant/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Andreas Lind"
    },
    "bugs": {
        "url": "https://github.com/papandreou/node-pngquant/issues"
    },
    "dependencies": {
        "memoizeasync": "0.8.0",
        "pngquant-bin": "3.1.1",
        "which": "1.1.2"
    },
    "description": "The pngquant utility as a readable/writable stream",
    "devDependencies": {
        "coveralls": "2.11.2",
        "istanbul": "0.3.15",
        "jshint": "2.8.0",
        "mocha": "2.4.5",
        "semver": "5.0.3",
        "sinon": "1.17.3",
        "unexpected": "10.11.1",
        "unexpected-sinon": "10.2.0",
        "unexpected-stream": "2.0.3"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "6ae7f3ff5bf15a5cc24c9d28ce64f81b99ff8c53",
        "tarball": "https://registry.npmjs.org/pngquant/-/pngquant-1.2.0.tgz"
    },
    "gitHead": "e5b73c4223a880b57d6564e7d5378422a1624cba",
    "homepage": "https://github.com/papandreou/node-pngquant#readme",
    "keywords": [
        "pngquant",
        "png",
        "image",
        "optimization",
        "stream",
        "filter",
        "read/write",
        "duplex"
    ],
    "license": "BSD-3-Clause",
    "main": "lib/PngQuant.js",
    "maintainers": [
        {
            "name": "papandreou"
        },
        {
            "name": "munter"
        }
    ],
    "name": "pngquant",
    "optionalDependencies": {
        "pngquant-bin": "3.1.1"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/papandreou/node-pngquant.git"
    },
    "scripts": {
        "coverage": "NODE_ENV=development istanbul cover _mocha -- --reporter dot && echo google-chrome coverage/lcov-report/index.html",
        "lint": "jshint .",
        "test": "mocha && npm run lint",
        "travis": "npm test && npm run coverage && (<coverage/lcov.info coveralls || true)"
    },
    "version": "1.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
