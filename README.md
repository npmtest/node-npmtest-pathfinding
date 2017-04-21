# npmtest-pathfinding

#### basic test coverage for  [pathfinding (v0.4.18)](https://github.com/qiao/PathFinding.js)  [![npm package](https://img.shields.io/npm/v/npmtest-pathfinding.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pathfinding) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pathfinding.svg)](https://travis-ci.org/npmtest/node-npmtest-pathfinding)

#### Comprehensive pathfinding library for grid based games

[![NPM](https://nodei.co/npm/pathfinding.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pathfinding)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pathfinding/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pathfinding/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pathfinding/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pathfinding/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pathfinding/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pathfinding/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pathfinding/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pathfinding/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pathfinding/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pathfinding/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pathfinding/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pathfinding/build/test-report.html](https://npmtest.github.io/node-npmtest-pathfinding/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pathfinding/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pathfinding/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pathfinding/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pathfinding/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pathfinding/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pathfinding/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pathfinding/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pathfinding/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "pathfinding",
    "version": "0.4.18",
    "description": "Comprehensive pathfinding library for grid based games",
    "homepage": "https://github.com/qiao/PathFinding.js",
    "keywords": [
        "pathfinding",
        "astar",
        "dijkstra",
        "game",
        "algorithm",
        "jumppoint",
        "depthfirst",
        "breadthfirst"
    ],
    "author": "Xueqiao Xu <xueqiaoxu@gmail.com>",
    "main": "./index.js",
    "dependencies": {
        "heap": "0.2.5"
    },
    "devDependencies": {
        "colors": "^1.0.3",
        "del": "^0.1.3",
        "gulp": "^3.8.10",
        "gulp-browserify": "^0.5.0",
        "gulp-concat": "^2.4.1",
        "gulp-jshint": "^1.9.0",
        "gulp-mocha": "^2.0.0",
        "gulp-rename": "^1.2.0",
        "gulp-uglify": "^1.0.1",
        "inquirer": "^0.8.0",
        "jshint-stylish": "^1.0.0",
        "jsonfile": "^2.0.0",
        "mocha": "2.0.x",
        "semver": "^4.2.0",
        "shelljs": "^0.3.0",
        "should": "4.3.x"
    },
    "scripts": {
        "test": "gulp test"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/qiao/PathFinding.js.git"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "http://opensource.org/licenses/mit-license.php"
        }
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
