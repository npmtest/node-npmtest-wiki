# npmtest-wiki

#### test coverage for  [wiki (v0.10.3)](https://github.com/fedwiki/wiki#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-wiki.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-wiki) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-wiki.svg)](https://travis-ci.org/npmtest/node-npmtest-wiki)

#### Federated Wiki

[![NPM](https://nodei.co/npm/wiki.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/wiki)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-wiki/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-wiki/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-wiki/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-wiki/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-wiki/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-wiki/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-wiki/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-wiki/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-wiki/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-wiki/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-wiki/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-wiki/build/test-report.html](https://npmtest.github.io/node-npmtest-wiki/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-wiki/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-wiki/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-wiki/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-wiki/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-wiki/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-wiki/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-wiki/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-wiki/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Paul Rodwell",
        "url": "http://wiki-paul90.rhcloud.com"
    },
    "bin": {
        "wiki": "./index.js",
        "wiki-migrate": "./scripts/wiki-migrate.js"
    },
    "bugs": {
        "url": "https://github.com/fedwiki/wiki/issues"
    },
    "contributors": [
        {
            "name": "Nick Niemeir",
            "url": "http://nrn.io"
        },
        {
            "name": "Ward Cunningham",
            "url": "http://ward.fed.wiki.org"
        }
    ],
    "dependencies": {
        "coffee-script": "^1.11.1",
        "coffee-trace": "~1.4.0",
        "config-chain": "^1.1.11",
        "glob": "^7.1.1",
        "lodash": "^4.17.2",
        "optimist": "0.6",
        "wiki-client": "^0.8.0",
        "wiki-plugin-activity": "0.2",
        "wiki-plugin-audio": "^0.1.5",
        "wiki-plugin-bars": "0.3",
        "wiki-plugin-bytebeat": "0.2",
        "wiki-plugin-calculator": "0.2",
        "wiki-plugin-calendar": "0.2",
        "wiki-plugin-changes": "0.2",
        "wiki-plugin-chart": "0.3",
        "wiki-plugin-code": "0.2",
        "wiki-plugin-data": "0.2",
        "wiki-plugin-factory": "0.2",
        "wiki-plugin-favicon": "0.2",
        "wiki-plugin-federatedwiki": "0.2",
        "wiki-plugin-flagmatic": "0.1",
        "wiki-plugin-force": "0.3",
        "wiki-plugin-future": "0.2",
        "wiki-plugin-grep": "^0.1.4",
        "wiki-plugin-html": "0.2",
        "wiki-plugin-image": "0.2",
        "wiki-plugin-line": "0.3",
        "wiki-plugin-map": "^0.3.3",
        "wiki-plugin-markdown": "^0.2.6",
        "wiki-plugin-mathjax": "0.2",
        "wiki-plugin-metabolism": "0.2",
        "wiki-plugin-method": "0.2",
        "wiki-plugin-pagefold": "^0.2.3",
        "wiki-plugin-paragraph": "0.2",
        "wiki-plugin-pushpin": "0.3",
        "wiki-plugin-radar": "0.3",
        "wiki-plugin-reduce": "0.2",
        "wiki-plugin-reference": "0.2",
        "wiki-plugin-report": "0.2",
        "wiki-plugin-rollup": "0.2",
        "wiki-plugin-roster": "^0.1.5",
        "wiki-plugin-scatter": "0.3",
        "wiki-plugin-search": "^0.1.1",
        "wiki-plugin-transport": "^0.1.2",
        "wiki-plugin-video": "^0.2.5",
        "wiki-security-friends": "0.1.0",
        "wiki-security-passportjs": "^0.1.1",
        "wiki-server": "^0.9.1"
    },
    "description": "Federated Wiki",
    "devDependencies": {
        "grunt": "^1.0.1",
        "grunt-git-authors": "^3.2.0",
        "grunt-nsp": "^2.3.1",
        "grunt-retire": "^1.0.3"
    },
    "directories": {},
    "dist": {
        "shasum": "be870004402eb2c09b1c822e2c65ee6fe0766184",
        "tarball": "https://registry.npmjs.org/wiki/-/wiki-0.10.3.tgz"
    },
    "engines": {
        "node": ">=4.x"
    },
    "gitHead": "f466b87d30b20edf158234a3a4ed90c953448418",
    "homepage": "https://github.com/fedwiki/wiki#readme",
    "license": "MIT",
    "maintainers": [
        {
            "name": "ward"
        },
        {
            "name": "nrn"
        },
        {
            "name": "paul90"
        }
    ],
    "name": "wiki",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/fedwiki/wiki.git"
    },
    "scripts": {
        "migrate": "node scripts/wiki-migrate.js",
        "start": "node index.js"
    },
    "version": "0.10.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
