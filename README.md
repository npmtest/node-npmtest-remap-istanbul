# npmtest-remap-istanbul

#### basic test coverage for  [remap-istanbul (v0.9.5)](https://github.com/SitePen/remap-istanbul)  [![npm package](https://img.shields.io/npm/v/npmtest-remap-istanbul.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-remap-istanbul) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-remap-istanbul.svg)](https://travis-ci.org/npmtest/node-npmtest-remap-istanbul)

#### A tool for remapping Istanbul coverage via Source Maps

[![NPM](https://nodei.co/npm/remap-istanbul.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/remap-istanbul)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-remap-istanbul/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-remap-istanbul/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-remap-istanbul/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-remap-istanbul/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-remap-istanbul/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-remap-istanbul/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-remap-istanbul/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-remap-istanbul/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-remap-istanbul/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-remap-istanbul/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-remap-istanbul/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-remap-istanbul/build/test-report.html](https://npmtest.github.io/node-npmtest-remap-istanbul/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-remap-istanbul/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-remap-istanbul/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-remap-istanbul/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-remap-istanbul/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-remap-istanbul/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-remap-istanbul/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-remap-istanbul/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-remap-istanbul/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "remap-istanbul",
    "version": "0.9.5",
    "description": "A tool for remapping Istanbul coverage via Source Maps",
    "homepage": "https://github.com/SitePen/remap-istanbul",
    "keywords": [
        "gulpplugin",
        "gruntplugin",
        "source-map",
        "istanbul",
        "coverage"
    ],
    "maintainers": [
        {
            "name": "kitsonk"
        },
        {
            "name": "bryanforbes"
        }
    ],
    "bugs": {
        "url": "https://github.com/SitePen/remap-istanbul"
    },
    "license": "BSD-3-Clause",
    "main": "./lib/main.js",
    "bin": "./bin/remap-istanbul.js",
    "repository": {
        "type": "git",
        "url": "https://github.com/SitePen/remap-istanbul.git"
    },
    "scripts": {
        "lint": "eslint ./src/",
        "test": "tests/run.sh",
        "build": "rimraf lib && babel src --out-dir ./lib --source-maps",
        "prepublish": "npm run build"
    },
    "dependencies": {
        "amdefine": "^1.0.0",
        "gulp-util": "3.0.7",
        "istanbul": "0.4.5",
        "minimatch": "^3.0.3",
        "source-map": ">=0.5.6",
        "through2": "2.0.1"
    },
    "devDependencies": {
        "babel-cli": "^6.16.0",
        "babel-core": "^6.17.0",
        "babel-plugin-transform-es2015-modules-amd": "^6.18.0",
        "babel-preset-es2015": "^6.16.0",
        "codecov.io": "0.1.6",
        "eslint": "^3.7.0",
        "eslint-config-airbnb-base": "^10.0.1",
        "eslint-plugin-import": "^2.0.1",
        "grunt": "^1.0.1",
        "gulp": "3.9.1",
        "intern": "^3.3.0",
        "rimraf": "^2.5.4"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
