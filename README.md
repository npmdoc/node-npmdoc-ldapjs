# npmdoc-ldapjs

#### api documentation for  [ldapjs (v1.0.1)](http://ldapjs.org)  [![npm package](https://img.shields.io/npm/v/npmdoc-ldapjs.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ldapjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ldapjs.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ldapjs)

#### LDAP client and server APIs

[![NPM](https://nodei.co/npm/ldapjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ldapjs)

- [https://npmdoc.github.io/node-npmdoc-ldapjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ldapjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ldapjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ldapjs/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ldapjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ldapjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mark Cavage"
    },
    "bin": {
        "ldapjs-add": "bin/ldapjs-add",
        "ldapjs-compare": "bin/ldapjs-compare",
        "ldapjs-delete": "bin/ldapjs-delete",
        "ldapjs-modify": "bin/ldapjs-modify",
        "ldapjs-search": "bin/ldapjs-search"
    },
    "bugs": {
        "url": "https://github.com/mcavage/node-ldapjs/issues"
    },
    "contributors": [
        {
            "name": "Craig Baker"
        },
        {
            "name": "Austin King"
        },
        {
            "name": "Mathieu Lecarme"
        },
        {
            "name": "Trent Mick"
        },
        {
            "name": "Yunong Xiao"
        },
        {
            "name": "Denis Vuyka"
        },
        {
            "name": "Pedro Palazón"
        },
        {
            "name": "Patrick Mooney"
        },
        {
            "name": "Matt Simerson"
        }
    ],
    "dependencies": {
        "asn1": "0.2.3",
        "assert-plus": "^1.0.0",
        "backoff": "^2.5.0",
        "bunyan": "^1.8.3",
        "dashdash": "^1.14.0",
        "dtrace-provider": "^0.7.0",
        "ldap-filter": "0.2.2",
        "once": "^1.4.0",
        "vasync": "^1.6.4",
        "verror": "^1.8.1"
    },
    "description": "LDAP client and server APIs",
    "devDependencies": {
        "faucet": "0.0.1",
        "istanbul": "^0.4.5",
        "node-uuid": "^1.4.7",
        "tape": "^4.6.2"
    },
    "directories": {
        "bin": "./bin",
        "lib": "./lib"
    },
    "dist": {
        "shasum": "352b812ae74b0a8e96549a4b896060eee1b9a546",
        "tarball": "https://registry.npmjs.org/ldapjs/-/ldapjs-1.0.1.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "homepage": "http://ldapjs.org",
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "mcavage"
        },
        {
            "name": "pfmooney"
        }
    ],
    "name": "ldapjs",
    "optionalDependencies": {
        "dtrace-provider": "^0.7.0"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/mcavage/node-ldapjs.git"
    },
    "scripts": {
        "report": "istanbul report html && open ./coverage/lcov-report/index.html",
        "test": "istanbul cover --print none test/test.js | ./node_modules/.bin/faucet"
    },
    "version": "1.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
