# npmtest-sails-auth

#### basic test-coverage for  [sails-auth (v2.1.3)](https://github.com/tjwebb/sails-auth)  [![npm package](https://img.shields.io/npm/v/npmtest-sails-auth.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sails-auth) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sails-auth.svg)](https://travis-ci.org/npmtest/node-npmtest-sails-auth)

#### Passport-based User Authentication system for sails.js applications.

[![NPM](https://nodei.co/npm/sails-auth.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sails-auth)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sails-auth/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sails-auth/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sails-auth/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sails-auth/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sails-auth/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sails-auth/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sails-auth/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sails-auth/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sails-auth/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sails-auth/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sails-auth/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sails-auth/build/test-report.html](https://npmtest.github.io/node-npmtest-sails-auth/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sails-auth/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sails-auth/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sails-auth/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sails-auth/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sails-auth/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sails-auth/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sails-auth/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sails-auth/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Travis Webb"
    },
    "bugs": {
        "url": "https://github.com/tjwebb/sails-auth/issues"
    },
    "bundleDependencies": [
        "bcryptjs",
        "lodash",
        "passport",
        "passport-http",
        "passport-local"
    ],
    "dependencies": {
        "bcryptjs": "^2.2",
        "lodash": "^3.10",
        "marlinspike": "^0.12",
        "passport": "^0.3",
        "passport-http": "^0.3",
        "passport-local": "^1.0.0"
    },
    "description": "Passport-based User Authentication system for sails.js applications.",
    "devDependencies": {
        "babel": "^5.8.21",
        "gulp": "^3.9.0",
        "gulp-babel": "^5.2.1",
        "mocha": "^1.21.4",
        "sails": "github:balderdashy/sails",
        "socket.io-client": "^1.3.5",
        "supertest": "^0.15.0",
        "waterline-sqlite3": "^0.12.1"
    },
    "directories": {},
    "dist": {
        "shasum": "e8062a29943b2e1e2fdd9413a957d3e0996fa00c",
        "tarball": "https://registry.npmjs.org/sails-auth/-/sails-auth-2.1.3.tgz"
    },
    "engines": {
        "node": ">= 0.12",
        "npm": ">= 2.11"
    },
    "gitHead": "f425b254e1249cb186e3ee19718eb916c5f080e2",
    "homepage": "https://github.com/tjwebb/sails-auth",
    "keywords": [
        "sails",
        "sails.js",
        "authentication",
        "auth",
        "passport",
        "oauth",
        "oauth2",
        "openid",
        "passport.js",
        "generator",
        "google",
        "facebook",
        "twitter",
        "linkedin",
        "instagram",
        "youtube"
    ],
    "license": "MIT",
    "main": "dist/api/hooks/auth/index.js",
    "maintainers": [
        {
            "name": "balderdash"
        },
        {
            "name": "ryanwilliamquinn"
        },
        {
            "name": "sailsjs"
        },
        {
            "name": "tjwebb"
        }
    ],
    "name": "sails-auth",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/tjwebb/sails-auth.git"
    },
    "sails": {
        "isHook": true,
        "hookName": "auth"
    },
    "scripts": {
        "prepublish": "gulp",
        "test": "mocha --reporter spec --compilers js:babel/register"
    },
    "version": "2.1.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
