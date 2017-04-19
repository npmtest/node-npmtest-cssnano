# npmtest-cssnano

#### test coverage for  [cssnano (v3.10.0)](https://github.com/ben-eb/cssnano)  [![npm package](https://img.shields.io/npm/v/npmtest-cssnano.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cssnano) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cssnano.svg)](https://travis-ci.org/npmtest/node-npmtest-cssnano)

#### A modular minifier, built on top of the PostCSS ecosystem.

[![NPM](https://nodei.co/npm/cssnano.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cssnano)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cssnano/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cssnano/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cssnano/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cssnano/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cssnano/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cssnano/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cssnano/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cssnano/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cssnano/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cssnano/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cssnano/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cssnano/build/test-report.html](https://npmtest.github.io/node-npmtest-cssnano/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cssnano/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cssnano/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cssnano/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cssnano/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cssnano/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cssnano/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cssnano/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cssnano/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ben Briggs",
        "url": "http://beneb.info"
    },
    "ava": {
        "require": "babel-core/register"
    },
    "bugs": {
        "url": "https://github.com/ben-eb/cssnano/issues"
    },
    "dependencies": {
        "autoprefixer": "^6.3.1",
        "decamelize": "^1.1.2",
        "defined": "^1.0.0",
        "has": "^1.0.1",
        "object-assign": "^4.0.1",
        "postcss": "^5.0.14",
        "postcss-calc": "^5.2.0",
        "postcss-colormin": "^2.1.8",
        "postcss-convert-values": "^2.3.4",
        "postcss-discard-comments": "^2.0.4",
        "postcss-discard-duplicates": "^2.0.1",
        "postcss-discard-empty": "^2.0.1",
        "postcss-discard-overridden": "^0.1.1",
        "postcss-discard-unused": "^2.2.1",
        "postcss-filter-plugins": "^2.0.0",
        "postcss-merge-idents": "^2.1.5",
        "postcss-merge-longhand": "^2.0.1",
        "postcss-merge-rules": "^2.0.3",
        "postcss-minify-font-values": "^1.0.2",
        "postcss-minify-gradients": "^1.0.1",
        "postcss-minify-params": "^1.0.4",
        "postcss-minify-selectors": "^2.0.4",
        "postcss-normalize-charset": "^1.1.0",
        "postcss-normalize-url": "^3.0.7",
        "postcss-ordered-values": "^2.1.0",
        "postcss-reduce-idents": "^2.2.2",
        "postcss-reduce-initial": "^1.0.0",
        "postcss-reduce-transforms": "^1.0.3",
        "postcss-svgo": "^2.1.1",
        "postcss-unique-selectors": "^2.0.2",
        "postcss-value-parser": "^3.2.3",
        "postcss-zindex": "^2.0.1"
    },
    "description": "A modular minifier, built on top of the PostCSS ecosystem.",
    "devDependencies": {
        "array-to-sentence": "^1.1.0",
        "ava": "^0.17.0",
        "babel-cli": "^6.5.1",
        "babel-core": "^6.5.1",
        "babel-loader": "^6.2.4",
        "babel-plugin-add-module-exports": "^0.2.0",
        "babel-plugin-precompile-charcodes": "^1.0.0",
        "babel-preset-es2015-loose": "^7.0.0",
        "babel-preset-stage-0": "^6.5.0",
        "coveralls": "^2.11.6",
        "cross-env": "^2.0.0",
        "css-frameworks": "git+https://git@github.com/ben-eb/css-frameworks.git",
        "css-minifier-tests": "git+https://git@github.com/ben-eb/css-minifier-tests.git",
        "del-cli": "^0.2.0",
        "eslint": "^3.0.0",
        "eslint-config-cssnano": "^3.0.0",
        "eslint-plugin-babel": "^3.3.0",
        "eslint-plugin-import": "^2.0.1",
        "gh-pages": "^0.11.0",
        "json-loader": "^0.5.4",
        "ncp": "^2.0.0",
        "nyc": "^10.0.0",
        "postcss-font-magician": "^1.5.0",
        "webpack": "^1.12.13",
        "webpack-bundle-size-analyzer": "^2.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "4f38f6cea2b9b17fa01490f23f1dc68ea65c1c38",
        "tarball": "https://registry.npmjs.org/cssnano/-/cssnano-3.10.0.tgz"
    },
    "eslintConfig": {
        "extends": "cssnano"
    },
    "files": [
        "dist",
        "LICENSE-MIT",
        "quickstart.js"
    ],
    "gitHead": "355c6ec30fe77a505f4b3c8d4c37db421e5109c8",
    "homepage": "https://github.com/ben-eb/cssnano",
    "keywords": [
        "css",
        "compress",
        "minify",
        "optimise",
        "optimisation",
        "postcss",
        "postcss-plugin"
    ],
    "license": "MIT",
    "main": "dist/index.js",
    "maintainers": [
        {
            "name": "beneb"
        },
        {
            "name": "trysound"
        }
    ],
    "name": "cssnano",
    "nyc": {
        "exclude": [
            "node_modules",
            "**/__tests__"
        ]
    },
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ben-eb/cssnano.git"
    },
    "scripts": {
        "bundle-size": "webpack --json --config src/__tests__/_webpack.config.js | webpack-bundle-size-analyzer",
        "docs": "cd docs && npm run build && cd .. && gh-pages -d docs/dist",
        "prepublish": "del-cli dist && cross-env BABEL_ENV=publish babel src --out-dir dist --ignore /__tests__/",
        "pretest": "eslint --ignore-path .gitignore src",
        "report": "nyc report --reporter=html",
        "test": "nyc ava src/__tests__/*.js",
        "test-012": "nyc ava src/__tests__/*.js"
    },
    "tonicExampleFilename": "quickstart.js",
    "version": "3.10.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
