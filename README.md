# test coverage for  [gulp-git (v2.1.0)](http://github.com/stevelacy/gulp-git)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-git.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-git) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-git.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-git)
#### Git plugin for gulp (gulpjs.com)

[![NPM](https://nodei.co/npm/gulp-git.png?downloads=true)](https://www.npmjs.com/package/gulp-git)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-git/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-git/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-git/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-git/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-git/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-git/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-git/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-git/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-gulp-git/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-git/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-gulp-git%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-git/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-git/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-gulp-git%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-git/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-git/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-git/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Steve Lacy me@slacy.me",
        "url": "slacy.me"
    },
    "bugs": {
        "url": "https://github.com/stevelacy/gulp-git/issues"
    },
    "dependencies": {
        "any-shell-escape": "^0.1.1",
        "gulp-util": "^3.0.8",
        "require-dir": "^0.3.1",
        "strip-bom-stream": "^3.0.0",
        "through2": "^2.0.3",
        "vinyl": "^2.0.1"
    },
    "description": "Git plugin for gulp (gulpjs.com)",
    "devDependencies": {
        "eslint": "^3.17.0",
        "mocha": "^3.2.0",
        "rimraf": "^2.6.1",
        "should": "^11.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "f09661529e4e15626b6dae7d330820d9871f9d65",
        "tarball": "https://registry.npmjs.org/gulp-git/-/gulp-git-2.1.0.tgz"
    },
    "engines": {
        "node": ">= 0.9.0"
    },
    "gitHead": "7894cdd4629c2d86626eed14ebb31ecb95edcb35",
    "homepage": "http://github.com/stevelacy/gulp-git",
    "keywords": [
        "gulp",
        "git",
        "gulpgit",
        "gulpplugin",
        "gulp-plugin"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "stevelacy",
            "email": "me@slacy.me"
        }
    ],
    "name": "gulp-git",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/stevelacy/gulp-git.git"
    },
    "scripts": {
        "docs": "rimraf docs/* && jsdoc ./index.js ./lib --recurse --destination ./docs",
        "pretest": "rimraf test/repo test/tmp && eslint ./index.js ./examples/ ./lib/ ./test/",
        "test": "mocha --reporter spec --timeout 6000 test/main.js"
    },
    "version": "2.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
