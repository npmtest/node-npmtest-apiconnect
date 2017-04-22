# npmtest-apiconnect

#### basic test coverage for  apiconnect (v2.6.2)  [![npm package](https://img.shields.io/npm/v/npmtest-apiconnect.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-apiconnect) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-apiconnect.svg)](https://travis-ci.org/npmtest/node-npmtest-apiconnect)

#### IBM API Connect Developer Toolkit

[![NPM](https://nodei.co/npm/apiconnect.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/apiconnect)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-apiconnect/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-apiconnect/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-apiconnect/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-apiconnect/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-apiconnect/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-apiconnect/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-apiconnect/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-apiconnect/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-apiconnect/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-apiconnect/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-apiconnect/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-apiconnect/build/test-report.html](https://npmtest.github.io/node-npmtest-apiconnect/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-apiconnect/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-apiconnect/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-apiconnect/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-apiconnect/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-apiconnect/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-apiconnect/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-apiconnect/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-apiconnect/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "apiconnect",
    "version": "2.6.2",
    "product-name": "API Connect",
    "product-version": "5.0.7.0",
    "description": "IBM API Connect Developer Toolkit",
    "main": "index.js",
    "scripts": {
        "pretest": "eslint --ignore-path .gitignore .",
        "test": "tap --bail --timeout=1000 ./test/test-* --reporter=spec",
        "preuninstall": "node ./lib/apic-uninstall.js",
        "postuninstall": "node ./lib/apic-npm-cache-clear.js"
    },
    "bin": {
        "apic": "./bin/cli.js"
    },
    "repository": {
        "type": "git",
        "url": "git@github.ibm.com:apimesh/apiconnect.git"
    },
    "author": "IBM API Connect",
    "license": "SEE LICENSE IN LICENSE.txt",
    "dependencies": {
        "apiconnect-cli-apis": "^2.x",
        "apiconnect-cli-apps": "^2.x",
        "apiconnect-cli-auth": "^3.x",
        "apiconnect-cli-catalogs": "^2.x",
        "apiconnect-cli-components": "^1.x",
        "apiconnect-cli-config": "^3.x",
        "apiconnect-cli-create": "^2.x",
        "apiconnect-cli-devapps": "^1.x",
        "apiconnect-cli-drafts": "^2.x",
        "apiconnect-cli-edit": "^3.x",
        "apiconnect-cli-explore": "^1.x",
        "apiconnect-cli-extensions": "^1.x",
        "apiconnect-cli-logger": "^1.x",
        "apiconnect-cli-loopback": "^2.x",
        "apiconnect-cli-members": "^1.x",
        "apiconnect-cli-orgs": "^2.x",
        "apiconnect-cli-plugins": "^3.x",
        "apiconnect-cli-pm": "^2.x",
        "apiconnect-cli-policies": "^1.x",
        "apiconnect-cli-products": "^2.x",
        "apiconnect-cli-securegateways": "^1.x",
        "apiconnect-cli-spaces": "^1.x",
        "apiconnect-cli-subscriptions": "^1.x",
        "apiconnect-cli-swiftserver": "^1.x",
        "apiconnect-cli-validate": "^2.x",
        "apiconnect-cli-version-checker": "^1.x",
        "apiconnect-config": "^1.x",
        "apiconnect-tracking": "^1.x",
        "bluebird": "^3.x",
        "commander": "^2.x",
        "debug": "^2.x",
        "fs-extra": "~0.26.4",
        "inquirer": "~0.8.5",
        "lodash": "^4.x",
        "mkdirp": "~0.5.1",
        "strong-globalize": "^2.x"
    },
    "devDependencies": {
        "apiconnect-cli-test-support": "^3.x",
        "bluebird": "^3.x",
        "eslint": "^2.x",
        "eslint-config-apiconnect": "^2.x",
        "fast-stats": "0.0.3",
        "rimraf": "^2.x",
        "tap": "^5.x"
    },
    "engines": {
        "node": ">=4"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
