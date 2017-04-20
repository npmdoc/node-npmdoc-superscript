# npmdoc-superscript

#### api documentation for  [superscript (v1.1.0)](http://superscriptjs.com)  [![npm package](https://img.shields.io/npm/v/npmdoc-superscript.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-superscript) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-superscript.svg)](https://travis-ci.org/npmdoc/node-npmdoc-superscript)

#### A dialog system and bot engine for creating human-like chat bots.

[![NPM](https://nodei.co/npm/superscript.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/superscript)

- [https://npmdoc.github.io/node-npmdoc-superscript/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-superscript/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-superscript/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-superscript/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-superscript/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-superscript/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Rob Ellis"
    },
    "bin": {
        "bot-init": "lib/bin/bot-init.js",
        "cleanup": "lib/bin/cleanup.js",
        "parse": "lib/bin/parse.js"
    },
    "bugs": {
        "url": "https://github.com/superscriptjs/superscript/issues"
    },
    "contributors": [
        {
            "name": "Rob Ellis"
        },
        {
            "name": "Issam Hakimi"
        },
        {
            "name": "Marius Ursache"
        },
        {
            "name": "Michael Lewkowitz"
        },
        {
            "name": "John Wehr"
        },
        {
            "name": "Ben James"
        }
    ],
    "dependencies": {
        "async": "^2.3.0",
        "commander": "^2.4.0",
        "debug": "^2.6.3",
        "debug-levels": "^0.2.0",
        "lodash": "^4.17.4",
        "mkdirp": "^0.5.1",
        "moment": "^2.18.1",
        "mongo-tenant": "^1.0.4",
        "mongoose": "^4.9.3",
        "natural": "^0.5.0",
        "pegjs": "^0.10.0",
        "pluralize": "^4.0.0",
        "require-dir": "^0.3.1",
        "rhymes": "^1.0.1",
        "roman-numerals": "^0.3.2",
        "safe-eval": "^0.3.0",
        "sfacts": "^1.0.1",
        "ss-message": "^1.1.2",
        "ss-parser": "^1.0.2",
        "syllablistic": "^0.1.0",
        "wordpos": "^1.1.2"
    },
    "description": "A dialog system and bot engine for creating human-like chat bots.",
    "devDependencies": {
        "babel-cli": "^6.24.0",
        "babel-preset-env": "^1.3.2",
        "babel-register": "^6.24.0",
        "coveralls": "^2.13.0",
        "eslint": "^3.19.0",
        "eslint-config-airbnb": "^14.1.0",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-jsx-a11y": "^4.0.0",
        "eslint-plugin-react": "^6.10.3",
        "istanbul": "^1.1.0-alpha.1",
        "mocha": "^3.2.0",
        "should": "^11.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "968ff0c2f9f54102436f8ecc34e045d86586f1c3",
        "tarball": "https://registry.npmjs.org/superscript/-/superscript-1.1.0.tgz"
    },
    "gitHead": "5b11bcc45dafeff554f65fe01ae3b423b607f4a1",
    "homepage": "http://superscriptjs.com",
    "license": "MIT",
    "main": "lib/bot/index.js",
    "maintainers": [
        {
            "name": "benhjames"
        },
        {
            "name": "silentrob"
        }
    ],
    "name": "superscript",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/superscriptjs/superscript.git"
    },
    "scripts": {
        "build": "babel src --out-dir lib --copy-files",
        "dtest": "DEBUG=*,-mquery,-mocha*, mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive",
        "itest": "DEBUG=SS* DEBUG_LEVEL=info mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive",
        "lint": "eslint --env node src *.js",
        "prepublish": "npm run build",
        "profile": "mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --prof --log-timer-events --recursive",
        "test": "mocha --compilers js:babel-register test -R spec -s 1700 -t 300000 --recursive",
        "test-travis": "./node_modules/istanbul/lib/cli.js cover ./node_modules/mocha/bin/_mocha -- --compilers js:babel-register -R spec test -s 1700 -t 300000 --recursive"
    },
    "version": "1.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
