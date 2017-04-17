# test coverage for  [z-schema (v3.18.2)](https://github.com/zaggino/z-schema)  [![npm package](https://img.shields.io/npm/v/npmtest-z-schema.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-z-schema) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-z-schema.svg)](https://travis-ci.org/npmtest/node-npmtest-z-schema)
#### JSON schema validator

[![NPM](https://nodei.co/npm/z-schema.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/z-schema)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-z-schema/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-z-schema/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-z-schema/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-z-schema/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-z-schema/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-z-schema/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-z-schema/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-z-schema/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-z-schema/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-z-schema/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-z-schema/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-z-schema/build/test-report.html](https://npmtest.github.io/node-npmtest-z-schema/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-z-schema/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-z-schema/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-z-schema/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-z-schema/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-z-schema/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-z-schema/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-z-schema/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-z-schema/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "authors": [
        "Martin Zagora <zaggino@gmail.com>"
    ],
    "bin": {
        "z-schema": "./bin/z-schema"
    },
    "bugs": {
        "url": "https://github.com/zaggino/z-schema/issues"
    },
    "dependencies": {
        "commander": "^2.7.1",
        "lodash.get": "^4.1.2",
        "lodash.isequal": "^4.4.0",
        "validator": "^6.0.0"
    },
    "description": "JSON schema validator",
    "devDependencies": {
        "coveralls": "latest",
        "grunt": "^0.4.0",
        "grunt-browserify": "^3.2.1",
        "grunt-cli": "latest",
        "grunt-contrib-copy": "latest",
        "grunt-contrib-jasmine": "latest",
        "grunt-contrib-jshint": "latest",
        "grunt-contrib-uglify": "latest",
        "grunt-jasmine-node": "latest",
        "grunt-jasmine-node-coverage": "^0.4.0",
        "grunt-jscs": "latest",
        "grunt-lineending": "latest",
        "jasmine-node": "latest",
        "jasmine-reporters": "latest",
        "remapify": "latest"
    },
    "directories": {},
    "dist": {
        "shasum": "e422196b5efe60b46adef3c3f2aef2deaa911161",
        "tarball": "https://registry.npmjs.org/z-schema/-/z-schema-3.18.2.tgz"
    },
    "files": [
        "bin",
        "src",
        "dist",
        "LICENSE",
        "README.md"
    ],
    "gitHead": "5b612d146cc526a0b331605a7cd239127655bce8",
    "homepage": "https://github.com/zaggino/z-schema",
    "keywords": [
        "JSON",
        "Schema",
        "Validator"
    ],
    "license": "MIT",
    "main": "src/ZSchema.js",
    "maintainers": [
        {
            "name": "zaggino"
        }
    ],
    "name": "z-schema",
    "optionalDependencies": {
        "commander": "^2.7.1"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/zaggino/z-schema.git"
    },
    "scripts": {
        "prepublish": "grunt",
        "test": "grunt test && grunt lint"
    },
    "testling": {
        "scripts": [
            "test/lib/jasmine-2.0.1/jasmine.js",
            "test/lib/jasmine-2.0.1/jasmine-html.js",
            "test/lib/jasmine-2.0.1/boot.js",
            "test/lib/jasmine-2.0.1/tap_reporter.js",
            "test/Runner.js",
            "dist/ZSchema-browser-min.js",
            "dist/ZSchema-browser-test.js"
        ],
        "browsers": [
            "iexplore/9..latest",
            "chrome/4",
            "chrome/28..latest",
            "firefox/3.5",
            "firefox/23..latest",
            "safari/5.1..latest",
            "opera/12..latest",
            "iphone/6..latest",
            "ipad/6..latest",
            "android-browser/4.2..latest"
        ]
    },
    "version": "3.18.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
