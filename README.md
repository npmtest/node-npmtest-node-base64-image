# test coverage for  [node-base64-image (v1.0.3)](http://riyadhalnur.github.io/node-base64-image/)  [![npm package](https://img.shields.io/npm/v/npmtest-node-base64-image.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-base64-image) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-base64-image.svg)](https://travis-ci.org/npmtest/node-npmtest-node-base64-image)
#### Download images from remote URLs and encode/decode them to base64

[![NPM](https://nodei.co/npm/node-base64-image.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-base64-image)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-base64-image/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-base64-image/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-base64-image/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-base64-image/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-base64-image/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-base64-image/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-base64-image/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-base64-image/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-base64-image/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-base64-image/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-base64-image/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-base64-image/build/test-report.html](https://npmtest.github.io/node-npmtest-node-base64-image/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-base64-image/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-base64-image/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-base64-image/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-base64-image/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-base64-image/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-base64-image/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-base64-image/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-base64-image/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Riyadh Al Nur",
        "url": "https://riyadhalnur.com"
    },
    "babelBoilerplateOptions": {
        "entryFileName": "node-base64-image",
        "mainVarName": "base64"
    },
    "bugs": {
        "url": "https://github.com/riyadhalnur/node-base64-image/issues"
    },
    "dependencies": {
        "lodash": "4.11.1",
        "polygoat": "1.1.4",
        "request": "2.74.0"
    },
    "description": "Download images from remote URLs and encode/decode them to base64",
    "devDependencies": {
        "babel-cli": "6.9.0",
        "babel-core": "^6.3.26",
        "babel-eslint": "6.0.4",
        "babel-loader": "^6.2.0",
        "babel-plugin-transform-flow-strip-types": "6.7.0",
        "babel-polyfill": "^6.3.14",
        "babel-preset-es2015": "^6.3.13",
        "babel-register": "^6.3.13",
        "chai": "^3.4.1",
        "coveralls": "2.11.9",
        "eslint": "2.10.2",
        "eslint-plugin-flow-vars": "0.4.0",
        "flow-bin": "0.25.0",
        "gulp": "^3.9.0",
        "gulp-babel": "^6.1.1",
        "gulp-documentation": "2.2.0",
        "gulp-eslint": "^2.0.0",
        "gulp-filter": "^3.0.0",
        "gulp-istanbul": "^0.10.3",
        "gulp-load-plugins": "^1.1.0",
        "gulp-mocha": "^2.2.0",
        "gulp-plumber": "^1.0.1",
        "gulp-tag-version": "1.3.0",
        "gulp-util": "^3.0.7",
        "isparta": "^4.0.0",
        "mocha": "^2.3.4",
        "sinon": "^1.17.2",
        "sinon-chai": "^2.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "deabafe27b594671944eab9cbeabb225a7c30b07",
        "tarball": "https://registry.npmjs.org/node-base64-image/-/node-base64-image-1.0.3.tgz"
    },
    "gitHead": "3f3485430d6276575049f94e7be7f197b2d2b8c3",
    "homepage": "http://riyadhalnur.github.io/node-base64-image/",
    "keywords": [
        "image",
        "download",
        "base64",
        "encode",
        "decode",
        "javascript",
        "node"
    ],
    "license": "MIT",
    "main": "dist/node-base64-image.js",
    "maintainers": [
        {
            "name": "riyadhalnur"
        }
    ],
    "name": "node-base64-image",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/riyadhalnur/node-base64-image.git"
    },
    "scripts": {
        "build": "babel src --presets babel-preset-es2015 --out-dir dist",
        "coverage": "gulp coverage",
        "doc": "gulp doc",
        "lint": "gulp lint",
        "prepublish": "npm run build && npm run coverage && npm run tag",
        "tag": "gulp tag",
        "test": "gulp",
        "test-browser": "gulp test-browser",
        "watch": "gulp watch"
    },
    "version": "1.0.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
