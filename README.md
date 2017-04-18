# npmtest-psy

#### test coverage for  [psy (v1.8.1)](https://github.com/substack/psy#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-psy.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-psy) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-psy.svg)](https://travis-ci.org/npmtest/node-npmtest-psy)

#### process monitor command

[![NPM](https://nodei.co/npm/psy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/psy)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-psy/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-psy/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-psy/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-psy/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-psy/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-psy/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-psy/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-psy/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-psy/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-psy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-psy/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-psy/build/test-report.html](https://npmtest.github.io/node-npmtest-psy/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-psy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-psy/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-psy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-psy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-psy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-psy/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-psy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-psy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "substack"
    },
    "bin": {
        "psy": "cmd.js"
    },
    "bugs": {
        "url": "https://github.com/substack/psy/issues"
    },
    "dependencies": {
        "auto-daemon": "^2.1.3",
        "defined": "^1.0.0",
        "end-of-stream": "^1.1.0",
        "has": "^1.0.0",
        "inherits": "^2.0.1",
        "minimist": "^1.1.1",
        "mkdirp": "^0.5.1",
        "once": "^1.3.2",
        "respawn-group": "^1.0.1",
        "rpc-stream": "^2.1.1",
        "slice-file": "^1.0.0",
        "sprintf": "^0.1.5",
        "text-table": "^0.2.0",
        "through2": "^0.6.5",
        "timeago.js": "^1.0.9",
        "xdg-basedir": "^2.0.0",
        "xtend": "^4.0.1"
    },
    "description": "process monitor command",
    "devDependencies": {
        "tape": "^4.2.2"
    },
    "directories": {},
    "dist": {
        "shasum": "4670ddb60b09a28f52d1663ebee0c7555b067474",
        "tarball": "https://registry.npmjs.org/psy/-/psy-1.8.1.tgz"
    },
    "gitHead": "68dd5803b71b5eb15cddf27bc5f5c6efadf61c73",
    "homepage": "https://github.com/substack/psy#readme",
    "keywords": [
        "respawn",
        "process",
        "monitor",
        "oppa",
        "gangnam style",
        "launch",
        "init",
        "spawn"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "aredridel"
        },
        {
            "name": "karissa"
        },
        {
            "name": "substack"
        },
        {
            "name": "yoshuawuyts"
        }
    ],
    "name": "psy",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/substack/psy.git"
    },
    "scripts": {
        "start": "node server.js",
        "test": "tape test/*.js"
    },
    "version": "1.8.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
