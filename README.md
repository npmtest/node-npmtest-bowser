# npmtest-bowser

#### basic test coverage for  [bowser (v1.6.1)](https://github.com/ded/bowser)  [![npm package](https://img.shields.io/npm/v/npmtest-bowser.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-bowser) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-bowser.svg)](https://travis-ci.org/npmtest/node-npmtest-bowser)

#### Lightweight browser detector

[![NPM](https://nodei.co/npm/bowser.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bowser)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-bowser/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-bowser/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-bowser/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-bowser/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-bowser/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-bowser/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-bowser/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-bowser/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-bowser/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-bowser/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-bowser/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-bowser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-bowser/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-bowser/build/test-report.html](https://npmtest.github.io/node-npmtest-bowser/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-bowser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-bowser/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-bowser/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bowser/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bowser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bowser/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-bowser/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-bowser/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dustin Diaz",
        "url": "http://dustindiaz.com"
    },
    "bugs": {
        "url": "https://github.com/ded/bowser/issues"
    },
    "dependencies": {},
    "description": "Lightweight browser detector",
    "devDependencies": {
        "mocha": "*",
        "smoosh": "*"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "9157e9498f456e937173a2918f3b2161e5353eb3",
        "tarball": "https://registry.npmjs.org/bowser/-/bowser-1.6.1.tgz"
    },
    "gitHead": "9b87b2f3af3a471a287ac7821a7cee75e562da3c",
    "homepage": "https://github.com/ded/bowser",
    "keywords": [
        "browser",
        "useragent",
        "user-agent",
        "parser",
        "ua",
        "detection",
        "ender",
        "sniff"
    ],
    "license": "MIT",
    "main": "./src/bowser.js",
    "maintainers": [
        {
            "name": "ded"
        },
        {
            "name": "lancedikson"
        }
    ],
    "name": "bowser",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ded/bowser.git"
    },
    "scripts": {
        "prepublish": "make boosh",
        "test": "make test"
    },
    "typings": "./typings.d.ts",
    "version": "1.6.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
