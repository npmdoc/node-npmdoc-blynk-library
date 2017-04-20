# npmdoc-blynk-library

#### api documentation for  blynk-library (v0.4.7)  [![npm package](https://img.shields.io/npm/v/npmdoc-blynk-library.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-blynk-library) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-blynk-library.svg)](https://travis-ci.org/npmdoc/node-npmdoc-blynk-library)

#### Blynk library implementation for JavaScript (Node.js, Espruino)

[![NPM](https://nodei.co/npm/blynk-library.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/blynk-library)

- [https://npmdoc.github.io/node-npmdoc-blynk-library/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-blynk-library/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-blynk-library/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-blynk-library/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-blynk-library/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-blynk-library/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "blynk-library",
    "version": "0.4.7",
    "description": "Blynk library implementation for JavaScript (Node.js, Espruino)",
    "author": "Volodymyr Shymanskyy",
    "license": "MIT",
    "main": "./blynk.js",
    "bin": {
        "blynk-client": "bin/blynk-client.js",
        "blynk-ctrl": "bin/blynk-ctrl.js"
    },
    "engines": {
        "node": ">= 0.12.0"
    },
    "scripts": {
        "prepublish": "make clean all",
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "browser": {
        "./blynk-node.js": false
    },
    "dependencies": {},
    "keywords": [
        "Arduino",
        "Espruino",
        "Raspberry Pi",
        "IoT",
        "Internet of Things"
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/vshymanskyy/blynk-library-js"
    },
    "bugs": {
        "url": "https://github.com/vshymanskyy/blynk-library-js/issues"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
