# antd-admin-boilerplate
以 antd 为基础组件构建的一套中后台管理系统的基本架构模板

## 技术栈

- react
- antd
- webpack
- es6(babel)

## 兼容性

原则上支持 IE9+ 及现代浏览器

## 环境

- node 4 LTS 版本
- npm 建议 3+
- webpack 1+

> npm 建议使用cnpm, 通过设置 alias 的方式;(在私有npm还没搭建起来的时候)

## 开发

```bash

    cpm install -g webpack webpack-dev-server

    cnpm install

    npm run dev

```
### 设置 api 代理

可在 webpack.dev.config.js 里面的 devServer 配置项设置 api 代理

## 其他

其他功能问题请阅读本项目源代码，或者提 issue

## 鸣谢

其中很多代码参考了前同事范峻植的最初版本，在此表示感谢。

## License

MIT
