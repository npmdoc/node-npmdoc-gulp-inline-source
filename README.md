# npmdoc-gulp-inline-source

#### api documentation for  [gulp-inline-source (v3.1.0)](https://github.com/fmal/gulp-inline-source#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-inline-source.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-inline-source) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-inline-source.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-inline-source)

#### Inline flagged js & css sources.

[![NPM](https://nodei.co/npm/gulp-inline-source.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-inline-source)

- [https://npmdoc.github.io/node-npmdoc-gulp-inline-source/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-inline-source/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-inline-source/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-inline-source/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-inline-source/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-inline-source/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Filip Malinowski"
    },
    "bugs": {
        "url": "https://github.com/fmal/gulp-inline-source/issues"
    },
    "config": {
        "commitizen": {
            "path": "./node_modules/cz-conventional-changelog"
        }
    },
    "dependencies": {
        "gulp-util": "~3.0.6",
        "inline-source": "~5.2.1",
        "through2": "~2.0.0"
    },
    "description": "Inline flagged js & css sources.",
    "devDependencies": {
        "commitizen": "^2.9.6",
        "cz-conventional-changelog": "^2.0.0",
        "faucet": "0.0.1",
        "husky": "^0.13.3",
        "semantic-release": "^6.3.2",
        "tape": "^4.0.1",
        "validate-commit-msg": "^2.12.1"
    },
    "directories": {},
    "dist": {
        "shasum": "fe7b94a3105d3523356ab4e639112fcb2cbfea52",
        "tarball": "https://registry.npmjs.org/gulp-inline-source/-/gulp-inline-source-3.1.0.tgz"
    },
    "gitHead": "029107b8bb75ad09ec295f6fee07ae85b64c1f21",
    "homepage": "https://github.com/fmal/gulp-inline-source#readme",
    "keywords": [
        "gulpplugin",
        "inline",
        "css",
        "javascript"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "fmal"
        }
    ],
    "name": "gulp-inline-source",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/fmal/gulp-inline-source.git"
    },
    "scripts": {
        "commit": "git-cz",
        "commitmsg": "validate-commit-msg",
        "prepush": "npm test",
        "semantic-release": "semantic-release pre && npm publish && semantic-release post",
        "test": "tape test/*.js | faucet"
    },
    "version": "3.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
