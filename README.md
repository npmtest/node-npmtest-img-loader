# npmtest-img-loader

#### basic test coverage for  [img-loader (v2.0.0)](https://github.com/thetalecrafter/img-loader)  [![npm package](https://img.shields.io/npm/v/npmtest-img-loader.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-img-loader) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-img-loader.svg)](https://travis-ci.org/npmtest/node-npmtest-img-loader)

#### Image minimizing loader for webpack

[![NPM](https://nodei.co/npm/img-loader.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/img-loader)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-img-loader/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-img-loader/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-img-loader/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-img-loader/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-img-loader/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-img-loader/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-img-loader/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-img-loader/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-img-loader/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-img-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-img-loader/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-img-loader/build/test-report.html](https://npmtest.github.io/node-npmtest-img-loader/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-img-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-img-loader/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-img-loader/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-img-loader/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-img-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-img-loader/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-img-loader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-img-loader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "img-loader",
    "version": "2.0.0",
    "description": "Image minimizing loader for webpack",
    "keywords": [
        "image",
        "imagemin",
        "image-loader",
        "optimize",
        "minify",
        "webpack",
        "webpack-loader"
    ],
    "repository": {
        "type": "git",
        "url": "http://github.com/thetalecrafter/img-loader.git"
    },
    "author": {
        "name": "Andy VanWagoner"
    },
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/thetalecrafter/img-loader/issues"
    },
    "homepage": "https://github.com/thetalecrafter/img-loader",
    "dependencies": {
        "imagemin": "^5.2.0",
        "imagemin-gifsicle": "^5.1.0",
        "imagemin-mozjpeg": "^6.0.0",
        "imagemin-optipng": "^5.2.0",
        "imagemin-pngquant": "^5.0.0",
        "imagemin-svgo": "^5.2.0",
        "loader-utils": "^1.0.4"
    },
    "devDependencies": {
        "mocha": "^3.0.0",
        "standard": "^9.0.0"
    },
    "scripts": {
        "pretest": "standard",
        "test": "mocha __tests__/*.spec.js"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
