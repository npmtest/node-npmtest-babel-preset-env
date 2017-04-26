# npmtest-babel-preset-env

#### basic test coverage for  [babel-preset-env (v1.4.0)](https://babeljs.io/)  [![npm package](https://img.shields.io/npm/v/npmtest-babel-preset-env.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-babel-preset-env) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-babel-preset-env.svg)](https://travis-ci.org/npmtest/node-npmtest-babel-preset-env)

#### A Babel preset for each environment.

[![NPM](https://nodei.co/npm/babel-preset-env.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/babel-preset-env)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-babel-preset-env/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-babel-preset-env/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-babel-preset-env/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-babel-preset-env/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-babel-preset-env/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-babel-preset-env/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-babel-preset-env/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-babel-preset-env/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-babel-preset-env/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-babel-preset-env/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-babel-preset-env/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-babel-preset-env/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-babel-preset-env/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-babel-preset-env/build/test-report.html](https://npmtest.github.io/node-npmtest-babel-preset-env/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-babel-preset-env/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-babel-preset-env/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-babel-preset-env/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-babel-preset-env/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-babel-preset-env/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-babel-preset-env/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-babel-preset-env/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-babel-preset-env/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Henry Zhu"
    },
    "babel": {
        "presets": [
            [
                "es2015",
                {
                    "loose": true
                }
            ]
        ],
        "plugins": [
            "transform-flow-strip-types"
        ],
        "env": {
            "test": {
                "plugins": [
                    "istanbul"
                ]
            }
        }
    },
    "bugs": {
        "url": "https://github.com/babel/babel-preset-env/issues"
    },
    "dependencies": {
        "babel-plugin-check-es2015-constants": "^6.22.0",
        "babel-plugin-syntax-trailing-function-commas": "^6.22.0",
        "babel-plugin-transform-async-to-generator": "^6.22.0",
        "babel-plugin-transform-es2015-arrow-functions": "^6.22.0",
        "babel-plugin-transform-es2015-block-scoped-functions": "^6.22.0",
        "babel-plugin-transform-es2015-block-scoping": "^6.23.0",
        "babel-plugin-transform-es2015-classes": "^6.23.0",
        "babel-plugin-transform-es2015-computed-properties": "^6.22.0",
        "babel-plugin-transform-es2015-destructuring": "^6.23.0",
        "babel-plugin-transform-es2015-duplicate-keys": "^6.22.0",
        "babel-plugin-transform-es2015-for-of": "^6.23.0",
        "babel-plugin-transform-es2015-function-name": "^6.22.0",
        "babel-plugin-transform-es2015-literals": "^6.22.0",
        "babel-plugin-transform-es2015-modules-amd": "^6.22.0",
        "babel-plugin-transform-es2015-modules-commonjs": "^6.23.0",
        "babel-plugin-transform-es2015-modules-systemjs": "^6.23.0",
        "babel-plugin-transform-es2015-modules-umd": "^6.23.0",
        "babel-plugin-transform-es2015-object-super": "^6.22.0",
        "babel-plugin-transform-es2015-parameters": "^6.23.0",
        "babel-plugin-transform-es2015-shorthand-properties": "^6.22.0",
        "babel-plugin-transform-es2015-spread": "^6.22.0",
        "babel-plugin-transform-es2015-sticky-regex": "^6.22.0",
        "babel-plugin-transform-es2015-template-literals": "^6.22.0",
        "babel-plugin-transform-es2015-typeof-symbol": "^6.23.0",
        "babel-plugin-transform-es2015-unicode-regex": "^6.22.0",
        "babel-plugin-transform-exponentiation-operator": "^6.22.0",
        "babel-plugin-transform-regenerator": "^6.22.0",
        "browserslist": "^1.4.0",
        "invariant": "^2.2.2"
    },
    "description": "A Babel preset for each environment.",
    "devDependencies": {
        "babel-cli": "^6.23.0",
        "babel-eslint": "^7.1.1",
        "babel-helper-fixtures": "^6.22.0",
        "babel-helper-plugin-test-runner": "^6.22.0",
        "babel-plugin-istanbul": "^3.1.2",
        "babel-plugin-transform-flow-strip-types": "^6.22.0",
        "babel-preset-es2015": "^6.22.0",
        "babel-register": "^6.23.0",
        "chai": "^3.5.0",
        "codecov": "^1.0.1",
        "compat-table": "github:kangax/compat-table#861954b6e13d3eaa1ba9ef1a016906c0fc1072db",
        "electron-to-chromium": "^1.3.2",
        "eslint": "^3.17.1",
        "eslint-config-babel": "^6.0.0",
        "eslint-plugin-flowtype": "^2.29.1",
        "fs-extra": "^2.0.0",
        "lodash": "^4.17.4",
        "mocha": "^3.2.0",
        "nyc": "^10.1.2",
        "rimraf": "^2.6.1"
    },
    "directories": {},
    "dist": {
        "shasum": "c8e02a3bcc7792f23cded68e0355b9d4c28f0f7a",
        "tarball": "https://registry.npmjs.org/babel-preset-env/-/babel-preset-env-1.4.0.tgz"
    },
    "gitHead": "125e9283cc70f6b2db15ccf864ff2ff4b3dd10ea",
    "homepage": "https://babeljs.io/",
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "danez"
        },
        {
            "name": "hzoo"
        },
        {
            "name": "loganfsmyth"
        }
    ],
    "name": "babel-preset-env",
    "nyc": {
        "all": true,
        "include": [
            "src/*.js"
        ],
        "instrument": false,
        "sourceMap": false
    },
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/babel/babel-preset-env.git"
    },
    "scripts": {
        "build": "rimraf lib && babel src -d lib",
        "build-data": "node ./scripts/build-data.js",
        "changelog": "git log 'git describe --tags --abbrev=0'..HEAD --pretty=format:' * %s (%an)' | grep -v 'Merge pull request'",
        "coverage": "BABEL_ENV=test nyc npm run test",
        "coverage-ci": "nyc report --reporter=json && codecov -f coverage/coverage-final.json",
        "dev": "babel -w src -d lib",
        "fix": "eslint . --fix",
        "lint": "eslint .",
        "prepublish": "npm run build",
        "test": "npm run build && npm run test-only",
        "test-ci": "nyc npm run test",
        "test-only": "mocha ./test --compilers js:babel-register -t 10000"
    },
    "version": "1.4.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
