# npmtest-styled-jsx

#### basic test coverage for  [styled-jsx (v0.5.7)](https://github.com/zeit/styled-jsx#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-styled-jsx.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-styled-jsx) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-styled-jsx.svg)](https://travis-ci.org/npmtest/node-npmtest-styled-jsx)

#### Full CSS support for JSX without compromises

[![NPM](https://nodei.co/npm/styled-jsx.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/styled-jsx)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-styled-jsx/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-styled-jsx/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-styled-jsx/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-styled-jsx/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-styled-jsx/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-styled-jsx/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-styled-jsx/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-styled-jsx/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-styled-jsx/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-styled-jsx/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-styled-jsx/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-styled-jsx/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-styled-jsx/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-styled-jsx/build/test-report.html](https://npmtest.github.io/node-npmtest-styled-jsx/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-styled-jsx/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-styled-jsx/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-styled-jsx/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-styled-jsx/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-styled-jsx/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-styled-jsx/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-styled-jsx/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-styled-jsx/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "ava": {
        "require": [
            "babel-register",
            "babel-polyfill"
        ]
    },
    "babel": {
        "presets": [
            "es2015",
            "stage-3",
            "react"
        ]
    },
    "bugs": {
        "url": "https://github.com/zeit/styled-jsx/issues"
    },
    "dependencies": {
        "babel-plugin-syntax-jsx": "6.18.0",
        "babel-traverse": "6.21.0",
        "babylon": "6.14.1",
        "convert-source-map": "1.3.0",
        "escape-string-regexp": "1.0.5",
        "object.entries": "1.0.4",
        "source-map": "0.5.6",
        "string-hash": "1.1.1"
    },
    "description": "Full CSS support for JSX without compromises",
    "devDependencies": {
        "ava": "0.17.0",
        "babel-cli": "6.18.0",
        "babel-core": "6.18.2",
        "babel-plugin-transform-runtime": "6.15.0",
        "babel-polyfill": "6.16.0",
        "babel-preset-babili": "0.0.10",
        "babel-preset-es2015": "6.16.0",
        "babel-preset-react": "6.16.0",
        "babel-preset-stage-3": "6.16.0",
        "babel-register": "6.18.0",
        "benchmark": "2.1.3",
        "gulp": "3.9.1",
        "gulp-babel": "6.1.2",
        "gulp-benchmark": "1.1.1",
        "human-size": "1.1.0",
        "mz": "2.6.0",
        "react": "15.4.1",
        "react-dom": "15.4.1",
        "xo": "0.17.1"
    },
    "directories": {},
    "dist": {
        "shasum": "2cb02263ffa719b1435a864fdd6c62802ae86669",
        "tarball": "https://registry.npmjs.org/styled-jsx/-/styled-jsx-0.5.7.tgz"
    },
    "files": [
        "dist",
        "lib",
        "server.js",
        "babel.js",
        "style.js"
    ],
    "gitHead": "df90c37c929b5b9d17c5ef62d6fb71b723c830f4",
    "homepage": "https://github.com/zeit/styled-jsx#readme",
    "license": "MIT",
    "maintainers": [
        {
            "name": "leo"
        },
        {
            "name": "nkzawa"
        },
        {
            "name": "rauchg"
        }
    ],
    "name": "styled-jsx",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^15.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/zeit/styled-jsx.git"
    },
    "scripts": {
        "dev": "gulp",
        "prepublish": "gulp transpile",
        "start": "node server.js",
        "test": "xo && ava"
    },
    "version": "0.5.7",
    "xo": {
        "esnext": true,
        "space": true,
        "semicolon": false,
        "ignores": [
            "lib/**",
            "test/fixtures/**"
        ],
        "envs": [
            "node",
            "browser"
        ],
        "rules": {
            "eqeqeq": [
                "error",
                "always",
                {
                    "null": "ignore"
                }
            ],
            "no-eq-null": 0,
            "import/no-unresolved": 0,
            "new-cap": 0
        }
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
