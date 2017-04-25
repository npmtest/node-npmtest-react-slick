# npmtest-react-slick

#### basic test coverage for  [react-slick (v0.14.11)](https://github.com/akiran/react-slick)  [![npm package](https://img.shields.io/npm/v/npmtest-react-slick.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-slick) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-slick.svg)](https://travis-ci.org/npmtest/node-npmtest-react-slick)

####  React port of slick carousel

[![NPM](https://nodei.co/npm/react-slick.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-slick)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-slick/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-slick/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-slick/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-slick/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-slick/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react-slick/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react-slick/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-slick/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-slick/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-slick/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-slick/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-slick/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-slick/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-slick/build/test-report.html](https://npmtest.github.io/node-npmtest-react-slick/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-slick/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-slick/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-slick/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-slick/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-slick/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-slick/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-slick/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-slick/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kiran Abburi"
    },
    "bugs": {
        "url": "https://github.com/akiran/react-slick/issues"
    },
    "dependencies": {
        "can-use-dom": "^0.1.0",
        "classnames": "^2.2.5",
        "create-react-class": "^15.5.2",
        "enquire.js": "^2.1.6",
        "json2mq": "^0.2.0",
        "object-assign": "^4.1.0",
        "slick-carousel": "^1.6.0"
    },
    "description": " React port of slick carousel",
    "devDependencies": {
        "autoprefixer-core": "^6.0.1",
        "babel-cli": "^6.16.0",
        "babel-core": "^6.16.0",
        "babel-eslint": "^7.0.0",
        "babel-jest": "^19.0.0",
        "babel-loader": "^6.2.5",
        "babel-plugin-transform-object-assign": "^6.8.0",
        "babel-polyfill": "^6.16.0",
        "babel-preset-airbnb": "^2.1.1",
        "babel-preset-es2015": "^6.16.0",
        "babel-preset-react": "^6.16.0",
        "css-loader": "^0.28.0",
        "deepmerge": "^1.1.0",
        "del": "^2.2.2",
        "enzyme": "^2.8.2",
        "es5-shim": "^4.5.9",
        "eslint": "^3.6.1",
        "eslint-plugin-react": "^6.3.0",
        "express": "^4.14.0",
        "foundation-apps": "^1.2.0",
        "gulp": "^3.9.1",
        "gulp-sass": "^3.1.0",
        "jasmine-core": "^2.5.2",
        "jest": "^19.0.2",
        "json-loader": "^0.5.4",
        "node-sass": "^4.5.2",
        "postcss-loader": "^1.3.3",
        "react": "^15.3.2",
        "react-addons-test-utils": "^15.3.2",
        "react-dom": "^15.3.2",
        "react-test-renderer": "^15.5.4",
        "run-sequence": "^1.2.2",
        "sass-loader": "^6.0.3",
        "sinon": "^2.1.0",
        "style-loader": "^0.16.1",
        "webpack": "^1.13.2",
        "webpack-dev-server": "^1.16.1"
    },
    "directories": {},
    "dist": {
        "shasum": "c2cbdbe3728c66a2ff4929be96d457e3ea0d80f3",
        "tarball": "https://registry.npmjs.org/react-slick/-/react-slick-0.14.11.tgz"
    },
    "gitHead": "8d514f25d5dcd85427fb29225e32705b0f07e284",
    "homepage": "https://github.com/akiran/react-slick",
    "jest": {
        "setupFiles": [
            "./test-setup.js"
        ]
    },
    "keywords": [
        "slick",
        "carousel",
        "Image slider",
        "orbit",
        "slider",
        "react-component"
    ],
    "license": "MIT",
    "main": "./lib",
    "maintainers": [
        {
            "name": "akiran"
        }
    ],
    "name": "react-slick",
    "npmFileMap": [
        {
            "basePath": "/dist/",
            "files": [
                "*.js"
            ]
        }
    ],
    "npmName": "react-slick",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.1",
        "react-dom": "^0.14.0 || ^15.0.1"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/akiran/react-slick.git"
    },
    "scripts": {
        "dev-test": "jest --watch",
        "lint": "eslint src",
        "prepublish": "babel ./src --out-dir ./lib && gulp dist",
        "start": "gulp server",
        "test": "jest"
    },
    "version": "0.14.11",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
