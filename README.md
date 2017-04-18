# npmtest-vue

#### test coverage for  [vue (v2.2.6)](https://github.com/vuejs/vue#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-vue.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-vue) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-vue.svg)](https://travis-ci.org/npmtest/node-npmtest-vue)

#### Reactive, component-oriented view layer for modern web interfaces.

[![NPM](https://nodei.co/npm/vue.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/vue)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-vue/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-vue/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-vue/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-vue/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-vue/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-vue/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-vue/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-vue/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-vue/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-vue/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-vue/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-vue/build/test-report.html](https://npmtest.github.io/node-npmtest-vue/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-vue/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-vue/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-vue/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-vue/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-vue/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-vue/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-vue/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-vue/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Evan You"
    },
    "bugs": {
        "url": "https://github.com/vuejs/vue/issues"
    },
    "dependencies": {},
    "description": "Reactive, component-oriented view layer for modern web interfaces.",
    "devDependencies": {
        "babel-core": "^6.9.0",
        "babel-eslint": "^7.1.0",
        "babel-helper-vue-jsx-merge-props": "^2.0.2",
        "babel-loader": "^6.2.4",
        "babel-plugin-istanbul": "^4.0.0",
        "babel-plugin-syntax-dynamic-import": "^6.18.0",
        "babel-plugin-syntax-jsx": "^6.18.0",
        "babel-plugin-transform-vue-jsx": "^3.2.0",
        "babel-preset-es2015": "^6.9.0",
        "babel-preset-flow-vue": "^1.0.0",
        "buble": "^0.15.2",
        "chromedriver": "^2.21.2",
        "codecov.io": "^0.1.6",
        "cross-spawn": "^5.0.1",
        "de-indent": "^1.0.2",
        "es6-promise": "^4.0.5",
        "eslint": "^3.10.1",
        "eslint-config-vue": "^2.0.1",
        "eslint-loader": "^1.3.0",
        "eslint-plugin-flowtype": "^2.16.0",
        "eslint-plugin-jasmine": "^2.1.0",
        "eslint-plugin-vue": "^2.0.0",
        "flow-bin": "^0.39.0",
        "he": "^1.1.0",
        "http-server": "^0.9.0",
        "jasmine": "^2.5.2",
        "jasmine-core": "^2.5.2",
        "karma": "^1.1.0",
        "karma-chrome-launcher": "^2.0.0",
        "karma-coverage": "^1.0.0",
        "karma-firefox-launcher": "^1.0.0",
        "karma-jasmine": "^1.0.2",
        "karma-mocha-reporter": "^2.0.4",
        "karma-phantomjs-launcher": "^1.0.0",
        "karma-safari-launcher": "^1.0.0",
        "karma-sauce-launcher": "^1.0.0",
        "karma-sourcemap-loader": "^0.3.0",
        "karma-webpack": "^2.0.1",
        "lodash": "^4.17.1",
        "nightwatch": "^0.9.9",
        "nightwatch-helpers": "^1.2.0",
        "phantomjs-prebuilt": "^2.1.1",
        "resolve": "^1.2.0",
        "rollup": "^0.41.4",
        "rollup-plugin-alias": "^1.2.0",
        "rollup-plugin-babel": "^2.4.0",
        "rollup-plugin-buble": "^0.15.0",
        "rollup-plugin-flow-no-whitespace": "^1.0.0",
        "rollup-plugin-replace": "^1.1.0",
        "rollup-watch": "^3.2.2",
        "selenium-server": "^2.53.1",
        "typescript": "^2.1.6",
        "uglify-js": "^2.6.2",
        "vue-ssr-html-stream": "^2.1.0",
        "vue-ssr-webpack-plugin": "^1.0.0",
        "webpack": "^2.2.0",
        "weex-js-runtime": "^0.17.0-alpha4",
        "weex-vdom-tester": "^0.1.4"
    },
    "directories": {},
    "dist": {
        "shasum": "451714b394dd6d4eae7b773c40c2034a59621aed",
        "tarball": "https://registry.npmjs.org/vue/-/vue-2.2.6.tgz"
    },
    "files": [
        "src",
        "dist/*.js",
        "types/*.d.ts"
    ],
    "gitHead": "0cebdf55ab645001a7c8c80381ab27e03ced5c7c",
    "homepage": "https://github.com/vuejs/vue#readme",
    "keywords": [
        "vue"
    ],
    "license": "MIT",
    "main": "dist/vue.runtime.common.js",
    "maintainers": [
        {
            "name": "yyx990803"
        }
    ],
    "module": "dist/vue.runtime.esm.js",
    "name": "vue",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/vuejs/vue.git"
    },
    "scripts": {
        "bench:ssr": "npm run build:ssr && node benchmarks/ssr/renderToString.js && node benchmarks/ssr/renderToStream.js",
        "build": "node build/build.js",
        "build:ssr": "npm run build -- vue.runtime.common.js,vue-server-renderer",
        "build:weex": "npm run build -- weex-vue-framework,weex-template-compiler",
        "dev": "rollup -w -c build/config.js --environment TARGET:web-full-dev",
        "dev:cjs": "rollup -w -c build/config.js --environment TARGET:web-runtime-cjs",
        "dev:compiler": "rollup -w -c build/config.js --environment TARGET:web-compiler ",
        "dev:ssr": "rollup -w -c build/config.js --environment TARGET:web-server-renderer",
        "dev:test": "karma start build/karma.dev.config.js",
        "dev:weex": "rollup -w -c build/config.js --environment TARGET:weex-framework ",
        "dev:weex:compiler": "rollup -w -c build/config.js --environment TARGET:weex-compiler ",
        "flow": "flow check",
        "install:hooks": "ln -fs ../../build/git-hooks/pre-commit .git/hooks/pre-commit",
        "lint": "eslint src build test",
        "release": "bash build/release.sh",
        "release:weex": "bash build/release-weex.sh",
        "sauce": "karma start build/karma.sauce.config.js",
        "test": "npm run lint && flow check && npm run test:types && npm run test:cover && npm run test:e2e -- --env phantomjs && npm run test:ssr && npm run test:weex",
        "test:cover": "karma start build/karma.cover.config.js",
        "test:e2e": "npm run build -- vue.min.js && node test/e2e/runner.js",
        "test:sauce": "npm run sauce -- 0 && npm run sauce -- 1 && npm run sauce -- 2",
        "test:ssr": "npm run build:ssr && jasmine JASMINE_CONFIG_PATH=test/ssr/jasmine.json",
        "test:types": "tsc -p ./types/test/tsconfig.json",
        "test:unit": "karma start build/karma.unit.config.js",
        "test:weex": "npm run build:weex && jasmine JASMINE_CONFIG_PATH=test/weex/jasmine.json"
    },
    "typings": "types/index.d.ts",
    "unpkg": "dist/vue.js",
    "version": "2.2.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
