# npmtest-html2jade

#### basic test coverage for  [html2jade (v0.8.6)](https://github.com/donpark/html2jade#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-html2jade.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-html2jade) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-html2jade.svg)](https://travis-ci.org/npmtest/node-npmtest-html2jade)

#### HTML to Jade conversion tool

[![NPM](https://nodei.co/npm/html2jade.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/html2jade)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-html2jade/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-html2jade/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-html2jade/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-html2jade/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-html2jade/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-html2jade/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-html2jade/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-html2jade/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-html2jade/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-html2jade/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-html2jade/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-html2jade/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-html2jade/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-html2jade/build/test-report.html](https://npmtest.github.io/node-npmtest-html2jade/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-html2jade/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-html2jade/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-html2jade/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-html2jade/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-html2jade/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-html2jade/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-html2jade/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-html2jade/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Don Park"
    },
    "bin": {
        "html2jade": "./cli.js"
    },
    "bugs": {
        "url": "https://github.com/donpark/html2jade/issues"
    },
    "dependencies": {
        "commander": "*",
        "he": "^0.4.1",
        "jsdom-little": "^0.10.5"
    },
    "description": "HTML to Jade conversion tool",
    "devDependencies": {
        "async": "*",
        "coffee-script": "~1.6.3",
        "mocha": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "2b3774189d395f77397888e91c8c61ec46e4248b",
        "tarball": "https://registry.npmjs.org/html2jade/-/html2jade-0.8.6.tgz"
    },
    "engines": {
        "node": ">= 0.4.0"
    },
    "gitHead": "29f27cfa901f845360035221778b7aa7876f49b0",
    "homepage": "https://github.com/donpark/html2jade#readme",
    "license": "BSD",
    "main": "./lib/html2jade.js",
    "maintainers": [
        {
            "name": "aichholzer"
        },
        {
            "name": "donpark"
        }
    ],
    "name": "html2jade",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/donpark/html2jade.git"
    },
    "scripts": {
        "prepublish": "coffee -c lib",
        "test": "mocha"
    },
    "version": "0.8.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
