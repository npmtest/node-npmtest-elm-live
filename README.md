# npmtest-elm-live

#### basic test coverage for  elm-live (v2.7.4)  [![npm package](https://img.shields.io/npm/v/npmtest-elm-live.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-elm-live) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-elm-live.svg)](https://travis-ci.org/npmtest/node-npmtest-elm-live)

#### A flexible dev server for Elm. Live reload included!

[![NPM](https://nodei.co/npm/elm-live.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/elm-live)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-elm-live/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-elm-live/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-elm-live/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-elm-live/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-elm-live/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-elm-live/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-elm-live/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-elm-live/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-elm-live/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-elm-live/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-elm-live/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-elm-live/build/test-report.html](https://npmtest.github.io/node-npmtest-elm-live/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-elm-live/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-elm-live/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-elm-live/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-elm-live/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-elm-live/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-elm-live/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-elm-live/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-elm-live/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "elm-live",
    "version": "2.7.4",
    "description": "A flexible dev server for Elm. Live reload included!",
    "bin": {
        "elm-live": "bin/elm-live.js"
    },
    "dependencies": {
        "budo": "^9.0.0",
        "chalk": "^1.1.1",
        "chokidar": "^1.4.3",
        "cross-spawn": "^5.0.1",
        "hasbin": "^1.2.1",
        "indent-string": "^3.0.0",
        "q-stream": "^0.2.0"
    },
    "scripts": {
        "develop": "ava --watch",
        "manpages": "scripts/manpages.sh",
        "prepublish": "npm run manpages",
        "test": "eslint . && nyc ava"
    },
    "engines": {
        "node": ">= 6.0.0"
    },
    "engineStrict": true,
    "files": [
        "**/*.js",
        "!/test.js",
        "/Readme.md",
        "/License.md",
        "/manpages/"
    ],
    "man": [
        "/manpages/elm-live.1"
    ],
    "license": "MIT",
    "keywords": [
        "cli",
        "tool"
    ],
    "author": "Tomek Wiszniewski <t.wiszniewski@gmail.com>",
    "repository": {
        "type": "git",
        "url": "git@github.com:tomekwi/elm-live"
    },
    "devDependencies": {
        "ava": "^0.16.0",
        "coveralls": "^2.11.9",
        "dev-null": "^0.1.1",
        "eslint": "^3.3.1",
        "eslint-config-airbnb-base": "^5.0.2",
        "eslint-plugin-import": "^1.13.0",
        "marked-man": "^0.1.5",
        "nyc": "^8.1.0",
        "proxyquire": "^1.7.4",
        "strip-ansi": "^3.0.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
