# api documentation for  [cucumber (v1.3.2)](http://github.com/cucumber/cucumber-js)  [![npm package](https://img.shields.io/npm/v/npmdoc-cucumber.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-cucumber) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-cucumber.svg)](https://travis-ci.org/npmdoc/node-npmdoc-cucumber)
#### The official JavaScript implementation of Cucumber.

[![NPM](https://nodei.co/npm/cucumber.png?downloads=true)](https://www.npmjs.com/package/cucumber)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cucumber/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-cucumber_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cucumber/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-cucumber/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-cucumber/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Julien Biezemans",
        "email": "jb@jbpros.com",
        "url": "http://jbpros.net"
    },
    "bin": {
        "cucumber.js": "./bin/cucumber.js",
        "cucumber-js": "./bin/cucumber.js",
        "cucumberjs": "./bin/cucumber.js"
    },
    "bugs": {
        "url": "http://github.com/cucumber/cucumber-js/issues",
        "email": "cukes@googlegroups.com"
    },
    "contributors": [
        {
            "name": "Julien Biezemans",
            "email": "jb@jbpros.com",
            "url": "http://jbpros.net"
        },
        {
            "name": "Fernando Acorreia",
            "email": "fernandoacorreia@gmail.com"
        },
        {
            "name": "Paul Jensen",
            "email": "paulbjensen@gmail.com"
        },
        {
            "name": "Kushal Pisavadia"
        },
        {
            "name": "Olivier Melcher",
            "email": "olivier.melcher@gmail.com"
        },
        {
            "name": "Tristan Dunn",
            "email": "tristanzdunn@gmail.com"
        },
        {
            "name": "Ted de Koning"
        },
        {
            "name": "Renier Morales",
            "email": "renier@morales-rodriguez.net"
        },
        {
            "name": "Aslak Hellesøy",
            "email": "aslak.hellesoy@gmail.com"
        },
        {
            "name": "Aaron Garvey"
        },
        {
            "name": "Omar Gonzalez",
            "email": "omar@almerblank.com"
        },
        {
            "name": "Chris Young",
            "email": "chris@chrisyoung.org"
        },
        {
            "name": "Israel Halle",
            "email": "isra017@gmail.com"
        },
        {
            "name": "Matteo Collina",
            "email": "matteo.collina@gmail.com"
        },
        {
            "name": "Niklas Närhinen",
            "email": "niklas@narhinen.net"
        },
        {
            "name": "Kim, Jang-hwan",
            "email": "janghwan@gmail.com"
        },
        {
            "name": "Michael Zedeler",
            "email": "michael@zedeler.dk"
        },
        {
            "name": "Tom V",
            "email": "tom@toc.com"
        },
        {
            "name": "David Godfrey",
            "email": "reactiveraven@reactiveraven.co.uk"
        },
        {
            "name": "Paul Shannon",
            "url": "http://devpaul.com"
        },
        {
            "name": "Simon Dean",
            "email": "simon@simondean.org",
            "url": "http://www.simondean.org"
        },
        {
            "name": "John Wright",
            "email": "johngeorge.wright@gmail.com"
        },
        {
            "name": "Johny Jose",
            "email": "johny@playlyfe.com"
        },
        {
            "name": "Marat Dyatko",
            "email": "vectart@gmail.com"
        },
        {
            "name": "Tim Perry",
            "email": "tim.perry@softwire.com"
        },
        {
            "name": "Fedotov Daniil",
            "email": "hairyhum@gmail.com"
        },
        {
            "name": "unknown",
            "email": "jharlin@NormanDev2.telogical.com"
        },
        {
            "name": "Ben Van Treese",
            "email": "vantreeseba@gmail.com"
        },
        {
            "name": "Gabe Hayes",
            "email": "gabriel.hayes@gmail.com"
        },
        {
            "name": "Brian Clozel",
            "email": "brian.clozel@gmail.com"
        },
        {
            "name": "Lukas Degener",
            "email": "l.degener@tarent.de"
        },
        {
            "name": "Simon Lampen",
            "email": "simonlampen@vinsight.net"
        },
        {
            "name": "Eddie Loeffen",
            "email": "eddieloeffen@gmail.com"
        },
        {
            "name": "Stanley Shyiko",
            "email": "stanley.shyiko@gmail.com"
        },
        {
            "name": "Artur Kania",
            "email": "kaniartur@gmail.com"
        },
        {
            "name": "Sam Saccone",
            "email": "sam@samx.it"
        },
        {
            "name": "Craig Morris",
            "email": "craig.michael.morris@gmail.com"
        },
        {
            "name": "Gary Taylor",
            "email": "gary.taylor@hismessages.com"
        },
        {
            "name": "Krispin Schulz",
            "email": "krispin.schulz@blackbridge.com"
        },
        {
            "name": "Elwyn",
            "email": "elwyn@L1.co.nz"
        },
        {
            "name": "Jan-Eric Duden",
            "email": "jeduden@gmail.com"
        },
        {
            "name": "kostya.misura",
            "email": "kostya.misura@gmail.com"
        },
        {
            "name": "Julian",
            "email": "microweb10@gmail.com"
        },
        {
            "name": "nebehr",
            "email": "thorgeir@tut.by"
        },
        {
            "name": "Jesse Harlin",
            "email": "harlinjesse@gmail.com"
        },
        {
            "name": "Sonny Piers",
            "email": "sonny@fastmail.net"
        },
        {
            "name": "Will Farrell",
            "email": "will@mojotech.com"
        },
        {
            "name": "Kevin Kirsche",
            "email": "Kev.Kirsche+GitHub@gmail.com"
        },
        {
            "name": "chrismilleruk",
            "email": "chrismilleruk@gmail.com"
        },
        {
            "name": "Mateusz Derks",
            "email": "mateusz.derks@schibsted.pl"
        },
        {
            "name": "Mark Amery",
            "email": "markamery@btinternet.com"
        },
        {
            "name": "Artem Repko",
            "email": "roby-boby@ukr.net"
        },
        {
            "name": "zs-zs",
            "email": "zsolt.zsigmondi@hotmail.com"
        },
        {
            "name": "Dale Gardner",
            "email": "dalegardner@live.com"
        },
        {
            "name": "Charles Rudolph",
            "email": "charles.rudolph@originate.com"
        },
        {
            "name": "Karthik Viswanath",
            "email": "karthik.viswanath-contractor@adp.com"
        },
        {
            "name": "Marcel Hoyer",
            "email": "mhoyer@pixelplastic.de"
        },
        {
            "name": "Artem Bronitsky",
            "email": "quex@yandex.ru"
        },
        {
            "name": "Karine Pires",
            "email": "karine.pires@alterway.fr"
        },
        {
            "name": "Rick Lee-Morlang",
            "email": "rick@lee-morlang.com"
        },
        {
            "name": "Noah Davis",
            "email": "noahd1@yahoo.com"
        },
        {
            "name": "Miika Hänninen",
            "email": "miika.hanninen@gmail.com"
        },
        {
            "name": "Kevin Goslar",
            "email": "kevin.goslar@gmail.com"
        },
        {
            "name": "John Krull",
            "email": "astrom.flux@gmail.com"
        },
        {
            "name": "Maxim Koretskiy",
            "email": "mr.green.tv@gmail.com"
        },
        {
            "name": "seantdg",
            "email": "sm.davis@gmx.com"
        },
        {
            "name": "Marc Burton",
            "email": "marc.burton@first-utility.com"
        },
        {
            "name": "Jonathan Kim",
            "email": "jkimbo@gmail.com"
        },
        {
            "name": "Ádám Gólya",
            "email": "adam.golya@lab.coop"
        },
        {
            "name": "Scott Deakin",
            "email": "scott.deakin@kantar.com"
        },
        {
            "name": "efokschaner",
            "email": "eddyaod@gmail.com"
        },
        {
            "name": "John McLaughlin",
            "email": "john.mjhm@gmail.com"
        },
        {
            "name": "Josh Goldberg",
            "email": "joshuakgoldberg@outlook.com"
        },
        {
            "name": "Artur Pomadowski",
            "email": "artur.pomadowski@gmail.com"
        },
        {
            "name": "Benjamín Eidelman",
            "email": "beneidel+gh@gmail.com"
        },
        {
            "name": "Jan Molak",
            "email": "jan.molak@smartcodeltd.co.uk"
        },
        {
            "name": "dbillingham",
            "email": "dbillinghamuk@yahoo.co.uk"
        },
        {
            "name": "Jonathan Gomez",
            "email": "jonathanbgomez@gmail.com"
        },
        {
            "name": "Oliver Rogers",
            "email": "oli.rogers@gmail.com"
        },
        {
            "name": "Hugues Malphettes",
            "email": "hmalphettes@gmail.com"
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
            "name": "charlierudolph",
            "email": "charles.w.rudolph@gmail.com"
        },
        {
            "name": "jbpros",
            "email": "jb@jbpros.com"
        }
    ],
    "name": "cucumber",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
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



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module cucumber](#apidoc.module.cucumber)
1.  [function <span class="apidocSignatureSpan"></span>cucumber (featureSource, supportCodeInitializer, options)](#apidoc.element.cucumber.cucumber)
1.  [function <span class="apidocSignatureSpan">cucumber.</span>Ast.Filter (rules)](#apidoc.element.cucumber.Ast.Filter)
1.  [function <span class="apidocSignatureSpan">cucumber.</span>Cli (argv)](#apidoc.element.cucumber.Cli)
1.  [function <span class="apidocSignatureSpan">cucumber.</span>Listener (options)](#apidoc.element.cucumber.Listener)
1.  [function <span class="apidocSignatureSpan">cucumber.</span>Parser (featureSources, astFilter)](#apidoc.element.cucumber.Parser)
1.  [function <span class="apidocSignatureSpan">cucumber.</span>Runtime (configuration)](#apidoc.element.cucumber.Runtime)
1.  [function <span class="apidocSignatureSpan">cucumber.</span>SupportCode.StepDefinitionSnippetBuilder (step, syntax)](#apidoc.element.cucumber.SupportCode.StepDefinitionSnippetBuilder)
1.  [function <span class="apidocSignatureSpan">cucumber.</span>TagGroupParser (tagGroupString)](#apidoc.element.cucumber.TagGroupParser)
1.  [function <span class="apidocSignatureSpan">cucumber.</span>Type.String ()](#apidoc.element.cucumber.Type.String)
1.  [function <span class="apidocSignatureSpan">cucumber.</span>VolatileConfiguration (features, supportCodeInitializer, options)](#apidoc.element.cucumber.VolatileConfiguration)
1.  object <span class="apidocSignatureSpan">cucumber.</span>Api
1.  object <span class="apidocSignatureSpan">cucumber.</span>Ast
1.  object <span class="apidocSignatureSpan">cucumber.</span>Cli.FeaturePathExpander
1.  object <span class="apidocSignatureSpan">cucumber.</span>Cli.PathExpander
1.  object <span class="apidocSignatureSpan">cucumber.</span>Cli.ProfilesLoader
1.  object <span class="apidocSignatureSpan">cucumber.</span>Cli.SupportCodePathExpander
1.  object <span class="apidocSignatureSpan">cucumber.</span>Debug
1.  object <span class="apidocSignatureSpan">cucumber.</span>Events
1.  object <span class="apidocSignatureSpan">cucumber.</span>Runtime.StackTraceFilter
1.  object <span class="apidocSignatureSpan">cucumber.</span>Status
1.  object <span class="apidocSignatureSpan">cucumber.</span>SupportCode
1.  object <span class="apidocSignatureSpan">cucumber.</span>Type
1.  object <span class="apidocSignatureSpan">cucumber.</span>Type.String.prototype
1.  object <span class="apidocSignatureSpan">cucumber.</span>Util
1.  object <span class="apidocSignatureSpan">cucumber.</span>Util.Exception
1.  object <span class="apidocSignatureSpan">cucumber.</span>Util.RealTime
1.  object <span class="apidocSignatureSpan">cucumber.</span>Util.RegExp
1.  object <span class="apidocSignatureSpan">cucumber.</span>Util.String
1.  string <span class="apidocSignatureSpan">cucumber.</span>VERSION

#### [module cucumber.Api](#apidoc.module.cucumber.Api)
1.  [function <span class="apidocSignatureSpan">cucumber.Api.</span>Scenario (astScenario, scenarioResult)](#apidoc.element.cucumber.Api.Scenario)

#### [module cucumber.Ast](#apidoc.module.cucumber.Ast)
1.  [function <span class="apidocSignatureSpan">cucumber.Ast.</span>DataTable (data)](#apidoc.element.cucumber.Ast.DataTable)
1.  [function <span class="apidocSignatureSpan">cucumber.Ast.</span>DocString (data)](#apidoc.element.cucumber.Ast.DocString)
1.  [function <span class="apidocSignatureSpan">cucumber.Ast.</span>Feature (data, uri, scenarios)](#apidoc.element.cucumber.Ast.Feature)
1.  [function <span class="apidocSignatureSpan">cucumber.Ast.</span>Filter (rules)](#apidoc.element.cucumber.Ast.Filter)
1.  [function <span class="apidocSignatureSpan">cucumber.Ast.</span>HookStep (keyword)](#apidoc.element.cucumber.Ast.HookStep)
1.  [function <span class="apidocSignatureSpan">cucumber.Ast.</span>Scenario (data, uri)](#apidoc.element.cucumber.Ast.Scenario)
1.  [function <span class="apidocSignatureSpan">cucumber.Ast.</span>Step (data)](#apidoc.element.cucumber.Ast.Step)
1.  [function <span class="apidocSignatureSpan">cucumber.Ast.</span>Tag (data)](#apidoc.element.cucumber.Ast.Tag)

#### [module cucumber.Ast.Filter](#apidoc.module.cucumber.Ast.Filter)
1.  [function <span class="apidocSignatureSpan">cucumber.Ast.</span>Filter (rules)](#apidoc.element.cucumber.Ast.Filter.Filter)
1.  [function <span class="apidocSignatureSpan">cucumber.Ast.Filter.</span>AnyOfNamesRule (names)](#apidoc.element.cucumber.Ast.Filter.AnyOfNamesRule)
1.  [function <span class="apidocSignatureSpan">cucumber.Ast.Filter.</span>AnyOfTagsRule (tags)](#apidoc.element.cucumber.Ast.Filter.AnyOfTagsRule)
1.  [function <span class="apidocSignatureSpan">cucumber.Ast.Filter.</span>ElementMatchingTagSpec (tagName)](#apidoc.element.cucumber.Ast.Filter.ElementMatchingTagSpec)
1.  [function <span class="apidocSignatureSpan">cucumber.Ast.Filter.</span>ScenarioAtLineRule (suppliedPaths)](#apidoc.element.cucumber.Ast.Filter.ScenarioAtLineRule)

#### [module cucumber.Cli](#apidoc.module.cucumber.Cli)
1.  [function <span class="apidocSignatureSpan">cucumber.</span>Cli (argv)](#apidoc.element.cucumber.Cli.Cli)
1.  [function <span class="apidocSignatureSpan">cucumber.Cli.</span>Configuration (options, args)](#apidoc.element.cucumber.Cli.Configuration)
1.  [function <span class="apidocSignatureSpan">cucumber.Cli.</span>FeatureSourceLoader (featureFilePaths)](#apidoc.element.cucumber.Cli.FeatureSourceLoader)
1.  [function <span class="apidocSignatureSpan">cucumber.Cli.</span>SupportCodeLoader (supportCodeFilePaths, compilerModules)](#apidoc.element.cucumber.Cli.SupportCodeLoader)
1.  object <span class="apidocSignatureSpan">cucumber.Cli.</span>FeaturePathExpander
1.  object <span class="apidocSignatureSpan">cucumber.Cli.</span>PathExpander
1.  object <span class="apidocSignatureSpan">cucumber.Cli.</span>ProfilesLoader
1.  object <span class="apidocSignatureSpan">cucumber.Cli.</span>SupportCodePathExpander

#### [module cucumber.Cli.FeaturePathExpander](#apidoc.module.cucumber.Cli.FeaturePathExpander)
1.  [function <span class="apidocSignatureSpan">cucumber.Cli.FeaturePathExpander.</span>expandPaths (paths)](#apidoc.element.cucumber.Cli.FeaturePathExpander.expandPaths)

#### [module cucumber.Cli.PathExpander](#apidoc.module.cucumber.Cli.PathExpander)
1.  [function <span class="apidocSignatureSpan">cucumber.Cli.PathExpander.</span>expandDirectoryWithExtensions (realPath, extensions)](#apidoc.element.cucumber.Cli.PathExpander.expandDirectoryWithExtensions)
1.  [function <span class="apidocSignatureSpan">cucumber.Cli.PathExpander.</span>expandPathWithExtensions (path, extensions)](#apidoc.element.cucumber.Cli.PathExpander.expandPathWithExtensions)
1.  [function <span class="apidocSignatureSpan">cucumber.Cli.PathExpander.</span>expandPathsWithExtensions (paths, extensions)](#apidoc.element.cucumber.Cli.PathExpander.expandPathsWithExtensions)

#### [module cucumber.Cli.ProfilesLoader](#apidoc.module.cucumber.Cli.ProfilesLoader)
1.  [function <span class="apidocSignatureSpan">cucumber.Cli.ProfilesLoader.</span>getArgs (profiles)](#apidoc.element.cucumber.Cli.ProfilesLoader.getArgs)

#### [module cucumber.Cli.SupportCodePathExpander](#apidoc.module.cucumber.Cli.SupportCodePathExpander)
1.  [function <span class="apidocSignatureSpan">cucumber.Cli.SupportCodePathExpander.</span>expandPaths (paths, extensions)](#apidoc.element.cucumber.Cli.SupportCodePathExpander.expandPaths)

#### [module cucumber.Debug](#apidoc.module.cucumber.Debug)
1.  [function <span class="apidocSignatureSpan">cucumber.Debug.</span>SimpleAstListener (options)](#apidoc.element.cucumber.Debug.SimpleAstListener)
1.  [function <span class="apidocSignatureSpan">cucumber.Debug.</span>TODO (description)](#apidoc.element.cucumber.Debug.TODO)
1.  [function <span class="apidocSignatureSpan">cucumber.Debug.</span>isMessageLeveltoBeDisplayed (level)](#apidoc.element.cucumber.Debug.isMessageLeveltoBeDisplayed)
1.  [function <span class="apidocSignatureSpan">cucumber.Debug.</span>notice (string, caption, level)](#apidoc.element.cucumber.Debug.notice)
1.  [function <span class="apidocSignatureSpan">cucumber.Debug.</span>noticeString (string, caption)](#apidoc.element.cucumber.Debug.noticeString)
1.  [function <span class="apidocSignatureSpan">cucumber.Debug.</span>prefix ()](#apidoc.element.cucumber.Debug.prefix)
1.  [function <span class="apidocSignatureSpan">cucumber.Debug.</span>warn (string, caption, level)](#apidoc.element.cucumber.Debug.warn)
1.  [function <span class="apidocSignatureSpan">cucumber.Debug.</span>warningString (string, caption)](#apidoc.element.cucumber.Debug.warningString)

#### [module cucumber.Events](#apidoc.module.cucumber.Events)
1.  [function <span class="apidocSignatureSpan">cucumber.Events.</span>getAfterEvent (name)](#apidoc.element.cucumber.Events.getAfterEvent)
1.  [function <span class="apidocSignatureSpan">cucumber.Events.</span>getBeforeEvent (name)](#apidoc.element.cucumber.Events.getBeforeEvent)
1.  object <span class="apidocSignatureSpan">cucumber.Events.</span>ALL
1.  string <span class="apidocSignatureSpan">cucumber.Events.</span>FEATURES_EVENT_NAME
1.  string <span class="apidocSignatureSpan">cucumber.Events.</span>FEATURES_RESULT_EVENT_NAME
1.  string <span class="apidocSignatureSpan">cucumber.Events.</span>FEATURE_EVENT_NAME
1.  string <span class="apidocSignatureSpan">cucumber.Events.</span>SCENARIO_EVENT_NAME
1.  string <span class="apidocSignatureSpan">cucumber.Events.</span>SCENARIO_RESULT_EVENT_NAME
1.  string <span class="apidocSignatureSpan">cucumber.Events.</span>STEP_EVENT_NAME
1.  string <span class="apidocSignatureSpan">cucumber.Events.</span>STEP_RESULT_EVENT_NAME

#### [module cucumber.Listener](#apidoc.module.cucumber.Listener)
1.  [function <span class="apidocSignatureSpan">cucumber.</span>Listener (options)](#apidoc.element.cucumber.Listener.Listener)
1.  [function <span class="apidocSignatureSpan">cucumber.Listener.</span>Formatter (options)](#apidoc.element.cucumber.Listener.Formatter)
1.  [function <span class="apidocSignatureSpan">cucumber.Listener.</span>JsonFormatter (options)](#apidoc.element.cucumber.Listener.JsonFormatter)
1.  [function <span class="apidocSignatureSpan">cucumber.Listener.</span>PrettyFormatter (options)](#apidoc.element.cucumber.Listener.PrettyFormatter)
1.  [function <span class="apidocSignatureSpan">cucumber.Listener.</span>ProgressFormatter (options)](#apidoc.element.cucumber.Listener.ProgressFormatter)
1.  [function <span class="apidocSignatureSpan">cucumber.Listener.</span>RerunFormatter (options)](#apidoc.element.cucumber.Listener.RerunFormatter)
1.  [function <span class="apidocSignatureSpan">cucumber.Listener.</span>SnippetsFormatter (options)](#apidoc.element.cucumber.Listener.SnippetsFormatter)
1.  [function <span class="apidocSignatureSpan">cucumber.Listener.</span>SummaryFormatter (options)](#apidoc.element.cucumber.Listener.SummaryFormatter)
1.  string <span class="apidocSignatureSpan">cucumber.Listener.</span>EVENT_HANDLER_NAME_PREFIX
1.  string <span class="apidocSignatureSpan">cucumber.Listener.</span>EVENT_HANDLER_NAME_SUFFIX

#### [module cucumber.Runtime](#apidoc.module.cucumber.Runtime)
1.  [function <span class="apidocSignatureSpan">cucumber.</span>Runtime (configuration)](#apidoc.element.cucumber.Runtime.Runtime)
1.  [function <span class="apidocSignatureSpan">cucumber.Runtime.</span>Attachment (payload)](#apidoc.element.cucumber.Runtime.Attachment)
1.  [function <span class="apidocSignatureSpan">cucumber.Runtime.</span>Event (name, payload)](#apidoc.element.cucumber.Runtime.Event)
1.  [function <span class="apidocSignatureSpan">cucumber.Runtime.</span>EventBroadcaster (listeners, listenerDefaultTimeout)](#apidoc.element.cucumber.Runtime.EventBroadcaster)
1.  [function <span class="apidocSignatureSpan">cucumber.Runtime.</span>FeaturesResult (strict)](#apidoc.element.cucumber.Runtime.FeaturesResult)
1.  [function <span class="apidocSignatureSpan">cucumber.Runtime.</span>FeaturesRunner (features, supportCodeLibrary, listeners, options)](#apidoc.element.cucumber.Runtime.FeaturesRunner)
1.  [function <span class="apidocSignatureSpan">cucumber.Runtime.</span>ScenarioResult (scenario)](#apidoc.element.cucumber.Runtime.ScenarioResult)
1.  [function <span class="apidocSignatureSpan">cucumber.Runtime.</span>ScenarioRunner (scenario, supportCodeLibrary, eventBroadcaster, options)](#apidoc.element.cucumber.Runtime.ScenarioRunner)
1.  [function <span class="apidocSignatureSpan">cucumber.Runtime.</span>StepResult (payload)](#apidoc.element.cucumber.Runtime.StepResult)
1.  object <span class="apidocSignatureSpan">cucumber.Runtime.</span>StackTraceFilter
1.  string <span class="apidocSignatureSpan">cucumber.Runtime.</span>START_MISSING_CALLBACK_ERROR

#### [module cucumber.Runtime.StackTraceFilter](#apidoc.module.cucumber.Runtime.StackTraceFilter)
1.  [function <span class="apidocSignatureSpan">cucumber.Runtime.StackTraceFilter.</span>filter ()](#apidoc.element.cucumber.Runtime.StackTraceFilter.filter)
1.  [function <span class="apidocSignatureSpan">cucumber.Runtime.StackTraceFilter.</span>unfilter ()](#apidoc.element.cucumber.Runtime.StackTraceFilter.unfilter)

#### [module cucumber.Status](#apidoc.module.cucumber.Status)
1.  [function <span class="apidocSignatureSpan">cucumber.Status.</span>getMapping (initialValue)](#apidoc.element.cucumber.Status.getMapping)
1.  string <span class="apidocSignatureSpan">cucumber.Status.</span>AMBIGUOUS
1.  string <span class="apidocSignatureSpan">cucumber.Status.</span>FAILED
1.  string <span class="apidocSignatureSpan">cucumber.Status.</span>PASSED
1.  string <span class="apidocSignatureSpan">cucumber.Status.</span>PENDING
1.  string <span class="apidocSignatureSpan">cucumber.Status.</span>SKIPPED
1.  string <span class="apidocSignatureSpan">cucumber.Status.</span>UNDEFINED

#### [module cucumber.SupportCode](#apidoc.module.cucumber.SupportCode)
1.  [function <span class="apidocSignatureSpan">cucumber.SupportCode.</span>Hook (code, options, uri, line)](#apidoc.element.cucumber.SupportCode.Hook)
1.  [function <span class="apidocSignatureSpan">cucumber.SupportCode.</span>Library (supportCodeDefinition)](#apidoc.element.cucumber.SupportCode.Library)
1.  [function <span class="apidocSignatureSpan">cucumber.SupportCode.</span>StepDefinition (pattern, options, code, uri, line)](#apidoc.element.cucumber.SupportCode.StepDefinition)
1.  [function <span class="apidocSignatureSpan">cucumber.SupportCode.</span>StepDefinitionSnippetBuilder (step, syntax)](#apidoc.element.cucumber.SupportCode.StepDefinitionSnippetBuilder)

#### [module cucumber.SupportCode.StepDefinitionSnippetBuilder](#apidoc.module.cucumber.SupportCode.StepDefinitionSnippetBuilder)
1.  [function <span class="apidocSignatureSpan">cucumber.SupportCode.</span>StepDefinitionSnippetBuilder (step, syntax)](#apidoc.element.cucumber.SupportCode.StepDefinitionSnippetBuilder.StepDefinitionSnippetBuilder)
1.  [function <span class="apidocSignatureSpan">cucumber.SupportCode.StepDefinitionSnippetBuilder.</span>JavaScriptSyntax (interface)](#apidoc.element.cucumber.SupportCode.StepDefinitionSnippetBuilder.JavaScriptSyntax)

#### [module cucumber.TagGroupParser](#apidoc.module.cucumber.TagGroupParser)
1.  [function <span class="apidocSignatureSpan">cucumber.</span>TagGroupParser (tagGroupString)](#apidoc.element.cucumber.TagGroupParser.TagGroupParser)
1.  [function <span class="apidocSignatureSpan">cucumber.TagGroupParser.</span>getTagGroupsFromStrings (tagGroupStrings)](#apidoc.element.cucumber.TagGroupParser.getTagGroupsFromStrings)
1.  string <span class="apidocSignatureSpan">cucumber.TagGroupParser.</span>TAG_SEPARATOR

#### [module cucumber.Type](#apidoc.module.cucumber.Type)
1.  [function <span class="apidocSignatureSpan">cucumber.Type.</span>HashDataTable (rawArray)](#apidoc.element.cucumber.Type.HashDataTable)
1.  [function <span class="apidocSignatureSpan">cucumber.Type.</span>String ()](#apidoc.element.cucumber.Type.String)

#### [module cucumber.Type.String](#apidoc.module.cucumber.Type.String)
1.  [function <span class="apidocSignatureSpan">cucumber.Type.</span>String ()](#apidoc.element.cucumber.Type.String.String)

#### [module cucumber.Type.String.prototype](#apidoc.module.cucumber.Type.String.prototype)
1.  [function <span class="apidocSignatureSpan">cucumber.Type.String.prototype.</span>entityify ()](#apidoc.element.cucumber.Type.String.prototype.entityify)
1.  [function <span class="apidocSignatureSpan">cucumber.Type.String.prototype.</span>isAlpha ( )](#apidoc.element.cucumber.Type.String.prototype.isAlpha)
1.  [function <span class="apidocSignatureSpan">cucumber.Type.String.prototype.</span>isDigit ()](#apidoc.element.cucumber.Type.String.prototype.isDigit)
1.  [function <span class="apidocSignatureSpan">cucumber.Type.String.prototype.</span>supplant (e)](#apidoc.element.cucumber.Type.String.prototype.supplant)

#### [module cucumber.Util](#apidoc.module.cucumber.Util)
1.  [function <span class="apidocSignatureSpan">cucumber.Util.</span>Arguments (argumentsObject)](#apidoc.element.cucumber.Util.Arguments)
1.  [function <span class="apidocSignatureSpan">cucumber.Util.</span>Colors (useColors)](#apidoc.element.cucumber.Util.Colors)
1.  [function <span class="apidocSignatureSpan">cucumber.Util.</span>asyncForEach (items, userFunction, callback)](#apidoc.element.cucumber.Util.asyncForEach)
1.  [function <span class="apidocSignatureSpan">cucumber.Util.</span>run (fn, thisArg, argsArray, timeoutInMilliseconds, callback)](#apidoc.element.cucumber.Util.run)
1.  object <span class="apidocSignatureSpan">cucumber.Util.</span>Exception
1.  object <span class="apidocSignatureSpan">cucumber.Util.</span>RealTime
1.  object <span class="apidocSignatureSpan">cucumber.Util.</span>RegExp
1.  object <span class="apidocSignatureSpan">cucumber.Util.</span>String

#### [module cucumber.Util.Exception](#apidoc.module.cucumber.Util.Exception)
1.  [function <span class="apidocSignatureSpan">cucumber.Util.Exception.</span>registerUncaughtExceptionHandler (exceptionHandler)](#apidoc.element.cucumber.Util.Exception.registerUncaughtExceptionHandler)
1.  [function <span class="apidocSignatureSpan">cucumber.Util.Exception.</span>unregisterUncaughtExceptionHandler (exceptionHandler)](#apidoc.element.cucumber.Util.Exception.unregisterUncaughtExceptionHandler)

#### [module cucumber.Util.RealTime](#apidoc.module.cucumber.Util.RealTime)
1.  [function <span class="apidocSignatureSpan">cucumber.Util.RealTime.</span>Date ()](#apidoc.element.cucumber.Util.RealTime.Date)
1.  [function <span class="apidocSignatureSpan">cucumber.Util.RealTime.</span>clearImmediate ()](#apidoc.element.cucumber.Util.RealTime.clearImmediate)
1.  [function <span class="apidocSignatureSpan">cucumber.Util.RealTime.</span>clearInterval ()](#apidoc.element.cucumber.Util.RealTime.clearInterval)
1.  [function <span class="apidocSignatureSpan">cucumber.Util.RealTime.</span>clearTimeout ()](#apidoc.element.cucumber.Util.RealTime.clearTimeout)
1.  [function <span class="apidocSignatureSpan">cucumber.Util.RealTime.</span>setImmediate ()](#apidoc.element.cucumber.Util.RealTime.setImmediate)
1.  [function <span class="apidocSignatureSpan">cucumber.Util.RealTime.</span>setInterval ()](#apidoc.element.cucumber.Util.RealTime.setInterval)
1.  [function <span class="apidocSignatureSpan">cucumber.Util.RealTime.</span>setTimeout ()](#apidoc.element.cucumber.Util.RealTime.setTimeout)

#### [module cucumber.Util.RegExp](#apidoc.module.cucumber.Util.RegExp)
1.  [function <span class="apidocSignatureSpan">cucumber.Util.RegExp.</span>escapeString (string)](#apidoc.element.cucumber.Util.RegExp.escapeString)
1.  object <span class="apidocSignatureSpan">cucumber.Util.RegExp.</span>ESCAPE_PATTERN
1.  string <span class="apidocSignatureSpan">cucumber.Util.RegExp.</span>ESCAPE_REPLACEMENT

#### [module cucumber.Util.String](#apidoc.module.cucumber.Util.String)
1.  [function <span class="apidocSignatureSpan">cucumber.Util.String.</span>count (hayStack, needle)](#apidoc.element.cucumber.Util.String.count)

#### [module cucumber.cucumber](#apidoc.module.cucumber.cucumber)
1.  [function <span class="apidocSignatureSpan">cucumber.</span>cucumber (featureSource, supportCodeInitializer, options)](#apidoc.element.cucumber.cucumber.cucumber)
1.  [function <span class="apidocSignatureSpan">cucumber.cucumber.</span>Cli (argv)](#apidoc.element.cucumber.cucumber.Cli)
1.  [function <span class="apidocSignatureSpan">cucumber.cucumber.</span>Listener (options)](#apidoc.element.cucumber.cucumber.Listener)
1.  [function <span class="apidocSignatureSpan">cucumber.cucumber.</span>Parser (featureSources, astFilter)](#apidoc.element.cucumber.cucumber.Parser)
1.  [function <span class="apidocSignatureSpan">cucumber.cucumber.</span>Runtime (configuration)](#apidoc.element.cucumber.cucumber.Runtime)
1.  [function <span class="apidocSignatureSpan">cucumber.cucumber.</span>TagGroupParser (tagGroupString)](#apidoc.element.cucumber.cucumber.TagGroupParser)
1.  [function <span class="apidocSignatureSpan">cucumber.cucumber.</span>VolatileConfiguration (features, supportCodeInitializer, options)](#apidoc.element.cucumber.cucumber.VolatileConfiguration)
1.  object <span class="apidocSignatureSpan">cucumber.cucumber.</span>Api
1.  object <span class="apidocSignatureSpan">cucumber.cucumber.</span>Ast
1.  object <span class="apidocSignatureSpan">cucumber.cucumber.</span>Debug
1.  object <span class="apidocSignatureSpan">cucumber.cucumber.</span>Events
1.  object <span class="apidocSignatureSpan">cucumber.cucumber.</span>Status
1.  object <span class="apidocSignatureSpan">cucumber.cucumber.</span>SupportCode
1.  object <span class="apidocSignatureSpan">cucumber.cucumber.</span>Type
1.  object <span class="apidocSignatureSpan">cucumber.cucumber.</span>Util
1.  string <span class="apidocSignatureSpan">cucumber.cucumber.</span>VERSION



# <a name="apidoc.module.cucumber"></a>[module cucumber](#apidoc.module.cucumber)

#### <a name="apidoc.element.cucumber.cucumber"></a>[function <span class="apidocSignatureSpan"></span>cucumber (featureSource, supportCodeInitializer, options)](#apidoc.element.cucumber.cucumber)
- description and source-code
```javascript
function Cucumber(featureSource, supportCodeInitializer, options) {
  var configuration = Cucumber.VolatileConfiguration(featureSource, supportCodeInitializer, options);
  var runtime       = Cucumber.Runtime(configuration);
  return runtime;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cucumber.Ast.Filter"></a>[function <span class="apidocSignatureSpan">cucumber.</span>Ast.Filter (rules)](#apidoc.element.cucumber.Ast.Filter)
- description and source-code
```javascript
function Filter(rules) {
  var self = {
    isElementEnrolled: function isElementEnrolled(element) {
      var enrolled = _.every(rules, function (rule) {
        return rule.isSatisfiedByElement(element);
      });
      return enrolled;
    }
  };
  return self;
}
```
- example usage
```shell
...
  var tagGroups = Cucumber.TagGroupParser.getTagGroupsFromStrings(options.tags);
  var tagRules = tagGroups.map(function (tags) {
     return Cucumber.Ast.Filter.AnyOfTagsRule(tags);
  });
  var lineRule = Cucumber.Ast.Filter.ScenarioAtLineRule(unexpandedFeaturePaths);
  var nameRule = Cucumber.Ast.Filter.AnyOfNamesRule(options.name);
  var rules = tagRules.concat([lineRule, nameRule]);
  return Cucumber.Ast.Filter(rules);
},

getSupportCodeLibrary: function getSupportCodeLibrary() {
  var supportCodePaths = getSupportCodePaths();
  var compilerModules = getCompilerModules();
  var supportCodeLoader = Cucumber.Cli.SupportCodeLoader(supportCodePaths, compilerModules);
  return supportCodeLoader.getSupportCodeLibrary();
...
```

#### <a name="apidoc.element.cucumber.Cli"></a>[function <span class="apidocSignatureSpan">cucumber.</span>Cli (argv)](#apidoc.element.cucumber.Cli)
- description and source-code
```javascript
function Cli(argv) {
  var Cucumber = require('../cucumber');
  var Command = require('commander').Command;
  var path = require('path');
  var _ = require('lodash');

  function mergeWorldParametersJson(str, memo) {
    var val;
    try {
      val = JSON.parse(str);
    } catch (error) {
      throw new Error('--world-parameters passed invalid JSON: ' + error.message + ': ' + str);
    }
    if (!_.isPlainObject(val)) {
      throw new Error('--world-parameters must be passed a JSON string of an object: ' + str);
    }
    _.merge(memo, val);
    return memo;
  }

  function collect(val, memo) {
    memo.push(val);
    return memo;
  }

  function getProgram () {
    var program = new Command(path.basename(argv[1]));

    program
      .usage('[options] [<DIR | FILE[:LINE]>...]')
      .version(Cucumber.VERSION, '-v, --version')
      .option('-b, --backtrace', 'show full backtrace for errors')
      .option('--compiler <EXTENSION:MODULE>', 'require files with the given EXTENSION after requiring MODULE (repeatable)', collect
, [])
      .option('-d, --dry-run', 'invoke formatters without executing steps')
      .option('--fail-fast', 'abort the run on first failure')
      .option('-f, --format <TYPE[:PATH]>', 'specify the output format, optionally supply PATH to redirect formatter output (repeatable
)', collect, ['pretty'])
      .option('--name <REGEXP>', 'only execute the scenarios with name matching the expression (repeatable)', collect, [])
      .option('--no-colors', 'disable colors in formatter output')
      .option('-p, --profile <NAME>', 'specify the profile to use (repeatable)', collect, [])
      .option('-r, --require <FILE | DIR>', 'require files before executing features (repeatable)', collect, [])
      .option('--snippet-interface [callback | generator | promise | synchronous]', 'specify a snippet interface', 'callback')
      .option('--snippet-syntax [<FILE>]', 'specify a custom snippet syntax')
      .option('-S, --strict', 'fail if there are any undefined or pending steps')
      .option('-t, --tags <EXPRESSION>', 'only execute the features or scenarios with tags matching the expression (repeatable)',
collect, [])
      .option('--world-parameters <JSON>', 'provide parameters that will be passed to the world constructor (repeatable)', mergeWorldParametersJson
, {});

    program.on('--help', function(){
      console.log('  For more details please visit https://github.com/cucumber/cucumber-js#cli\n');
    });

    return program;
  }

  function getConfiguration() {
    var program = getProgram();
    program.parse(argv);
    var profileArgs = Cucumber.Cli.ProfilesLoader.getArgs(program.profile);
    if (profileArgs.length > 0) {
      var fullArgs = argv.slice(0, 2).concat(profileArgs).concat(argv.slice(2));
      program = getProgram();
      program.parse(fullArgs);
    }
    var configuration = Cucumber.Cli.Configuration(program.opts(), program.args);
    return configuration;
  }

  var self = {
    run: function run(callback) {
      var configuration = getConfiguration();
      var runtime    = Cucumber.Runtime(configuration);
      var formatters = configuration.getFormatters();
      formatters.forEach(function (formatter) {
        runtime.attachListener(formatter);
      });
      runtime.start(callback);
    }
  };
  return self;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cucumber.Listener"></a>[function <span class="apidocSignatureSpan">cucumber.</span>Listener (options)](#apidoc.element.cucumber.Listener)
- description and source-code
```javascript
function Listener(options) {
  var Cucumber     = require('../cucumber');

  if (!options) {
    options = {};
  }

  var self = {
    hear: function hear(event, defaultTimeout, callback) {
      if (self.hasHandlerForEvent(event)) {
        var handler = self.getHandlerForEvent(event);
        var timeout = self.getTimeout() || defaultTimeout;
        Cucumber.Util.run(handler, null, [event.getPayload()], timeout, function(error) {
          error = self.prependLocationToError(error);
          callback(error);
        });
      } else {
        callback();
      }
    },

    hasHandlerForEvent: function hasHandlerForEvent(event) {
      var handlerName = self.buildHandlerNameForEvent(event);
      return self[handlerName] !== undefined;
    },

    buildHandlerNameForEvent: function buildHandlerNameForEvent(event) {
      return self.buildHandlerName(event.getName());
    },

    getHandlerForEvent: function getHandlerForEvent(event) {
      var eventHandlerName = self.buildHandlerNameForEvent(event);
      return self[eventHandlerName];
    },

    buildHandlerName: function buildHandler(shortName) {
      return Listener.EVENT_HANDLER_NAME_PREFIX + shortName + Listener.EVENT_HANDLER_NAME_SUFFIX;
    },

    setHandlerForEvent: function setHandlerForEvent(shortname, handler) {
      var eventName = self.buildHandlerName(shortname);
      self[eventName] = handler;
    },

    getTimeout: function() {
      return options.timeout;
    },

    getUri: function() {
      return options.uri;
    },

    getLine: function() {
      return options.line;
    },

    prependLocationToError: function(error) {
      if (error && self.getUri()) {
        var ref = path.relative(process.cwd(), self.getUri()) + ':' + self.getLine() + ' ';
        if (error instanceof Error) {
          error.message = ref + error.message;
        } else {
          error = ref + error;
        }
      }
      return error;
    },
  };
  return self;
}
```
- example usage
```shell
...
var Cucumber = require('../../cucumber');

if (!options)
  options = {};

var logs = '';

var self = Cucumber.Listener(options);

self.log = function log(string) {
  logs += string;
  if (options.stream)
    options.stream.write(string);
  if (typeof(options.logToFunction) === 'function')
    options.logToFunction(string);
...
```

#### <a name="apidoc.element.cucumber.Parser"></a>[function <span class="apidocSignatureSpan">cucumber.</span>Parser (featureSources, astFilter)](#apidoc.element.cucumber.Parser)
- description and source-code
```javascript
function Parser(featureSources, astFilter) {
  var Gherkin      = require('gherkin');
  var Cucumber     = require('../cucumber');

  var parser = new Gherkin.Parser();
  var compiler = new Gherkin.Compiler();

  var self = {
    parse: function parse() {
      var features = [];

      featureSources.forEach(function (featureSource) {
        var uri    = featureSource[Parser.FEATURE_NAME_SOURCE_PAIR_URI_INDEX];
        var source = featureSource[Parser.FEATURE_NAME_SOURCE_PAIR_SOURCE_INDEX];

        var gherkinDocument;
        try {
          gherkinDocument = parser.parse(source);
        } catch(e) {
          e.message += '\npath: ' + uri;
          throw e;
        }

        var pickles = compiler.compile(gherkinDocument);
        var scenarios = [];
        pickles.forEach(function (pickleData) {
          var scenario = Cucumber.Ast.Scenario(pickleData, uri);
          if (astFilter.isElementEnrolled(scenario)) {
            scenarios.push(scenario);
          }
        });

        if (scenarios.length > 0) {
          features.push(Cucumber.Ast.Feature(gherkinDocument.feature, uri, scenarios));
        }
      });

      return features;
    }
  };
  return self;
}
```
- example usage
```shell
...
}).call(this,require('_process'))

},{"../../cucumber":"cucumber","_process":173,"cli-table":75,"duration":102,"lodash":165,"path":170}],35:[function(require,module
,exports){
function Parser(featureSources, astFilter) {
  var Gherkin      = require('gherkin');
  var Cucumber     = require('../cucumber');

  var parser = new Gherkin.Parser();
  var compiler = new Gherkin.Compiler();

  var self = {
    parse: function parse() {
var features = [];

featureSources.forEach(function (featureSource) {
...
```

#### <a name="apidoc.element.cucumber.Runtime"></a>[function <span class="apidocSignatureSpan">cucumber.</span>Runtime (configuration)](#apidoc.element.cucumber.Runtime)
- description and source-code
```javascript
function Runtime(configuration) {
  var Cucumber = require('../cucumber');

  var listeners = [];

  var self = {
    start: function start(callback) {
      if (typeof(callback) !== 'function')
        throw new Error(Runtime.START_MISSING_CALLBACK_ERROR);

      var features = self.getFeatures();
      var supportCodeLibrary = self.getSupportCodeLibrary();
      var options = {
        dryRun: configuration.isDryRunRequested && configuration.isDryRunRequested(),
        failFast: configuration.isFailFastRequested && configuration.isFailFastRequested(),
        strict: configuration.isStrictRequested && configuration.isStrictRequested(),
        worldParameters: configuration.getWorldParameters()
      };

      var featuresRunner = Runtime.FeaturesRunner(features, supportCodeLibrary, listeners, options);

      if (configuration.shouldFilterStackTraces())
        Runtime.StackTraceFilter.filter();

      featuresRunner.run(function (result) {
        Runtime.StackTraceFilter.unfilter();
        callback(result);
      });
    },

    attachListener: function attachListener(listener) {
      listeners.push(listener);
    },

    getFeatures: function getFeatures() {
      var featureSources = configuration.getFeatureSources();
      var astFilter      = configuration.getAstFilter();
      var parser         = Cucumber.Parser(featureSources, astFilter);
      var features       = parser.parse();
      return features;
    },

    getSupportCodeLibrary: function getSupportCodeLibrary() {
      var supportCodeLibrary = configuration.getSupportCodeLibrary();
      return supportCodeLibrary;
    }
  };
  return self;
}
```
- example usage
```shell
...
  var configuration = Cucumber.Cli.Configuration(program.opts(), program.args);
  return configuration;
}

var self = {
  run: function run(callback) {
    var configuration = getConfiguration();
    var runtime    = Cucumber.Runtime(configuration);
    var formatters = configuration.getFormatters();
    formatters.forEach(function (formatter) {
      runtime.attachListener(formatter);
    });
    runtime.start(callback);
  }
};
...
```

#### <a name="apidoc.element.cucumber.SupportCode.StepDefinitionSnippetBuilder"></a>[function <span class="apidocSignatureSpan">cucumber.</span>SupportCode.StepDefinitionSnippetBuilder (step, syntax)](#apidoc.element.cucumber.SupportCode.StepDefinitionSnippetBuilder)
- description and source-code
```javascript
function StepDefinitionSnippetBuilder(step, syntax) {
  var Cucumber = require('../../cucumber');

  var self = {
    buildSnippet: function buildSnippet() {
      var functionName = self.buildStepDefinitionFunctionName();
      var pattern      = self.buildStepDefinitionPattern();
      var parameters   = self.buildStepDefinitionParameters();
      var comment      = 'Write code here that turns the phrase above into concrete actions';
      return syntax.build(functionName, pattern, parameters, comment);
    },

    buildStepDefinitionFunctionName: function buildStepDefinitionFunctionName() {
      if (step.isOutcomeStep())
        return 'Then';
      else if (step.isEventStep())
        return 'When';
      else
        return 'Given';
    },

    buildStepDefinitionPattern: function buildStepDefinitionPattern() {
      var stepName              = step.getName();
      var escapedStepName       = Cucumber.Util.RegExp.escapeString(stepName);
      var parameterizedStepName = self.parameterizeStepName(escapedStepName);
      var pattern               = '/^' + parameterizedStepName + '$/';
      return pattern;
    },

    buildStepDefinitionParameters: function buildStepDefinitionParameters() {
      var parameters = self.getStepDefinitionPatternMatchingGroupParameters();
      step.getArguments().forEach(function (arg) {
        switch (arg.getType()) {
          case 'DataTable':
            parameters.push('table');
            break;
          case 'DocString':
            parameters.push('string');
            break;
          default:
            throw new Error('Unknown argument type:' + arg.getType());
        }
      });
      parameters.push('callback');
      return parameters;
    },

    getStepDefinitionPatternMatchingGroupParameters: function getStepDefinitionPatternMatchingGroupParameters() {
      var parameterCount = self.countStepDefinitionPatternMatchingGroups();
      var parameters = _.times(parameterCount, function (n) {
        return 'arg' + (n + 1);
      });
      return parameters;
    },

    countStepDefinitionPatternMatchingGroups: function countStepDefinitionPatternMatchingGroups() {
      var stepDefinitionPattern    = self.buildStepDefinitionPattern();
      var numberMatchingGroupCount = Cucumber.Util.String.count(stepDefinitionPattern, NUMBER_MATCHING_GROUP);
      var quotedStringMatchingGroupCount = Cucumber.Util.String.count(stepDefinitionPattern, QUOTED_STRING_MATCHING_GROUP);
      var count = numberMatchingGroupCount + quotedStringMatchingGroupCount;
      return count;
    },

    parameterizeStepName: function parameterizeStepName(stepName) {
      var parameterizedStepName =
          stepName
          .replace(NUMBER_PATTERN, NUMBER_MATCHING_GROUP)
          .replace(QUOTED_STRING_PATTERN, QUOTED_STRING_MATCHING_GROUP);
      return parameterizedStepName;
    }
  };
  return self;
}
```
- example usage
```shell
...
var self = Cucumber.Listener.Formatter(options);
var snippets = [];

self.handleStepResultEvent = function handleStepResult(stepResult) {
  var status = stepResult.getStatus();
  if (status === Cucumber.Status.UNDEFINED) {
    var step = stepResult.getStep();
    var snippetBuilder = Cucumber.SupportCode.StepDefinitionSnippetBuilder(step, options.snippetSyntax);
    snippets.push(snippetBuilder.buildSnippet());
  }
};

self.handleFeaturesResultEvent = function handleFeaturesResultEvent(featuresResult, callback) {
  self.log(snippets.join('\n\n'));
  self.finish(callback);
...
```

#### <a name="apidoc.element.cucumber.TagGroupParser"></a>[function <span class="apidocSignatureSpan">cucumber.</span>TagGroupParser (tagGroupString)](#apidoc.element.cucumber.TagGroupParser)
- description and source-code
```javascript
function TagGroupParser(tagGroupString) {
  var self = {
    parse: function parse() {
      var splitTags = tagGroupString.split(TagGroupParser.TAG_SEPARATOR);
      var trimmedTags = splitTags.map(function (tag) { return tag.trim(); });
      return trimmedTags;
    }
  };
  return self;
}
```
- example usage
```shell
...
  return self;
}

TagGroupParser.getTagGroupsFromStrings = function getTagGroupsFromStrings(tagGroupStrings) {
  var Cucumber = require('../cucumber');

  var tagGroups = tagGroupStrings.map(function (tagOptionValue) {
    var tagGroupParser = Cucumber.TagGroupParser(tagOptionValue);
    var tagGroup       = tagGroupParser.parse();
    return tagGroup;
  });
  return tagGroups;
};

TagGroupParser.TAG_SEPARATOR = ',';
...
```

#### <a name="apidoc.element.cucumber.Type.String"></a>[function <span class="apidocSignatureSpan">cucumber.</span>Type.String ()](#apidoc.element.cucumber.Type.String)
- description and source-code
```javascript
function String() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cucumber.VolatileConfiguration"></a>[function <span class="apidocSignatureSpan">cucumber.</span>VolatileConfiguration (features, supportCodeInitializer, options)](#apidoc.element.cucumber.VolatileConfiguration)
- description and source-code
```javascript
function VolatileConfiguration(features, supportCodeInitializer, options) {
  var Cucumber = require('../cucumber');
  var supportCodeLibrary = Cucumber.SupportCode.Library(supportCodeInitializer);

  options = options || {};
  var strictMode = !!options.strict;
  var tagGroupStrings = options.tags || [];
  var backtrace = !!options.backtrace;
  var worldParameters = options.worldParameters || {};

  var self = {
    isStrictRequested: function isStrictRequested() {
      return strictMode;
    },

    getFeatureSources: function getFeatureSources() {
      if (features.replace) { // single source
        var featureNameSourcePair = [VolatileConfiguration.FEATURE_SOURCE_NAME, features];
        return [featureNameSourcePair];
      } else { // multiple features
        return features;
      }
    },

    getAstFilter: function getAstFilter() {
      var tagRules = self.getTagAstFilterRules();
      var astFilter = Cucumber.Ast.Filter(tagRules);
      return astFilter;
    },

    getSupportCodeLibrary: function getSupportCodeLibrary() {
      return supportCodeLibrary;
    },

    getTagAstFilterRules: function getTagAstFilterRules() {
      var rules = [];
      tagGroupStrings.forEach(function (tagGroupString) {
        var rule = self.buildAstFilterRuleFromTagGroupString(tagGroupString);
        rules.push(rule);
      });
      return rules;
    },

    buildAstFilterRuleFromTagGroupString: function buildAstFilterRuleFromTagGroupString(tagGroupString) {
      var tagGroupParser = Cucumber.TagGroupParser(tagGroupString);
      var tagGroup       = tagGroupParser.parse();
      var rule           = Cucumber.Ast.Filter.AnyOfTagsRule(tagGroup);
      return rule;
    },

    shouldFilterStackTraces: function shouldFilterStackTraces() {
      return !backtrace;
    },

    getWorldParameters: function getWorldParameters() {
      return worldParameters;
    }
  };
  return self;
}
```
- example usage
```shell
...
    "lib/",
    "release/"
  ]
}

},{}],"cucumber":[function(require,module,exports){
function Cucumber(featureSource, supportCodeInitializer, options) {
  var configuration = Cucumber.VolatileConfiguration(featureSource, supportCodeInitializer, options);
  var runtime       = Cucumber.Runtime(configuration);
  return runtime;
}

Cucumber.Api                   = require('./cucumber/api');
Cucumber.Ast                   = require('./cucumber/ast');
Cucumber.Cli                   = require('./cucumber/cli');
...
```



# <a name="apidoc.module.cucumber.Api"></a>[module cucumber.Api](#apidoc.module.cucumber.Api)

#### <a name="apidoc.element.cucumber.Api.Scenario"></a>[function <span class="apidocSignatureSpan">cucumber.Api.</span>Scenario (astScenario, scenarioResult)](#apidoc.element.cucumber.Api.Scenario)
- description and source-code
```javascript
function Scenario(astScenario, scenarioResult) {
  var Cucumber = require('../../cucumber');

  var attachments = [];

  function isStream(value) {
    return value && typeof value === 'object' && typeof value.pipe === 'function';
  }

  function attachData(data, mimeType) {
    var attachment = Cucumber.Runtime.Attachment({mimeType: mimeType, data: data});
    attachments.push(attachment);
  }

  function attachStream(stream, mimeType, callback) {
    var buffers = [];

    stream.on('data', function (chunk) {
      buffers.push(chunk);
    });
    stream.on('end', function () {
      attachData(Buffer.concat(buffers), mimeType);
      callback();
    });
  }

  var self = {
    getKeyword:     function getKeyword()     { return astScenario.getKeyword(); },
    getName:        function getName()        { return astScenario.getName(); },
    getDescription: function getDescription() { return astScenario.getDescription(); },
    getUri:         function getUri()         { return astScenario.getUri(); },
    getLine:        function getLine()        { return astScenario.getLine(); },
    getTags:        function getTags()        { return astScenario.getTags(); },
    isSuccessful:   function isSuccessful()   { return scenarioResult.getStatus() === Cucumber.Status.PASSED; },
    isFailed:       function isFailed()       { return scenarioResult.getStatus() === Cucumber.Status.FAILED; },
    isPending:      function isPending()      { return scenarioResult.getStatus() === Cucumber.Status.PENDING; },
    isUndefined:    function isUndefined()    { return scenarioResult.getStatus() === Cucumber.Status.UNDEFINED; },
    isSkipped:      function isSkipped()      { return scenarioResult.getStatus() === Cucumber.Status.SKIPPED; },
    getException:   function getException()   { return scenarioResult.getFailureException(); },
    getAttachments: function getAttachments() { return attachments; },
    clearAttachments: function clearAttachments() { attachments = []; },

    attach: function attach(data, mimeType, callback) {
      if (isStream(data)) {
        if (!mimeType)
          throw Error(Scenario.ATTACH_MISSING_MIME_TYPE_ARGUMENT);
        if (!callback)
          throw Error(Scenario.ATTACH_MISSING_CALLBACK_ARGUMENT_FOR_STREAM_READABLE);

        attachStream(data, mimeType, callback);
      }
      else if (Buffer && Buffer.isBuffer(data)) {
        if (!mimeType)
          throw Error(Scenario.ATTACH_MISSING_MIME_TYPE_ARGUMENT);

        attachData(data, mimeType);
        if (callback) callback();
      }
      else if (typeof(data) === 'string') {
        if (!mimeType)
          mimeType = Scenario.DEFAULT_TEXT_MIME_TYPE;

        attachData(data, mimeType);
        if (callback) callback();
      } else {
        throw Error(Scenario.ATTACH_INVALID_DATA_TYPE);
      }
    }
  };

  return self;
}
```
- example usage
```shell
...
  e.message += '\npath: ' + uri;
  throw e;
}

var pickles = compiler.compile(gherkinDocument);
var scenarios = [];
pickles.forEach(function (pickleData) {
  var scenario = Cucumber.Ast.Scenario(pickleData, uri);
  if (astFilter.isElementEnrolled(scenario)) {
    scenarios.push(scenario);
  }
});

if (scenarios.length > 0) {
  features.push(Cucumber.Ast.Feature(gherkinDocument.feature, uri, scenarios));
...
```



# <a name="apidoc.module.cucumber.Ast"></a>[module cucumber.Ast](#apidoc.module.cucumber.Ast)

#### <a name="apidoc.element.cucumber.Ast.DataTable"></a>[function <span class="apidocSignatureSpan">cucumber.Ast.</span>DataTable (data)](#apidoc.element.cucumber.Ast.DataTable)
- description and source-code
```javascript
function DataTable(data) {
  var Cucumber = require('../../cucumber');
  var _ = require('lodash');

  var rawTable = data.rows.map(function (row) {
    return row.cells.map(function (cell) {
      return cell.value;
    });
  });

  var self = {
    getType: function getType() {
      return 'DataTable';
    },

    rows: function rows() {
      var copy = self.raw();
      copy.shift();
      return copy;
    },

    rowsHash: function rowsHash() {
      var rows = self.raw();
      var everyRowHasTwoColumns = rows.every(function (row) {
        return row.length === 2;
      });

      if (!everyRowHasTwoColumns) {
        throw new Error('rowsHash was called on a data table with more than two columns');
      }

      return _.fromPairs(rows);
    },

    raw: function raw() {
      return rawTable.slice(0);
    },

    hashes: function hashes() {
      var raw              = self.raw();
      var hashDataTable    = Cucumber.Type.HashDataTable(raw);
      var rawHashDataTable = hashDataTable.raw();
      return rawHashDataTable;
    }
  };
  return self;
}
```
- example usage
```shell
...
var stepArguments = [];

if (data.arguments) {
  stepArguments = data.arguments.map(function (arg) {
    if (arg.hasOwnProperty('content')) {
      return Cucumber.Ast.DocString(arg);
    } else if (arg.hasOwnProperty('rows')) {
      return Cucumber.Ast.DataTable(arg);
    } else {
      throw new Error('Unknown step argument type: ' + JSON.stringify(arg));
    }
  });
}

var self = {
...
```

#### <a name="apidoc.element.cucumber.Ast.DocString"></a>[function <span class="apidocSignatureSpan">cucumber.Ast.</span>DocString (data)](#apidoc.element.cucumber.Ast.DocString)
- description and source-code
```javascript
function DocString(data) {
  var self = {
    getType: function getType() {
      return 'DocString';
    },

    getContent: function getContent() {
      return data.content;
    },

    getContentType: function getContentType() {
      return data.contentType;
    },

    getLine: function getLine() {
      return data.location.line;
    }
  };
  return self;
}
```
- example usage
```shell
...
var previousStep, scenario;

var stepArguments = [];

if (data.arguments) {
  stepArguments = data.arguments.map(function (arg) {
    if (arg.hasOwnProperty('content')) {
      return Cucumber.Ast.DocString(arg);
    } else if (arg.hasOwnProperty('rows')) {
      return Cucumber.Ast.DataTable(arg);
    } else {
      throw new Error('Unknown step argument type: ' + JSON.stringify(arg));
    }
  });
}
...
```

#### <a name="apidoc.element.cucumber.Ast.Feature"></a>[function <span class="apidocSignatureSpan">cucumber.Ast.</span>Feature (data, uri, scenarios)](#apidoc.element.cucumber.Ast.Feature)
- description and source-code
```javascript
function Feature(data, uri, scenarios) {
  var Cucumber = require('../../cucumber');
  var Gherkin = require('gherkin');
  var _ = require('lodash');

  var tags = [];
  if (data.tags) {
    tags = data.tags.map(function (tagData) {
      return Cucumber.Ast.Tag(tagData);
    });
  }

  var self = {
    getStepKeywordByLines: function getStepKeywordByLines(lines) {
      var steps = _.flatten(_.map(data.children, 'steps'));
      var step = _.find(steps, function(node) {
        return _.includes(lines, node.location.line);
      });
      if (step) {
        return step.keyword;
      }
    },

    getScenarioDescriptionByLines: function getScenarioDescriptionByLines(lines) {
      var element = _.find(data.children, function(node) {
        return _.includes(lines, node.location.line);
      });
      if (element) {
        return element.description;
      }
    },

    getScenarioKeyword: function() {
      return Gherkin.DIALECTS[self.getLanguage()].scenario;
    },

    getKeyword: function getKeyword() {
      return data.keyword;
    },

    getLanguage: function getKeyword() {
      return data.language;
    },

    getName: function getName() {
      return data.name;
    },

    getDescription: function getDescription() {
      return data.description;
    },

    getUri: function getUri() {
      return uri;
    },

    getLine: function getLine() {
      return data.location.line;
    },

    getTags: function getTags() {
      return tags;
    },

    getScenarios: function getScenarios() {
      return scenarios;
    }
  };

  scenarios.forEach(function(scenario) {
    scenario.setFeature(self);
  });

  return self;
}
```
- example usage
```shell
...
        var scenario = Cucumber.Ast.Scenario(pickleData, uri);
        if (astFilter.isElementEnrolled(scenario)) {
          scenarios.push(scenario);
        }
      });

      if (scenarios.length > 0) {
        features.push(Cucumber.Ast.Feature(gherkinDocument.feature, uri, scenarios));
      }
    });

    return features;
  }
};
return self;
...
```

#### <a name="apidoc.element.cucumber.Ast.Filter"></a>[function <span class="apidocSignatureSpan">cucumber.Ast.</span>Filter (rules)](#apidoc.element.cucumber.Ast.Filter)
- description and source-code
```javascript
function Filter(rules) {
  var self = {
    isElementEnrolled: function isElementEnrolled(element) {
      var enrolled = _.every(rules, function (rule) {
        return rule.isSatisfiedByElement(element);
      });
      return enrolled;
    }
  };
  return self;
}
```
- example usage
```shell
...
  var tagGroups = Cucumber.TagGroupParser.getTagGroupsFromStrings(options.tags);
  var tagRules = tagGroups.map(function (tags) {
     return Cucumber.Ast.Filter.AnyOfTagsRule(tags);
  });
  var lineRule = Cucumber.Ast.Filter.ScenarioAtLineRule(unexpandedFeaturePaths);
  var nameRule = Cucumber.Ast.Filter.AnyOfNamesRule(options.name);
  var rules = tagRules.concat([lineRule, nameRule]);
  return Cucumber.Ast.Filter(rules);
},

getSupportCodeLibrary: function getSupportCodeLibrary() {
  var supportCodePaths = getSupportCodePaths();
  var compilerModules = getCompilerModules();
  var supportCodeLoader = Cucumber.Cli.SupportCodeLoader(supportCodePaths, compilerModules);
  return supportCodeLoader.getSupportCodeLibrary();
...
```

#### <a name="apidoc.element.cucumber.Ast.HookStep"></a>[function <span class="apidocSignatureSpan">cucumber.Ast.</span>HookStep (keyword)](#apidoc.element.cucumber.Ast.HookStep)
- description and source-code
```javascript
function HookStep(keyword) {
  var Cucumber = require('../../cucumber');
  var self = Cucumber.Ast.Step({});

  self.getKeyword = function getKeyword() {
    return keyword;
  };

  self.isHidden = function isHidden() {
    return true;
  };

  self.hasUri = function hasUri() {
    return false;
  };

  return self;
}
```
- example usage
```shell
...
    }
  );
},

runBeforeHooks: function runBeforeHooks(callback) {
  var beforeHooks = supportCodeLibrary.lookupBeforeHooksByScenario(scenario);
  Cucumber.Util.asyncForEach(beforeHooks, function(beforeHook, callback) {
    var beforeStep = Cucumber.Ast.HookStep(Cucumber.Ast.HookStep.BEFORE_STEP_KEYWORD);
    beforeStep.setScenario(scenario);
    self.runHookStep(beforeStep, beforeHook, callback);
  }, callback);
},

runSteps: function runSteps(callback) {
  Cucumber.Util.asyncForEach(scenario.getSteps(), self.runStep, callback);
...
```

#### <a name="apidoc.element.cucumber.Ast.Scenario"></a>[function <span class="apidocSignatureSpan">cucumber.Ast.</span>Scenario (data, uri)](#apidoc.element.cucumber.Ast.Scenario)
- description and source-code
```javascript
function Scenario(data, uri) {
  var Cucumber = require('../../cucumber');
  var _ = require('lodash');
  var feature, steps, tags = [];

  var self = {
    getName: function getName() {
      return data.name;
    },

    getKeyword: function getKeyword() {
      return self.getFeature().getScenarioKeyword();
    },

    getDescription: function getDescription() {
      return self.getFeature().getScenarioDescriptionByLines(self.getLines());
    },

    getFeature: function getFeature() {
      return feature;
    },

    setFeature: function setFeature(value) {
      feature = value;
    },

    getUri: function getUri() {
      return uri;
    },

    getLine: function getLine() {
      return _.first(self.getLines());
    },

    getLines: function getLines() {
      return _.map(data.locations, 'line');
    },

    getTags: function getTags() {
      return tags;
    },

    getSteps: function getSteps() {
      return steps;
    }
  };

  var previousStep;
  steps = data.steps.map(function (stepData) {
    var step = Cucumber.Ast.Step(stepData);
    step.setScenario(self);
    step.setPreviousStep(previousStep);
    previousStep = step;
    return step;
  });

  if (data.tags) {
    tags = data.tags.map(function (tagData) {
      return Cucumber.Ast.Tag(tagData);
    });
  }

  return self;
}
```
- example usage
```shell
...
  e.message += '\npath: ' + uri;
  throw e;
}

var pickles = compiler.compile(gherkinDocument);
var scenarios = [];
pickles.forEach(function (pickleData) {
  var scenario = Cucumber.Ast.Scenario(pickleData, uri);
  if (astFilter.isElementEnrolled(scenario)) {
    scenarios.push(scenario);
  }
});

if (scenarios.length > 0) {
  features.push(Cucumber.Ast.Feature(gherkinDocument.feature, uri, scenarios));
...
```

#### <a name="apidoc.element.cucumber.Ast.Step"></a>[function <span class="apidocSignatureSpan">cucumber.Ast.</span>Step (data)](#apidoc.element.cucumber.Ast.Step)
- description and source-code
```javascript
function Step(data) {
  var Cucumber = require('../../cucumber');
  var Gherkin = require('gherkin');
  var _ = require('lodash');
  var previousStep, scenario;

  var stepArguments = [];

  if (data.arguments) {
    stepArguments = data.arguments.map(function (arg) {
      if (arg.hasOwnProperty('content')) {
        return Cucumber.Ast.DocString(arg);
      } else if (arg.hasOwnProperty('rows')) {
        return Cucumber.Ast.DataTable(arg);
      } else {
        throw new Error('Unknown step argument type: ' + JSON.stringify(arg));
      }
    });
  }

  var self = {
    getScenario: function getScenario() {
      return scenario;
    },

    setScenario: function setScenario(newScenario) {
      scenario = newScenario;
    },

    setPreviousStep: function setPreviousStep(newPreviousStep) {
      previousStep = newPreviousStep;
    },

    isHidden: function isHidden() {
      return false;
    },

    getName: function getName() {
      return data.text;
    },

    getKeyword: function getKeyword() {
      return self.getScenario().getFeature().getStepKeywordByLines(self.getLines());
    },

    hasUri: function hasUri() {
      return true;
    },

    getLine: function getLine() {
      return _.last(self.getLines());
    },

    getLines: function getLines() {
      return _.map(data.locations, 'line');
    },

    getUri: function getUri() {
      return self.getScenario().getUri();
    },

    getPreviousStep: function getPreviousStep() {
      return previousStep;
    },

    hasPreviousStep: function hasPreviousStep() {
      return !!previousStep;
    },

    getArguments: function getArguments() {
      return stepArguments;
    },

    isOutcomeStep: function isOutcomeStep() {
      return self.hasOutcomeStepKeyword() || self.isRepeatingOutcomeStep();
    },

    isEventStep: function isEventStep() {
      return self.hasEventStepKeyword() || self.isRepeatingEventStep();
    },

    hasOutcomeStepKeyword: function hasOutcomeStepKeyword() {
      var language = self.getScenario().getFeature().getLanguage();
      return _.chain(Gherkin.DIALECTS[language].then)
        .includes(self.getKeyword())
        .value();
    },

    hasEventStepKeyword: function hasEventStepKeyword() {
      var language = self.getScenario().getFeature().getLanguage();
      return _.chain(Gherkin.DIALECTS[language].when)
        .includes(self.getKeyword())
        .value();
    },

    isRepeatingOutcomeStep: function isRepeatingOutcomeStep() {
      return self.hasRepeatStepKeyword() && self.isPrecededByOutcomeStep();
    },

    isRepeatingEventStep: function isRepeatingEventStep() {
      return self.hasRepeatStepKeyword() && self.isPrecededByEventStep();
    },

    hasRepeatStepKeyword: function hasRepeatStepKeyword() {
      var language = self.getScenario().getFeature().getLanguage();
      return _.chain(Gherkin.DIALECTS[language].and)
        .concat(Gherkin.DIALECTS[language].but)
        .includes(self.getKeyword())
        .value();
    },

    isPrecededByOutcomeStep: function isPrecededByOutcomeStep() {
      var result = false;

      if (self.hasPreviousStep()) {
        var previousStep = self.getPreviousStep();
        result = previousStep.isOutcomeStep();
      }
      return result;
    },

    isPrecededByEventStep: function isPrecededByEventStep() {
      var result = false;

      if (self.hasPreviousStep()) {
        var previousStep = self.getPreviousStep();
        result = previousStep.isEventStep();
      }
      return result;
    }
  };
  return self;
}
```
- example usage
```shell
...
}

module.exports = ScenarioAtLineRule;

},{"../../../cucumber":"cucumber","fs":72,"lodash":165}],12:[function(require,module,exports){
function HookStep(keyword) {
var Cucumber = require('../../cucumber');
var self = Cucumber.Ast.Step({});

self.getKeyword = function getKeyword() {
  return keyword;
};

self.isHidden = function isHidden() {
  return true;
...
```

#### <a name="apidoc.element.cucumber.Ast.Tag"></a>[function <span class="apidocSignatureSpan">cucumber.Ast.</span>Tag (data)](#apidoc.element.cucumber.Ast.Tag)
- description and source-code
```javascript
function Tag(data) {
  var self = {
    getName: function getName() {
      return data.name;
    },

    getLine: function getLine() {
      return data.location.line;
    }
  };
  return self;
}
```
- example usage
```shell
...
var Cucumber = require('../../cucumber');
var Gherkin = require('gherkin');
var _ = require('lodash');

var tags = [];
if (data.tags) {
  tags = data.tags.map(function (tagData) {
    return Cucumber.Ast.Tag(tagData);
  });
}

var self = {
  getStepKeywordByLines: function getStepKeywordByLines(lines) {
    var steps = _.flatten(_.map(data.children, 'steps'));
    var step = _.find(steps, function(node) {
...
```



# <a name="apidoc.module.cucumber.Ast.Filter"></a>[module cucumber.Ast.Filter](#apidoc.module.cucumber.Ast.Filter)

#### <a name="apidoc.element.cucumber.Ast.Filter.Filter"></a>[function <span class="apidocSignatureSpan">cucumber.Ast.</span>Filter (rules)](#apidoc.element.cucumber.Ast.Filter.Filter)
- description and source-code
```javascript
function Filter(rules) {
  var self = {
    isElementEnrolled: function isElementEnrolled(element) {
      var enrolled = _.every(rules, function (rule) {
        return rule.isSatisfiedByElement(element);
      });
      return enrolled;
    }
  };
  return self;
}
```
- example usage
```shell
...
  var tagGroups = Cucumber.TagGroupParser.getTagGroupsFromStrings(options.tags);
  var tagRules = tagGroups.map(function (tags) {
     return Cucumber.Ast.Filter.AnyOfTagsRule(tags);
  });
  var lineRule = Cucumber.Ast.Filter.ScenarioAtLineRule(unexpandedFeaturePaths);
  var nameRule = Cucumber.Ast.Filter.AnyOfNamesRule(options.name);
  var rules = tagRules.concat([lineRule, nameRule]);
  return Cucumber.Ast.Filter(rules);
},

getSupportCodeLibrary: function getSupportCodeLibrary() {
  var supportCodePaths = getSupportCodePaths();
  var compilerModules = getCompilerModules();
  var supportCodeLoader = Cucumber.Cli.SupportCodeLoader(supportCodePaths, compilerModules);
  return supportCodeLoader.getSupportCodeLibrary();
...
```

#### <a name="apidoc.element.cucumber.Ast.Filter.AnyOfNamesRule"></a>[function <span class="apidocSignatureSpan">cucumber.Ast.Filter.</span>AnyOfNamesRule (names)](#apidoc.element.cucumber.Ast.Filter.AnyOfNamesRule)
- description and source-code
```javascript
function AnyOfNamesRule(names) {
  var self = {
    isSatisfiedByElement: function isSatisfiedByElement(element) {
      if (names.length === 0) {
        return true;
      }
      var satisfied = _.some(names, function (name) {
        return element.getName().match(name);
      });
      return satisfied;
    }
  };
  return self;
}
```
- example usage
```shell
...

getAstFilter: function getAstFilter() {
  var tagGroups = Cucumber.TagGroupParser.getTagGroupsFromStrings(options.tags);
  var tagRules = tagGroups.map(function (tags) {
     return Cucumber.Ast.Filter.AnyOfTagsRule(tags);
  });
  var lineRule = Cucumber.Ast.Filter.ScenarioAtLineRule(unexpandedFeaturePaths);
  var nameRule = Cucumber.Ast.Filter.AnyOfNamesRule(options.name);
  var rules = tagRules.concat([lineRule, nameRule]);
  return Cucumber.Ast.Filter(rules);
},

getSupportCodeLibrary: function getSupportCodeLibrary() {
  var supportCodePaths = getSupportCodePaths();
  var compilerModules = getCompilerModules();
...
```

#### <a name="apidoc.element.cucumber.Ast.Filter.AnyOfTagsRule"></a>[function <span class="apidocSignatureSpan">cucumber.Ast.Filter.</span>AnyOfTagsRule (tags)](#apidoc.element.cucumber.Ast.Filter.AnyOfTagsRule)
- description and source-code
```javascript
function AnyOfTagsRule(tags) {
  var Cucumber = require('../../../cucumber');

  var self = {
    isSatisfiedByElement: function isSatisfiedByElement(element) {
      var satisfied = _.some(tags, function (tag) {
        var spec = Cucumber.Ast.Filter.ElementMatchingTagSpec(tag);
        return spec.isMatching(element);
      });
      return satisfied;
    }
  };
  return self;
}
```
- example usage
```shell
...
  var featureSourceLoader = Cucumber.Cli.FeatureSourceLoader(expandedFeaturePaths);
  return featureSourceLoader.getSources();
},

getAstFilter: function getAstFilter() {
  var tagGroups = Cucumber.TagGroupParser.getTagGroupsFromStrings(options.tags);
  var tagRules = tagGroups.map(function (tags) {
     return Cucumber.Ast.Filter.AnyOfTagsRule(tags);
  });
  var lineRule = Cucumber.Ast.Filter.ScenarioAtLineRule(unexpandedFeaturePaths);
  var nameRule = Cucumber.Ast.Filter.AnyOfNamesRule(options.name);
  var rules = tagRules.concat([lineRule, nameRule]);
  return Cucumber.Ast.Filter(rules);
},
...
```

#### <a name="apidoc.element.cucumber.Ast.Filter.ElementMatchingTagSpec"></a>[function <span class="apidocSignatureSpan">cucumber.Ast.Filter.</span>ElementMatchingTagSpec (tagName)](#apidoc.element.cucumber.Ast.Filter.ElementMatchingTagSpec)
- description and source-code
```javascript
function ElementMatchingTagSpec(tagName) {
  var self = {
    isMatching: function isMatching(element) {
      var elementTags = element.getTags();
      var matching;
      if (self.isExpectingTag())
        matching = _.some(elementTags, self.isTagSatisfying);
      else
        matching = _.every(elementTags, self.isTagSatisfying);
      return matching;
    },

    isTagSatisfying: function isTagSatisfying(tag) {
      var checkedTagName = tag.getName();
      var satisfying;
      if (self.isExpectingTag())
        satisfying = checkedTagName === tagName;
      else {
        var negatedCheckedTagName = ElementMatchingTagSpec.NEGATION_CHARACTER + checkedTagName;
        satisfying = negatedCheckedTagName !== tagName;
      }
      return satisfying;
    },

    isExpectingTag: function isExpectingTag() {
      var expectingTag = tagName[0] !== ElementMatchingTagSpec.NEGATION_CHARACTER;
      return expectingTag;
    }
  };
  return self;
}
```
- example usage
```shell
...

function AnyOfTagsRule(tags) {
  var Cucumber = require('../../../cucumber');

  var self = {
    isSatisfiedByElement: function isSatisfiedByElement(element) {
      var satisfied = _.some(tags, function (tag) {
        var spec = Cucumber.Ast.Filter.ElementMatchingTagSpec(tag);
        return spec.isMatching(element);
      });
      return satisfied;
    }
  };
  return self;
}
...
```

#### <a name="apidoc.element.cucumber.Ast.Filter.ScenarioAtLineRule"></a>[function <span class="apidocSignatureSpan">cucumber.Ast.Filter.</span>ScenarioAtLineRule (suppliedPaths)](#apidoc.element.cucumber.Ast.Filter.ScenarioAtLineRule)
- description and source-code
```javascript
function ScenarioAtLineRule(suppliedPaths) {
  var Cucumber = require('../../../cucumber');
  var fs = require('fs');
  var _ = require('lodash');

  var mapping = {};
  suppliedPaths.forEach(function(path){
    var matches = Cucumber.Cli.Configuration.FEATURE_FILENAME_AND_LINENUM_REGEXP.exec(path);
    var specifiedLineNums = matches && matches[2];
    if (specifiedLineNums) {
      var realPath = fs.realpathSync(matches[1]);
      if (!mapping[realPath]) {
        mapping[realPath] = [];
      }
      specifiedLineNums.split(':').forEach(function (lineNum) {
        mapping[realPath].push(parseInt(lineNum));
      });
    }
  });

  var self = {
    isSatisfiedByElement: function isSatisfiedByElement(element) {
      if (element.getUri && element.getLines) {
        var lines = mapping[element.getUri()];
        if (lines) {
          return _.some(element.getLines(), function (line) {
            return _.includes(lines, line);
          });
        }
      }
      return true;
    }
  };
  return self;
}
```
- example usage
```shell
...
},

getAstFilter: function getAstFilter() {
  var tagGroups = Cucumber.TagGroupParser.getTagGroupsFromStrings(options.tags);
  var tagRules = tagGroups.map(function (tags) {
     return Cucumber.Ast.Filter.AnyOfTagsRule(tags);
  });
  var lineRule = Cucumber.Ast.Filter.ScenarioAtLineRule(unexpandedFeaturePaths);
  var nameRule = Cucumber.Ast.Filter.AnyOfNamesRule(options.name);
  var rules = tagRules.concat([lineRule, nameRule]);
  return Cucumber.Ast.Filter(rules);
},

getSupportCodeLibrary: function getSupportCodeLibrary() {
  var supportCodePaths = getSupportCodePaths();
...
```



# <a name="apidoc.module.cucumber.Cli"></a>[module cucumber.Cli](#apidoc.module.cucumber.Cli)

#### <a name="apidoc.element.cucumber.Cli.Cli"></a>[function <span class="apidocSignatureSpan">cucumber.</span>Cli (argv)](#apidoc.element.cucumber.Cli.Cli)
- description and source-code
```javascript
function Cli(argv) {
  var Cucumber = require('../cucumber');
  var Command = require('commander').Command;
  var path = require('path');
  var _ = require('lodash');

  function mergeWorldParametersJson(str, memo) {
    var val;
    try {
      val = JSON.parse(str);
    } catch (error) {
      throw new Error('--world-parameters passed invalid JSON: ' + error.message + ': ' + str);
    }
    if (!_.isPlainObject(val)) {
      throw new Error('--world-parameters must be passed a JSON string of an object: ' + str);
    }
    _.merge(memo, val);
    return memo;
  }

  function collect(val, memo) {
    memo.push(val);
    return memo;
  }

  function getProgram () {
    var program = new Command(path.basename(argv[1]));

    program
      .usage('[options] [<DIR | FILE[:LINE]>...]')
      .version(Cucumber.VERSION, '-v, --version')
      .option('-b, --backtrace', 'show full backtrace for errors')
      .option('--compiler <EXTENSION:MODULE>', 'require files with the given EXTENSION after requiring MODULE (repeatable)', collect
, [])
      .option('-d, --dry-run', 'invoke formatters without executing steps')
      .option('--fail-fast', 'abort the run on first failure')
      .option('-f, --format <TYPE[:PATH]>', 'specify the output format, optionally supply PATH to redirect formatter output (repeatable
)', collect, ['pretty'])
      .option('--name <REGEXP>', 'only execute the scenarios with name matching the expression (repeatable)', collect, [])
      .option('--no-colors', 'disable colors in formatter output')
      .option('-p, --profile <NAME>', 'specify the profile to use (repeatable)', collect, [])
      .option('-r, --require <FILE | DIR>', 'require files before executing features (repeatable)', collect, [])
      .option('--snippet-interface [callback | generator | promise | synchronous]', 'specify a snippet interface', 'callback')
      .option('--snippet-syntax [<FILE>]', 'specify a custom snippet syntax')
      .option('-S, --strict', 'fail if there are any undefined or pending steps')
      .option('-t, --tags <EXPRESSION>', 'only execute the features or scenarios with tags matching the expression (repeatable)',
collect, [])
      .option('--world-parameters <JSON>', 'provide parameters that will be passed to the world constructor (repeatable)', mergeWorldParametersJson
, {});

    program.on('--help', function(){
      console.log('  For more details please visit https://github.com/cucumber/cucumber-js#cli\n');
    });

    return program;
  }

  function getConfiguration() {
    var program = getProgram();
    program.parse(argv);
    var profileArgs = Cucumber.Cli.ProfilesLoader.getArgs(program.profile);
    if (profileArgs.length > 0) {
      var fullArgs = argv.slice(0, 2).concat(profileArgs).concat(argv.slice(2));
      program = getProgram();
      program.parse(fullArgs);
    }
    var configuration = Cucumber.Cli.Configuration(program.opts(), program.args);
    return configuration;
  }

  var self = {
    run: function run(callback) {
      var configuration = getConfiguration();
      var runtime    = Cucumber.Runtime(configuration);
      var formatters = configuration.getFormatters();
      formatters.forEach(function (formatter) {
        runtime.attachListener(formatter);
      });
      runtime.start(callback);
    }
  };
  return self;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cucumber.Cli.Configuration"></a>[function <span class="apidocSignatureSpan">cucumber.Cli.</span>Configuration (options, args)](#apidoc.element.cucumber.Cli.Configuration)
- description and source-code
```javascript
function Configuration(options, args) {
  var Cucumber = require('../../cucumber');
  var path = require('path');
  var fs = require('fs');
  var _ = require('lodash');

  var unexpandedFeaturePaths = ['features'];
  if (args.length > 0) {
    unexpandedFeaturePaths = [];
    args.forEach(function(arg) {
      var filename = path.basename(arg);
      if (filename[0] === '@') {
        var content = fs.readFileSync(arg, 'utf8');
        unexpandedFeaturePaths = unexpandedFeaturePaths.concat(content.split('\n'));
      } else {
        unexpandedFeaturePaths.push(arg);
      }
    });
  }

  var expandedFeaturePaths = Cucumber.Cli.FeaturePathExpander.expandPaths(unexpandedFeaturePaths);


  function getCompilerExtensions() {
    return options.compiler.map(function(compiler) {
      return compiler.split(':')[0];
    });
  }

  function getCompilerModules() {
    return options.compiler.map(function(compiler) {
      return compiler.split(':')[1];
    });
  }


  function getFeatureDirectoryPaths() {
    return expandedFeaturePaths.map(function (featurePath) {
      return path.dirname(featurePath);
    });
  }

  function getFormats() {
    var outputMapping = {};
    options.format.forEach(function (format) {
      var parts = format.split(':');
      var type = parts[0];
      var outputTo = parts.slice(1).join(':');
      outputMapping[outputTo] = type;
    });
    return _.map(outputMapping, function (type, outputTo) {
      var stream = process.stdout;
      if (outputTo) {
        var fd = fs.openSync(outputTo, 'w');
        stream = fs.createWriteStream(null, {fd: fd});
      }
      return {stream: stream, type: type};
    });
  }

  function getSnippetSyntax () {
    var builder = Cucumber.SupportCode.StepDefinitionSnippetBuilder.JavaScriptSyntax;
    if (options.snippetSyntax) {
      var snippetSyntaxPath = path.resolve(process.cwd(), options.snippetSyntax);
      builder = require(snippetSyntaxPath);
    }
    return builder(options.snippetInterface);
  }

  function getSupportCodePaths() {
    var unexpandedSupportCodePaths = options.require.length > 0 ? options.require : getFeatureDirectoryPaths();
    var extensions = ['js'].concat(getCompilerExtensions());
    return Cucumber.Cli.SupportCodePathExpander.expandPaths(unexpandedSupportCodePaths, extensions);
  }

  var self = {

    getFormatters: function getFormatters() {
      var formats = getFormats();
      var snippetSyntax = getSnippetSyntax();
      var formatters = formats.map(function (format) {
        var formatterOptions = {
          snippetSyntax: snippetSyntax,
          stream: format.stream,
          useColors: options.colors
        };

        switch(format.type) {
          case 'json':
            return Cucumber.Listener.JsonFormatter(formatterOptions);
          case 'progress':
            return Cucumber.Listener.ProgressFormatter(formatterOptions);
          case 'pretty':
            return Cucumber.Listener.PrettyFormatter(formatterOptions);
          case 'snippets':
            return Cucumber.Listener.SnippetsFormatter(formatterOptions);
          case 'summary':
            return Cucumber.Listener.SummaryFormatter(formatterOptions);
          case 'rerun':
            return Cucumber.Listener.RerunFormatter(formatterOptions);
          default:
            throw new Error('Unknown formatter name "' + format.type + '".');
        }
      });
      return formatters;
    },

    getFeatureSources: function getFeatureSources() {
      var featureSourceLoader = Cucumber.Cli.FeatureSourceLoader(expandedFeaturePaths);
      return featureSourceLoader.getSources();
    },

    getAstFilter: function getAstFilter() {
      var tagGroups = Cucumber.TagGroupParser.getTagGroupsFromStrings(options.tags);
      var tagRules = tagGroups.map(function (tags) {
         return Cucumber.Ast.Filter.AnyOfTagsRule(tags);
      });
      var lineRule = Cucumber.Ast.Filter.ScenarioAtLineRule(unexpandedFeaturePaths);
      var nameRule = Cucumber.Ast.Filter.AnyOfNamesRule(options.name);
      var rules = tagRules.concat([lineRule, nameRule]); ...
```
- example usage
```shell
...
  program.parse(argv);
  var profileArgs = Cucumber.Cli.ProfilesLoader.getArgs(program.profile);
  if (profileArgs.length > 0) {
    var fullArgs = argv.slice(0, 2).concat(profileArgs).concat(argv.slice(2));
    program = getProgram();
    program.parse(fullArgs);
  }
  var configuration = Cucumber.Cli.Configuration(program.opts(), program.args);
  return configuration;
}

var self = {
  run: function run(callback) {
    var configuration = getConfiguration();
    var runtime    = Cucumber.Runtime(configuration);
...
```

#### <a name="apidoc.element.cucumber.Cli.FeatureSourceLoader"></a>[function <span class="apidocSignatureSpan">cucumber.Cli.</span>FeatureSourceLoader (featureFilePaths)](#apidoc.element.cucumber.Cli.FeatureSourceLoader)
- description and source-code
```javascript
function FeatureSourceLoader(featureFilePaths) {
  var fs = require('fs');

  var self = {
    getSources: function getSources() {
      var sources = [];
      featureFilePaths.forEach(function (featureFilePath) {
        var source = fs.readFileSync(featureFilePath, 'utf8');
        sources.push([featureFilePath, source]);
      });
      return sources;
    }
  };
  return self;
}
```
- example usage
```shell
...
        throw new Error('Unknown formatter name "' + format.type + '".');
    }
  });
  return formatters;
},

getFeatureSources: function getFeatureSources() {
  var featureSourceLoader = Cucumber.Cli.FeatureSourceLoader(expandedFeaturePaths);
  return featureSourceLoader.getSources();
},

getAstFilter: function getAstFilter() {
  var tagGroups = Cucumber.TagGroupParser.getTagGroupsFromStrings(options.tags);
  var tagRules = tagGroups.map(function (tags) {
     return Cucumber.Ast.Filter.AnyOfTagsRule(tags);
...
```

#### <a name="apidoc.element.cucumber.Cli.SupportCodeLoader"></a>[function <span class="apidocSignatureSpan">cucumber.Cli.</span>SupportCodeLoader (supportCodeFilePaths, compilerModules)](#apidoc.element.cucumber.Cli.SupportCodeLoader)
- description and source-code
```javascript
function SupportCodeLoader(supportCodeFilePaths, compilerModules) {
  var Cucumber = require('../../cucumber');

  var self = {
    getSupportCodeLibrary: function getSupportCodeLibrary() {
      var supportCodeInitialiazer = self.getSupportCodeInitializer();
      var supportCodeLibrary      = Cucumber.SupportCode.Library(supportCodeInitialiazer);
      return supportCodeLibrary;
    },

    getSupportCodeInitializer: function getSupportCodeInitializer() {
      var primeSupportCodeInitializer     = self.getPrimeSupportCodeInitializer();
      var secondarySupportCodeInitializer = self.getSecondarySupportCodeInitializer();
      var initializer = function () {
        var supportCodeHelper = this;
        var userLandModulesPath = path.join(process.cwd(), 'node_modules');
        process.env.NODE_PATH += SupportCodeLoader.ENV_VAR_PATH_SEPARATOR + userLandModulesPath;
        require('module').Module._initPaths();
        compilerModules.forEach(require);
        primeSupportCodeInitializer.call(supportCodeHelper);
        secondarySupportCodeInitializer.call(supportCodeHelper);
      };
      return initializer;
    },

    getPrimeSupportCodeInitializer: function getPrimeSupportCodeInitializer() {
      var primeSupportCodeFilePaths   = self.getPrimeSupportCodeFilePaths();
      var primeSupportCodeInitializer = self.buildSupportCodeInitializerFromPaths(primeSupportCodeFilePaths);
      return primeSupportCodeInitializer;
     },

    getSecondarySupportCodeInitializer: function getSecondarySupportCodeBlocks() {
      var secondarySupportCodeFilePaths = self.getSecondarySupportCodeFilePaths();
      var secondarySupportCodeInitializer = self.buildSupportCodeInitializerFromPaths(secondarySupportCodeFilePaths);
      return secondarySupportCodeInitializer;
    },

    getPrimeSupportCodeFilePaths: function getPrimeSupportCodeFilePaths() {
      var primeSupportCodeFilePaths = [];
      supportCodeFilePaths.forEach(function (path) {
        if (path.match(SupportCodeLoader.PRIME_SUPPORT_CODE_PATH_REGEXP))
          primeSupportCodeFilePaths.push(path);
      });
      return primeSupportCodeFilePaths;
    },

    getSecondarySupportCodeFilePaths: function getSecondarySupportCodeFilePaths() {
      var secondarySupportCodeFilePaths = [];
      supportCodeFilePaths.forEach(function (path) {
        if (!path.match(SupportCodeLoader.PRIME_SUPPORT_CODE_PATH_REGEXP))
          secondarySupportCodeFilePaths.push(path);
      });
      return secondarySupportCodeFilePaths;
    },

    buildSupportCodeInitializerFromPaths: function buildSupportCodeInitializerFromPaths(paths) {
      var wrapper = function () {
        var supportCodeHelper = this;
        paths.forEach(function (path) {
          var initializer = require(path);
          if (typeof(initializer) === 'function') {
            initializer.call(supportCodeHelper);
          } else if (initializer.hasOwnProperty('default') && typeof(initializer.default) === 'function') {
            initializer.default.call(supportCodeHelper);
          }
        });
      };
      return wrapper;
    }
  };
  return self;
}
```
- example usage
```shell
...
  var rules = tagRules.concat([lineRule, nameRule]);
  return Cucumber.Ast.Filter(rules);
},

getSupportCodeLibrary: function getSupportCodeLibrary() {
  var supportCodePaths = getSupportCodePaths();
  var compilerModules = getCompilerModules();
  var supportCodeLoader = Cucumber.Cli.SupportCodeLoader(supportCodePaths, compilerModules);
  return supportCodeLoader.getSupportCodeLibrary();
},

getWorldParameters: function getWorldParameters() {
  return options.worldParameters;
},
...
```



# <a name="apidoc.module.cucumber.Cli.FeaturePathExpander"></a>[module cucumber.Cli.FeaturePathExpander](#apidoc.module.cucumber.Cli.FeaturePathExpander)

#### <a name="apidoc.element.cucumber.Cli.FeaturePathExpander.expandPaths"></a>[function <span class="apidocSignatureSpan">cucumber.Cli.FeaturePathExpander.</span>expandPaths (paths)](#apidoc.element.cucumber.Cli.FeaturePathExpander.expandPaths)
- description and source-code
```javascript
function expandPaths(paths) {
  var Cucumber     = require('../../cucumber');
  var PathExpander = Cucumber.Cli.PathExpander;

  paths = paths.map(function(path) {
    return path.replace(/(:\d+)*$/g, ''); // Strip line numbers
  });
  var expandedPaths = PathExpander.expandPathsWithExtensions(paths, ['feature']);
  return expandedPaths;
}
```
- example usage
```shell
...
      unexpandedFeaturePaths = unexpandedFeaturePaths.concat(content.split('\n'));
    } else {
      unexpandedFeaturePaths.push(arg);
    }
  });
}

var expandedFeaturePaths = Cucumber.Cli.FeaturePathExpander.expandPaths(unexpandedFeaturePaths);


function getCompilerExtensions() {
  return options.compiler.map(function(compiler) {
    return compiler.split(':')[0];
  });
}
...
```



# <a name="apidoc.module.cucumber.Cli.PathExpander"></a>[module cucumber.Cli.PathExpander](#apidoc.module.cucumber.Cli.PathExpander)

#### <a name="apidoc.element.cucumber.Cli.PathExpander.expandDirectoryWithExtensions"></a>[function <span class="apidocSignatureSpan">cucumber.Cli.PathExpander.</span>expandDirectoryWithExtensions (realPath, extensions)](#apidoc.element.cucumber.Cli.PathExpander.expandDirectoryWithExtensions)
- description and source-code
```javascript
function expandDirectoryWithExtensions(realPath, extensions) {
  var pattern = realPath + '/**/*.';
  if (extensions.length > 1) {
    pattern += '{' + extensions.join(',') + '}';
  } else {
    pattern += extensions[0];
  }
  return glob.sync(pattern);
}
```
- example usage
```shell
...
  return _.uniq(_.flatten(expandedPaths));
},

expandPathWithExtensions: function expandPathWithExtensions(path, extensions) {
  var realPath = fs.realpathSync(path);
  var stats = fs.statSync(realPath);
  if (stats.isDirectory()) {
    return this.expandDirectoryWithExtensions(realPath, extensions);
  } else {
    return [realPath];
  }
},

expandDirectoryWithExtensions: function expandDirectoryWithExtensions(realPath, extensions) {
  var pattern = realPath + '/**/*.';
...
```

#### <a name="apidoc.element.cucumber.Cli.PathExpander.expandPathWithExtensions"></a>[function <span class="apidocSignatureSpan">cucumber.Cli.PathExpander.</span>expandPathWithExtensions (path, extensions)](#apidoc.element.cucumber.Cli.PathExpander.expandPathWithExtensions)
- description and source-code
```javascript
function expandPathWithExtensions(path, extensions) {
  var realPath = fs.realpathSync(path);
  var stats = fs.statSync(realPath);
  if (stats.isDirectory()) {
    return this.expandDirectoryWithExtensions(realPath, extensions);
  } else {
    return [realPath];
  }
}
```
- example usage
```shell
...
var fs = require('fs');
var glob = require('glob');
var _ = require('lodash');

var PathExpander = {
expandPathsWithExtensions: function expandPathsWithExtensions(paths, extensions) {
  var expandedPaths = paths.map(function (path) {
    return PathExpander.expandPathWithExtensions(path, extensions);
  });
  return _.uniq(_.flatten(expandedPaths));
},

expandPathWithExtensions: function expandPathWithExtensions(path, extensions) {
  var realPath = fs.realpathSync(path);
  var stats = fs.statSync(realPath);
...
```

#### <a name="apidoc.element.cucumber.Cli.PathExpander.expandPathsWithExtensions"></a>[function <span class="apidocSignatureSpan">cucumber.Cli.PathExpander.</span>expandPathsWithExtensions (paths, extensions)](#apidoc.element.cucumber.Cli.PathExpander.expandPathsWithExtensions)
- description and source-code
```javascript
function expandPathsWithExtensions(paths, extensions) {
  var expandedPaths = paths.map(function (path) {
    return PathExpander.expandPathWithExtensions(path, extensions);
  });
  return _.uniq(_.flatten(expandedPaths));
}
```
- example usage
```shell
...
  expandPaths: function expandPaths(paths) {
    var Cucumber     = require('../../cucumber');
    var PathExpander = Cucumber.Cli.PathExpander;

    paths = paths.map(function(path) {
      return path.replace(/(:\d+)*$/g, ''); // Strip line numbers
    });
    var expandedPaths = PathExpander.expandPathsWithExtensions(paths, ['feature']);
    return expandedPaths;
  }
};
module.exports = FeaturePathExpander;

},{"../../cucumber":"cucumber"}],19:[function(require,module,exports){
function FeatureSourceLoader(featureFilePaths) {
...
```



# <a name="apidoc.module.cucumber.Cli.ProfilesLoader"></a>[module cucumber.Cli.ProfilesLoader](#apidoc.module.cucumber.Cli.ProfilesLoader)

#### <a name="apidoc.element.cucumber.Cli.ProfilesLoader.getArgs"></a>[function <span class="apidocSignatureSpan">cucumber.Cli.ProfilesLoader.</span>getArgs (profiles)](#apidoc.element.cucumber.Cli.ProfilesLoader.getArgs)
- description and source-code
```javascript
function getArgs(profiles) {
  var definitions = getDefinitions();
  if (profiles.length === 0 && definitions['default']) {
    profiles = ['default'];
  }
  var profilesArgs = profiles.map(function (profile){
    if (!definitions[profile]){
      throw new Error('Undefined profile: ' + profile);
    }
    return definitions[profile].split(/\s/);
  });
  return _.flatten(profilesArgs);
}
```
- example usage
```shell
...

  return program;
}

function getConfiguration() {
  var program = getProgram();
  program.parse(argv);
  var profileArgs = Cucumber.Cli.ProfilesLoader.getArgs(program.profile);
  if (profileArgs.length > 0) {
    var fullArgs = argv.slice(0, 2).concat(profileArgs).concat(argv.slice(2));
    program = getProgram();
    program.parse(fullArgs);
  }
  var configuration = Cucumber.Cli.Configuration(program.opts(), program.args);
  return configuration;
...
```



# <a name="apidoc.module.cucumber.Cli.SupportCodePathExpander"></a>[module cucumber.Cli.SupportCodePathExpander](#apidoc.module.cucumber.Cli.SupportCodePathExpander)

#### <a name="apidoc.element.cucumber.Cli.SupportCodePathExpander.expandPaths"></a>[function <span class="apidocSignatureSpan">cucumber.Cli.SupportCodePathExpander.</span>expandPaths (paths, extensions)](#apidoc.element.cucumber.Cli.SupportCodePathExpander.expandPaths)
- description and source-code
```javascript
function expandPaths(paths, extensions) {
  var Cucumber = require('../../cucumber');
  var PathExpander = Cucumber.Cli.PathExpander;

  var expandedPaths = PathExpander.expandPathsWithExtensions(paths, extensions);
  return expandedPaths;
}
```
- example usage
```shell
...
      unexpandedFeaturePaths = unexpandedFeaturePaths.concat(content.split('\n'));
    } else {
      unexpandedFeaturePaths.push(arg);
    }
  });
}

var expandedFeaturePaths = Cucumber.Cli.FeaturePathExpander.expandPaths(unexpandedFeaturePaths);


function getCompilerExtensions() {
  return options.compiler.map(function(compiler) {
    return compiler.split(':')[0];
  });
}
...
```



# <a name="apidoc.module.cucumber.Debug"></a>[module cucumber.Debug](#apidoc.module.cucumber.Debug)

#### <a name="apidoc.element.cucumber.Debug.SimpleAstListener"></a>[function <span class="apidocSignatureSpan">cucumber.Debug.</span>SimpleAstListener (options)](#apidoc.element.cucumber.Debug.SimpleAstListener)
- description and source-code
```javascript
function SimpleAstListener(options) {
  var logs                        = '';
  var failed                      = false;
  var beforeEachScenarioCallbacks = [];
  var currentFeature, currentStep;

  if (!options)
    options = {};

  function indent(text, indentation) {
    var indented;
    text.split('\n').forEach(function (line) {
      var prefix = new Array(indentation + 1).join('  ');
      line = prefix + line;
      indented = (typeof(indented) === 'undefined' ? line : indented + '\n' + line);
    });
    return indented;
  }

  function log(message, indentation) {
    if (indentation)
      message = indent(message, indentation);
    logs = logs + message + '\n';
    if (options.stream)
      options.stream.write(message);
    if (typeof(options.logToFunction) === 'function')
      options.logToFunction (message);
  }

  var self = {
    hear: function hear(event, callback) {
      switch(event.getName()) {
      case 'BeforeFeature':
        self.hearBeforeFeature(event.getPayloadItem('feature'), callback);
        break;
      case 'BeforeScenario':
        self.hearBeforeScenario(event.getPayloadItem('scenario'), callback);
        break;
      case 'BeforeStep':
        self.hearBeforeStep(event.getPayloadItem('step'), callback);
        break;
      case 'StepResult':
        self.hearStepResult(event.getPayloadItem('stepResult'), callback);
        break;
      default:
        callback();
      }
    },

    hearBeforeFeature: function hearBeforeFeature(feature, callback) {
      currentFeature = feature;
      log('Feature: ' + feature.getName());
      var description = feature.getDescription();
      if (description !== '')
        log(description, 1);
      callback();
    },

    hearBeforeScenario: function hearBeforeScenario(scenario, callback) {
      beforeEachScenarioCallbacks.forEach(function (func) {
        func();
      });
      log('');
      log(scenario.getName(), 1);
      callback();
    },

    hearBeforeStep: function hearBeforeStep(step, callback) {
      currentStep = step;
      currentStep =
      callback();
    },

    hearStepResult: function hearStepResult(stepResult, callback) {
      log(currentStep.getKeyword() + (currentStep.getName() || ''), 2);
      if (currentStep.hasDocString()) {
        log('"""', 3);
        log(currentStep.getDocString().getContents(), 3);
        log('"""', 3);
      }
      callback();
    },

    getLogs: function getLogs() {
      return logs;
    },

    featuresPassed: function featuresPassed() {
      return !failed;
    },

    beforeEachScenarioDo: function beforeEachScenarioDo(func) {
      beforeEachScenarioCallbacks.push(func);
    }
  };
  return self;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cucumber.Debug.TODO"></a>[function <span class="apidocSignatureSpan">cucumber.Debug.</span>TODO (description)](#apidoc.element.cucumber.Debug.TODO)
- description and source-code
```javascript
function TODO(description) {
  return function () { throw(new Error('IMPLEMENT ME: ' + description)); };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cucumber.Debug.isMessageLeveltoBeDisplayed"></a>[function <span class="apidocSignatureSpan">cucumber.Debug.</span>isMessageLeveltoBeDisplayed (level)](#apidoc.element.cucumber.Debug.isMessageLeveltoBeDisplayed)
- description and source-code
```javascript
function isMessageLeveltoBeDisplayed(level) {
  if (process.env) {
    level = level || 3; // default level
    return (level <= process.env.DEBUG_LEVEL);
  } else {
    return false;
  }
}
```
- example usage
```shell
...
(function (process){
var Debug = {
TODO: function TODO(description) {
  return function () { throw(new Error('IMPLEMENT ME: ' + description)); };
},

warn: function warn(string, caption, level) {
  if (Debug.isMessageLeveltoBeDisplayed(level))
    process.stdout.write(Debug.warningString(string, caption));
},

notice: function notice(string, caption, level) {
  if (Debug.isMessageLeveltoBeDisplayed(level))
    process.stdout.write(Debug.noticeString(string, caption));
},
...
```

#### <a name="apidoc.element.cucumber.Debug.notice"></a>[function <span class="apidocSignatureSpan">cucumber.Debug.</span>notice (string, caption, level)](#apidoc.element.cucumber.Debug.notice)
- description and source-code
```javascript
function notice(string, caption, level) {
  if (Debug.isMessageLeveltoBeDisplayed(level))
    process.stdout.write(Debug.noticeString(string, caption));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cucumber.Debug.noticeString"></a>[function <span class="apidocSignatureSpan">cucumber.Debug.</span>noticeString (string, caption)](#apidoc.element.cucumber.Debug.noticeString)
- description and source-code
```javascript
function noticeString(string, caption) {
  caption = caption || 'debug-notice';
  return '\x1B[30;46m' + caption + ':\x1B[0m \x1B[36m' + string + '\x1B[0m';
}
```
- example usage
```shell
...
warn: function warn(string, caption, level) {
  if (Debug.isMessageLeveltoBeDisplayed(level))
    process.stdout.write(Debug.warningString(string, caption));
},

notice: function notice(string, caption, level) {
  if (Debug.isMessageLeveltoBeDisplayed(level))
    process.stdout.write(Debug.noticeString(string, caption));
},

warningString: function warningString(string, caption) {
  caption = caption || 'debug-warning';
  return '\x1B[30;43m' + caption + ':\x1B[0m[33m' + string + '\x1B[0m';
},
...
```

#### <a name="apidoc.element.cucumber.Debug.prefix"></a>[function <span class="apidocSignatureSpan">cucumber.Debug.</span>prefix ()](#apidoc.element.cucumber.Debug.prefix)
- description and source-code
```javascript
function prefix() {
  return ;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cucumber.Debug.warn"></a>[function <span class="apidocSignatureSpan">cucumber.Debug.</span>warn (string, caption, level)](#apidoc.element.cucumber.Debug.warn)
- description and source-code
```javascript
function warn(string, caption, level) {
  if (Debug.isMessageLeveltoBeDisplayed(level))
    process.stdout.write(Debug.warningString(string, caption));
}
```
- example usage
```shell
...

function buildAfterEventName(eventName) {
  return Cucumber.Events.getAfterEvent(eventName);
}

payload.getPayloadItem = function getPayloadItem() {
  if (!deprecatedMessageDisplayed) {
    console.warn(
      'cucumber event handlers attached via registerHandler are now passed the' +
      ' associated object instead of an event' +
      '\ngetPayloadItem will be removed in the next major release'
    );
    deprecatedMessageDisplayed = true;
  }
  return payload;
...
```

#### <a name="apidoc.element.cucumber.Debug.warningString"></a>[function <span class="apidocSignatureSpan">cucumber.Debug.</span>warningString (string, caption)](#apidoc.element.cucumber.Debug.warningString)
- description and source-code
```javascript
function warningString(string, caption) {
  caption = caption || 'debug-warning';
  return '\x1B[30;43m' + caption + ':\x1B[0m[33m' + string + '\x1B[0m';
}
```
- example usage
```shell
...
var Debug = {
TODO: function TODO(description) {
  return function () { throw(new Error('IMPLEMENT ME: ' + description)); };
},

warn: function warn(string, caption, level) {
  if (Debug.isMessageLeveltoBeDisplayed(level))
    process.stdout.write(Debug.warningString(string, caption));
},

notice: function notice(string, caption, level) {
  if (Debug.isMessageLeveltoBeDisplayed(level))
    process.stdout.write(Debug.noticeString(string, caption));
},
...
```



# <a name="apidoc.module.cucumber.Events"></a>[module cucumber.Events](#apidoc.module.cucumber.Events)

#### <a name="apidoc.element.cucumber.Events.getAfterEvent"></a>[function <span class="apidocSignatureSpan">cucumber.Events.</span>getAfterEvent (name)](#apidoc.element.cucumber.Events.getAfterEvent)
- description and source-code
```javascript
function getAfterEvent(name) {
  return AFTER_EVENT_NAME_PREFIX + name;
}
```
- example usage
```shell
...
var Cucumber = require('../../cucumber');

function buildBeforeEventName(eventName) {
  return Cucumber.Events.getBeforeEvent(eventName);
}

function buildAfterEventName(eventName) {
  return Cucumber.Events.getAfterEvent(eventName);
}

payload.getPayloadItem = function getPayloadItem() {
  if (!deprecatedMessageDisplayed) {
    console.warn(
      'cucumber event handlers attached via registerHandler are now passed the' +
      ' associated object instead of an event' +
...
```

#### <a name="apidoc.element.cucumber.Events.getBeforeEvent"></a>[function <span class="apidocSignatureSpan">cucumber.Events.</span>getBeforeEvent (name)](#apidoc.element.cucumber.Events.getBeforeEvent)
- description and source-code
```javascript
function getBeforeEvent(name) {
  return BEFORE_EVENT_NAME_PREFIX + name;
}
```
- example usage
```shell
...
},{}],38:[function(require,module,exports){
var deprecatedMessageDisplayed = false;

function Event(name, payload) {
var Cucumber = require('../../cucumber');

function buildBeforeEventName(eventName) {
  return Cucumber.Events.getBeforeEvent(eventName);
}

function buildAfterEventName(eventName) {
  return Cucumber.Events.getAfterEvent(eventName);
}

payload.getPayloadItem = function getPayloadItem() {
...
```



# <a name="apidoc.module.cucumber.Listener"></a>[module cucumber.Listener](#apidoc.module.cucumber.Listener)

#### <a name="apidoc.element.cucumber.Listener.Listener"></a>[function <span class="apidocSignatureSpan">cucumber.</span>Listener (options)](#apidoc.element.cucumber.Listener.Listener)
- description and source-code
```javascript
function Listener(options) {
  var Cucumber     = require('../cucumber');

  if (!options) {
    options = {};
  }

  var self = {
    hear: function hear(event, defaultTimeout, callback) {
      if (self.hasHandlerForEvent(event)) {
        var handler = self.getHandlerForEvent(event);
        var timeout = self.getTimeout() || defaultTimeout;
        Cucumber.Util.run(handler, null, [event.getPayload()], timeout, function(error) {
          error = self.prependLocationToError(error);
          callback(error);
        });
      } else {
        callback();
      }
    },

    hasHandlerForEvent: function hasHandlerForEvent(event) {
      var handlerName = self.buildHandlerNameForEvent(event);
      return self[handlerName] !== undefined;
    },

    buildHandlerNameForEvent: function buildHandlerNameForEvent(event) {
      return self.buildHandlerName(event.getName());
    },

    getHandlerForEvent: function getHandlerForEvent(event) {
      var eventHandlerName = self.buildHandlerNameForEvent(event);
      return self[eventHandlerName];
    },

    buildHandlerName: function buildHandler(shortName) {
      return Listener.EVENT_HANDLER_NAME_PREFIX + shortName + Listener.EVENT_HANDLER_NAME_SUFFIX;
    },

    setHandlerForEvent: function setHandlerForEvent(shortname, handler) {
      var eventName = self.buildHandlerName(shortname);
      self[eventName] = handler;
    },

    getTimeout: function() {
      return options.timeout;
    },

    getUri: function() {
      return options.uri;
    },

    getLine: function() {
      return options.line;
    },

    prependLocationToError: function(error) {
      if (error && self.getUri()) {
        var ref = path.relative(process.cwd(), self.getUri()) + ':' + self.getLine() + ' ';
        if (error instanceof Error) {
          error.message = ref + error.message;
        } else {
          error = ref + error;
        }
      }
      return error;
    },
  };
  return self;
}
```
- example usage
```shell
...
var Cucumber = require('../../cucumber');

if (!options)
  options = {};

var logs = '';

var self = Cucumber.Listener(options);

self.log = function log(string) {
  logs += string;
  if (options.stream)
    options.stream.write(string);
  if (typeof(options.logToFunction) === 'function')
    options.logToFunction(string);
...
```

#### <a name="apidoc.element.cucumber.Listener.Formatter"></a>[function <span class="apidocSignatureSpan">cucumber.Listener.</span>Formatter (options)](#apidoc.element.cucumber.Listener.Formatter)
- description and source-code
```javascript
function Formatter(options) {
  var Cucumber = require('../../cucumber');

  if (!options)
    options = {};

  var logs = '';

  var self = Cucumber.Listener(options);

  self.log = function log(string) {
    logs += string;
    if (options.stream)
      options.stream.write(string);
    if (typeof(options.logToFunction) === 'function')
      options.logToFunction(string);
  };

  self.finish = function finish(callback) {
    if (options.stream && options.stream !== process.stdout)
      options.stream.end(callback);
    else
      callback();
  };

  self.getLogs = function getLogs() {
    return logs;
  };

  return self;
}
```
- example usage
```shell
...

},{"../../cucumber":"cucumber","_process":173}],29:[function(require,module,exports){
(function (Buffer){
/* jshint -W106 */
function JsonFormatter(options) {
var Cucumber = require('../../cucumber');

var self = Cucumber.Listener.Formatter(options);

var features = [];
var currentFeature;
var currentScenario;

var formatTag = function formatTag(tag) {
  return {
...
```

#### <a name="apidoc.element.cucumber.Listener.JsonFormatter"></a>[function <span class="apidocSignatureSpan">cucumber.Listener.</span>JsonFormatter (options)](#apidoc.element.cucumber.Listener.JsonFormatter)
- description and source-code
```javascript
function JsonFormatter(options) {
  var Cucumber = require('../../cucumber');

  var self = Cucumber.Listener.Formatter(options);

  var features = [];
  var currentFeature;
  var currentScenario;

  var formatTag = function formatTag(tag) {
    return {
      name: tag.getName(),
      line: tag.getLine()
    };
  };

  self.handleBeforeFeatureEvent = function handleBeforeFeatureEvent(feature) {
    currentFeature = {
      description: feature.getDescription(),
      elements: [],
      id: feature.getName().replace(/ /g, '-').toLowerCase(),
      keyword: feature.getKeyword(),
      line: feature.getLine(),
      name: feature.getName(),
      tags: feature.getTags().map(formatTag),
      uri: feature.getUri()
    };
    features.push(currentFeature);
  };

  self.handleBeforeScenarioEvent = function handleBeforeScenarioEvent(scenario) {
    currentScenario = {
      description: scenario.getDescription(),
      id: currentFeature.id + ';' + scenario.getName().replace(/ /g, '-').toLowerCase(),
      keyword: 'Scenario',
      line: scenario.getLine(),
      name: scenario.getName(),
      steps: [],
      tags: scenario.getTags().map(formatTag),
      type: 'scenario'
    };
    currentFeature.elements.push(currentScenario);
  };

  self.handleStepResultEvent = function handleStepResultEvent(stepResult) {
    var step = stepResult.getStep();
    var status = stepResult.getStatus();

    var currentStep = {
      arguments: step.getArguments().map(function(arg) {
        switch (arg.getType()) {
          case 'DataTable':
            return {
              rows: arg.raw().map(function (row) {
                return { cells: row };
              })
            };
          case 'DocString':
            return {
              line: arg.getLine(),
              content: arg.getContent(),
              contentType: arg.getContentType()
            };
          default:
            throw new Error('Unknown argument type:' + arg.getType());
        }
      }),
      keyword: step.getKeyword(),
      name: step.getName(),
      result: {
        status: status
      }
    };

    if (step.isHidden()) {
      currentStep.hidden = true;
    } else {
      currentStep.line = step.getLine();
    }

    if (status === Cucumber.Status.PASSED || status === Cucumber.Status.FAILED) {
      currentStep.result.duration = stepResult.getDuration();
    }

    if (stepResult.hasAttachments()) {
      currentStep.embeddings = stepResult.getAttachments().map(function (attachment) {
        var data = attachment.getData();
        if (!(data instanceof Buffer)) {
          data = new Buffer(data);
        }
        return {
          data: data.toString('base64'),
          mime_type: attachment.getMimeType(),
        };
      });
    }

    if (status === Cucumber.Status.FAILED) {
      var failureMessage = stepResult.getFailureException();
      if (failureMessage) {
        currentStep.result.error_message = (failureMessage.stack || failureMessage);
      }
    }

    var stepDefinition = stepResult.getStepDefinition();
    if (stepDefinition) {
      var location = stepDefinition.getUri() + ':' + stepDefinition.getLine();
      currentStep.match = {location: location};
    }

    currentScenario.steps.push(currentStep);
  };

  self.handleAfterFeaturesEvent = function handleAfterFeaturesEvent(event, callback) {
    self.log(JSON.stringify(features, null, 2));
    self.finish(callback);
  };

  return self;
}
```
- example usage
```shell
...
  snippetSyntax: snippetSyntax,
  stream: format.stream,
  useColors: options.colors
};

switch(format.type) {
  case 'json':
    return Cucumber.Listener.JsonFormatter(formatterOptions);
  case 'progress':
    return Cucumber.Listener.ProgressFormatter(formatterOptions);
  case 'pretty':
    return Cucumber.Listener.PrettyFormatter(formatterOptions);
  case 'snippets':
    return Cucumber.Listener.SnippetsFormatter(formatterOptions);
  case 'summary':
...
```

#### <a name="apidoc.element.cucumber.Listener.PrettyFormatter"></a>[function <span class="apidocSignatureSpan">cucumber.Listener.</span>PrettyFormatter (options)](#apidoc.element.cucumber.Listener.PrettyFormatter)
- description and source-code
```javascript
function PrettyFormatter(options) {
  var Cucumber         = require('../../cucumber');
  var figures          = require('figures');

  var colors           = Cucumber.Util.Colors(options.useColors);
  var self             = Cucumber.Listener.Formatter(options);
  var summaryFormatter = Cucumber.Listener.SummaryFormatter({
    snippetSyntax: options.snippetSyntax,
    useColors: options.useColors
  });

  var parentHear = self.hear;
  self.hear = function hear(event, defaultTimeout, callback) {
    summaryFormatter.hear(event, defaultTimeout, function () {
      parentHear(event, defaultTimeout, callback);
    });
  };

  var characters = {};
  characters[Cucumber.Status.AMBIGUOUS] = figures.cross;
  characters[Cucumber.Status.FAILED] = figures.cross;
  characters[Cucumber.Status.PASSED] = figures.tick;
  characters[Cucumber.Status.PENDING] = '?';
  characters[Cucumber.Status.SKIPPED] = '-';
  characters[Cucumber.Status.UNDEFINED] = '?';

  self.handleBeforeFeatureEvent = function handleBeforeFeatureEvent(feature) {
    var source = '';

    var tagsSource = self.formatTags(feature.getTags());
    if (tagsSource) {
      source = tagsSource + '\n';
    }

    var identifier = feature.getKeyword() + ': ' + feature.getName();
    source += identifier;

    var description = feature.getDescription();
    if (description) {
      source += '\n\n' + self.indent(description, 1);
    }

    source += '\n\n';

    self.log(source);
  };

  self.handleBeforeScenarioEvent = function handleBeforeScenarioEvent(scenario) {
    var source = '';

    var tagsSource = self.formatTags(scenario.getTags());
    if (tagsSource) {
      source = tagsSource + '\n';
    }

    var identifier = scenario.getKeyword() + ': ' + scenario.getName();
    source += identifier;

    self.logIndented(source, 1);
    self.log('\n');
  };

  self.handleAfterScenarioEvent = function handleAfterScenarioEvent() {
    self.log('\n');
  };

  self.applyColor = function applyColor (stepResult, source) {
    var status = stepResult.getStatus();
    return colors[status](source);
  };

  self.getSymbol = function getSymbol (stepResult) {
    var status = stepResult.getStatus();
    return characters[status];
  };

  self.handleStepResultEvent = function handleStepResultEvent(stepResult) {
    var step = stepResult.getStep();
    if (!step.isHidden()) {
      self.logStepResult(step, stepResult);
    }
  };

  self.formatTags = function formatTags(tags) {
    if (tags.length === 0) {
      return '';
    }

    var tagNames = tags.map(function (tag) {
      return tag.getName();
    });

    return colors.tag(tagNames.join(' '));
  };

  self.logStepResult = function logStepResult(step, stepResult) {
    var symbol = self.getSymbol(stepResult);
    var identifier = symbol + ' ' + step.getKeyword() + (step.getName() || '');
    identifier = self.applyColor(stepResult, identifier);
    self.logIndented(identifier, 1);
    self.log('\n');

    step.getArguments().forEach(function (arg) {
      var str;
      switch(arg.getType()) {
        case 'DataTable':
          str = self.formatDataTable(stepResult, arg);
          break;
        case 'DocString':
          str = self.formatDocString(stepResult, arg);
          break;
        default:
          throw new Error('Unknown argument type: ' + arg.getType());
      }
      self.logIndented(str, 3);
    });
  };

  self.handleAfterFeaturesEvent = function handleAfterFeaturesEvent(features, callback) {
    var summaryLogs = summaryFormatter.getLogs();
    self.log(summaryLogs);
    self.finish(callback);
  };

  self.formatDataTable = function formatDataTable(stepResult, dataTable) {
    var rows = dataTable.raw().map(function (row) {
      return row.map(function (cell) {
        return cell
          .replace(/\\/g, '\\\\')
          .replace(/\n/g, '\\n');
      });
    });
    var columnWidths = self._determineColumnWidthsFromRows(rows);
    var source = '';
    rows.forEach(function (row) {
      source += '|';
      row.forEach(function (cell, columnIndex) {
        var columnWidth = columnWidths[columnIndex]; ...
```
- example usage
```shell
...

        switch(format.type) {
case 'json':
  return Cucumber.Listener.JsonFormatter(formatterOptions);
case 'progress':
  return Cucumber.Listener.ProgressFormatter(formatterOptions);
case 'pretty':
  return Cucumber.Listener.PrettyFormatter(formatterOptions);
case 'snippets':
  return Cucumber.Listener.SnippetsFormatter(formatterOptions);
case 'summary':
  return Cucumber.Listener.SummaryFormatter(formatterOptions);
case 'rerun':
  return Cucumber.Listener.RerunFormatter(formatterOptions);
default:
...
```

#### <a name="apidoc.element.cucumber.Listener.ProgressFormatter"></a>[function <span class="apidocSignatureSpan">cucumber.Listener.</span>ProgressFormatter (options)](#apidoc.element.cucumber.Listener.ProgressFormatter)
- description and source-code
```javascript
function ProgressFormatter(options) {
  var Cucumber = require('../../cucumber');

  if (!options)
    options = {};

  var colors = Cucumber.Util.Colors(options.useColors);

  var self             = Cucumber.Listener.Formatter(options);
  var summaryFormatter = Cucumber.Listener.SummaryFormatter({
    snippetSyntax: options.snippetSyntax,
    useColors: options.useColors
  });

  var parentHear = self.hear;
  self.hear = function hear(event, defaultTimeout, callback) {
    summaryFormatter.hear(event, defaultTimeout, function () {
      parentHear(event, defaultTimeout, callback);
    });
  };

  var characters = {};
  characters[Cucumber.Status.AMBIGUOUS] = 'A';
  characters[Cucumber.Status.FAILED] = 'F';
  characters[Cucumber.Status.PASSED] = '.';
  characters[Cucumber.Status.PENDING] = 'P';
  characters[Cucumber.Status.SKIPPED] = '-';
  characters[Cucumber.Status.UNDEFINED] = 'U';

  self.handleStepResultEvent = function handleStepResult(stepResult) {
    var status = stepResult.getStatus();
    var step = stepResult.getStep();
    if (!step.isHidden() || status === Cucumber.Status.FAILED) {
      var character = colors[status](characters[status]);
      self.log(character);
    }
  };

  self.handleAfterFeaturesEvent = function handleAfterFeaturesEvent(features, callback) {
    var summaryLogs = summaryFormatter.getLogs();
    self.log('\n\n');
    self.log(summaryLogs);
    self.finish(callback);
  };

  return self;
}
```
- example usage
```shell
...
  useColors: options.colors
};

switch(format.type) {
  case 'json':
    return Cucumber.Listener.JsonFormatter(formatterOptions);
  case 'progress':
    return Cucumber.Listener.ProgressFormatter(formatterOptions);
  case 'pretty':
    return Cucumber.Listener.PrettyFormatter(formatterOptions);
  case 'snippets':
    return Cucumber.Listener.SnippetsFormatter(formatterOptions);
  case 'summary':
    return Cucumber.Listener.SummaryFormatter(formatterOptions);
  case 'rerun':
...
```

#### <a name="apidoc.element.cucumber.Listener.RerunFormatter"></a>[function <span class="apidocSignatureSpan">cucumber.Listener.</span>RerunFormatter (options)](#apidoc.element.cucumber.Listener.RerunFormatter)
- description and source-code
```javascript
function RerunFormatter(options) {
  var Cucumber = require('../../cucumber');
  var path = require('path');
  var _ = require('lodash');

  var self = Cucumber.Listener.Formatter(options);
  var failures = {};


  self.handleScenarioResultEvent = function handleScenarioResultEvent(scenarioResult) {
    if (scenarioResult.getStatus() !== Cucumber.Status.PASSED) {
      var scenario = scenarioResult.getScenario();
      var uri = path.relative(process.cwd(), scenario.getUri());
      var line = scenario.getLine();
      if (!failures[uri]) {
        failures[uri] = [];
      }
      failures[uri].push(line);
    }
  };

  self.handleAfterFeaturesEvent = function handleAfterFeaturesEvent(features, callback) {
    var text = _.map(failures, function(lines, uri) {
      return uri + ':' + lines.join(':');
    }).join('\n');
    self.log(text);
    self.finish(callback);
  };

  return self;
}
```
- example usage
```shell
...
      case 'pretty':
        return Cucumber.Listener.PrettyFormatter(formatterOptions);
      case 'snippets':
        return Cucumber.Listener.SnippetsFormatter(formatterOptions);
      case 'summary':
        return Cucumber.Listener.SummaryFormatter(formatterOptions);
      case 'rerun':
        return Cucumber.Listener.RerunFormatter(formatterOptions);
      default:
        throw new Error('Unknown formatter name "' + format.type + '".');
    }
  });
  return formatters;
},
...
```

#### <a name="apidoc.element.cucumber.Listener.SnippetsFormatter"></a>[function <span class="apidocSignatureSpan">cucumber.Listener.</span>SnippetsFormatter (options)](#apidoc.element.cucumber.Listener.SnippetsFormatter)
- description and source-code
```javascript
function SnippetsFormatter(options) {
  var Cucumber = require('../../cucumber');

  var self = Cucumber.Listener.Formatter(options);
  var snippets = [];

  self.handleStepResultEvent = function handleStepResult(stepResult) {
    var status = stepResult.getStatus();
    if (status === Cucumber.Status.UNDEFINED) {
      var step = stepResult.getStep();
      var snippetBuilder = Cucumber.SupportCode.StepDefinitionSnippetBuilder(step, options.snippetSyntax);
      snippets.push(snippetBuilder.buildSnippet());
    }
  };

  self.handleFeaturesResultEvent = function handleFeaturesResultEvent(featuresResult, callback) {
    self.log(snippets.join('\n\n'));
    self.finish(callback);
  };

  return self;
}
```
- example usage
```shell
...
  case 'json':
    return Cucumber.Listener.JsonFormatter(formatterOptions);
  case 'progress':
    return Cucumber.Listener.ProgressFormatter(formatterOptions);
  case 'pretty':
    return Cucumber.Listener.PrettyFormatter(formatterOptions);
  case 'snippets':
    return Cucumber.Listener.SnippetsFormatter(formatterOptions);
  case 'summary':
    return Cucumber.Listener.SummaryFormatter(formatterOptions);
  case 'rerun':
    return Cucumber.Listener.RerunFormatter(formatterOptions);
  default:
    throw new Error('Unknown formatter name "' + format.type + '".');
}
...
```

#### <a name="apidoc.element.cucumber.Listener.SummaryFormatter"></a>[function <span class="apidocSignatureSpan">cucumber.Listener.</span>SummaryFormatter (options)](#apidoc.element.cucumber.Listener.SummaryFormatter)
- description and source-code
```javascript
function SummaryFormatter(options) {
  var Cucumber = require('../../cucumber');
  var Duration = require('duration');
  var Table    = require('cli-table');
  var path     = require('path');
  var _        = require('lodash');

  var failures = [];
  var warnings = [];
  var colors = Cucumber.Util.Colors(options.useColors);
  var statusReportOrder = [
    Cucumber.Status.FAILED,
    Cucumber.Status.AMBIGUOUS,
    Cucumber.Status.UNDEFINED,
    Cucumber.Status.PENDING,
    Cucumber.Status.SKIPPED,
    Cucumber.Status.PASSED
  ];

  function indent(text, level) {
    var indented;
    text.split('\n').forEach(function (line) {
      var prefix = new Array(level + 1).join(' ');
      line = (prefix + line).replace(/\s+$/, '');
      indented = (typeof(indented) === 'undefined' ? line : indented + '\n' + line);
    });
    return indented;
  }

  var self = Cucumber.Listener.Formatter(options);

  self.handleStepResultEvent = function handleStepResult(stepResult) {
    var status = stepResult.getStatus();
    switch (status) {
      case Cucumber.Status.AMBIGUOUS:
        self.storeAmbiguousStepResult(stepResult);
        break;
      case Cucumber.Status.FAILED:
        self.storeFailedStepResult(stepResult);
        break;
      case Cucumber.Status.UNDEFINED:
        self.storeUndefinedStepResult(stepResult);
        break;
      case Cucumber.Status.PENDING:
        self.storePendingStepResult(stepResult);
        break;
    }
  };

  self.handleFeaturesResultEvent = function handleFeaturesResultEvent(featuresResult, callback) {
    self.logSummary(featuresResult);
    self.finish(callback);
  };

  self.storeAmbiguousStepResult = function storeAmbiguousStepResult(stepResult) {
    var stepDefinitions = stepResult.getAmbiguousStepDefinitions();

    var table = new Table({
      chars: {
        'bottom': '', 'bottom-left': '', 'bottom-mid': '', 'bottom-right': '',
        'left': '', 'left-mid': '',
        'mid': '', 'mid-mid': '',
        'middle': ' - ',
        'right': '', 'right-mid': '',
        'top': '' , 'top-left': '', 'top-mid': '', 'top-right': ''
      },
      style: {
        border: [], 'padding-left': 0, 'padding-right': 0
      }
    });
    table.push.apply(table, stepDefinitions.map(function (stepDefinition) {
      var pattern = stepDefinition.getPattern().toString();
      var relativeUri = path.relative(process.cwd(), stepDefinition.getUri());
      var line = stepDefinition.getLine();
      return [pattern, relativeUri + ':' + line];
    }));
    failures.push({
      stepResult: stepResult,
      message: 'Multiple step definitions match:' + '\n' + indent(table.toString(), 2)
    });
  };

  self.storeFailedStepResult = function storeFailedStepResult(stepResult) {
    var failureException = stepResult.getFailureException();
    failures.push({
      stepResult: stepResult,
      message: failureException.stack || failureException
    });
  };

  self.storeUndefinedStepResult = function storeUndefinedStepResult(stepResult) {
    var step = stepResult.getStep();
    var snippetBuilder = Cucumber.SupportCode.StepDefinitionSnippetBuilder(step, options.snippetSyntax);
    var snippet = snippetBuilder.buildSnippet();
    warnings.push({
      stepResult: stepResult,
      message: 'Undefined. Implement with the following snippet:' + '\n\n' + indent(snippet, 2)
    });
  };

  self.storePendingStepResult = function storePendingStepResult(stepResult) {
    var message = 'Pending';
    var pendingReason = stepResult.getPendingReason();
    if (pendingReason) {
      message += ': ' + pendingReason;
    }
    warnings.push({
      stepResult: stepResult,
      message: message
    });
  };

  self.logSummary = function logSummary(featuresResult) {
    if (failures.length > 0) {
      self.logFailures();
    }

    if (warnings.length > 0) {
      self.logWarnings();
    }

    self.logScenariosSummary(featuresResult);
    self.logStepsSummary(featuresResult);
    self.logDuration(featuresResult);
  };

  self.logFailures = function logFailures() {
    self.log('Failures:\n\n');
    failures.forEach(func ...
```
- example usage
```shell
...
    case 'progress':
      return Cucumber.Listener.ProgressFormatter(formatterOptions);
    case 'pretty':
      return Cucumber.Listener.PrettyFormatter(formatterOptions);
    case 'snippets':
      return Cucumber.Listener.SnippetsFormatter(formatterOptions);
    case 'summary':
      return Cucumber.Listener.SummaryFormatter(formatterOptions);
    case 'rerun':
      return Cucumber.Listener.RerunFormatter(formatterOptions);
    default:
      throw new Error('Unknown formatter name "' + format.type + '".');
  }
});
return formatters;
...
```



# <a name="apidoc.module.cucumber.Runtime"></a>[module cucumber.Runtime](#apidoc.module.cucumber.Runtime)

#### <a name="apidoc.element.cucumber.Runtime.Runtime"></a>[function <span class="apidocSignatureSpan">cucumber.</span>Runtime (configuration)](#apidoc.element.cucumber.Runtime.Runtime)
- description and source-code
```javascript
function Runtime(configuration) {
  var Cucumber = require('../cucumber');

  var listeners = [];

  var self = {
    start: function start(callback) {
      if (typeof(callback) !== 'function')
        throw new Error(Runtime.START_MISSING_CALLBACK_ERROR);

      var features = self.getFeatures();
      var supportCodeLibrary = self.getSupportCodeLibrary();
      var options = {
        dryRun: configuration.isDryRunRequested && configuration.isDryRunRequested(),
        failFast: configuration.isFailFastRequested && configuration.isFailFastRequested(),
        strict: configuration.isStrictRequested && configuration.isStrictRequested(),
        worldParameters: configuration.getWorldParameters()
      };

      var featuresRunner = Runtime.FeaturesRunner(features, supportCodeLibrary, listeners, options);

      if (configuration.shouldFilterStackTraces())
        Runtime.StackTraceFilter.filter();

      featuresRunner.run(function (result) {
        Runtime.StackTraceFilter.unfilter();
        callback(result);
      });
    },

    attachListener: function attachListener(listener) {
      listeners.push(listener);
    },

    getFeatures: function getFeatures() {
      var featureSources = configuration.getFeatureSources();
      var astFilter      = configuration.getAstFilter();
      var parser         = Cucumber.Parser(featureSources, astFilter);
      var features       = parser.parse();
      return features;
    },

    getSupportCodeLibrary: function getSupportCodeLibrary() {
      var supportCodeLibrary = configuration.getSupportCodeLibrary();
      return supportCodeLibrary;
    }
  };
  return self;
}
```
- example usage
```shell
...
  var configuration = Cucumber.Cli.Configuration(program.opts(), program.args);
  return configuration;
}

var self = {
  run: function run(callback) {
    var configuration = getConfiguration();
    var runtime    = Cucumber.Runtime(configuration);
    var formatters = configuration.getFormatters();
    formatters.forEach(function (formatter) {
      runtime.attachListener(formatter);
    });
    runtime.start(callback);
  }
};
...
```

#### <a name="apidoc.element.cucumber.Runtime.Attachment"></a>[function <span class="apidocSignatureSpan">cucumber.Runtime.</span>Attachment (payload)](#apidoc.element.cucumber.Runtime.Attachment)
- description and source-code
```javascript
function Attachment(payload) {
  var self = {
    getMimeType:  function getMimeType()  { return payload.mimeType; },
    getData:      function getData()      { return payload.data; }
  };

  return self;
}
```
- example usage
```shell
...
  var attachments = [];

  function isStream(value) {
return value && typeof value === 'object' && typeof value.pipe === 'function';
  }

  function attachData(data, mimeType) {
var attachment = Cucumber.Runtime.Attachment({mimeType: mimeType, data: data});
attachments.push(attachment);
  }

  function attachStream(stream, mimeType, callback) {
var buffers = [];

stream.on('data', function (chunk) {
...
```

#### <a name="apidoc.element.cucumber.Runtime.Event"></a>[function <span class="apidocSignatureSpan">cucumber.Runtime.</span>Event (name, payload)](#apidoc.element.cucumber.Runtime.Event)
- description and source-code
```javascript
function Event(name, payload) {
  var Cucumber = require('../../cucumber');

  function buildBeforeEventName(eventName) {
    return Cucumber.Events.getBeforeEvent(eventName);
  }

  function buildAfterEventName(eventName) {
    return Cucumber.Events.getAfterEvent(eventName);
  }

  payload.getPayloadItem = function getPayloadItem() {
    if (!deprecatedMessageDisplayed) {
      console.warn(
        'cucumber event handlers attached via registerHandler are now passed the' +
        ' associated object instead of an event' +
        '\ngetPayloadItem will be removed in the next major release'
      );
      deprecatedMessageDisplayed = true;
    }
    return payload;
  };

  var self = {
    getName: function getName() {
      return name;
    },

    getPayload: function getPayload() {
      return payload;
    },

    replicateAsPreEvent: function replicateAsPreEvent() {
      var newName = buildBeforeEventName(name);
      return Cucumber.Runtime.Event(newName, payload);
    },

    replicateAsPostEvent: function replicateAsPostEvent() {
      var newName = buildAfterEventName(name);
      return Cucumber.Runtime.Event(newName, payload);
    },

    occurredOn: function occurredOn(eventName) {
      return eventName === name;
    },

    occurredAfter: function occurredAfter(eventName) {
      var afterEventName = buildAfterEventName(eventName);
      return afterEventName === name;
    }
  };

  return self;
}
```
- example usage
```shell
...

getPayload: function getPayload() {
  return payload;
},

replicateAsPreEvent: function replicateAsPreEvent() {
  var newName = buildBeforeEventName(name);
  return Cucumber.Runtime.Event(newName, payload);
},

replicateAsPostEvent: function replicateAsPostEvent() {
  var newName = buildAfterEventName(name);
  return Cucumber.Runtime.Event(newName, payload);
},
...
```

#### <a name="apidoc.element.cucumber.Runtime.EventBroadcaster"></a>[function <span class="apidocSignatureSpan">cucumber.Runtime.</span>EventBroadcaster (listeners, listenerDefaultTimeout)](#apidoc.element.cucumber.Runtime.EventBroadcaster)
- description and source-code
```javascript
function EventBroadcaster(listeners, listenerDefaultTimeout) {
  var Cucumber = require('../../cucumber');

  var self = {
    broadcastAroundEvent: function broadcastAroundEvent(event, userFunction, callback) {
      self.broadcastBeforeEvent(event, function() {
        userFunction(function() {
          var userFunctionCallbackArguments = arguments;
          self.broadcastAfterEvent(event, function() {
            callback.apply(null, userFunctionCallbackArguments);
          });
        });
      });
    },

    broadcastBeforeEvent: function broadcastBeforeEvent(event, callback) {
      var preEvent = event.replicateAsPreEvent();
      self.broadcastEvent(preEvent, callback);
    },

    broadcastAfterEvent: function broadcastAfterEvent(event, callback) {
      var postEvent = event.replicateAsPostEvent();
      self.broadcastEvent(postEvent, callback);
    },

    broadcastEvent: function broadcastEvent(event, callback) {
      Cucumber.Util.asyncForEach(listeners, function (listener, callback) {
        listener.hear(event, listenerDefaultTimeout, function(error) {
          if (error) {
            throw error;
          }
          callback();
        });
      }, callback);
    }
  };

  return self;
}
```
- example usage
```shell
...
module.exports = FeaturesResult;

},{"../../cucumber":"cucumber","lodash":165}],41:[function(require,module,exports){
function FeaturesRunner(features, supportCodeLibrary, listeners, options) {
var Cucumber = require('../../cucumber');

var allListeners = listeners.concat(supportCodeLibrary.getListeners());
var eventBroadcaster = Cucumber.Runtime.EventBroadcaster(allListeners, supportCodeLibrary.getDefaultTimeout());
var featuresResult = Cucumber.Runtime.FeaturesResult(options.strict);

var self = {
  run: function run(callback) {
    var event = Cucumber.Runtime.Event(Cucumber.Events.FEATURES_EVENT_NAME, features);
    eventBroadcaster.broadcastAroundEvent(
      event,
...
```

#### <a name="apidoc.element.cucumber.Runtime.FeaturesResult"></a>[function <span class="apidocSignatureSpan">cucumber.Runtime.</span>FeaturesResult (strict)](#apidoc.element.cucumber.Runtime.FeaturesResult)
- description and source-code
```javascript
function FeaturesResult(strict) {
  var Cucumber = require('../../cucumber');
  var _ = require('lodash');

  var duration = 0;
  var scenarioCounts = Cucumber.Status.getMapping(0);
  var stepCounts = Cucumber.Status.getMapping(0);

  var self = {
    getDuration: function getDuration() {
      return duration;
    },

    getScenarioCounts: function getScenarioCounts() {
      return _.clone(scenarioCounts);
    },

    getStepCounts: function getStepCounts() {
      return _.clone(stepCounts);
    },

    isSuccessful: function isSuccessful() {
      if (scenarioCounts[Cucumber.Status.FAILED] > 0 || scenarioCounts[Cucumber.Status.AMBIGUOUS] > 0) {
        return false;
      }
      if (strict && (scenarioCounts[Cucumber.Status.PENDING] > 0 || scenarioCounts[Cucumber.Status.UNDEFINED] > 0)) {
        return false;
      }
      return true;
    },

    witnessScenarioResult: function witnessScenarioResult(scenarioResult) {
      duration += scenarioResult.getDuration();
      scenarioCounts[scenarioResult.getStatus()] += 1;
      _.mergeWith(stepCounts, scenarioResult.getStepCounts(), function(a, b) { return a + b; });
    }
  };

  return self;
}
```
- example usage
```shell
...

},{"../../cucumber":"cucumber","lodash":165}],41:[function(require,module,exports){
function FeaturesRunner(features, supportCodeLibrary, listeners, options) {
var Cucumber = require('../../cucumber');

var allListeners = listeners.concat(supportCodeLibrary.getListeners());
var eventBroadcaster = Cucumber.Runtime.EventBroadcaster(allListeners, supportCodeLibrary.getDefaultTimeout());
var featuresResult = Cucumber.Runtime.FeaturesResult(options.strict);

var self = {
  run: function run(callback) {
    var event = Cucumber.Runtime.Event(Cucumber.Events.FEATURES_EVENT_NAME, features);
    eventBroadcaster.broadcastAroundEvent(
      event,
      function (callback) {
...
```

#### <a name="apidoc.element.cucumber.Runtime.FeaturesRunner"></a>[function <span class="apidocSignatureSpan">cucumber.Runtime.</span>FeaturesRunner (features, supportCodeLibrary, listeners, options)](#apidoc.element.cucumber.Runtime.FeaturesRunner)
- description and source-code
```javascript
function FeaturesRunner(features, supportCodeLibrary, listeners, options) {
  var Cucumber = require('../../cucumber');

  var allListeners = listeners.concat(supportCodeLibrary.getListeners());
  var eventBroadcaster = Cucumber.Runtime.EventBroadcaster(allListeners, supportCodeLibrary.getDefaultTimeout());
  var featuresResult = Cucumber.Runtime.FeaturesResult(options.strict);

  var self = {
    run: function run(callback) {
      var event = Cucumber.Runtime.Event(Cucumber.Events.FEATURES_EVENT_NAME, features);
      eventBroadcaster.broadcastAroundEvent(
        event,
        function (callback) {
          Cucumber.Util.asyncForEach(features, self.runFeature, function() {
            self.broadcastFeaturesResult(callback);
          });
        },
        function() {
          callback(featuresResult.isSuccessful());
        }
      );
    },

    broadcastFeaturesResult: function visitFeaturesResult(callback) {
      var event = Cucumber.Runtime.Event(Cucumber.Events.FEATURES_RESULT_EVENT_NAME, featuresResult);
      eventBroadcaster.broadcastEvent(event, callback);
    },

    runFeature: function runFeature(feature, callback) {
      if (!featuresResult.isSuccessful() && options.failFast) {
        return callback();
      }
      var event = Cucumber.Runtime.Event(Cucumber.Events.FEATURE_EVENT_NAME, feature);
      eventBroadcaster.broadcastAroundEvent(
        event,
        function (callback) {
          Cucumber.Util.asyncForEach(feature.getScenarios(), self.runScenario, callback);
        },
        callback
      );
    },

    runScenario: function runScenario(scenario, callback) {
      if (!featuresResult.isSuccessful() && options.failFast) {
        return callback();
      }

      var scenarioRunner = Cucumber.Runtime.ScenarioRunner(scenario, supportCodeLibrary, eventBroadcaster, options);
      scenarioRunner.run(function(scenarioResult) {
        featuresResult.witnessScenarioResult(scenarioResult);
        callback();
      });
    }
  };
  return self;
}
```
- example usage
```shell
...
var options = {
  dryRun: configuration.isDryRunRequested && configuration.isDryRunRequested(),
  failFast: configuration.isFailFastRequested && configuration.isFailFastRequested(),
  strict: configuration.isStrictRequested && configuration.isStrictRequested(),
  worldParameters: configuration.getWorldParameters()
};

var featuresRunner = Runtime.FeaturesRunner(features, supportCodeLibrary, listeners, options);

if (configuration.shouldFilterStackTraces())
  Runtime.StackTraceFilter.filter();

featuresRunner.run(function (result) {
  Runtime.StackTraceFilter.unfilter();
  callback(result);
...
```

#### <a name="apidoc.element.cucumber.Runtime.ScenarioResult"></a>[function <span class="apidocSignatureSpan">cucumber.Runtime.</span>ScenarioResult (scenario)](#apidoc.element.cucumber.Runtime.ScenarioResult)
- description and source-code
```javascript
function ScenarioResult(scenario) {
  var Cucumber = require('../../cucumber');
  var _ = require('lodash');

  var duration = 0;
  var status = Cucumber.Status.PASSED;
  var stepCounts = Cucumber.Status.getMapping(0);
  var failureException = null;

  var shouldUpdateStatus = function shouldUpdateStatus(stepStatus) {
    switch (stepStatus) {
      case Cucumber.Status.FAILED:
        return true;
      case Cucumber.Status.AMBIGUOUS:
      case Cucumber.Status.PENDING:
      case Cucumber.Status.SKIPPED:
      case Cucumber.Status.UNDEFINED:
        return status === Cucumber.Status.PASSED;
      default:
        return false;
    }
  };

  var self = {
    getDuration: function getDuration() {
      return duration;
    },

    getFailureException: function getFailureException() {
      return failureException;
    },

    getScenario: function getScenario() {
      return scenario;
    },

    getStepCounts: function getStepCounts() {
      return _.clone(stepCounts);
    },

    getStatus: function getStatus() {
      return status;
    },

    witnessStepResult: function witnessStepResult(stepResult) {
      var stepDuration = stepResult.getDuration();
      if (stepDuration) {
        duration += stepDuration;
      }
      var stepStatus = stepResult.getStatus();
      if (shouldUpdateStatus(stepStatus)) {
        status = stepStatus;
      }
      if (stepStatus === Cucumber.Status.FAILED) {
        failureException = stepResult.getFailureException();
      }
      var step = stepResult.getStep();
      if (!step.isHidden()) {
        stepCounts[stepStatus] += 1;
      }
    }
  };

  return self;
}
```
- example usage
```shell
...
module.exports = ScenarioResult;

},{"../../cucumber":"cucumber","lodash":165}],43:[function(require,module,exports){
(function (process){
function ScenarioRunner(scenario, supportCodeLibrary, eventBroadcaster, options) {
var Cucumber = require('../../cucumber');

var scenarioResult = Cucumber.Runtime.ScenarioResult(scenario);
var apiScenario = Cucumber.Api.Scenario(scenario, scenarioResult);
var defaultTimeout = supportCodeLibrary.getDefaultTimeout();
var world = supportCodeLibrary.instantiateNewWorld(options.worldParameters);

var self = {
  run: function run(callback) {
    var event = Cucumber.Runtime.Event(Cucumber.Events.SCENARIO_EVENT_NAME, scenario);
...
```

#### <a name="apidoc.element.cucumber.Runtime.ScenarioRunner"></a>[function <span class="apidocSignatureSpan">cucumber.Runtime.</span>ScenarioRunner (scenario, supportCodeLibrary, eventBroadcaster, options)](#apidoc.element.cucumber.Runtime.ScenarioRunner)
- description and source-code
```javascript
function ScenarioRunner(scenario, supportCodeLibrary, eventBroadcaster, options) {
  var Cucumber = require('../../cucumber');

  var scenarioResult = Cucumber.Runtime.ScenarioResult(scenario);
  var apiScenario = Cucumber.Api.Scenario(scenario, scenarioResult);
  var defaultTimeout = supportCodeLibrary.getDefaultTimeout();
  var world = supportCodeLibrary.instantiateNewWorld(options.worldParameters);

  var self = {
    run: function run(callback) {
      var event = Cucumber.Runtime.Event(Cucumber.Events.SCENARIO_EVENT_NAME, scenario);
      eventBroadcaster.broadcastAroundEvent(
        event,
        function (callback) {
          self.runBeforeHooks(function () {
            self.runSteps(function() {
              self.runAfterHooks(function(){
                self.broadcastScenarioResult(callback);
              });
            });
          });
        },
        function() {
          callback(scenarioResult);
        }
      );
    },

    runBeforeHooks: function runBeforeHooks(callback) {
      var beforeHooks = supportCodeLibrary.lookupBeforeHooksByScenario(scenario);
      Cucumber.Util.asyncForEach(beforeHooks, function(beforeHook, callback) {
        var beforeStep = Cucumber.Ast.HookStep(Cucumber.Ast.HookStep.BEFORE_STEP_KEYWORD);
        beforeStep.setScenario(scenario);
        self.runHookStep(beforeStep, beforeHook, callback);
      }, callback);
    },

    runSteps: function runSteps(callback) {
      Cucumber.Util.asyncForEach(scenario.getSteps(), self.runStep, callback);
    },

    runAfterHooks: function runAfterHooks(callback) {
      var afterHooks = supportCodeLibrary.lookupAfterHooksByScenario(scenario).reverse();
      Cucumber.Util.asyncForEach(afterHooks, function(afterHook, callback) {
        var afterStep = Cucumber.Ast.HookStep(Cucumber.Ast.HookStep.AFTER_STEP_KEYWORD);
        afterStep.setScenario(scenario);
        self.runHookStep(afterStep, afterHook, callback);
      }, callback);
    },

    broadcastScenarioResult: function broadcastScenarioResult(callback) {
      var event = Cucumber.Runtime.Event(Cucumber.Events.SCENARIO_RESULT_EVENT_NAME, scenarioResult);
      eventBroadcaster.broadcastEvent(event, callback);
    },

    runStep: function runStep(step, callback) {
      var event = Cucumber.Runtime.Event(Cucumber.Events.STEP_EVENT_NAME, step);
      eventBroadcaster.broadcastAroundEvent(
        event,
        function (callback) {
          process.nextTick(function() {
            self.processStep(step, callback);
          });
        },
        callback
      );
    },

    runHookStep: function(step, hook, callback) {
      var event = Cucumber.Runtime.Event(Cucumber.Events.STEP_EVENT_NAME, step);
      eventBroadcaster.broadcastAroundEvent(
        event,
        function (callback) {
          if (options.dryRun) {
            self.skipStep(step, hook, callback);
          } else {
            self.executeStep(step, hook, callback);
          }
        },
        callback
      );
    },

    broadcastStepResult: function broadcastStepResult(stepResult, callback) {
      scenarioResult.witnessStepResult(stepResult);
      var event = Cucumber.Runtime.Event(Cucumber.Events.STEP_RESULT_EVENT_NAME, stepResult);
      eventBroadcaster.broadcastEvent(event, callback);
    },

    isSkippingSteps: function isSkippingSteps() {
      return scenarioResult.getStatus() !== Cucumber.Status.PASSED;
    },

    processStep: function processStep(step, callback) {
      var stepName = step.getName();
      var stepDefinitions = supportCodeLibrary.lookupStepDefinitionsByName(stepName);
      if (stepDefinitions.length === 0) {
        self.skipUndefinedStep(step, callback);
      } else if (stepDefinitions.length > 1) {
        self.skipAmbiguousStep(step, stepDefinitions, callback);
      } else if (options.dryRun || self.isSkippingSteps()) {
        self.skipStep(step, stepDefinitions[0], callback);
      } else {
        self.executeStep(step, stepDefinitions[0], callback);
      }
    },

    executeStep: function executeStep(step, stepDefinition, callback) {
      stepDefin ...
```
- example usage
```shell
...
  },

  runScenario: function runScenario(scenario, callback) {
    if (!featuresResult.isSuccessful() && options.failFast) {
      return callback();
    }

    var scenarioRunner = Cucumber.Runtime.ScenarioRunner(scenario, supportCodeLibrary, eventBroadcaster, options);
    scenarioRunner.run(function(scenarioResult) {
      featuresResult.witnessScenarioResult(scenarioResult);
      callback();
    });
  }
};
return self;
...
```

#### <a name="apidoc.element.cucumber.Runtime.StepResult"></a>[function <span class="apidocSignatureSpan">cucumber.Runtime.</span>StepResult (payload)](#apidoc.element.cucumber.Runtime.StepResult)
- description and source-code
```javascript
function StepResult(payload) {
  var self = {
    getAmbiguousStepDefinitions: function getAmbiguousStepDefinitions() {
      return payload.ambiguousStepDefinitions;
    },

    getAttachments: function getAttachments() {
      return payload.attachments;
    },

    getDuration: function getDuration() {
      return payload.duration;
    },

    getFailureException: function getFailureException() {
      return payload.failureException;
    },

    getPendingReason: function getPendingReason() {
      return payload.pendingReason;
    },

    getStep: function getStep() {
      return payload.step;
    },

    getStepDefinition: function getStepDefinition() {
      return payload.stepDefinition;
    },

    getStatus: function getStatus() {
      return payload.status;
    },

    hasAttachments: function hasAttachments() {
      return payload.attachments && payload.attachments.length > 0;
    }
  };

  return self;
}
```
- example usage
```shell
...
  stepDefinition.invoke(step, world, apiScenario, defaultTimeout, function (stepResult) {
    apiScenario.clearAttachments();
    self.broadcastStepResult(stepResult, callback);
  });
},

skipAmbiguousStep: function skipAmbiguousStep(step, stepDefinitions, callback) {
  var ambiguousStepResult = Cucumber.Runtime.StepResult({
    ambiguousStepDefinitions: stepDefinitions,
    step: step,
    status: Cucumber.Status.AMBIGUOUS
  });
  self.broadcastStepResult(ambiguousStepResult, callback);
},
...
```



# <a name="apidoc.module.cucumber.Runtime.StackTraceFilter"></a>[module cucumber.Runtime.StackTraceFilter](#apidoc.module.cucumber.Runtime.StackTraceFilter)

#### <a name="apidoc.element.cucumber.Runtime.StackTraceFilter.filter"></a>[function <span class="apidocSignatureSpan">cucumber.Runtime.StackTraceFilter.</span>filter ()](#apidoc.element.cucumber.Runtime.StackTraceFilter.filter)
- description and source-code
```javascript
function filter() {
  currentFilter = chain.filter.attach(function (error, frames) {
    if (frames.length > 0 && isFrameInCucumber(frames[0])) {
      return frames;
    }
    return frames.filter(_.negate(isFrameInCucumber));
  });
}
```
- example usage
```shell
...
    strict: configuration.isStrictRequested && configuration.isStrictRequested(),
    worldParameters: configuration.getWorldParameters()
  };

  var featuresRunner = Runtime.FeaturesRunner(features, supportCodeLibrary, listeners, options);

  if (configuration.shouldFilterStackTraces())
    Runtime.StackTraceFilter.filter();

  featuresRunner.run(function (result) {
    Runtime.StackTraceFilter.unfilter();
    callback(result);
  });
},
...
```

#### <a name="apidoc.element.cucumber.Runtime.StackTraceFilter.unfilter"></a>[function <span class="apidocSignatureSpan">cucumber.Runtime.StackTraceFilter.</span>unfilter ()](#apidoc.element.cucumber.Runtime.StackTraceFilter.unfilter)
- description and source-code
```javascript
function unfilter() {
  chain.filter.deattach(currentFilter);
}
```
- example usage
```shell
...

  var featuresRunner = Runtime.FeaturesRunner(features, supportCodeLibrary, listeners, options);

  if (configuration.shouldFilterStackTraces())
    Runtime.StackTraceFilter.filter();

  featuresRunner.run(function (result) {
    Runtime.StackTraceFilter.unfilter();
    callback(result);
  });
},

attachListener: function attachListener(listener) {
  listeners.push(listener);
},
...
```



# <a name="apidoc.module.cucumber.Status"></a>[module cucumber.Status](#apidoc.module.cucumber.Status)

#### <a name="apidoc.element.cucumber.Status.getMapping"></a>[function <span class="apidocSignatureSpan">cucumber.Status.</span>getMapping (initialValue)](#apidoc.element.cucumber.Status.getMapping)
- description and source-code
```javascript
function getMapping(initialValue) {
  var statuses = [
    Status.AMBIGUOUS,
    Status.FAILED,
    Status.PASSED,
    Status.PENDING,
    Status.SKIPPED,
    Status.UNDEFINED
  ];
  var counts = {};
  statuses.forEach(function (status) {
    counts[status] = initialValue;
  });
  return counts;
}
```
- example usage
```shell
...

},{"../../cucumber":"cucumber"}],40:[function(require,module,exports){
function FeaturesResult(strict) {
var Cucumber = require('../../cucumber');
var _ = require('lodash');

var duration = 0;
var scenarioCounts = Cucumber.Status.getMapping(0);
var stepCounts = Cucumber.Status.getMapping(0);

var self = {
  getDuration: function getDuration() {
    return duration;
  },
...
```



# <a name="apidoc.module.cucumber.SupportCode"></a>[module cucumber.SupportCode](#apidoc.module.cucumber.SupportCode)

#### <a name="apidoc.element.cucumber.SupportCode.Hook"></a>[function <span class="apidocSignatureSpan">cucumber.SupportCode.</span>Hook (code, options, uri, line)](#apidoc.element.cucumber.SupportCode.Hook)
- description and source-code
```javascript
function Hook(code, options, uri, line) {
  var Cucumber = require('../../cucumber');
  var self = Cucumber.SupportCode.StepDefinition(Hook.EMPTY_PATTERN, options, code, uri, line);
  var tags = options.tags || [];

  self.buildInvocationParameters = function buildInvocationParameters(step, scenario) {
    return [scenario];
  };

  self.appliesToScenario = function appliesToScenario(scenario) {
    var astFilter = self.getAstFilter();
    return astFilter.isElementEnrolled(scenario);
  };

  self.getAstFilter = function getAstFilter() {
    var tagGroups = Cucumber.TagGroupParser.getTagGroupsFromStrings(tags);
    var rules = tagGroups.map(function (tagGroup) {
      var rule = Cucumber.Ast.Filter.AnyOfTagsRule(tagGroup);
      return rule;
    });
    var astFilter = Cucumber.Ast.Filter(rules);
    return astFilter;
  };

  self.validCodeLengths = function validCodeLengths () {
    return [0, 1, 2];
  };

  self.invalidCodeLengthMessage = function invalidCodeLengthMessage() {
    return self.buildInvalidCodeLengthMessage('0 or 1', '2');
  };

  return self;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cucumber.SupportCode.Library"></a>[function <span class="apidocSignatureSpan">cucumber.SupportCode.</span>Library (supportCodeDefinition)](#apidoc.element.cucumber.SupportCode.Library)
- description and source-code
```javascript
function Library(supportCodeDefinition) {
  var Cucumber = require('../../cucumber');
  var StackTrace = require('stacktrace-js');
  var _ = require('lodash');

  var listeners = [];
  var stepDefinitions = [];
  var beforeHooks = [];
  var afterHooks = [];
  var World = function World(parameters) {
    this.parameters = parameters;
  };
  var defaultTimeout= 5 * 1000;

  function createEventListenerMethod(library, eventName) {
    return function (handler) {
      library.registerHandler(eventName, handler);
    };
  }

  function appendEventHandlers(supportCodeHelper, library) {
    _.each(Cucumber.Events.ALL, function(eventName) {
      supportCodeHelper[eventName] = createEventListenerMethod(library, eventName);
    });
  }

  function getStackframe() {
    var stackframes = StackTrace.getSync();
    if (stackframes.length > 2) {
      return stackframes[2];
    } else {
      return stackframes[0];
    }
  }

  var self = {
    lookupBeforeHooksByScenario: function lookupBeforeHooksByScenario(scenario) {
      return self.lookupHooksByScenario(beforeHooks, scenario);
    },

    lookupAfterHooksByScenario: function lookupBeforeHooksByScenario(scenario) {
      return self.lookupHooksByScenario(afterHooks, scenario);
    },

    lookupHooksByScenario: function lookupHooksByScenario(hooks, scenario) {
      return hooks.filter(function (hook) {
        return hook.appliesToScenario(scenario);
      });
    },

    lookupStepDefinitionsByName: function lookupStepDefinitionsByName(name) {
      return stepDefinitions.filter(function (stepDefinition) {
        return stepDefinition.matchesStepName(name);
      });
    },

    defineHook: function defineHook(builder, collection) {
      return function(options, code) {
        if (typeof(options) === 'string') {
          options = {tags: [options]};
        } else if (typeof(options) === 'function') {
          code = options;
          options = {};
        }
        var stackframe = getStackframe();
        var line = stackframe.getLineNumber();
        var uri = stackframe.getFileName() || 'unknown';
        var hook = builder(code, options, uri, line);
        collection.push(hook);
      };
    },

    defineStep: function defineStep(name, options, code) {
      if (typeof(options) === 'function') {
        code = options;
        options = {};
      }
      var stackframe = getStackframe();
      var line = stackframe.getLineNumber();
      var uri = stackframe.getFileName() || 'unknown';
      var stepDefinition = Cucumber.SupportCode.StepDefinition(name, options, code, uri, line);
      stepDefinitions.push(stepDefinition);
    },

    registerListener: function registerListener(listener) {
      listeners.push(listener);
    },

    registerHandler: function registerHandler(eventName, options, handler) {
      if (typeof(options) === 'function') {
        handler = options;
        options = {};
      }
      var stackframe = getStackframe();
      options.line = stackframe.getLineNumber();
      options.uri = stackframe.getFileName() || 'unknown';
      var listener = Cucumber.Listener(options);
      listener.setHandlerForEvent(eventName, handler);
      self.registerListener(listener);
    },

    getListeners: function getListeners() {
      return listeners;
    },

    instantiateNewWorld: function instantiateNewWorld(parameters) {
      return new World(parameters);
    },

    getDefaultTimeout: function getDefaultTimeout() {
      return defaultTimeout;
    },

    setDefaultTimeout: function setDefaultTimeout(milliseconds) {
      defaultTimeout = milliseconds;
    }
  };

  var supportCodeHelper = {
    Before            : self.defineHook(Cucumber.SupportCode.Hook, beforeHooks),
    After             : self.defineHook(Cucumber.SupportCode.Hook, afterHooks),
    Given             : self.defineStep,
    When              : self.defineStep,
    Then              : self.defineStep,
    defineStep        : self.defineStep,
    registerListener  : self.registerListener,
    registerHandler   : self.registerHandler,
    setDefaultTimeout : self.setDefaultTim ...
```
- example usage
```shell
...

function SupportCodeLoader(supportCodeFilePaths, compilerModules) {
  var Cucumber = require('../../cucumber');

  var self = {
getSupportCodeLibrary: function getSupportCodeLibrary() {
  var supportCodeInitialiazer = self.getSupportCodeInitializer();
  var supportCodeLibrary      = Cucumber.SupportCode.Library(supportCodeInitialiazer);
  return supportCodeLibrary;
},

getSupportCodeInitializer: function getSupportCodeInitializer() {
  var primeSupportCodeInitializer     = self.getPrimeSupportCodeInitializer();
  var secondarySupportCodeInitializer = self.getSecondarySupportCodeInitializer();
  var initializer = function () {
...
```

#### <a name="apidoc.element.cucumber.SupportCode.StepDefinition"></a>[function <span class="apidocSignatureSpan">cucumber.SupportCode.</span>StepDefinition (pattern, options, code, uri, line)](#apidoc.element.cucumber.SupportCode.StepDefinition)
- description and source-code
```javascript
function StepDefinition(pattern, options, code, uri, line) {
  var Cucumber = require('../../cucumber');


  function time() {
    if (typeof process !== 'undefined' && process.hrtime) {
      return process.hrtime();
    }
    else {
      return new Cucumber.Util.RealTime.Date().getTime();
    }
  }

  function durationInNanoseconds(start) {
    if (typeof process !== 'undefined' && process.hrtime) {
      var duration = process.hrtime(start);
      return duration[0] * 1e9 + duration[1];
    }
    else {
      return (new Cucumber.Util.RealTime.Date().getTime() - start) * 1e6;
    }
  }

  var self = {
    getLine: function getLine() {
      return line;
    },

    getPattern: function getPatternRegexp() {
      return pattern;
    },

    getPatternRegexp: function getPatternRegexp() {
      var regexp;
      if (pattern.replace) {
        var regexpString = pattern
          .replace(StepDefinition.UNSAFE_STRING_CHARACTERS_REGEXP, StepDefinition.PREVIOUS_REGEXP_MATCH)
          .replace(StepDefinition.QUOTED_DOLLAR_PARAMETER_REGEXP, StepDefinition.QUOTED_DOLLAR_PARAMETER_SUBSTITUTION)
          .replace(StepDefinition.DOLLAR_PARAMETER_REGEXP, StepDefinition.DOLLAR_PARAMETER_SUBSTITUTION);
        regexpString =
          StepDefinition.STRING_PATTERN_REGEXP_PREFIX +
          regexpString +
          StepDefinition.STRING_PATTERN_REGEXP_SUFFIX;
        regexp = new RegExp(regexpString);
      }
      else
        regexp = pattern;
      return regexp;
    },

    getUri: function getUri() {
      return uri;
    },

    matchesStepName: function matchesStepName(stepName) {
      var regexp = self.getPatternRegexp();
      return regexp.test(stepName);
    },

    invoke: function invoke(step, world, scenario, defaultTimeout, callback) {
      var start = time();
      var parameters = self.buildInvocationParameters(step, scenario);
      var timeoutInMilliseconds = options.timeout || defaultTimeout;

      function finish(error, result) {
        var stepResultData = {
          step: step,
          stepDefinition: self,
          duration: durationInNanoseconds(start),
          attachments: scenario.getAttachments(),
        };

        if (result === 'pending') {
          stepResultData.status = Cucumber.Status.PENDING;
        } else if (error) {
          stepResultData.failureException = error;
          stepResultData.status = Cucumber.Status.FAILED;
        } else {
          stepResultData.status = Cucumber.Status.PASSED;
        }

        var stepResult = Cucumber.Runtime.StepResult(stepResultData);
        callback(stepResult);
      }

      var validCodeLengths = self.validCodeLengths(parameters);
      if (validCodeLengths.indexOf(code.length) === -1) {
        return finish(self.invalidCodeLengthMessage(parameters));
      }

      Cucumber.Util.run(code, world, parameters, timeoutInMilliseconds, finish);
    },

    buildInvocationParameters: function buildInvocationParameters(step) {
      var stepName      = step.getName();
      var patternRegexp = self.getPatternRegexp();
      var parameters    = patternRegexp.exec(stepName);
      parameters.shift();
      parameters = parameters.concat(step.getArguments().map(function(arg) {
        switch (arg.getType()) {
          case 'DataTable':
            return arg;
          case 'DocString':
            return arg.getContent();
          default:
            throw new Error('Unknown argument type:' + arg.getType());
        }
      }));
      return parameters;
    },

    buildExceptionHandlerToCodeCallback: function buildExceptionHandlerToCodeCallback(codeCallback) {
      var exceptionHandler = function handleScenarioException(exception) {
        if (exception)
          Cucumber.Debug.warn(exception.stack || exception, 'exception inside feature', 3);
        codeCallback(exception);
      };
      return exceptionHandler;
    },

    validCodeLengths: function validCodeLengths (parameters) {
      return [parameters.length, parameters.length + 1];
    },

    invalidCodeLengthMessage: function invalidCodeLengthMessage(parameters) {
      re ...
```
- example usage
```shell
...
SupportCode.StepDefinition               = require('./support_code/step_definition');
SupportCode.StepDefinitionSnippetBuilder = require('./support_code/step_definition_snippet_builder');
module.exports                           = SupportCode;

},{"./support_code/hook":48,"./support_code/library":49,"./support_code/step_definition":50,"./support_code/step_definition_snippet_builder
":51}],48:[function(require,module,exports){
function Hook(code, options, uri, line) {
var Cucumber = require('../../cucumber');
var self = Cucumber.SupportCode.StepDefinition(Hook.EMPTY_PATTERN, options, code, uri, line);
var tags = options.tags || [];

self.buildInvocationParameters = function buildInvocationParameters(step, scenario) {
  return [scenario];
};

self.appliesToScenario = function appliesToScenario(scenario) {
...
```

#### <a name="apidoc.element.cucumber.SupportCode.StepDefinitionSnippetBuilder"></a>[function <span class="apidocSignatureSpan">cucumber.SupportCode.</span>StepDefinitionSnippetBuilder (step, syntax)](#apidoc.element.cucumber.SupportCode.StepDefinitionSnippetBuilder)
- description and source-code
```javascript
function StepDefinitionSnippetBuilder(step, syntax) {
  var Cucumber = require('../../cucumber');

  var self = {
    buildSnippet: function buildSnippet() {
      var functionName = self.buildStepDefinitionFunctionName();
      var pattern      = self.buildStepDefinitionPattern();
      var parameters   = self.buildStepDefinitionParameters();
      var comment      = 'Write code here that turns the phrase above into concrete actions';
      return syntax.build(functionName, pattern, parameters, comment);
    },

    buildStepDefinitionFunctionName: function buildStepDefinitionFunctionName() {
      if (step.isOutcomeStep())
        return 'Then';
      else if (step.isEventStep())
        return 'When';
      else
        return 'Given';
    },

    buildStepDefinitionPattern: function buildStepDefinitionPattern() {
      var stepName              = step.getName();
      var escapedStepName       = Cucumber.Util.RegExp.escapeString(stepName);
      var parameterizedStepName = self.parameterizeStepName(escapedStepName);
      var pattern               = '/^' + parameterizedStepName + '$/';
      return pattern;
    },

    buildStepDefinitionParameters: function buildStepDefinitionParameters() {
      var parameters = self.getStepDefinitionPatternMatchingGroupParameters();
      step.getArguments().forEach(function (arg) {
        switch (arg.getType()) {
          case 'DataTable':
            parameters.push('table');
            break;
          case 'DocString':
            parameters.push('string');
            break;
          default:
            throw new Error('Unknown argument type:' + arg.getType());
        }
      });
      parameters.push('callback');
      return parameters;
    },

    getStepDefinitionPatternMatchingGroupParameters: function getStepDefinitionPatternMatchingGroupParameters() {
      var parameterCount = self.countStepDefinitionPatternMatchingGroups();
      var parameters = _.times(parameterCount, function (n) {
        return 'arg' + (n + 1);
      });
      return parameters;
    },

    countStepDefinitionPatternMatchingGroups: function countStepDefinitionPatternMatchingGroups() {
      var stepDefinitionPattern    = self.buildStepDefinitionPattern();
      var numberMatchingGroupCount = Cucumber.Util.String.count(stepDefinitionPattern, NUMBER_MATCHING_GROUP);
      var quotedStringMatchingGroupCount = Cucumber.Util.String.count(stepDefinitionPattern, QUOTED_STRING_MATCHING_GROUP);
      var count = numberMatchingGroupCount + quotedStringMatchingGroupCount;
      return count;
    },

    parameterizeStepName: function parameterizeStepName(stepName) {
      var parameterizedStepName =
          stepName
          .replace(NUMBER_PATTERN, NUMBER_MATCHING_GROUP)
          .replace(QUOTED_STRING_PATTERN, QUOTED_STRING_MATCHING_GROUP);
      return parameterizedStepName;
    }
  };
  return self;
}
```
- example usage
```shell
...
var self = Cucumber.Listener.Formatter(options);
var snippets = [];

self.handleStepResultEvent = function handleStepResult(stepResult) {
  var status = stepResult.getStatus();
  if (status === Cucumber.Status.UNDEFINED) {
    var step = stepResult.getStep();
    var snippetBuilder = Cucumber.SupportCode.StepDefinitionSnippetBuilder(step, options.snippetSyntax);
    snippets.push(snippetBuilder.buildSnippet());
  }
};

self.handleFeaturesResultEvent = function handleFeaturesResultEvent(featuresResult, callback) {
  self.log(snippets.join('\n\n'));
  self.finish(callback);
...
```



# <a name="apidoc.module.cucumber.SupportCode.StepDefinitionSnippetBuilder"></a>[module cucumber.SupportCode.StepDefinitionSnippetBuilder](#apidoc.module.cucumber.SupportCode.StepDefinitionSnippetBuilder)

#### <a name="apidoc.element.cucumber.SupportCode.StepDefinitionSnippetBuilder.StepDefinitionSnippetBuilder"></a>[function <span class="apidocSignatureSpan">cucumber.SupportCode.</span>StepDefinitionSnippetBuilder (step, syntax)](#apidoc.element.cucumber.SupportCode.StepDefinitionSnippetBuilder.StepDefinitionSnippetBuilder)
- description and source-code
```javascript
function StepDefinitionSnippetBuilder(step, syntax) {
  var Cucumber = require('../../cucumber');

  var self = {
    buildSnippet: function buildSnippet() {
      var functionName = self.buildStepDefinitionFunctionName();
      var pattern      = self.buildStepDefinitionPattern();
      var parameters   = self.buildStepDefinitionParameters();
      var comment      = 'Write code here that turns the phrase above into concrete actions';
      return syntax.build(functionName, pattern, parameters, comment);
    },

    buildStepDefinitionFunctionName: function buildStepDefinitionFunctionName() {
      if (step.isOutcomeStep())
        return 'Then';
      else if (step.isEventStep())
        return 'When';
      else
        return 'Given';
    },

    buildStepDefinitionPattern: function buildStepDefinitionPattern() {
      var stepName              = step.getName();
      var escapedStepName       = Cucumber.Util.RegExp.escapeString(stepName);
      var parameterizedStepName = self.parameterizeStepName(escapedStepName);
      var pattern               = '/^' + parameterizedStepName + '$/';
      return pattern;
    },

    buildStepDefinitionParameters: function buildStepDefinitionParameters() {
      var parameters = self.getStepDefinitionPatternMatchingGroupParameters();
      step.getArguments().forEach(function (arg) {
        switch (arg.getType()) {
          case 'DataTable':
            parameters.push('table');
            break;
          case 'DocString':
            parameters.push('string');
            break;
          default:
            throw new Error('Unknown argument type:' + arg.getType());
        }
      });
      parameters.push('callback');
      return parameters;
    },

    getStepDefinitionPatternMatchingGroupParameters: function getStepDefinitionPatternMatchingGroupParameters() {
      var parameterCount = self.countStepDefinitionPatternMatchingGroups();
      var parameters = _.times(parameterCount, function (n) {
        return 'arg' + (n + 1);
      });
      return parameters;
    },

    countStepDefinitionPatternMatchingGroups: function countStepDefinitionPatternMatchingGroups() {
      var stepDefinitionPattern    = self.buildStepDefinitionPattern();
      var numberMatchingGroupCount = Cucumber.Util.String.count(stepDefinitionPattern, NUMBER_MATCHING_GROUP);
      var quotedStringMatchingGroupCount = Cucumber.Util.String.count(stepDefinitionPattern, QUOTED_STRING_MATCHING_GROUP);
      var count = numberMatchingGroupCount + quotedStringMatchingGroupCount;
      return count;
    },

    parameterizeStepName: function parameterizeStepName(stepName) {
      var parameterizedStepName =
          stepName
          .replace(NUMBER_PATTERN, NUMBER_MATCHING_GROUP)
          .replace(QUOTED_STRING_PATTERN, QUOTED_STRING_MATCHING_GROUP);
      return parameterizedStepName;
    }
  };
  return self;
}
```
- example usage
```shell
...
var self = Cucumber.Listener.Formatter(options);
var snippets = [];

self.handleStepResultEvent = function handleStepResult(stepResult) {
  var status = stepResult.getStatus();
  if (status === Cucumber.Status.UNDEFINED) {
    var step = stepResult.getStep();
    var snippetBuilder = Cucumber.SupportCode.StepDefinitionSnippetBuilder(step, options.snippetSyntax);
    snippets.push(snippetBuilder.buildSnippet());
  }
};

self.handleFeaturesResultEvent = function handleFeaturesResultEvent(featuresResult, callback) {
  self.log(snippets.join('\n\n'));
  self.finish(callback);
...
```

#### <a name="apidoc.element.cucumber.SupportCode.StepDefinitionSnippetBuilder.JavaScriptSyntax"></a>[function <span class="apidocSignatureSpan">cucumber.SupportCode.StepDefinitionSnippetBuilder.</span>JavaScriptSyntax (interface)](#apidoc.element.cucumber.SupportCode.StepDefinitionSnippetBuilder.JavaScriptSyntax)
- description and source-code
```javascript
function JavaScriptSyntax(interface) {
  return {
    build: function build (functionName, pattern, parameters, comment) {
      var functionKeyword = 'function ';
      if (interface === 'generator') {
        functionKeyword += '*';
      }

      var implementation;
      if (interface === 'callback') {
        var callbackName = parameters[parameters.length - 1];
        implementation = callbackName + '(null, \'pending\');';
      } else {
        parameters.pop();
        implementation = 'return \'pending\';';
      }

      var snippet =
        'this.' + functionName + '(' + pattern + ', ' + functionKeyword + '(' + parameters.join(', ') + ') {' + '\n' +
        '  // ' + comment + '\n' +
        '  ' + implementation + '\n' +
        '});';
      return snippet;
    }
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.cucumber.TagGroupParser"></a>[module cucumber.TagGroupParser](#apidoc.module.cucumber.TagGroupParser)

#### <a name="apidoc.element.cucumber.TagGroupParser.TagGroupParser"></a>[function <span class="apidocSignatureSpan">cucumber.</span>TagGroupParser (tagGroupString)](#apidoc.element.cucumber.TagGroupParser.TagGroupParser)
- description and source-code
```javascript
function TagGroupParser(tagGroupString) {
  var self = {
    parse: function parse() {
      var splitTags = tagGroupString.split(TagGroupParser.TAG_SEPARATOR);
      var trimmedTags = splitTags.map(function (tag) { return tag.trim(); });
      return trimmedTags;
    }
  };
  return self;
}
```
- example usage
```shell
...
  return self;
}

TagGroupParser.getTagGroupsFromStrings = function getTagGroupsFromStrings(tagGroupStrings) {
  var Cucumber = require('../cucumber');

  var tagGroups = tagGroupStrings.map(function (tagOptionValue) {
    var tagGroupParser = Cucumber.TagGroupParser(tagOptionValue);
    var tagGroup       = tagGroupParser.parse();
    return tagGroup;
  });
  return tagGroups;
};

TagGroupParser.TAG_SEPARATOR = ',';
...
```

#### <a name="apidoc.element.cucumber.TagGroupParser.getTagGroupsFromStrings"></a>[function <span class="apidocSignatureSpan">cucumber.TagGroupParser.</span>getTagGroupsFromStrings (tagGroupStrings)](#apidoc.element.cucumber.TagGroupParser.getTagGroupsFromStrings)
- description and source-code
```javascript
function getTagGroupsFromStrings(tagGroupStrings) {
  var Cucumber = require('../cucumber');

  var tagGroups = tagGroupStrings.map(function (tagOptionValue) {
    var tagGroupParser = Cucumber.TagGroupParser(tagOptionValue);
    var tagGroup       = tagGroupParser.parse();
    return tagGroup;
  });
  return tagGroups;
}
```
- example usage
```shell
...

getFeatureSources: function getFeatureSources() {
  var featureSourceLoader = Cucumber.Cli.FeatureSourceLoader(expandedFeaturePaths);
  return featureSourceLoader.getSources();
},

getAstFilter: function getAstFilter() {
  var tagGroups = Cucumber.TagGroupParser.getTagGroupsFromStrings(options.tags);
  var tagRules = tagGroups.map(function (tags) {
     return Cucumber.Ast.Filter.AnyOfTagsRule(tags);
  });
  var lineRule = Cucumber.Ast.Filter.ScenarioAtLineRule(unexpandedFeaturePaths);
  var nameRule = Cucumber.Ast.Filter.AnyOfNamesRule(options.name);
  var rules = tagRules.concat([lineRule, nameRule]);
  return Cucumber.Ast.Filter(rules);
...
```



# <a name="apidoc.module.cucumber.Type"></a>[module cucumber.Type](#apidoc.module.cucumber.Type)

#### <a name="apidoc.element.cucumber.Type.HashDataTable"></a>[function <span class="apidocSignatureSpan">cucumber.Type.</span>HashDataTable (rawArray)](#apidoc.element.cucumber.Type.HashDataTable)
- description and source-code
```javascript
function HashDataTable(rawArray) {
  var self = {
    raw: function raw() {
      var hashKeys        = self.getHashKeys();
      var hashValueArrays = self.getHashValueArrays();
      var hashes          = self.createHashesFromKeysAndValueArrays(hashKeys, hashValueArrays);
      return hashes;
    },

    getHashKeys: function getHashKeys() {
      return rawArray[0];
    },

    getHashValueArrays: function getHashValueArrays() {
      var _rawArray = [].concat(rawArray);
      _rawArray.shift();
      return _rawArray;
    },

    createHashesFromKeysAndValueArrays: function createHashesFromKeysAndValueArrays(keys, valueArrays) {
      var hashes = [];
      valueArrays.forEach(function (values) {
        var hash = self.createHashFromKeysAndValues(keys, values);
        hashes.push(hash);
      });
      return hashes;
    },

    createHashFromKeysAndValues: function createHashFromKeysAndValues(keys, values) {
      var hash = {};
      var len  = keys.length;
      for (var i = 0; i < len; i++) {
        hash[keys[i]] = values[i];
      }
      return hash;
    }
  };
  return self;
}
```
- example usage
```shell
...

    raw: function raw() {
      return rawTable.slice(0);
    },

    hashes: function hashes() {
      var raw              = self.raw();
      var hashDataTable    = Cucumber.Type.HashDataTable(raw);
      var rawHashDataTable = hashDataTable.raw();
      return rawHashDataTable;
    }
  };
  return self;
}
...
```

#### <a name="apidoc.element.cucumber.Type.String"></a>[function <span class="apidocSignatureSpan">cucumber.Type.</span>String ()](#apidoc.element.cucumber.Type.String)
- description and source-code
```javascript
function String() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.cucumber.Type.String"></a>[module cucumber.Type.String](#apidoc.module.cucumber.Type.String)

#### <a name="apidoc.element.cucumber.Type.String.String"></a>[function <span class="apidocSignatureSpan">cucumber.Type.</span>String ()](#apidoc.element.cucumber.Type.String.String)
- description and source-code
```javascript
function String() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.cucumber.Type.String.prototype"></a>[module cucumber.Type.String.prototype](#apidoc.module.cucumber.Type.String.prototype)

#### <a name="apidoc.element.cucumber.Type.String.prototype.entityify"></a>[function <span class="apidocSignatureSpan">cucumber.Type.String.prototype.</span>entityify ()](#apidoc.element.cucumber.Type.String.prototype.entityify)
- description and source-code
```javascript
entityify = function (){return this.replace(/&/g,"&amp;").replace(/</g,"&lt;").replace(/>/g,"&gt;"
)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cucumber.Type.String.prototype.isAlpha"></a>[function <span class="apidocSignatureSpan">cucumber.Type.String.prototype.</span>isAlpha ( )](#apidoc.element.cucumber.Type.String.prototype.isAlpha)
- description and source-code
```javascript
isAlpha = function ( ){return this>="a"&&this<="z\uffff"||this>="A"&&this<="Z\uffff"}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cucumber.Type.String.prototype.isDigit"></a>[function <span class="apidocSignatureSpan">cucumber.Type.String.prototype.</span>isDigit ()](#apidoc.element.cucumber.Type.String.prototype.isDigit)
- description and source-code
```javascript
isDigit = function (){return this>="0"&&
this<="9"}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cucumber.Type.String.prototype.supplant"></a>[function <span class="apidocSignatureSpan">cucumber.Type.String.prototype.</span>supplant (e)](#apidoc.element.cucumber.Type.String.prototype.supplant)
- description and source-code
```javascript
supplant = function (e){return this.replace(/\{([^{}]*)\}/g,function(t,n){var r=e[n];return typeof
r=="string"||typeof r=="number"?r:t})}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.cucumber.Util"></a>[module cucumber.Util](#apidoc.module.cucumber.Util)

#### <a name="apidoc.element.cucumber.Util.Arguments"></a>[function <span class="apidocSignatureSpan">cucumber.Util.</span>Arguments (argumentsObject)](#apidoc.element.cucumber.Util.Arguments)
- description and source-code
```javascript
function Arguments(argumentsObject) {
  return Array.prototype.slice.call(argumentsObject);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cucumber.Util.Colors"></a>[function <span class="apidocSignatureSpan">cucumber.Util.</span>Colors (useColors)](#apidoc.element.cucumber.Util.Colors)
- description and source-code
```javascript
function Colors(useColors) {
  colors.enabled = useColors;
  return {
    ambiguous: colors.red,
    bold: colors.bold,
    failed: colors.red,
    location: colors.grey,
    passed: colors.green,
    pending: colors.yellow,
    skipped: colors.cyan,
    tag: colors.cyan,
    undefined: colors.yellow
  };
}
```
- example usage
```shell
...
}).call(this,require("buffer").Buffer)

},{"../../cucumber":"cucumber","buffer":74}],30:[function(require,module,exports){
function PrettyFormatter(options) {
var Cucumber         = require('../../cucumber');
var figures          = require('figures');

var colors           = Cucumber.Util.Colors(options.useColors);
var self             = Cucumber.Listener.Formatter(options);
var summaryFormatter = Cucumber.Listener.SummaryFormatter({
  snippetSyntax: options.snippetSyntax,
  useColors: options.useColors
});

var parentHear = self.hear;
...
```

#### <a name="apidoc.element.cucumber.Util.asyncForEach"></a>[function <span class="apidocSignatureSpan">cucumber.Util.</span>asyncForEach (items, userFunction, callback)](#apidoc.element.cucumber.Util.asyncForEach)
- description and source-code
```javascript
function asyncForEach(items, userFunction, callback) {
  var itemsCopy = items.slice(0);

  function iterate() {
    if (itemsCopy.length > 0) {
      var item = itemsCopy.shift();
      userFunction(item, function () {
        process.nextTick(iterate);
      });
    } else {
      callback();
    }
  }

  iterate();
}
```
- example usage
```shell
...

broadcastAfterEvent: function broadcastAfterEvent(event, callback) {
  var postEvent = event.replicateAsPostEvent();
  self.broadcastEvent(postEvent, callback);
},

broadcastEvent: function broadcastEvent(event, callback) {
  Cucumber.Util.asyncForEach(listeners, function (listener, callback) {
    listener.hear(event, listenerDefaultTimeout, function(error) {
      if (error) {
        throw error;
      }
      callback();
    });
  }, callback);
...
```

#### <a name="apidoc.element.cucumber.Util.run"></a>[function <span class="apidocSignatureSpan">cucumber.Util.</span>run (fn, thisArg, argsArray, timeoutInMilliseconds, callback)](#apidoc.element.cucumber.Util.run)
- description and source-code
```javascript
function run(fn, thisArg, argsArray, timeoutInMilliseconds, callback) {
  var Cucumber = require('../../cucumber');
  var timeoutId;

  function finish(error, result) {
    Cucumber.Util.Exception.unregisterUncaughtExceptionHandler(finish);
    if (timeoutId) {
      Cucumber.Util.RealTime.clearTimeout(timeoutId);
    }
    if (error && !(error instanceof Error)) {
      error = util.format(error);
    }
    callback(error, result);
    callback = function() {};
  }

  argsArray.push(finish);

  timeoutId = Cucumber.Util.RealTime.setTimeout(function(){
    finish('function timed out after ' + timeoutInMilliseconds + ' milliseconds');
  }, timeoutInMilliseconds);

  Cucumber.Util.Exception.registerUncaughtExceptionHandler(finish);

  var result;
  try {
    if (isGeneratorFn(fn)) {
      result = co.wrap(fn).apply(thisArg, argsArray);
    } else {
      result = fn.apply(thisArg, argsArray);
    }
  } catch (error) {
    return finish(error);
  }

  var callbackInterface = fn.length === argsArray.length;
  var promiseInterface = result && typeof result.then === 'function';
  if (callbackInterface && promiseInterface) {
    finish('function accepts a callback and returns a promise');
  } else if (promiseInterface) {
    result.then(function(result){
      finish(null, result);
    }, function(error) {
      finish(error || 'Promise rejected');
    });
  } else if (!callbackInterface) {
    finish(null, result);
  }
}
```
- example usage
```shell
...
}

var self = {
  hear: function hear(event, defaultTimeout, callback) {
    if (self.hasHandlerForEvent(event)) {
      var handler = self.getHandlerForEvent(event);
      var timeout = self.getTimeout() || defaultTimeout;
      Cucumber.Util.run(handler, null, [event.getPayload()], timeout, function(error) {
        error = self.prependLocationToError(error);
        callback(error);
      });
    } else {
      callback();
    }
  },
...
```



# <a name="apidoc.module.cucumber.Util.Exception"></a>[module cucumber.Util.Exception](#apidoc.module.cucumber.Util.Exception)

#### <a name="apidoc.element.cucumber.Util.Exception.registerUncaughtExceptionHandler"></a>[function <span class="apidocSignatureSpan">cucumber.Util.Exception.</span>registerUncaughtExceptionHandler (exceptionHandler)](#apidoc.element.cucumber.Util.Exception.registerUncaughtExceptionHandler)
- description and source-code
```javascript
function registerUncaughtExceptionHandler(exceptionHandler) {
  if (process.on) {
    process.on('uncaughtException', exceptionHandler);
  } else if (typeof(window) !== 'undefined') {
    window.onerror = exceptionHandler;
  }
}
```
- example usage
```shell
...

argsArray.push(finish);

timeoutId = Cucumber.Util.RealTime.setTimeout(function(){
  finish('function timed out after ' + timeoutInMilliseconds + ' milliseconds');
}, timeoutInMilliseconds);

Cucumber.Util.Exception.registerUncaughtExceptionHandler(finish);

var result;
try {
  if (isGeneratorFn(fn)) {
    result = co.wrap(fn).apply(thisArg, argsArray);
  } else {
    result = fn.apply(thisArg, argsArray);
...
```

#### <a name="apidoc.element.cucumber.Util.Exception.unregisterUncaughtExceptionHandler"></a>[function <span class="apidocSignatureSpan">cucumber.Util.Exception.</span>unregisterUncaughtExceptionHandler (exceptionHandler)](#apidoc.element.cucumber.Util.Exception.unregisterUncaughtExceptionHandler)
- description and source-code
```javascript
function unregisterUncaughtExceptionHandler(exceptionHandler) {
  if (process.removeListener) {
    process.removeListener('uncaughtException', exceptionHandler);
  } else if (typeof(window) !== 'undefined') {
    window.onerror = void(0);
  }
}
```
- example usage
```shell
...
var isGeneratorFn = require('is-generator').fn;

function run(fn, thisArg, argsArray, timeoutInMilliseconds, callback) {
var Cucumber = require('../../cucumber');
var timeoutId;

function finish(error, result) {
  Cucumber.Util.Exception.unregisterUncaughtExceptionHandler(finish);
  if (timeoutId) {
    Cucumber.Util.RealTime.clearTimeout(timeoutId);
  }
  if (error && !(error instanceof Error)) {
    error = util.format(error);
  }
  callback(error, result);
...
```



# <a name="apidoc.module.cucumber.Util.RealTime"></a>[module cucumber.Util.RealTime](#apidoc.module.cucumber.Util.RealTime)

#### <a name="apidoc.element.cucumber.Util.RealTime.Date"></a>[function <span class="apidocSignatureSpan">cucumber.Util.RealTime.</span>Date ()](#apidoc.element.cucumber.Util.RealTime.Date)
- description and source-code
```javascript
function Date() { [native code] }
```
- example usage
```shell
...


function time() {
  if (typeof process !== 'undefined' && process.hrtime) {
    return process.hrtime();
  }
  else {
    return new Cucumber.Util.RealTime.Date().getTime();
  }
}

function durationInNanoseconds(start) {
  if (typeof process !== 'undefined' && process.hrtime) {
    var duration = process.hrtime(start);
    return duration[0] * 1e9 + duration[1];
...
```

#### <a name="apidoc.element.cucumber.Util.RealTime.clearImmediate"></a>[function <span class="apidocSignatureSpan">cucumber.Util.RealTime.</span>clearImmediate ()](#apidoc.element.cucumber.Util.RealTime.clearImmediate)
- description and source-code
```javascript
clearImmediate = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cucumber.Util.RealTime.clearInterval"></a>[function <span class="apidocSignatureSpan">cucumber.Util.RealTime.</span>clearInterval ()](#apidoc.element.cucumber.Util.RealTime.clearInterval)
- description and source-code
```javascript
clearInterval = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cucumber.Util.RealTime.clearTimeout"></a>[function <span class="apidocSignatureSpan">cucumber.Util.RealTime.</span>clearTimeout ()](#apidoc.element.cucumber.Util.RealTime.clearTimeout)
- description and source-code
```javascript
clearTimeout = function () { [native code] }
```
- example usage
```shell
...
function run(fn, thisArg, argsArray, timeoutInMilliseconds, callback) {
var Cucumber = require('../../cucumber');
var timeoutId;

function finish(error, result) {
  Cucumber.Util.Exception.unregisterUncaughtExceptionHandler(finish);
  if (timeoutId) {
    Cucumber.Util.RealTime.clearTimeout(timeoutId);
  }
  if (error && !(error instanceof Error)) {
    error = util.format(error);
  }
  callback(error, result);
  callback = function() {};
}
...
```

#### <a name="apidoc.element.cucumber.Util.RealTime.setImmediate"></a>[function <span class="apidocSignatureSpan">cucumber.Util.RealTime.</span>setImmediate ()](#apidoc.element.cucumber.Util.RealTime.setImmediate)
- description and source-code
```javascript
setImmediate = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cucumber.Util.RealTime.setInterval"></a>[function <span class="apidocSignatureSpan">cucumber.Util.RealTime.</span>setInterval ()](#apidoc.element.cucumber.Util.RealTime.setInterval)
- description and source-code
```javascript
setInterval = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cucumber.Util.RealTime.setTimeout"></a>[function <span class="apidocSignatureSpan">cucumber.Util.RealTime.</span>setTimeout ()](#apidoc.element.cucumber.Util.RealTime.setTimeout)
- description and source-code
```javascript
setTimeout = function () { [native code] }
```
- example usage
```shell
...
  }
  callback(error, result);
  callback = function() {};
}

argsArray.push(finish);

timeoutId = Cucumber.Util.RealTime.setTimeout(function(){
  finish('function timed out after ' + timeoutInMilliseconds + ' milliseconds');
}, timeoutInMilliseconds);

Cucumber.Util.Exception.registerUncaughtExceptionHandler(finish);

var result;
try {
...
```



# <a name="apidoc.module.cucumber.Util.RegExp"></a>[module cucumber.Util.RegExp](#apidoc.module.cucumber.Util.RegExp)

#### <a name="apidoc.element.cucumber.Util.RegExp.escapeString"></a>[function <span class="apidocSignatureSpan">cucumber.Util.RegExp.</span>escapeString (string)](#apidoc.element.cucumber.Util.RegExp.escapeString)
- description and source-code
```javascript
function escapeString(string) {
  var escaped = string.replace(_RegExp.ESCAPE_PATTERN, _RegExp.ESCAPE_REPLACEMENT);
  return escaped;
}
```
- example usage
```shell
...
    return 'When';
  else
    return 'Given';
},

buildStepDefinitionPattern: function buildStepDefinitionPattern() {
  var stepName              = step.getName();
  var escapedStepName       = Cucumber.Util.RegExp.escapeString(stepName);
  var parameterizedStepName = self.parameterizeStepName(escapedStepName);
  var pattern               = '/^' + parameterizedStepName + '$/';
  return pattern;
},

buildStepDefinitionParameters: function buildStepDefinitionParameters() {
  var parameters = self.getStepDefinitionPatternMatchingGroupParameters();
...
```



# <a name="apidoc.module.cucumber.Util.String"></a>[module cucumber.Util.String](#apidoc.module.cucumber.Util.String)

#### <a name="apidoc.element.cucumber.Util.String.count"></a>[function <span class="apidocSignatureSpan">cucumber.Util.String.</span>count (hayStack, needle)](#apidoc.element.cucumber.Util.String.count)
- description and source-code
```javascript
function count(hayStack, needle) {
  var splitHayStack = hayStack.split(needle);
  return splitHayStack.length - 1;
}
```
- example usage
```shell
...
    return 'arg' + (n + 1);
  });
  return parameters;
},

countStepDefinitionPatternMatchingGroups: function countStepDefinitionPatternMatchingGroups() {
  var stepDefinitionPattern    = self.buildStepDefinitionPattern();
  var numberMatchingGroupCount = Cucumber.Util.String.count(stepDefinitionPattern, NUMBER_MATCHING_GROUP);
  var quotedStringMatchingGroupCount = Cucumber.Util.String.count(stepDefinitionPattern, QUOTED_STRING_MATCHING_GROUP);
  var count = numberMatchingGroupCount + quotedStringMatchingGroupCount;
  return count;
},

parameterizeStepName: function parameterizeStepName(stepName) {
  var parameterizedStepName =
...
```



# <a name="apidoc.module.cucumber.cucumber"></a>[module cucumber.cucumber](#apidoc.module.cucumber.cucumber)

#### <a name="apidoc.element.cucumber.cucumber.cucumber"></a>[function <span class="apidocSignatureSpan">cucumber.</span>cucumber (featureSource, supportCodeInitializer, options)](#apidoc.element.cucumber.cucumber.cucumber)
- description and source-code
```javascript
function Cucumber(featureSource, supportCodeInitializer, options) {
  var configuration = Cucumber.VolatileConfiguration(featureSource, supportCodeInitializer, options);
  var runtime       = Cucumber.Runtime(configuration);
  return runtime;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cucumber.cucumber.Cli"></a>[function <span class="apidocSignatureSpan">cucumber.cucumber.</span>Cli (argv)](#apidoc.element.cucumber.cucumber.Cli)
- description and source-code
```javascript
function Cli(argv) {
  var Cucumber = require('../cucumber');
  var Command = require('commander').Command;
  var path = require('path');
  var _ = require('lodash');

  function mergeWorldParametersJson(str, memo) {
    var val;
    try {
      val = JSON.parse(str);
    } catch (error) {
      throw new Error('--world-parameters passed invalid JSON: ' + error.message + ': ' + str);
    }
    if (!_.isPlainObject(val)) {
      throw new Error('--world-parameters must be passed a JSON string of an object: ' + str);
    }
    _.merge(memo, val);
    return memo;
  }

  function collect(val, memo) {
    memo.push(val);
    return memo;
  }

  function getProgram () {
    var program = new Command(path.basename(argv[1]));

    program
      .usage('[options] [<DIR | FILE[:LINE]>...]')
      .version(Cucumber.VERSION, '-v, --version')
      .option('-b, --backtrace', 'show full backtrace for errors')
      .option('--compiler <EXTENSION:MODULE>', 'require files with the given EXTENSION after requiring MODULE (repeatable)', collect
, [])
      .option('-d, --dry-run', 'invoke formatters without executing steps')
      .option('--fail-fast', 'abort the run on first failure')
      .option('-f, --format <TYPE[:PATH]>', 'specify the output format, optionally supply PATH to redirect formatter output (repeatable
)', collect, ['pretty'])
      .option('--name <REGEXP>', 'only execute the scenarios with name matching the expression (repeatable)', collect, [])
      .option('--no-colors', 'disable colors in formatter output')
      .option('-p, --profile <NAME>', 'specify the profile to use (repeatable)', collect, [])
      .option('-r, --require <FILE | DIR>', 'require files before executing features (repeatable)', collect, [])
      .option('--snippet-interface [callback | generator | promise | synchronous]', 'specify a snippet interface', 'callback')
      .option('--snippet-syntax [<FILE>]', 'specify a custom snippet syntax')
      .option('-S, --strict', 'fail if there are any undefined or pending steps')
      .option('-t, --tags <EXPRESSION>', 'only execute the features or scenarios with tags matching the expression (repeatable)',
collect, [])
      .option('--world-parameters <JSON>', 'provide parameters that will be passed to the world constructor (repeatable)', mergeWorldParametersJson
, {});

    program.on('--help', function(){
      console.log('  For more details please visit https://github.com/cucumber/cucumber-js#cli\n');
    });

    return program;
  }

  function getConfiguration() {
    var program = getProgram();
    program.parse(argv);
    var profileArgs = Cucumber.Cli.ProfilesLoader.getArgs(program.profile);
    if (profileArgs.length > 0) {
      var fullArgs = argv.slice(0, 2).concat(profileArgs).concat(argv.slice(2));
      program = getProgram();
      program.parse(fullArgs);
    }
    var configuration = Cucumber.Cli.Configuration(program.opts(), program.args);
    return configuration;
  }

  var self = {
    run: function run(callback) {
      var configuration = getConfiguration();
      var runtime    = Cucumber.Runtime(configuration);
      var formatters = configuration.getFormatters();
      formatters.forEach(function (formatter) {
        runtime.attachListener(formatter);
      });
      runtime.start(callback);
    }
  };
  return self;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cucumber.cucumber.Listener"></a>[function <span class="apidocSignatureSpan">cucumber.cucumber.</span>Listener (options)](#apidoc.element.cucumber.cucumber.Listener)
- description and source-code
```javascript
function Listener(options) {
  var Cucumber     = require('../cucumber');

  if (!options) {
    options = {};
  }

  var self = {
    hear: function hear(event, defaultTimeout, callback) {
      if (self.hasHandlerForEvent(event)) {
        var handler = self.getHandlerForEvent(event);
        var timeout = self.getTimeout() || defaultTimeout;
        Cucumber.Util.run(handler, null, [event.getPayload()], timeout, function(error) {
          error = self.prependLocationToError(error);
          callback(error);
        });
      } else {
        callback();
      }
    },

    hasHandlerForEvent: function hasHandlerForEvent(event) {
      var handlerName = self.buildHandlerNameForEvent(event);
      return self[handlerName] !== undefined;
    },

    buildHandlerNameForEvent: function buildHandlerNameForEvent(event) {
      return self.buildHandlerName(event.getName());
    },

    getHandlerForEvent: function getHandlerForEvent(event) {
      var eventHandlerName = self.buildHandlerNameForEvent(event);
      return self[eventHandlerName];
    },

    buildHandlerName: function buildHandler(shortName) {
      return Listener.EVENT_HANDLER_NAME_PREFIX + shortName + Listener.EVENT_HANDLER_NAME_SUFFIX;
    },

    setHandlerForEvent: function setHandlerForEvent(shortname, handler) {
      var eventName = self.buildHandlerName(shortname);
      self[eventName] = handler;
    },

    getTimeout: function() {
      return options.timeout;
    },

    getUri: function() {
      return options.uri;
    },

    getLine: function() {
      return options.line;
    },

    prependLocationToError: function(error) {
      if (error && self.getUri()) {
        var ref = path.relative(process.cwd(), self.getUri()) + ':' + self.getLine() + ' ';
        if (error instanceof Error) {
          error.message = ref + error.message;
        } else {
          error = ref + error;
        }
      }
      return error;
    },
  };
  return self;
}
```
- example usage
```shell
...
var Cucumber = require('../../cucumber');

if (!options)
  options = {};

var logs = '';

var self = Cucumber.Listener(options);

self.log = function log(string) {
  logs += string;
  if (options.stream)
    options.stream.write(string);
  if (typeof(options.logToFunction) === 'function')
    options.logToFunction(string);
...
```

#### <a name="apidoc.element.cucumber.cucumber.Parser"></a>[function <span class="apidocSignatureSpan">cucumber.cucumber.</span>Parser (featureSources, astFilter)](#apidoc.element.cucumber.cucumber.Parser)
- description and source-code
```javascript
function Parser(featureSources, astFilter) {
  var Gherkin      = require('gherkin');
  var Cucumber     = require('../cucumber');

  var parser = new Gherkin.Parser();
  var compiler = new Gherkin.Compiler();

  var self = {
    parse: function parse() {
      var features = [];

      featureSources.forEach(function (featureSource) {
        var uri    = featureSource[Parser.FEATURE_NAME_SOURCE_PAIR_URI_INDEX];
        var source = featureSource[Parser.FEATURE_NAME_SOURCE_PAIR_SOURCE_INDEX];

        var gherkinDocument;
        try {
          gherkinDocument = parser.parse(source);
        } catch(e) {
          e.message += '\npath: ' + uri;
          throw e;
        }

        var pickles = compiler.compile(gherkinDocument);
        var scenarios = [];
        pickles.forEach(function (pickleData) {
          var scenario = Cucumber.Ast.Scenario(pickleData, uri);
          if (astFilter.isElementEnrolled(scenario)) {
            scenarios.push(scenario);
          }
        });

        if (scenarios.length > 0) {
          features.push(Cucumber.Ast.Feature(gherkinDocument.feature, uri, scenarios));
        }
      });

      return features;
    }
  };
  return self;
}
```
- example usage
```shell
...
}).call(this,require('_process'))

},{"../../cucumber":"cucumber","_process":173,"cli-table":75,"duration":102,"lodash":165,"path":170}],35:[function(require,module
,exports){
function Parser(featureSources, astFilter) {
  var Gherkin      = require('gherkin');
  var Cucumber     = require('../cucumber');

  var parser = new Gherkin.Parser();
  var compiler = new Gherkin.Compiler();

  var self = {
    parse: function parse() {
var features = [];

featureSources.forEach(function (featureSource) {
...
```

#### <a name="apidoc.element.cucumber.cucumber.Runtime"></a>[function <span class="apidocSignatureSpan">cucumber.cucumber.</span>Runtime (configuration)](#apidoc.element.cucumber.cucumber.Runtime)
- description and source-code
```javascript
function Runtime(configuration) {
  var Cucumber = require('../cucumber');

  var listeners = [];

  var self = {
    start: function start(callback) {
      if (typeof(callback) !== 'function')
        throw new Error(Runtime.START_MISSING_CALLBACK_ERROR);

      var features = self.getFeatures();
      var supportCodeLibrary = self.getSupportCodeLibrary();
      var options = {
        dryRun: configuration.isDryRunRequested && configuration.isDryRunRequested(),
        failFast: configuration.isFailFastRequested && configuration.isFailFastRequested(),
        strict: configuration.isStrictRequested && configuration.isStrictRequested(),
        worldParameters: configuration.getWorldParameters()
      };

      var featuresRunner = Runtime.FeaturesRunner(features, supportCodeLibrary, listeners, options);

      if (configuration.shouldFilterStackTraces())
        Runtime.StackTraceFilter.filter();

      featuresRunner.run(function (result) {
        Runtime.StackTraceFilter.unfilter();
        callback(result);
      });
    },

    attachListener: function attachListener(listener) {
      listeners.push(listener);
    },

    getFeatures: function getFeatures() {
      var featureSources = configuration.getFeatureSources();
      var astFilter      = configuration.getAstFilter();
      var parser         = Cucumber.Parser(featureSources, astFilter);
      var features       = parser.parse();
      return features;
    },

    getSupportCodeLibrary: function getSupportCodeLibrary() {
      var supportCodeLibrary = configuration.getSupportCodeLibrary();
      return supportCodeLibrary;
    }
  };
  return self;
}
```
- example usage
```shell
...
  var configuration = Cucumber.Cli.Configuration(program.opts(), program.args);
  return configuration;
}

var self = {
  run: function run(callback) {
    var configuration = getConfiguration();
    var runtime    = Cucumber.Runtime(configuration);
    var formatters = configuration.getFormatters();
    formatters.forEach(function (formatter) {
      runtime.attachListener(formatter);
    });
    runtime.start(callback);
  }
};
...
```

#### <a name="apidoc.element.cucumber.cucumber.TagGroupParser"></a>[function <span class="apidocSignatureSpan">cucumber.cucumber.</span>TagGroupParser (tagGroupString)](#apidoc.element.cucumber.cucumber.TagGroupParser)
- description and source-code
```javascript
function TagGroupParser(tagGroupString) {
  var self = {
    parse: function parse() {
      var splitTags = tagGroupString.split(TagGroupParser.TAG_SEPARATOR);
      var trimmedTags = splitTags.map(function (tag) { return tag.trim(); });
      return trimmedTags;
    }
  };
  return self;
}
```
- example usage
```shell
...
  return self;
}

TagGroupParser.getTagGroupsFromStrings = function getTagGroupsFromStrings(tagGroupStrings) {
  var Cucumber = require('../cucumber');

  var tagGroups = tagGroupStrings.map(function (tagOptionValue) {
    var tagGroupParser = Cucumber.TagGroupParser(tagOptionValue);
    var tagGroup       = tagGroupParser.parse();
    return tagGroup;
  });
  return tagGroups;
};

TagGroupParser.TAG_SEPARATOR = ',';
...
```

#### <a name="apidoc.element.cucumber.cucumber.VolatileConfiguration"></a>[function <span class="apidocSignatureSpan">cucumber.cucumber.</span>VolatileConfiguration (features, supportCodeInitializer, options)](#apidoc.element.cucumber.cucumber.VolatileConfiguration)
- description and source-code
```javascript
function VolatileConfiguration(features, supportCodeInitializer, options) {
  var Cucumber = require('../cucumber');
  var supportCodeLibrary = Cucumber.SupportCode.Library(supportCodeInitializer);

  options = options || {};
  var strictMode = !!options.strict;
  var tagGroupStrings = options.tags || [];
  var backtrace = !!options.backtrace;
  var worldParameters = options.worldParameters || {};

  var self = {
    isStrictRequested: function isStrictRequested() {
      return strictMode;
    },

    getFeatureSources: function getFeatureSources() {
      if (features.replace) { // single source
        var featureNameSourcePair = [VolatileConfiguration.FEATURE_SOURCE_NAME, features];
        return [featureNameSourcePair];
      } else { // multiple features
        return features;
      }
    },

    getAstFilter: function getAstFilter() {
      var tagRules = self.getTagAstFilterRules();
      var astFilter = Cucumber.Ast.Filter(tagRules);
      return astFilter;
    },

    getSupportCodeLibrary: function getSupportCodeLibrary() {
      return supportCodeLibrary;
    },

    getTagAstFilterRules: function getTagAstFilterRules() {
      var rules = [];
      tagGroupStrings.forEach(function (tagGroupString) {
        var rule = self.buildAstFilterRuleFromTagGroupString(tagGroupString);
        rules.push(rule);
      });
      return rules;
    },

    buildAstFilterRuleFromTagGroupString: function buildAstFilterRuleFromTagGroupString(tagGroupString) {
      var tagGroupParser = Cucumber.TagGroupParser(tagGroupString);
      var tagGroup       = tagGroupParser.parse();
      var rule           = Cucumber.Ast.Filter.AnyOfTagsRule(tagGroup);
      return rule;
    },

    shouldFilterStackTraces: function shouldFilterStackTraces() {
      return !backtrace;
    },

    getWorldParameters: function getWorldParameters() {
      return worldParameters;
    }
  };
  return self;
}
```
- example usage
```shell
...
    "lib/",
    "release/"
  ]
}

},{}],"cucumber":[function(require,module,exports){
function Cucumber(featureSource, supportCodeInitializer, options) {
  var configuration = Cucumber.VolatileConfiguration(featureSource, supportCodeInitializer, options);
  var runtime       = Cucumber.Runtime(configuration);
  return runtime;
}

Cucumber.Api                   = require('./cucumber/api');
Cucumber.Ast                   = require('./cucumber/ast');
Cucumber.Cli                   = require('./cucumber/cli');
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
