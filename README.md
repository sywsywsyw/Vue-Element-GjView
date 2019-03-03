# element-gj

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).


### 开发流程

```
vue init webpack


// 安装element-ui
npm i element-ui -S  ====  npm install  element-ui --save-dev

// 安装sass
npm i node -sass -S
npm i sass-loader -S

// 安装骨架屏

vue-skeleton-webpack-plugin骨架屏与page-skeleton-webpack-plugin骨架屏生成插件

npm install vue-skeleton-webpack-plugin
https://blog.csdn.net/zmkyf1993/article/details/82866649
https://github.com/lavas-project/vue-skeleton-webpack-plugin

// 饿了么自动生成骨架屏(不会用)
npm install --save-dev page-skeleton-webpack-plugin
npm install --save-dev html-webpack-plugin
https://github.com/ElemeFE/page-skeleton-webpack-plugin/blob/master/docs/i18n/zh_cn.md

```