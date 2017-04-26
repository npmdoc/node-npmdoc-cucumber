# npmdoc-cucumber

#### basic api documentation for  [cucumber (v1.3.2)](http://github.com/cucumber/cucumber-js)  [![npm package](https://img.shields.io/npm/v/npmdoc-cucumber.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-cucumber) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-cucumber.svg)](https://travis-ci.org/npmdoc/node-npmdoc-cucumber)

#### The official JavaScript implementation of Cucumber.

[![NPM](https://nodei.co/npm/cucumber.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cucumber)

- [https://npmdoc.github.io/node-npmdoc-cucumber/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cucumber/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cucumber/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cucumber/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-cucumber/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-cucumber/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Julien Biezemans",
        "url": "http://jbpros.net"
    },
    "bin": {
        "cucumber.js": "./bin/cucumber.js",
        "cucumber-js": "./bin/cucumber.js",
        "cucumberjs": "./bin/cucumber.js"
    },
    "bugs": {
        "url": "http://github.com/cucumber/cucumber-js/issues"
    },
    "contributors": [
        {
            "name": "Julien Biezemans",
            "url": "http://jbpros.net"
        },
        {
            "name": "Fernando Acorreia"
        },
        {
            "name": "Paul Jensen"
        },
        {
            "name": "Kushal Pisavadia"
        },
        {
            "name": "Olivier Melcher"
        },
        {
            "name": "Tristan Dunn"
        },
        {
            "name": "Ted de Koning"
        },
        {
            "name": "Renier Morales"
        },
        {
            "name": "Aslak Hellesøy"
        },
        {
            "name": "Aaron Garvey"
        },
        {
            "name": "Omar Gonzalez"
        },
        {
            "name": "Chris Young"
        },
        {
            "name": "Israel Halle"
        },
        {
            "name": "Matteo Collina"
        },
        {
            "name": "Niklas Närhinen"
        },
        {
            "name": "Kim, Jang-hwan"
        },
        {
            "name": "Michael Zedeler"
        },
        {
            "name": "Tom V"
        },
        {
            "name": "David Godfrey"
        },
        {
            "name": "Paul Shannon",
            "url": "http://devpaul.com"
        },
        {
            "name": "Simon Dean",
            "url": "http://www.simondean.org"
        },
        {
            "name": "John Wright"
        },
        {
            "name": "Johny Jose"
        },
        {
            "name": "Marat Dyatko"
        },
        {
            "name": "Tim Perry"
        },
        {
            "name": "Fedotov Daniil"
        },
        {
            "name": "unknown"
        },
        {
            "name": "Ben Van Treese"
        },
        {
            "name": "Gabe Hayes"
        },
        {
            "name": "Brian Clozel"
        },
        {
            "name": "Lukas Degener"
        },
        {
            "name": "Simon Lampen"
        },
        {
            "name": "Eddie Loeffen"
        },
        {
            "name": "Stanley Shyiko"
        },
        {
            "name": "Artur Kania"
        },
        {
            "name": "Sam Saccone"
        },
        {
            "name": "Craig Morris"
        },
        {
            "name": "Gary Taylor"
        },
        {
            "name": "Krispin Schulz"
        },
        {
            "name": "Elwyn"
        },
        {
            "name": "Jan-Eric Duden"
        },
        {
            "name": "kostya.misura"
        },
        {
            "name": "Julian"
        },
        {
            "name": "nebehr"
        },
        {
            "name": "Jesse Harlin"
        },
        {
            "name": "Sonny Piers"
        },
        {
            "name": "Will Farrell"
        },
        {
            "name": "Kevin Kirsche"
        },
        {
            "name": "chrismilleruk"
        },
        {
            "name": "Mateusz Derks"
        },
        {
            "name": "Mark Amery"
        },
        {
            "name": "Artem Repko"
        },
        {
            "name": "zs-zs"
        },
        {
            "name": "Dale Gardner"
        },
        {
            "name": "Charles Rudolph"
        },
        {
            "name": "Karthik Viswanath"
        },
        {
            "name": "Marcel Hoyer"
        },
        {
            "name": "Artem Bronitsky"
        },
        {
            "name": "Karine Pires"
        },
        {
            "name": "Rick Lee-Morlang"
        },
        {
            "name": "Noah Davis"
        },
        {
            "name": "Miika Hänninen"
        },
        {
            "name": "Kevin Goslar"
        },
        {
            "name": "John Krull"
        },
        {
            "name": "Maxim Koretskiy"
        },
        {
            "name": "seantdg"
        },
        {
            "name": "Marc Burton"
        },
        {
            "name": "Jonathan Kim"
        },
        {
            "name": "Ádám Gólya"
        },
        {
            "name": "Scott Deakin"
        },
        {
            "name": "efokschaner"
        },
        {
            "name": "John McLaughlin"
        },
        {
            "name": "Josh Goldberg"
        },
        {
            "name": "Artur Pomadowski"
        },
        {
            "name": "Benjamín Eidelman"
        },
        {
            "name": "Jan Molak"
        },
        {
            "name": "dbillingham"
        },
        {
            "name": "Jonathan Gomez"
        },
        {
            "name": "Oliver Rogers"
        },
        {
            "name": "Hugues Malphettes"
        }
    ],
    "dependencies": {
        "camel-case": "^3.0.0",
        "cli-table": "^0.3.1",
        "co": "^4.6.0",
        "colors": "^1.1.2",
        "commander": "^2.9.0",
        "duration": "^0.2.0",
        "figures": "1.7.0",
        "gherkin": "^4.1.0",
        "glob": "^7.0.0",
        "is-generator": "^1.0.2",
        "lodash": "^4.0.0",
        "stack-chain": "^1.3.5",
        "stacktrace-js": "^1.3.0"
    },
    "description": "The official JavaScript implementation of Cucumber.",
    "devDependencies": {
        "ansi_up": "^1.3.0",
        "async": "^1.5.0",
        "browserify": "^13.0.0",
        "coffee-script": "^1.12.4",
        "connect": "^3.4.0",
        "exorcist": "^0.4.0",
        "fs-extra": "^0.26.0",
        "jasmine": "2.4.1",
        "jshint": "^2.9.1",
        "json-diff": "^0.3.1",
        "rimraf": "^2.4.3",
        "serve-static": "^1.10.0",
        "sinon": "^1.17.3",
        "tmp": "0.0.28"
    },
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "05c94590ab625c08792a6017a477b4cba99b8149",
        "tarball": "https://registry.npmjs.org/cucumber/-/cucumber-1.3.2.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "files": [
        "bin/",
        "lib/",
        "release/"
    ],
    "gitHead": "7eeb7987814c290b07e34b7db7992ae38f432187",
    "homepage": "http://github.com/cucumber/cucumber-js",
    "keywords": [
        "testing",
        "bdd",
        "cucumber",
        "gherkin",
        "tests"
    ],
    "license": "MIT",
    "main": "./lib/cucumber",
    "maintainers": [
        {
            "name": "charlierudolph"
        },
        {
            "name": "jbpros"
        }
    ],
    "name": "cucumber",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/cucumber/cucumber-js.git"
    },
    "scripts": {
        "build-release": "node ./scripts/release.js",
        "feature-test": "node ./bin/cucumber.js",
        "feature-test-es5": "node ./bin/cucumber.js -p es5",
        "lint": "jshint bin features lib scripts spec",
        "prebuild-release": "npm install",
        "test": "npm run lint && npm run unit-test && npm run feature-test",
        "test-es5": "npm run lint && npm run unit-test && npm run feature-test-es5",
        "unit-test": "jasmine"
    },
    "version": "1.3.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
