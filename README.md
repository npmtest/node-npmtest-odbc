# npmtest-odbc

#### basic test coverage for  [odbc (v1.2.1)](http://github.com/wankdanker/node-odbc/)  [![npm package](https://img.shields.io/npm/v/npmtest-odbc.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-odbc) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-odbc.svg)](https://travis-ci.org/npmtest/node-npmtest-odbc)

#### unixodbc bindings for node

[![NPM](https://nodei.co/npm/odbc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/odbc)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-odbc/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-odbc/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-odbc/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-odbc/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-odbc/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-odbc/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-odbc/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-odbc/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-odbc/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-odbc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-odbc/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-odbc/build/test-report.html](https://npmtest.github.io/node-npmtest-odbc/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-odbc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-odbc/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-odbc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-odbc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-odbc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-odbc/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-odbc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-odbc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/w1nk/node-odbc/issues"
    },
    "contributors": [
        {
            "name": "Dan VerWeire"
        },
        {
            "name": "Lee Smith"
        }
    ],
    "dependencies": {
        "bindings": "^1.2.1",
        "nan": "^2.0.9"
    },
    "description": "unixodbc bindings for node",
    "devDependencies": {},
    "directories": {
        "lib": "."
    },
    "dist": {
        "shasum": "e376846405f93b891b7e1f045c65c54c00b8929c",
        "tarball": "https://registry.npmjs.org/odbc/-/odbc-1.2.1.tgz"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "gitHead": "bc80233c8dd9d3ace14bc135907fd34e373ef121",
    "gypfile": true,
    "homepage": "http://github.com/wankdanker/node-odbc/",
    "main": "lib/odbc.js",
    "maintainers": [
        {
            "name": "wink"
        },
        {
            "name": "wankdanker"
        }
    ],
    "name": "odbc",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/wankdanker/node-odbc.git"
    },
    "scripts": {
        "install": "node-gyp configure build",
        "test": "cd test && node run-tests.js"
    },
    "version": "1.2.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
