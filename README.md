# npmtest-hackmyresume

#### basic test coverage for  [hackmyresume (v1.8.0)](https://github.com/hacksalot/HackMyResume)  [![npm package](https://img.shields.io/npm/v/npmtest-hackmyresume.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-hackmyresume) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-hackmyresume.svg)](https://travis-ci.org/npmtest/node-npmtest-hackmyresume)

#### Generate polished résumés and CVs in HTML, Markdown, LaTeX, MS Word, PDF, plain text, JSON, XML, YAML, smoke signal, and carrier pigeon.

[![NPM](https://nodei.co/npm/hackmyresume.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hackmyresume)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-hackmyresume/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-hackmyresume/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-hackmyresume/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-hackmyresume/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-hackmyresume/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-hackmyresume/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-hackmyresume/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-hackmyresume/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-hackmyresume/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-hackmyresume/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-hackmyresume/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-hackmyresume/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-hackmyresume/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-hackmyresume/build/test-report.html](https://npmtest.github.io/node-npmtest-hackmyresume/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-hackmyresume/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-hackmyresume/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-hackmyresume/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hackmyresume/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hackmyresume/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hackmyresume/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-hackmyresume/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-hackmyresume/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "hacksalot",
        "url": "https://github.com/hacksalot"
    },
    "bin": {
        "hackmyresume": "dist/cli/index.js"
    },
    "bugs": {
        "url": "https://github.com/hacksalot/HackMyResume/issues"
    },
    "contributors": [
        {
            "name": "aruberto",
            "url": "https://github.com/aruberto"
        },
        {
            "name": "jjanusch",
            "url": "https://github.com/driftdev"
        },
        {
            "name": "robertmain",
            "url": "https://github.com/robertmain"
        },
        {
            "name": "tomheon",
            "url": "https://github.com/tomheon"
        },
        {
            "name": "zhuangya",
            "url": "https://github.com/zhuangya"
        },
        {
            "name": "hacksalot",
            "url": "https://github.com/hacksalot"
        }
    ],
    "dependencies": {
        "chalk": "^1.1.1",
        "commander": "^2.9.0",
        "copy": "^0.1.3",
        "escape-latex": "^0.1.2",
        "extend": "^3.0.0",
        "fresca": "~0.6.0",
        "fresh-jrs-converter": "^0.2.2",
        "fresh-resume-starter": "^0.2.2",
        "fresh-themes": "^0.15.1-beta",
        "fs-extra": "^0.26.4",
        "handlebars": "^4.0.5",
        "html": "0.0.10",
        "is-my-json-valid": "^2.12.4",
        "json-lint": "^0.1.0",
        "jsonlint": "^1.6.2",
        "lodash": "^3.10.1",
        "marked": "^0.3.5",
        "mkdirp": "^0.5.1",
        "moment": "^2.11.1",
        "parse-filepath": "^0.6.3",
        "path-exists": "^2.1.0",
        "pinkie-promise": "^2.0.0",
        "printf": "^0.2.3",
        "recursive-readdir-sync": "^1.0.6",
        "simple-html-tokenizer": "^0.2.1",
        "slash": "^1.0.0",
        "string-padding": "^1.0.2",
        "string.prototype.endswith": "^0.2.0",
        "string.prototype.startswith": "^0.2.0",
        "traverse": "^0.6.6",
        "underscore": "^1.8.3",
        "word-wrap": "^1.1.0",
        "xml-escape": "^1.0.0",
        "yamljs": "^0.2.4"
    },
    "description": "Generate polished résumés and CVs in HTML, Markdown, LaTeX, MS Word, PDF, plain text, JSON, XML, YAML, smoke signal, and carrier pigeon.",
    "devDependencies": {
        "chai": "*",
        "dir-compare": "0.0.2",
        "fresh-test-resumes": "^0.7.0",
        "grunt": "*",
        "grunt-cli": "^0.1.13",
        "grunt-contrib-clean": "^0.7.0",
        "grunt-contrib-coffee": "^0.13.0",
        "grunt-contrib-copy": "^0.8.2",
        "grunt-contrib-jshint": "^0.11.3",
        "grunt-contrib-yuidoc": "^0.10.0",
        "grunt-jsdoc": "^1.1.0",
        "grunt-simple-mocha": "*",
        "jsonresume-theme-boilerplate": "^0.1.2",
        "jsonresume-theme-classy": "^1.0.9",
        "jsonresume-theme-modern": "0.0.18",
        "jsonresume-theme-sceptile": "^1.0.5",
        "mocha": "*",
        "resample": "github:fluentdesk/resample",
        "stripcolorcodes": "^0.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "ce2b4cb7e1c27a0cabacaf25cdb4b7c8c9b999e1",
        "tarball": "https://registry.npmjs.org/hackmyresume/-/hackmyresume-1.8.0.tgz"
    },
    "gitHead": "3cf850ea0e956ca5162c792ad8dc03cc621cf79a",
    "homepage": "https://github.com/hacksalot/HackMyResume",
    "keywords": [
        "resume",
        "CV",
        "portfolio",
        "employment",
        "career",
        "Markdown",
        "JSON",
        "Word",
        "PDF",
        "YAML",
        "HTML",
        "LaTeX",
        "CLI",
        "Handlebars",
        "Underscore",
        "template"
    ],
    "license": "MIT",
    "main": "dist/index.js",
    "maintainers": [
        {
            "name": "hacksalot"
        }
    ],
    "name": "hackmyresume",
    "optionalDependencies": {},
    "preferGlobal": "true",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/hacksalot/HackMyResume.git"
    },
    "scripts": {
        "grunt": "grunt",
        "test": "grunt clean:test && mocha"
    },
    "version": "1.8.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
