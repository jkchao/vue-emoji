# vue-emoji


> 最近公司需求做个类似于QQ空间的项目(其实开始的时候我是崩溃的),好在历时一个月的时间,也终于进入测试的阶段。
> 完成项目过程中，发现并没有一个好用的emoji插件，于是写了一个简单的component，希望对各位有所帮助（若能顺手给个start, 那再好不过了）。

原理其实很简单，雪碧图+背景定位的方式实现。



![](./gif/demo.gif)




## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

```

## 在你的 Vue 项目里使用它

- 拷贝静态 emoji 图片，在 `static` 文件夹下；
- 拷贝必要的 js/scss 文件，`src/assets/scss/emoji-eprite.scss`、`src/data/emoji-data.js` 以及 `src/utils/emoji.js` 文件至你项目下相应的位置；
- 在你项目的入口文件如 `main.js`，下引入 `src/utils/emoji.js` 并将方法挂至 Vue 原型上，可以参考 `src/main.js`；（当然，你也可以仅在某个组件里使用这个方法）
- 具体的使用例子可以参考 `src/components/emoji.vue` 。
