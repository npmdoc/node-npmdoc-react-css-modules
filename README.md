# npmdoc-react-css-modules

#### api documentation for  react-css-modules (v4.2.1)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-css-modules.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-css-modules) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-css-modules.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-css-modules)

#### Seamless mapping of class names to CSS modules inside of React components.

[![NPM](https://nodei.co/npm/react-css-modules.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-css-modules)

- [https://npmdoc.github.io/node-npmdoc-react-css-modules/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-css-modules/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-css-modules/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-css-modules/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-css-modules/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-css-modules/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-css-modules",
    "description": "Seamless mapping of class names to CSS modules inside of React components.",
    "main": "./dist/",
    "repository": {
        "type": "git",
        "url": "https://github.com/gajus/react-css-modules"
    },
    "keywords": [
        "react-component",
        "react",
        "css",
        "modules"
    ],
    "version": "4.2.1",
    "author": {
        "name": "Gajus Kuizinas",
        "url": "http://gajus.com"
    },
    "license": "BSD-3-Clause",
    "dependencies": {
        "hoist-non-react-statics": "^1.2.0",
        "lodash": "^4.16.6",
        "object-unfreeze": "^1.1.0"
    },
    "devDependencies": {
        "babel-cli": "^6.18.0",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-plugin-lodash": "^3.2.9",
        "babel-plugin-transform-proto-to-assign": "^6.9.0",
        "babel-preset-es2015": "^6.18.0",
        "babel-preset-react": "^6.16.0",
        "babel-preset-stage-0": "^6.16.0",
        "babel-register": "^6.18.0",
        "chai": "^4.0.0-canary.1",
        "eslint": "^3.10.0",
        "eslint-config-canonical": "^5.5.0",
        "husky": "^0.11.9",
        "jsdom": "^9.8.3",
        "mocha": "^3.1.2",
        "react": "^15.4.0-rc.4",
        "react-addons-shallow-compare": "^15.4.0-rc.4",
        "react-addons-test-utils": "^15.4.0-rc.4",
        "react-dom": "^15.4.0-rc.4",
        "semantic-release": "^6.3.2"
    },
    "scripts": {
        "lint": "eslint ./src ./tests",
        "test": "NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build",
        "build": "NODE_ENV=production babel ./src --out-dir ./dist",
        "precommit": "npm run test"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
