# npmdoc-dploy

#### api documentation for  [dploy (v1.2.0)](https://github.com/LeanMeanFightingMachine/dploy)  [![npm package](https://img.shields.io/npm/v/npmdoc-dploy.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-dploy) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-dploy.svg)](https://travis-ci.org/npmdoc/node-npmdoc-dploy)

#### Command line tool to deploy websites using FTP/SFTP and git.

[![NPM](https://nodei.co/npm/dploy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/dploy)

- [https://npmdoc.github.io/node-npmdoc-dploy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-dploy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-dploy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-dploy/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-dploy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-dploy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Lucas Motta"
    },
    "bin": {
        "dploy": "./bin/dploy"
    },
    "bugs": {
        "url": "https://github.com/LeanMeanFightingMachine/dploy/issues"
    },
    "dependencies": {
        "colors": "~0.6.x",
        "ftp": "~0.3.x",
        "glob-expand": "0.0.2",
        "minimatch": "~0.2.x",
        "prompt": "~0.2.x",
        "signals": "~1.0.x",
        "ssh2": "~0.2.x",
        "yamljs": "~0.1.x"
    },
    "description": "Command line tool to deploy websites using FTP/SFTP and git.",
    "devDependencies": {
        "grunt": "~0.4.x",
        "grunt-bump": "~0.0.x",
        "grunt-coffeelint": "0.0.x",
        "grunt-contrib-coffee": "~0.7.x",
        "grunt-contrib-watch": "~0.5.x",
        "grunt-shell": "~0.6.x"
    },
    "directories": {},
    "dist": {
        "shasum": "69b32a507a6d76a4b93445d16c18ed45c93c4608",
        "tarball": "https://registry.npmjs.org/dploy/-/dploy-1.2.0.tgz"
    },
    "engines": {
        "node": ">= 0.10.x"
    },
    "homepage": "https://github.com/LeanMeanFightingMachine/dploy",
    "keywords": [
        "ftp",
        "sftp",
        "deploy",
        "git"
    ],
    "main": "./lib/dploy",
    "maintainers": [
        {
            "name": "lucasmotta"
        }
    ],
    "name": "dploy",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/LeanMeanFightingMachine/dploy.git"
    },
    "version": "1.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
