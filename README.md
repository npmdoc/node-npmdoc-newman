# api documentation for  [newman (v3.5.2)](https://github.com/postmanlabs/newman)  [![npm package](https://img.shields.io/npm/v/npmdoc-newman.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-newman) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-newman.svg)](https://travis-ci.org/npmdoc/node-npmdoc-newman)
#### Command-line companion utility for Postman

[![NPM](https://nodei.co/npm/newman.png?downloads=true)](https://www.npmjs.com/package/newman)

[![apidoc](https://npmdoc.github.io/node-npmdoc-newman/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-newman_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-newman/build..beta..travis-ci.org/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-newman/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-newman/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Postman Labs",
        "email": "help@getpostman.com",
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
            "name": "a85",
            "email": "abhinav@rickreation.com"
        },
        {
            "name": "abhijitkane",
            "email": "abhijitkane@gmail.com"
        },
        {
            "name": "czardoz",
            "email": "aniketpanse@gmail.com"
        },
        {
            "name": "kunagpal",
            "email": "kunagpal@gmail.com"
        },
        {
            "name": "postman-admin",
            "email": "help@getpostman.com"
        },
        {
            "name": "shamasis",
            "email": "mail@shamasis.net"
        }
    ],
    "name": "newman",
    "optionalDependencies": {},
    "preferGlobal": true,
    "readme": "ERROR: No README data found!",
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



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module newman](#apidoc.module.newman)
1.  [function <span class="apidocSignatureSpan">newman.</span>run (options, callback)](#apidoc.element.newman.run)
1.  [function <span class="apidocSignatureSpan">newman.</span>version ()](#apidoc.element.newman.version)
1.  object <span class="apidocSignatureSpan">newman.</span>util

#### [module newman.util](#apidoc.module.newman.util)
1.  [function <span class="apidocSignatureSpan">newman.util.</span>fetch (location, options, callback)](#apidoc.element.newman.util.fetch)
1.  [function <span class="apidocSignatureSpan">newman.util.</span>fetchJson (location, options, callback)](#apidoc.element.newman.util.fetchJson)
1.  [function <span class="apidocSignatureSpan">newman.util.</span>filesize (bytes)](#apidoc.element.newman.util.filesize)
1.  [function <span class="apidocSignatureSpan">newman.util.</span>getFullName (item, separator)](#apidoc.element.newman.util.getFullName)
1.  [function <span class="apidocSignatureSpan">newman.util.</span>prettyms (ms)](#apidoc.element.newman.util.prettyms)
1.  string <span class="apidocSignatureSpan">newman.util.</span>userAgent
1.  string <span class="apidocSignatureSpan">newman.util.</span>version



# <a name="apidoc.module.newman"></a>[module newman](#apidoc.module.newman)

#### <a name="apidoc.element.newman.run"></a>[function <span class="apidocSignatureSpan">newman.</span>run (options, callback)](#apidoc.element.newman.run)
- description and source-code
```javascript
run = function (options, callback) {
    // validate all options. it is to be noted that 'options' parameter is option and is polymorphic
    (!callback && _.isFunction(options)) && (
        (callback = options),
        (options = {})
    );
    !_.isFunction(callback) && (callback = _.noop);

    var emitter = new EventEmitter(), // @todo: create a new inherited constructor
        runner = new runtime.Runner();

    // get the configuration from various sources
    getOptions(options, function (err, options) {
        if (err) {
            return callback(err);
        }

        // ensure that the collection option is present before starting a run
        if (!_.isObject(options.collection)) {
            return callback(new Error('newman: expecting a collection to run'));
        }

        // store summary object and other relevant information inside the emitter
        emitter.summary = new RunSummary(emitter, options);

        // to store the exported content from reporters
        emitter.exports = [];

        // now start the run!
        runner.run(options.collection, {
            stopOnFailure: options.bail, // LOL, you just got trolled ¯\_(ツ)_/¯
            abortOnFailure: options.abortOnFailure, // used in integration tests, to be considered for a future release
            iterationCount: options.iterationCount,
            environment: options.environment,
            globals: options.globals,
            entrypoint: options.folder,
            data: options.iterationData,
            delay: {
                item: options.delayRequest
            },
            // todo: add support for more types of timeouts, currently only request is supported
            timeout: options.timeoutRequest ? { request: options.timeoutRequest } : undefined,
            fileResolver: fs,
            requester: {
                cookieJar: request.jar(),
                followRedirects: _.has(options, 'ignoreRedirects') ? !options.ignoreRedirects : undefined,
                strictSSL: _.has(options, 'insecure') ? !options.insecure : undefined
            },
            certificates: options.sslClientCert && new sdk.CertificateList({}, [{
                name: 'client-cert',
                matches: [sdk.UrlMatchPattern.MATCH_ALL_URLS],
                key: { src: options.sslClientKey },
                cert: { src: options.sslClientCert },
                passphrase: options.sslClientPassphrase
            }])
        }, function (err, run) {
            var callbacks = {},
                // ensure that the reporter option type polymorphism is handled
                reporters = _.isString(options.reporters) ? [options.reporters] : options.reporters;

            // emit events for all the callbacks triggered by the runtime
            _.forEach(runtimeEvents, function (definition, eventName) {
                // intercept each runtime.* callback and expose a global object based event
                callbacks[eventName] = function (err, cursor) {
                    var args = arguments,
                        obj = { cursor: cursor };

                    // convert the arguments into an object by taking the key name reference from the definition
                    // object
                    _.forEach(definition, function (key, index) {
                        obj[key] = args[index + 2]; // first two are err, cursor
                    });

                    args = [eventName, err, obj];
                    emitter.emit.apply(emitter, args); // eslint-disable-line prefer-spread
                };
            });

            // add non generic callback handling
            _.assignIn(callbacks, {

<span class="apidocCodeCommentSpan">                /**
                 * Bubbles up console messages.
                 *
                 * @param {Object} cursor - The run cursor instance.
                 * @param {String} level - The level of console logging [error, silent, etc].
                 * @returns {*}
                 */
</span>                console: function (cursor, level) {
                    emitter.emit('console', null, { ...
```
- example usage
```shell
...

Newman can be easily used within your JavaScript projects as a NodeJS module. The entire set of Newman CLI functionality is available
 for programmatic use as well. The following example runs a collection by reading a JSON collection file stored on disk.

'''javascript
var newman = require('newman'); // require newman in your project

// call newman.run to pass 'options' object and wait for callback
newman.run({
    collection: require('./sample-collection.json'),
    reporters: 'cli'
}, function (err) {
	if (err) { throw err; }
    console.log('collection run complete!');
});
'''
...
```

#### <a name="apidoc.element.newman.version"></a>[function <span class="apidocSignatureSpan">newman.</span>version ()](#apidoc.element.newman.version)
- description and source-code
```javascript
version = function () {
    console.info(version);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.newman.util"></a>[module newman.util](#apidoc.module.newman.util)

#### <a name="apidoc.element.newman.util.fetch"></a>[function <span class="apidocSignatureSpan">newman.util.</span>fetch (location, options, callback)](#apidoc.element.newman.util.fetch)
- description and source-code
```javascript
fetch = function (location, options, callback) {
    !callback && _.isFunction(options) && (callback = options, options = {});
    return (/^https?:\/\/.*/).test(location) ?
        // Load from URL
        request.get({ url: location }, (err, response, body) => {
            if (err) {
                return callback(err);
            }
            return callback(null, body);
        }) :
        fs.readFile(location, function (err, value) {
            if (err) {
                return callback(err);
            }
            return callback(null, value.toString());
        });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newman.util.fetchJson"></a>[function <span class="apidocSignatureSpan">newman.util.</span>fetchJson (location, options, callback)](#apidoc.element.newman.util.fetchJson)
- description and source-code
```javascript
fetchJson = function (location, options, callback) {
    !callback && _.isFunction(options) && (callback = options, options = {});
    return (/^https?:\/\/.*/).test(location) ?
        // Load from URL
        request.get({
            url: location,
            json: true,
            headers: { 'User-Agent': USER_AGENT_VALUE }
        }, (err, response, body) => {
            if (err) {
                return callback(_.set(err, 'help', 'unable to fetch data from url "${location}"'));
            }

            try {
                _.isString(body) && (body = parseJson(body));
            }
            catch (e) {
                return callback(_.set(e, 'help', 'the url "${location}" did not provide valid JSON data'));
            }

            return callback(null, body);
        }) :
        fs.readFile(location, function (err, value) {
            if (err) {
                return callback(_.set(err, 'help', 'unable to read data from file "${location}"'));
            }

            try {
                value = parseJson(value.toString());
            }
            catch (e) {
                return callback(_.set(e, 'help', 'the file at ${location} does not contain valid JSON data'));
            }

            return callback(null, value);
        });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newman.util.filesize"></a>[function <span class="apidocSignatureSpan">newman.util.</span>filesize (bytes)](#apidoc.element.newman.util.filesize)
- description and source-code
```javascript
filesize = function (bytes) {
    return filesize(bytes || 0, FILESIZE_OPTIONS);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newman.util.getFullName"></a>[function <span class="apidocSignatureSpan">newman.util.</span>getFullName (item, separator)](#apidoc.element.newman.util.getFullName)
- description and source-code
```javascript
getFullName = function (item, separator) {
    if (_.isEmpty(item) || !_.isFunction(item.parent) || !_.isFunction(item.forEachParent)) { return; }

    var chain = [];
    item.forEachParent(function (parent) { chain.unshift(parent.name || parent.id); });

    item.parent() && chain.push(item.name); // Add the current item only if it is not the collection instance
    return chain.join(_.isString(separator) ? separator : SEP);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newman.util.prettyms"></a>[function <span class="apidocSignatureSpan">newman.util.</span>prettyms (ms)](#apidoc.element.newman.util.prettyms)
- description and source-code
```javascript
prettyms = function (ms) {
    return (ms < 1998) ? '${parseInt(ms, 10)}ms' : prettyms(ms || 0);
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
