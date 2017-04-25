# npmtest-keystone

#### basic test coverage for  [keystone (v0.3.22)](http://keystonejs.com/)  [![npm package](https://img.shields.io/npm/v/npmtest-keystone.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-keystone) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-keystone.svg)](https://travis-ci.org/npmtest/node-npmtest-keystone)

#### Web Application Framework and Admin GUI / Content Management System built on Express.js and Mongoose

[![NPM](https://nodei.co/npm/keystone.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/keystone)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-keystone/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-keystone/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-keystone/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-keystone/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-keystone/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-keystone/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-keystone/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-keystone/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-keystone/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-keystone/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-keystone/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-keystone/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-keystone/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-keystone/build/test-report.html](https://npmtest.github.io/node-npmtest-keystone/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-keystone/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-keystone/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-keystone/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-keystone/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-keystone/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-keystone/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-keystone/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-keystone/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jed Watson"
    },
    "browserify": {
        "transform": [
            "babelify",
            "browserify-shim"
        ]
    },
    "browserify-shim": {
        "tinymce": "global:tinymce",
        "jquery": "global:$",
        "codemirror": "global:CodeMirror",
        "underscore": "global:_",
        "pikaday": "global.Pikaday",
        "moment": "global.moment"
    },
    "bugs": {
        "url": "https://github.com/keystonejs/keystone/issues"
    },
    "dependencies": {
        "async": "^1.5.2",
        "asyncdi": "^1.1.0",
        "azure": "^0.10.6",
        "babel-core": "^6.6.0",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-react": "^6.5.0",
        "babelify": "^7.2.0",
        "babyparse": "^0.4.3",
        "bcrypt-nodejs": "~0.0.3",
        "blacklist": "^1.1.2",
        "bluebird": "^2.10.2",
        "body-parser": "^1.14.1",
        "browserify-shim": "^3.8.10",
        "bytes": "^2.1.0",
        "caller-id": "^0.1.0",
        "chalk": "^1.1.1",
        "classnames": "^2.1.5",
        "cloudinary": "^1.2.5",
        "codemirror": "^5.7.0",
        "compression": "^1.6.0",
        "connect-flash": "^0.1.1",
        "cookie-parser": "^1.4.0",
        "debug": "^2.2.0",
        "embedly": "^1.0.4",
        "errorhandler": "^1.4.2",
        "express": "^4.13.3",
        "express-session": "^1.11.3",
        "fs-extra": "^0.26.7",
        "grappling-hook": "^3.0.0",
        "jade": "^1.11.0",
        "jquery": "^2.1.4",
        "juice": "^1.10.0",
        "keystone-utils": "^0.3.0",
        "knox": "^0.9.2",
        "less-middleware": "^2.0.1",
        "letsencrypt-express": "^1.1.5",
        "list-to-array": "^1.1.0",
        "mailgun-js": "^0.7.10",
        "mandrill-api": "^1.0.45",
        "marked": "^0.3.5",
        "method-override": "^2.3.5",
        "moment": "^2.10.6",
        "mongoose": "~3.8.35",
        "morgan": "^1.6.1",
        "mpromise": "^0.5.5",
        "multer": "^0.1.8",
        "numeral": "^1.5.3",
        "object-assign": "^4.0.1",
        "pikaday": "^1.3.3",
        "queryfilter": "^0.0.4",
        "range_check": "^0.0.5",
        "react": "^0.13.3",
        "react-alt-text": "^1.1.0",
        "react-select": "^0.6.12",
        "scmp": "^1.0.0",
        "semver": "^5.0.3",
        "serve-favicon": "^2.3.0",
        "store-prototype": "^1.1.1",
        "superagent": "^1.4.0",
        "underscore": "^1.8.3",
        "vkey": "^1.0.0",
        "watchify": "^3.4.0"
    },
    "description": "Web Application Framework and Admin GUI / Content Management System built on Express.js and Mongoose",
    "devDependencies": {
        "babel-eslint": "^4.1.3",
        "browserify": "^13.0.0",
        "codeclimate-test-reporter": "0.1.1",
        "eslint": "^1.6.0",
        "eslint-plugin-react": "^3.5.1",
        "gulp": "^3.9.0",
        "gulp-git": "^1.5.0",
        "gulp-streamify": "1.0.2",
        "gulp-uglify": "^1.4.2",
        "istanbul": "^0.3.22",
        "mocha": "^2.3.3",
        "must": "^0",
        "rimraf": "^2.4.3",
        "sinon": "^1.17.1",
        "supertest": "^1.1.0",
        "vinyl-source-stream": "^1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "77b699e4cb1d48d1d7c10349173ffed4c80a0577",
        "tarball": "https://registry.npmjs.org/keystone/-/keystone-0.3.22.tgz"
    },
    "engines": {
        "node": ">= 0.10.28",
        "npm": ">= 1.4.9"
    },
    "gitHead": "ef3fd612285315ea8e12f68da4c8d6031e2c7fe7",
    "homepage": "http://keystonejs.com/",
    "keywords": [
        "express",
        "web",
        "app",
        "cms",
        "admin",
        "framework",
        "mongoose",
        "gui",
        "site",
        "website",
        "forms"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jedwatson"
        },
        {
            "name": "mxstbr"
        }
    ],
    "name": "keystone",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/keystonejs/keystone.git"
    },
    "scripts": {
        "build": "NODE_ENV=production gulp build-packages",
        "build-dev": "gulp build-packages",
        "clean": "rimraf ./coverage",
        "lint": "eslint .",
        "posttest-cov": "if [ -n \"$CODECLIMATE_REPO_TOKEN\" ]; then codeclimate-test-reporter < coverage/lcov.info; fi",
        "pretest-cov": "npm run clean",
        "release": "gulp release",
        "test": "mocha",
        "test-cov": "istanbul cover ./node_modules/mocha/bin/_mocha"
    },
    "version": "0.3.22",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
