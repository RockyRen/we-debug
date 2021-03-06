<div align="center">
<br>
<br>
<img src="https://user-images.githubusercontent.com/16918885/77879578-4c0b8500-728d-11ea-934f-b6e55f6dbab0.png" width=64 />
  
<h1>we-debug</h1>

[![Build Status](https://travis-ci.com/dlhandsome/we-debug.svg?token=PfDv3SxcBYsJDq3kuspS&branch=master)](https://travis-ci.com/dlhandsome/we-debug) [![npm-version](https://img.shields.io/npm/v/@we-debug/core.svg)](https://www.npmjs.com/package/@we-debug/core) ![npm](https://img.shields.io/npm/dt/@we-debug/core)

<p>一款灵活、易于拓展的小程序端调试工具</p>
</div>

## 功能 

- 网络请求抓包

- 错误日志抓取

- 路由信息获取

- UI对比

- ...

## 安装

```bash
npm install @we-debug/core --save
```

## 使用

1. 在 json 配置中添加 we-debug 组件声明

```json
{
  "usingComponents": {
    "we-debug": "@we-debug/core/component/index/index"
  }
}
```

2. 在页面 wxml 中创建 we-debug 组件

```html
<we-debug></we-debug>
```

3. 在 app.js 中初始化 we-debug 相关配置

```javascript
const weDebug = require('@we-debug/core/libs/index')

weDebug.init()
```

## 在线体验

<br>
<img src=https://user-images.githubusercontent.com/16918885/77880177-9d684400-728e-11ea-9dc8-0b4be8042caf.jpg width=156/>
<br>

## 插件列表

- [自定义页面跳转](https://github.com/dlhandsome/we-debug/tree/master/packages/plugin-navigate)

## 相关链接

- [文档 · Document](https://dlhandsome.github.io/we-debug/#/)
- [开源协议 · The MIT License](http://opensource.org/licenses/MIT)
- [代码示例 · Example](https://github.com/dlhandsome/sail-laboratory/tree/master/miniprogram/pages/we-debug)

