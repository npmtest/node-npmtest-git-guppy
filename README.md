# npmtest-git-guppy

#### basic test coverage for  [git-guppy (v2.1.0)](https://github.com/therealklanni/git-guppy)  [![npm package](https://img.shields.io/npm/v/npmtest-git-guppy.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-git-guppy) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-git-guppy.svg)](https://travis-ci.org/npmtest/node-npmtest-git-guppy)

#### Simple git-hook integration for your gulp workflows.

[![NPM](https://nodei.co/npm/git-guppy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/git-guppy)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-git-guppy/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-git-guppy/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-git-guppy/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-git-guppy/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-git-guppy/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-git-guppy/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-git-guppy/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-git-guppy/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-git-guppy/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-git-guppy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-git-guppy/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-git-guppy/build/test-report.html](https://npmtest.github.io/node-npmtest-git-guppy/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-git-guppy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-git-guppy/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-git-guppy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-git-guppy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-git-guppy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-git-guppy/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-git-guppy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-git-guppy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kevin Lanni",
        "url": "https://github.com/therealklanni"
    },
    "bugs": {
        "url": "https://github.com/therealklanni/git-guppy/issues"
    },
    "dependencies": {
        "lodash": "^4.17.4",
        "map-stream": "0.0.6",
        "shelljs": "^0.6.0",
        "strip-bom": "^2.0.0"
    },
    "description": "Simple git-hook integration for your gulp workflows.",
    "devDependencies": {
        "chai": "^3.5.0",
        "gulp": "^3.9.1",
        "gulp-filter": "^4.0.0",
        "gulp-istanbul": "^1.0.0",
        "gulp-jshint": "^2.0.0",
        "gulp-load-plugins": "^1.2.0",
        "gulp-mocha": "^2.0.0",
        "guppy-pre-commit": "^0.3.0",
        "jshint": "^2.9.1",
        "jshint-stylish": "^2.1.0",
        "mocha": "*",
        "proxyquire": "^1.7.4",
        "semantic-release": "^4.3.5",
        "sinon": "^1.12.1",
        "sinon-chai": "^2.6.0",
        "updtr": "^0.1.10"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "f6513ec963c6056392c1083966ba001a250b6696",
        "tarball": "https://registry.npmjs.org/git-guppy/-/git-guppy-2.1.0.tgz"
    },
    "engines": {
        "node": ">= 4"
    },
    "gitHead": "86d114d3e1cb50b97445952984bef6a3f0116c9d",
    "homepage": "https://github.com/therealklanni/git-guppy",
    "keywords": [
        "git",
        "git-hook",
        "git-hooks",
        "gulp",
        "gulpplugin",
        "guppy"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "therealklanni"
        }
    ],
    "name": "git-guppy",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/therealklanni/git-guppy.git"
    },
    "scripts": {
        "semantic-release": "semantic-release pre && npm publish && semantic-release post",
        "test": "gulp test",
        "update": "updtr"
    },
    "version": "2.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
