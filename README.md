# 微信小程序开发 Skill

这是一个面向 Codex 的微信小程序开发 skill，依据微信官方小程序框架文档整理，帮助完成原生微信小程序的创建、修改、调试和代码审查。

## 功能

- 初始化和检查小程序项目目录
- 编写和修改 `app.js`、`app.json`、`app.wxss`
- 开发页面和自定义组件
- 编写 WXML、WXSS、JavaScript 或 TypeScript
- 处理数据绑定、事件、页面生命周期和页面路由
- 配置页面、窗口、tabBar、分包和组件依赖
- 接入网络请求、登录、授权及其他微信开放能力
- 检查 HTTPS/WSS、服务器域名和权限要求
- 进行性能、安全、兼容性和真机验证审查

## 目录

```text
wechat-miniprogram/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    └── official-docs.md
```

`SKILL.md` 包含主要开发规范，`references/official-docs.md` 提供微信官方文档索引。涉及具体 API、组件属性、基础库版本或平台差异时，应以官方文档的最新说明为准。

## 使用方式

将 `wechat-miniprogram` 目录安装到 Codex skills 目录后，可以直接使用：

```text
使用 $wechat-miniprogram 按微信官方框架规范完成这个小程序任务。
```

也可以在相关的小程序开发任务中直接描述需求，让 Codex 自动选择该 skill。

## 适用范围

适用于原生微信小程序项目，包括页面、组件、配置、路由、网络、权限、安全、性能和调试等任务。

不适用于普通 Web 页面、React/Vue 网站或原生 iOS/Android App；这些项目应使用对应技术栈的开发规范。

## 官方依据

- [微信小程序开发指南](https://developers.weixin.qq.com/miniprogram/dev/framework/)
- [微信小程序框架参考文档](https://developers.weixin.qq.com/miniprogram/dev/reference/)
- [微信小程序组件参考文档](https://developers.weixin.qq.com/miniprogram/dev/component/)
- [微信小程序 API 参考文档](https://developers.weixin.qq.com/miniprogram/dev/api/)
