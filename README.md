# npmdoc-newman

#### api documentation for  [newman (v3.5.2)](https://github.com/postmanlabs/newman)  [![npm package](https://img.shields.io/npm/v/npmdoc-newman.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-newman) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-newman.svg)](https://travis-ci.org/npmdoc/node-npmdoc-newman)

#### Command-line companion utility for Postman

[![NPM](https://nodei.co/npm/newman.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/newman)

- [https://npmdoc.github.io/node-npmdoc-newman/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-newman/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-newman/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-newman/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-newman/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-newman/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Postman Labs",
        "url": "="
    },
    "bin": {
        "newman": "./bin/newman.js"
    },
    "bugs": {
        "url": "https://github.com/postmanlabs/newman/issues"
    },
    "dependencies": {
        "argparse": "1.0.9",
        "async": "2.1.5",
        "cli-progress": "1.3.0",
        "cli-table2": "0.2.0",
        "colors": "1.1.2",
        "csv-parse": "1.1.12",
        "eventemitter3": "2.0.2",
        "filesize": "3.5.6",
        "handlebars": "4.0.6",
        "lodash": "4.17.2",
        "mkdirp": "0.5.1",
        "parse-json": "2.2.0",
        "postman-collection": "1.0.1",
        "postman-collection-transformer": "2.0.10",
        "postman-request": "2.80.1-postman.1",
        "postman-runtime": "5.0.0",
        "pretty-ms": "2.1.0",
        "semver": "5.3.0",
        "serialised-error": "1.1.2",
        "shelljs": "0.7.7",
        "word-wrap": "1.1.0",
        "xmlbuilder": "8.2.2"
    },
    "description": "Command-line companion utility for Postman",
    "devDependencies": {
        "editorconfig": "0.13.2",
        "eslint": "3.17.0",
        "eslint-plugin-lodash": "2.3.6",
        "eslint-plugin-mocha": "4.8.0",
        "eslint-plugin-security": "1.3.0",
        "expect.js": "0.3.1",
        "istanbul": "0.4.5",
        "js-yaml": "3.8.2",
        "jsdoc": "3.4.3",
        "jsdoc-to-markdown": "3.0.0",
        "mocha": "3.2.0",
        "nsp": "2.6.3",
        "packity": "0.3.2",
        "parse-gitignore": "0.3.1",
        "postman-jsdoc-theme": "0.0.2",
        "recursive-readdir": "2.1.1"
    },
    "directories": {},
    "dist": {
        "shasum": "f198d13be0a49a47485a59014688db2aee8133c0",
        "tarball": "https://registry.npmjs.org/newman/-/newman-3.5.2.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "gitHead": "13ac5ce23d3d6b7330672bc9634f47a3a391efc3",
    "homepage": "https://github.com/postmanlabs/newman",
    "keywords": [
        "newman",
        "postman",
        "api",
        "testing",
        "ci",
        "rest-client",
        "rest"
    ],
    "license": "Apache-2.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "a85"
        },
        {
            "name": "abhijitkane"
        },
        {
            "name": "czardoz"
        },
        {
            "name": "kunagpal"
        },
        {
            "name": "postman-admin"
        },
        {
            "name": "shamasis"
        }
    ],
    "name": "newman",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git://github.com/postmanlabs/newman.git"
    },
    "scripts": {
        "build-docs": "node npm/build-docs.js",
        "build-wiki": "node npm/build-wiki.js",
        "publish-docs": "node npm/publish-docs.js",
        "publish-wiki": "node npm/publish-wiki.js",
        "test": "node npm/test.js",
        "test-cli": "node npm/test-cli.js",
        "test-integration": "node npm/test-integration.js",
        "test-library": "node npm/test-library.js",
        "test-lint": "node npm/test-lint.js",
        "test-system": "node npm/test-system.js",
        "test-unit": "node npm/test-unit.js"
    },
    "version": "3.5.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
