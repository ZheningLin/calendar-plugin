[预览](https://zheninglin.github.io/calendar-plugin/dist/index.html#/)

# calendar-plugin

> A simple calender-plugin by Vue.js

[![build](https://img.shields.io/wercker/ci/wercker/docs.svg)](https://zheninglin.github.io/calendar-plugin/dist/index.html#/)
[![build](https://img.shields.io/badge/npm-1.0.2-blue.svg)](https://zheninglin.github.io/calendar-plugin/dist/index.html#/)
[![build](https://img.shields.io/npm/l/express.svg)](https://zheninglin.github.io/calendar-plugin/dist/index.html#/)

## 使用方法

```javascript
npm install calendar-plugin
```

### 在父组件中使用calendar-input
引入calendar-input, 如果父组件在vue-cli生成的components中，那么引用方法为：

```javascript
  import calendarInput from '../../node_modules/calendar-plugin/calendar-input.vue';
  export default {
    components: {
      calendarInput
    }
  }
```

如果父组件不在components中，就根据你的项目使用相对路径引入

使用并传递初始值，绑定子组件向父组件通信事件

```html
  <calendar-input :limit="limit" @getValue="getValue"></calendar-input>
```

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

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

