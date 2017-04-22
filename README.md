# npmtest-react-dnd

#### basic test coverage for  react-dnd (v2.3.0)  [![npm package](https://img.shields.io/npm/v/npmtest-react-dnd.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-dnd) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-dnd.svg)](https://travis-ci.org/npmtest/node-npmtest-react-dnd)

#### Drag and Drop for React

[![NPM](https://nodei.co/npm/react-dnd.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-dnd)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-dnd/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-dnd/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-dnd/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-dnd/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-dnd/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-dnd/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-dnd/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-dnd/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-dnd/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-dnd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-dnd/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-dnd/build/test-report.html](https://npmtest.github.io/node-npmtest-react-dnd/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-dnd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-dnd/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-dnd/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-dnd/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-dnd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-dnd/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-dnd/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-dnd/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "dependencies": {
        "disposables": "^1.0.1",
        "dnd-core": "^2.3.0",
        "hoist-non-react-statics": "^1.2.0",
        "invariant": "^2.1.0",
        "lodash": "^4.2.0"
    },
    "description": "Drag and Drop for React",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "aede61c06b968554dcf2a2445657cdbb3100be49",
        "tarball": "https://registry.npmjs.org/react-dnd/-/react-dnd-2.3.0.tgz"
    },
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "darthtrevino"
        },
        {
            "name": "gaearon"
        },
        {
            "name": "jordangens"
        }
    ],
    "name": "react-dnd",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0-0"
    },
    "scripts": {
        "babel": "../../node_modules/.bin/babel src --out-dir lib",
        "build": "../../node_modules/.bin/npm-run-all --parallel bundle:* babel",
        "bundle:min": "../../node_modules/.bin/webpack --output-filename=dist/ReactDnD.min.js --optimize-minimize",
        "bundle:unmin": "../../node_modules/.bin/webpack --output-filename=dist/ReactDnD.js",
        "clean": "../../node_modules/.bin/rimraf lib dist",
        "prepublish": "npm test",
        "test": "../../node_modules/.bin/npm-run-all clean build"
    },
    "version": "2.3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
