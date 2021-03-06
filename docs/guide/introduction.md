# 介绍

> MogoH5+ 是以一个 `vue+webpack` 的多页面脚手架,配合[HTML5+](http://www.html5plus.org/doc/h5p.html)使用可以快速开发安卓/苹果应用.

![GitHub tag](https://img.shields.io/github/tag/tyaqing/mogo-h5plus.svg)

下载 DEMO 体验[MogoH5+](https://fir.im/p52j)

文档是以`1.3.0`的基础上编写,如果您正在使用老版本出现问题,请加入 QQ 群 780150310 询问

## 特点

- **Vue 支持** 通过 vue 框架双向绑定等优点,可以快速开发出响应式 app 界面
- **ES6/ES7 支持** 支持使用 `ES7/ES8`甚至更加新的 ES 规范,享受 `async/await`
- **热更新** 支持`热更新`,自动化热更新平台正在内测中
- **npm 生态** 支持使用 `npm` 安装管理第三方依赖
- **css 预编译** 支持使用 `Less` 等
- **局域网调试** 无须数据线连接即可`调试`
- **vconsole 支持** 手机上享受`Chrome Dev Tools`一样的体验

想继续写,估计还可以写很多,很多...大概表达就是,这个东西很强大!

## 什么是 HTML5+

`HTML5+` 是一个运行环境,在这个环境下的网页都可以使用 `HTML5+`的 API,比如摄像头,定位,推送等原生 APP 才有的功能.

而这个运行环境的壳需要用`Hbuilder`来生成,所以需要搭配`Hbuilder`使用.

## 入门解疑

如果你要开发大型复杂 APP,游戏,请绕道....

### 兼容问题

`webapp`的本质就是`webview`,`webviwe` 也已经非常的成熟,比如小程序,因此,你知道如何处理网页兼容问题就可以了

### 性能问题

使用多`webview`来管理窗口,几乎满足大多数中小型 APP 的开发,可以安装 Demo 体验.

目前手机的性能越来越强,只要使用规范,可以接近原生界面.

### 与 mui 的关系

`mui`只是一个 ui 框架,`mui.js`中封装了很多`HTML5+`的方法.如果您追求性能,我们建议您最好不要使用任何 ui 框架.
