# vue_ele_example

> vue for elementui

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
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

## 全局引用elementui

  src/main.js
    注释
    import { Button, Row } from 'element-ui'
    Vue.use(Button)
    Vue.use(Row)
    放开
    import ElementUI from 'element-ui';
    import 'element-ui/lib/theme-chalk/index.css';
    Vue.use(ElementUI)
    
  文件  复制 .babelrc  替换  .babelrc
