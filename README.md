# npmtest-typescript

#### basic test coverage for  [typescript (v2.2.2)](http://typescriptlang.org/)  [![npm package](https://img.shields.io/npm/v/npmtest-typescript.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-typescript) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-typescript.svg)](https://travis-ci.org/npmtest/node-npmtest-typescript)

#### TypeScript is a language for application scale JavaScript development

[![NPM](https://nodei.co/npm/typescript.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/typescript)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-typescript/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-typescript/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-typescript/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-typescript/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-typescript/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-typescript/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-typescript/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-typescript/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-typescript/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-typescript/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-typescript/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-typescript/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-typescript/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-typescript/build/test-report.html](https://npmtest.github.io/node-npmtest-typescript/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-typescript/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-typescript/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-typescript/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-typescript/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-typescript/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-typescript/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-typescript/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-typescript/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Microsoft Corp."
    },
    "bin": {
        "tsc": "./bin/tsc",
        "tsserver": "./bin/tsserver"
    },
    "browser": {
        "buffer": false,
        "fs": false,
        "os": false,
        "path": false
    },
    "bugs": {
        "url": "https://github.com/Microsoft/TypeScript/issues"
    },
    "dependencies": {},
    "description": "TypeScript is a language for application scale JavaScript development",
    "devDependencies": {
        "@types/browserify": "latest",
        "@types/chai": "latest",
        "@types/convert-source-map": "latest",
        "@types/del": "latest",
        "@types/glob": "latest",
        "@types/gulp": "latest",
        "@types/gulp-concat": "latest",
        "@types/gulp-help": "latest",
        "@types/gulp-newer": "latest",
        "@types/gulp-sourcemaps": "latest",
        "@types/gulp-typescript": "latest",
        "@types/merge2": "latest",
        "@types/minimatch": "latest",
        "@types/minimist": "latest",
        "@types/mkdirp": "latest",
        "@types/mocha": "latest",
        "@types/node": "latest",
        "@types/q": "latest",
        "@types/run-sequence": "latest",
        "@types/through2": "latest",
        "browserify": "latest",
        "chai": "latest",
        "convert-source-map": "latest",
        "del": "latest",
        "gulp": "latest",
        "gulp-clone": "latest",
        "gulp-concat": "latest",
        "gulp-help": "latest",
        "gulp-insert": "latest",
        "gulp-newer": "latest",
        "gulp-sourcemaps": "latest",
        "gulp-typescript": "3.1.3",
        "into-stream": "latest",
        "istanbul": "latest",
        "jake": "latest",
        "merge2": "latest",
        "minimist": "latest",
        "mkdirp": "latest",
        "mocha": "latest",
        "mocha-fivemat-progress-reporter": "latest",
        "q": "latest",
        "run-sequence": "latest",
        "sorcery": "latest",
        "through2": "latest",
        "travis-fold": "latest",
        "ts-node": "latest",
        "tslint": "4.3.0-dev.0",
        "typescript": "^2.2"
    },
    "directories": {},
    "dist": {
        "shasum": "606022508479b55ffa368b58fee963a03dfd7b0c",
        "tarball": "https://registry.npmjs.org/typescript/-/typescript-2.2.2.tgz"
    },
    "engines": {
        "node": ">=4.2.0"
    },
    "gitHead": "d89553f63edab8d790e76afdfd4b541551732f6e",
    "homepage": "http://typescriptlang.org/",
    "keywords": [
        "TypeScript",
        "Microsoft",
        "compiler",
        "language",
        "javascript"
    ],
    "license": "Apache-2.0",
    "main": "./lib/typescript.js",
    "maintainers": [
        {
            "name": "typescript"
        }
    ],
    "name": "typescript",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Microsoft/TypeScript.git"
    },
    "scripts": {
        "build": "npm run build:compiler && npm run build:tests",
        "build:compiler": "jake local",
        "build:tests": "jake tests",
        "clean": "jake clean",
        "gulp": "gulp",
        "jake": "jake",
        "lint": "jake lint",
        "pretest": "jake tests",
        "setup-hooks": "node scripts/link-hooks.js",
        "start": "node lib/tsc",
        "test": "jake runtests-parallel"
    },
    "typings": "./lib/typescript.d.ts",
    "version": "2.2.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
