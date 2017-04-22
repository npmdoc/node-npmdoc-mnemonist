# npmdoc-mnemonist

#### api documentation for  [mnemonist (v0.12.0)](https://github.com/yomguithereal/mnemonist#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-mnemonist.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-mnemonist) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-mnemonist.svg)](https://travis-ci.org/npmdoc/node-npmdoc-mnemonist)

#### Curated collection of data structures for the JavaScript language.

[![NPM](https://nodei.co/npm/mnemonist.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mnemonist)

- [https://npmdoc.github.io/node-npmdoc-mnemonist/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mnemonist/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mnemonist/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mnemonist/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-mnemonist/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-mnemonist/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Guillaume Plique",
        "url": "http://github.com/Yomguithereal"
    },
    "bugs": {
        "url": "https://github.com/yomguithereal/mnemonist/issues"
    },
    "dependencies": {},
    "description": "Curated collection of data structures for the JavaScript language.",
    "devDependencies": {
        "@yomguithereal/eslint-config": "^3.0.0",
        "damerau-levenshtein": "^1.0.3",
        "eslint": "^3.8.1",
        "leven": "^2.0.0",
        "lodash": "^4.17.4",
        "mocha": "^3.1.2"
    },
    "directories": {},
    "dist": {
        "shasum": "5ff78f86cf0d28a28e1fb8e4f514469b4e78cc1b",
        "tarball": "https://registry.npmjs.org/mnemonist/-/mnemonist-0.12.0.tgz"
    },
    "eslintConfig": {
        "extends": "@yomguithereal/eslint-config",
        "globals": {
            "Set": true,
            "Map": true,
            "Symbol": true,
            "Uint8Array": true,
            "Uint16Array": true,
            "Float64Array": true
        },
        "parserOptions": {
            "ecmaVersion": 6
        },
        "ecmaFeatures": {
            "forOf": true
        }
    },
    "files": [
        "utils",
        "*.js"
    ],
    "gitHead": "6429f0279e8dd8e9cff0191c47deb96a6696412c",
    "homepage": "https://github.com/yomguithereal/mnemonist#readme",
    "keywords": [
        "data structures",
        "structures",
        "heap",
        "fibonacci heap",
        "stack",
        "queue",
        "inverted index",
        "linked list",
        "trie",
        "bag",
        "multiset",
        "multimap",
        "counter",
        "suffix tree",
        "symspell",
        "bk tree",
        "burkhard-keller tree",
        "vp tree",
        "vantage point tree"
    ],
    "license": "MIT",
    "main": "endpoint.js",
    "maintainers": [
        {
            "name": "yomguithereal"
        }
    ],
    "name": "mnemonist",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/yomguithereal/mnemonist.git"
    },
    "scripts": {
        "lint": "eslint ./*.js ./utils ./test",
        "prepublish": "npm run lint && npm test",
        "test": "mocha"
    },
    "version": "0.12.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
